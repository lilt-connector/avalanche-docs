[avalanche](../README.md) › [Common-JRPCAPI](../modules/common_jrpcapi.md) › [JRPCAPI](common_jrpcapi.jrpcapi.md)

# Clase: JRPCAPI

## Jerarquía

* [APIBA](common_apibase.apibase.md)

   m. **JRPCAPI**

   m. [AdminAPI](api_admin.adminapi.md)

   m. [AuthAPI](api_auth.authapi.md)

   m. [PlatformVMAPI](api_platformvm.platformvmapi.md)

   m. [AVMAPI](api_avm.avmapi.md)

   -[EVMAPI](api_evm.evmapi.md)

   m. [HealthAPI](api_health.healthapi.md)

   m. [IndexAPI](index_auth.indexapi.md)

   m. [InfoAPI](api_info.infoapi.md)

   m. [KeystoreAPI](api_keystore.keystoreapi.md)

## Índice de participación

### Constructores

* [constructor](common_jrpcapi.jrpcapi.md#constructor)

### Propiedades de las propiedades

* [baseurl](common_jrpcapi.jrpcapi.md#protected-baseurl)
* [núcleo de la](common_jrpcapi.jrpcapi.md#protected-core)
* [db](common_jrpcapi.jrpcapi.md#protected-db)
* [jrpcVersion](common_jrpcapi.jrpcapi.md#protected-jrpcversion)
* [rpcid](common_jrpcapi.jrpcapi.md#protected-rpcid)

### Métodos de trabajo

* [callMethod](common_jrpcapi.jrpcapi.md#callmethod)
* [getBaseURL](common_jrpcapi.jrpcapi.md#getbaseurl)
* [getDB](common_jrpcapi.jrpcapi.md#getdb)
* [getRPCID](common_jrpcapi.jrpcapi.md#getrpcid)
* [setBaseURL](common_jrpcapi.jrpcapi.md#setbaseurl)

## Constructores

### constructor

\+ **nuevo JRPCAPI(core:**`` [AvalancheCore](avalanchecore.avalanchecore-1.md), `baseurl`: string, `JRPCAPI(core`: string): *[JRPCAPI](common_jrpcapi.jrpcapi.md)*

*Overrides [APIbase.constructor](common_apibase.apibase.md)[](common_apibase.apibase.md#constructor)*

*Definido en [src/comm/jrpcapi.ts:69](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/jrpcapi.ts#L69)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `núcleo de la` | [AvalancheCore](avalanchecore.avalanchecore-1.md) | - | Referencia a la instancia de Avalanche utilizando este punto final |
| `baseurl` | cadena de producción | - | Camino de las API baseurl - ex: "/ext/bc/avm" |
| `jrpcVersion` | cadena de producción | "2.0" | La versión jrpc a utilizar, predeterminada "2.0". |

**Return:** *[JRPCAPI](common_jrpcapi.jrpcapi.md)*

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

*Definido en [src/comm/jrpcapi.ts:11](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/jrpcapi.ts#L11)*

___

### rpcid `protegido`

• **rpcid**: *número* = 1

*Definido en [src/comm/jrpcapi.ts:12](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/jrpcapi.ts#L12)*

## Métodos de trabajo

### callMethod

- **callMethod**(`method`: string, `params?`: objeto []| objeto, `baseurl?`: string, `headers?`: objeto): *Promise‹[RequestResponseData](common_apibase.requestresponsedata.md)›*

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

### getRPCID

- **getRPCID**(): *número*

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
