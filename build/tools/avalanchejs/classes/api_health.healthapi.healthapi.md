[avalanche](../README.md) › [API-Health](../modules/api_health.md) › [HealthAPI](api_health.healthapi.md)

# Clase: HealthAPI

Clase para interactuar con una API de nodo que está utilizando HealthApi.

**`comentarios`** Esto extiende la clase [JRPCAPI](common_jrpcapi.jrpcapi.md). Esta clase no debe ser llamada directamente. En cambio, utilice la función [Avalanche.addAPI](avalanche.avalanche-1.md#addapi) para registrar esta interfaz con Avalanche.

## Jerarquía

m. [JRPCAPI](common_jrpcapi.jrpcapi.md)

m. **HealthAPI**

## Índice de participación

### Constructores

* [constructor](api_health.healthapi.md#constructor)

### Propiedades de las propiedades

* [baseurl](api_health.healthapi.md#protected-baseurl)
* [núcleo de la](api_health.healthapi.md#protected-core)
* [db](api_health.healthapi.md#protected-db)
* [jrpcVersion](api_health.healthapi.md#protected-jrpcversion)
* [rpcid](api_health.healthapi.md#protected-rpcid)

### Métodos de trabajo

* [callMethod](api_health.healthapi.md#callmethod)
* [getBaseURL](api_health.healthapi.md#getbaseurl)
* [getDB](api_health.healthapi.md#getdb)
* [getLiveness](api_health.healthapi.md#getliveness)
* [getRPCID](api_health.healthapi.md#getrpcid)
* [setBaseURL](api_health.healthapi.md#setbaseurl)

## Constructores

### constructor

\+ **new HealthAPI**(`core`: [AvalancheCore](avalanchecore.avalanchecore-1.md), `baseurl`: string): *[HealthAPI](api_health.healthapi.md)*

*Superación [JRPCAPI](common_jrpcapi.jrpcapi.md).[constructor](common_jrpcapi.jrpcapi.md#constructor)*

*Definido en [src/apis/health/api.ts:25](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/health/api.ts#L25)*

Esta clase no debe ser instantiated directamente. En lugar de ello, utilice el método [Avalanche.addAPI](avalanche.avalanche-1.md#addapi).

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `núcleo de la` | [AvalancheCore](avalanchecore.avalanchecore-1.md) | - | Una referencia a la clase Avalanche |
| `baseurl` | cadena de producción | "/ext/health" | Default a la cadena "/ext/health" como el camino hacia el baseurl de blockchain |

**Returns:** *[HealthAPI](api_health.healthapi.md)*

## Propiedades de las propiedades

### Base `protegida`

• **baseurl**: *cadena*

*Heredada de [APIBase](common_apibase.apibase.md).[baseurl](common_apibase.apibase.md#protected-baseurl)*

*Definido en [src/comm/apibase.ts:28](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/apibase.ts#L28)*

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

___

### jrpcVersion `protegida`

• **jrpcVersion**: *cadena* = "2.0"

*Heredado de [JRPCAPI](common_jrpcapi.jrpcapi.md).[jrpcVersion](common_jrpcapi.jrpcapi.md#protected-jrpcversion)*

*Definido en [src/comm/jrpcapi.ts:11](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/jrpcapi.ts#L11)*

___

### rpcid `protegido`

• **rpcid**: *número* = 1

*Heredada de [JRPCAPI](common_jrpcapi.jrpcapi.md).[rpcid](common_jrpcapi.jrpcapi.md#protected-rpcid)*

*Definido en [src/comm/jrpcapi.ts:12](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/jrpcapi.ts#L12)*

## Métodos de trabajo

### callMethod

- **callMethod**(`method`: string, `params?`: objeto []| objeto, `baseurl?`: string, `headers?`: objeto): *Promise‹[RequestResponseData](common_apibase.requestresponsedata.md)›*

*Heredado de [JRPCAPI](common_jrpcapi.jrpcapi.md).[callMethod](common_jrpcapi.jrpcapi.md#callmethod) Method*

*Definido en [src/comm/jrpcapi.ts:14](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/jrpcapi.ts#L14)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `método` | cadena de producción |
| `¿params?` | objeto []&#124; objeto |
| `baseurl?` | cadena de producción |
| `¿Los encabezados?` | objeto de la operación |

**Return:** *Promise‹[RequestResponseData](common_apibase.requestresponsedata.md)›*

___

### getBaseURL

- **getBaseURL**(): *string*

*Heredada de [APIbase.getBaseURL](common_apibase.apibase.md)[](common_apibase.apibase.md#getbaseurl)*

*Definido en [src/comm/apibase.ts:53](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/apibase.ts#L53)*

Devuelve el camino del baseurl's

**Return:** *string*

___

### getDB

- **getDB**(): *StoreAPI*

*Heredada de [APIbase.getDB](common_apibase.apibase.md)[](common_apibase.apibase.md#getdb)*

*Definido en [src/comm/apibase.ts:58](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/apibase.ts#L58)*

Devuelve la base de datos del baseurl's

**Retornos:** *StoreAPI*

___

### getLiveness

- **getLiveness**(): *Promise‹object›*

*Definido en [src/apis/health/api.ts:22](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/health/api.ts#L22)*

**Returns:** *Promise‹object›*

Promesa para un objeto que contenga la respuesta de verificación de salud

___

### getRPCID

- **getRPCID**(): *número*

*Heredada de [JRPCAPI](common_jrpcapi.jrpcapi.md).[getRPCID](common_jrpcapi.jrpcapi.md#getrpcid)*

*Definido en [src/comm/jrpcapi.ts:69](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/jrpcapi.ts#L69)*

Devuelve el rpcid, un número de aumento estricto, a partir de 1, indicando el siguiente solicitar identificación que se enviará.

**Retornos:** *número*

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
