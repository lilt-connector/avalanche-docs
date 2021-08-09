[avalanche](../README.md) › [Common-RESTAPI](../modules/common_restapi.md) › [RESTAPI](common_restapi.restapi.md)

# Clase: RESTAPI

## Jerarquía

* [APIBA](common_apibase.apibase.md)

   m. **RESTAPI**

   [metricsAPI](api_metrics.metricsapi.md)

## Índice de participación

### Constructores

* [constructor](common_restapi.restapi.md#constructor)

### Propiedades de las propiedades

* [acceptType](common_restapi.restapi.md#protected-accepttype)
* [baseurl](common_restapi.restapi.md#protected-baseurl)
* [contentType de contenido](common_restapi.restapi.md#protected-contenttype)
* [núcleo de la](common_restapi.restapi.md#protected-core)
* [db](common_restapi.restapi.md#protected-db)

### Métodos de trabajo

* [axConf](common_restapi.restapi.md#protected-axconf)
* [eliminar las pérdidas de](common_restapi.restapi.md#delete)
* [Contrade](common_restapi.restapi.md#get)
* [getAcceptType](common_restapi.restapi.md#getaccepttype)
* [getBaseURL](common_restapi.restapi.md#getbaseurl)
* [getContentType](common_restapi.restapi.md#getcontenttype)
* [getDB](common_restapi.restapi.md#getdb)
* [Pareja de la parcela.](common_restapi.restapi.md#patch)
* [2.](common_restapi.restapi.md#post)
* [los preparadores](common_restapi.restapi.md#protected-prepheaders)
* [Pone en marcha](common_restapi.restapi.md#put)
* [setBaseURL](common_restapi.restapi.md#setbaseurl)

## Constructores

### constructor

\+ **new RESTAPI**`(core`: [AvalancheCore](avalanchecore.avalanchecore-1.md), `baseurl`: string, `contentType`: string, `RESTAPI(core`: string, RESTAPI(core: string): *[RESTAPI](common_restapi.restapi.md)*

*Overrides [APIbase.constructor](common_apibase.apibase.md)[](common_apibase.apibase.md#constructor)*

*Definido en [src/común/restapi.ts:119](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/restapi.ts#L119)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `núcleo de la` | [AvalancheCore](avalanchecore.avalanchecore-1.md) | - | Referencia a la instancia de Avalanche utilizando este punto final |
| `baseurl` | cadena de producción | - | Camino de las API baseurl - ex: "/ext/bc/avm" |
| `contentType de contenido` | cadena de producción | "application/jsoncharset=UTF-8" | Opcional Determina el tipo de entidad adjunta a la solicitud entrante |
| `acceptType` | cadena de producción | no definido. | Opcional Determina el tipo de representación que se desea en el lado del cliente |

**Returns:** *[RESTAPI](common_restapi.restapi.md)*

## Propiedades de las propiedades

### Aceptación `protegida`

• **acceptType**: *cadena*

*Definido en [src/común/restapi.ts:12](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/restapi.ts#L12)*

___

### Base `protegida`

• **baseurl**: *cadena*

*Heredada de [APIBase](common_apibase.apibase.md).[baseurl](common_apibase.apibase.md#protected-baseurl)*

*Definido en [src/comm/apibase.ts:28](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/apibase.ts#L28)*

___

### Contenido `protegido`

• **contentType**: *cadena*

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

*Definido en [src/común/restapi.ts:30](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/restapi.ts#L30)*

**Return:** *AxiosRequestConfig*

___

### eliminar las pérdidas de

- **delete(method:**`` string, `params?`: objeto []| objeto, `baseurl?`: string, `contentType?`: string, `delete(method`: string): *Promise‹[RequestResponseData](common_apibase.requestresponsedata.md)›*

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

### Pareja de la parcela.

- **patch(method:**`` string, `params?`: objeto []| objeto, `baseurl?`: string, `contentType?`: string, `patch(method`: string): *Promise‹[RequestResponseData](common_apibase.requestresponsedata.md)›*

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
