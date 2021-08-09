[avalanche](../README.md) › [API-Metrics](../modules/api_metrics.md) › [MetricsAPI](api_metrics.metricsapi.md)

# Clase: MetricsAPI

Clase para interactuar con una API de nodo que está utilizando MetricsApi.

**`comentarios`** Esto extiende la clase [RESTAPI](common_restapi.restapi.md). Esta clase no debe ser llamada directamente. En cambio, utilice la función [Avalanche.addAPI](avalanche.avalanche-1.md#addapi) para registrar esta interfaz con Avalanche.

## Jerarquía

m. [RESTAPI](common_restapi.restapi.md)

**metricsAPI**

## Índice de participación

### Constructores

* [constructor](api_metrics.metricsapi.md#constructor)

### Propiedades de las propiedades

* [acceptType](api_metrics.metricsapi.md#protected-accepttype)
* [baseurl](api_metrics.metricsapi.md#protected-baseurl)
* [contentType de contenido](api_metrics.metricsapi.md#protected-contenttype)
* [núcleo de la](api_metrics.metricsapi.md#protected-core)
* [db](api_metrics.metricsapi.md#protected-db)

### Métodos de trabajo

* [axConf](api_metrics.metricsapi.md#protected-axconf)
* [eliminar las pérdidas de](api_metrics.metricsapi.md#delete)
* [Contrade](api_metrics.metricsapi.md#get)
* [getAcceptType](api_metrics.metricsapi.md#getaccepttype)
* [getBaseURL](api_metrics.metricsapi.md#getbaseurl)
* [getContentType](api_metrics.metricsapi.md#getcontenttype)
* [getDB](api_metrics.metricsapi.md#getdb)
* [getMetrics](api_metrics.metricsapi.md#getmetrics)
* [Pareja de la parcela.](api_metrics.metricsapi.md#patch)
* [2.](api_metrics.metricsapi.md#post)
* [los preparadores](api_metrics.metricsapi.md#protected-prepheaders)
* [Pone en marcha](api_metrics.metricsapi.md#put)
* [setBaseURL](api_metrics.metricsapi.md#setbaseurl)

## Constructores

### constructor

\+ **new MetricsAPI**(`core`: [AvalancheCore](avalanchecore.avalanchecore-1.md), `baseurl`: string): *[MetricsAPI](api_metrics.metricsapi.md)*

*Supera [RESTAPI](common_restapi.restapi.md).[constructor](common_restapi.restapi.md#constructor)*

*Definido en [src/apis/métricas/api.ts:32](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/metrics/api.ts#L32)*

Esta clase no debe ser instantiated directamente. En lugar de ello, utilice el método [Avalanche.addAPI](avalanche.avalanche-1.md#addapi).

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `núcleo de la` | [AvalancheCore](avalanchecore.avalanchecore-1.md) | - | Una referencia a la clase Avalanche |
| `baseurl` | cadena de producción | "/ext/métricas" | Default a la cadena "/ext/métricas" como el camino hacia el baseurl de blockchain |

**Return:** *[MetricsAPI](api_metrics.metricsapi.md)*

## Propiedades de las propiedades

### Aceptación `protegida`

• **acceptType**: *cadena*

*Heredado de [RESTAPI](common_restapi.restapi.md).[acceptType](common_restapi.restapi.md#protected-accepttype)*

*Definido en [src/común/restapi.ts:12](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/restapi.ts#L12)*

___

### Base `protegida`

• **baseurl**: *cadena*

*Heredada de [APIBase](common_apibase.apibase.md).[baseurl](common_apibase.apibase.md#protected-baseurl)*

*Definido en [src/comm/apibase.ts:28](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/apibase.ts#L28)*

___

### Contenido `protegido`

• **contentType**: *cadena*

*Heredado de [RESTAPI](common_restapi.restapi.md).[contentType](common_restapi.restapi.md#protected-contenttype)*

*Definido en [src/común/restapi.ts:11](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/restapi.ts#L11)*

___

### Correa `protegida`

• **núcleo**: *[AvalancheCore](avalanchecore.avalanchecore-1.md)*

*Heredada de [APIbase.core](common_apibase.apibase.md)[](common_apibase.apibase.md#protected-core)*

*Definido en [src/comm/apibase.ts:26](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/apibase.ts#L26)*

___

### db `protegido`

• **db**: *StoreAPI*

*Heredada de [APIbase.db](common_apibase.apibase.md)[](common_apibase.apibase.md#protected-db)*

*Definido en [src/comm/apibase.ts:30](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/apibase.ts#L30)*

## Métodos de trabajo

### axConf `protegido`

- **axConf**(): *AxiosRequestConfig*

*Superaciones [RESTAPI](common_restapi.restapi.md).[axConf](common_restapi.restapi.md#protected-axconf)*

*Definido en [src/apis/métricas/api.ts:18](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/metrics/api.ts#L18)*

**Return:** *AxiosRequestConfig*

___

### eliminar las pérdidas de

- **delete(method:**`` string, `params?`: objeto []| objeto, `baseurl?`: string, `contentType?`: string, `delete(method`: string): *Promise‹[RequestResponseData](common_apibase.requestresponsedata.md)›*

*Heredado de [RESTAPI](common_restapi.restapi.md).[delete](common_restapi.restapi.md#delete)*

*Definido en [src/común/restapi.ts:79](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/restapi.ts#L79)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `método` | cadena de producción |
| `¿params?` | objeto []&#124; objeto |
| `baseurl?` | cadena de producción |
| `contentType?` | cadena de producción |
| `acceptType?` | cadena de producción |

**Return:** *Promise‹[RequestResponseData](common_apibase.requestresponsedata.md)›*

___

### Contrade

- **get(baseurl?:**`` string, `contentType?```: string, get(baseurl?: string): *Promise‹[RequestResponseData](common_apibase.requestresponsedata.md)›*

*Heredada de [RESTAPI](common_restapi.restapi.md).[get](common_restapi.restapi.md#get)*

*Definido en [src/común/restapi.ts:37](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/restapi.ts#L37)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `baseurl?` | cadena de producción |
| `contentType?` | cadena de producción |
| `acceptType?` | cadena de producción |

**Return:** *Promise‹[RequestResponseData](common_apibase.requestresponsedata.md)›*

___

### getAcceptType

- **getAcceptType**(): *string*

*Heredada de [RESTAPI](common_restapi.restapi.md).[getAcceptType](common_restapi.restapi.md#getaccepttype)*

*Definido en [src/común/restapi.ts:119](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/restapi.ts#L119)*

Devuelve qué tipo de representación se desea en el lado del cliente

**Return:** *string*

___

### getBaseURL

- **getBaseURL**(): *string*

*Heredada de [APIbase.getBaseURL](common_apibase.apibase.md)[](common_apibase.apibase.md#getbaseurl)*

*Definido en [src/comm/apibase.ts:53](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/apibase.ts#L53)*

Devuelve el camino del baseurl's

**Return:** *string*

___

### getContentType

- **getContentType**(): *string*

*Heredado de [RESTAPI](common_restapi.restapi.md).[getContentType](common_restapi.restapi.md#getcontenttype)*

*Definido en [src/común/restapi.ts:114](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/restapi.ts#L114)*

Devuelve el tipo de entidad adjunta a la solicitud entrante

**Return:** *string*

___

### getDB

- **getDB**(): *StoreAPI*

*Heredada de [APIbase.getDB](common_apibase.apibase.md)[](common_apibase.apibase.md#getdb)*

*Definido en [src/comm/apibase.ts:58](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/apibase.ts#L58)*

Devuelve la base de datos del baseurl's

**Retornos:** *StoreAPI*

___

### getMetrics

- **getMetrics**(): *Promise‹string›*

*Definido en [src/apis/métricas/api.ts:29](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/metrics/api.ts#L29)*

**Returns:** *Promise‹string›*

Promesa para un objeto que contenga la respuesta de las métricas

___

### Pareja de la parcela.

- **patch(method:**`` string, `params?`: objeto []| objeto, `baseurl?`: string, `contentType?`: string, `patch(method`: string): *Promise‹[RequestResponseData](common_apibase.requestresponsedata.md)›*

*Heredado de [RESTAPI](common_restapi.restapi.md).[patch](common_restapi.restapi.md#patch)*

*Definido en [src/común/restapi.ts:95](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/restapi.ts#L95)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `método` | cadena de producción |
| `¿params?` | objeto []&#124; objeto |
| `baseurl?` | cadena de producción |
| `contentType?` | cadena de producción |
| `acceptType?` | cadena de producción |

**Return:** *Promise‹[RequestResponseData](common_apibase.requestresponsedata.md)›*

___

### 2.

- **post(method:**`` string, `params?`: objeto []| objeto, `baseurl?`: string, `contentType?`: string, post(method: string, `acceptType?`: string): *Promise‹[RequestResponseData](common_apibase.requestresponsedata.md)›*

*Heredado de [RESTAPI](common_restapi.restapi.md).[post](common_restapi.restapi.md#post)*

*Definido en [src/común/restapi.ts:44](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/restapi.ts#L44)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `método` | cadena de producción |
| `¿params?` | objeto []&#124; objeto |
| `baseurl?` | cadena de producción |
| `contentType?` | cadena de producción |
| `acceptType?` | cadena de producción |

**Return:** *Promise‹[RequestResponseData](common_apibase.requestresponsedata.md)›*

___

### Precipitación `protegida`

- **prepHeaders(contentType?:**`` prepHeaders(contentType?: `prepHeaders(contentType?`: string): *objeto*

*Heredados de [RESTAPI](common_restapi.restapi.md).[prepHeaders](common_restapi.restapi.md#protected-prepheaders)*

*Definido en [src/común/restapi.ts:14](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/restapi.ts#L14)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `contentType?` | cadena de producción |
| `acceptType?` | cadena de producción |

**Return:** *objeto*

___

### Pone en marcha

- **put(method:**`` string, `params?`: objeto []| objeto, `baseurl?`: string, `contentType?`: string, put(method: string, `acceptType?`: string): *Promise‹[RequestResponseData](common_apibase.requestresponsedata.md)›*

*Heredado de [RESTAPI](common_restapi.restapi.md).[put](common_restapi.restapi.md#put)*

*Definido en [src/común/restapi.ts:60](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/restapi.ts#L60)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `método` | cadena de producción |
| `¿params?` | objeto []&#124; objeto |
| `baseurl?` | cadena de producción |
| `contentType?` | cadena de producción |
| `acceptType?` | cadena de producción |

**Return:** *Promise‹[RequestResponseData](common_apibase.requestresponsedata.md)›*

___

### setBaseURL

- **setBaseURL**(`baseurl`: string): *void*

*Heredado de [APIbase.setBaseURL](common_apibase.apibase.md)[](common_apibase.apibase.md#setbaseurl)*

*Definido en [src/comm/apibase.ts:37](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/apibase.ts#L37)*

Establece el camino de las API baseurl.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `baseurl` | cadena de producción | Camino de las API baseurl - ex: "/ext/bc/X" |

**Retornos:** *vacío*
