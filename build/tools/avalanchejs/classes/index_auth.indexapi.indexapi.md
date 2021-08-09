[avalanche](../README.md) › [Index-Auth](../modules/index_auth.md) › [IndexAPI](index_auth.indexapi.md)

# Clase: IndexAPI

Clase para interactuar con la IndexAPI de un nodo.

**`comentarios`** Esto extiende la clase [JRPCAPI](common_jrpcapi.jrpcapi.md). Esta clase no debe ser llamada directamente. En cambio, utilice la función [Avalanche.addAPI](avalanche.avalanche-1.md#addapi) para registrar esta interfaz con Avalanche.

## Jerarquía

m. [JRPCAPI](common_jrpcapi.jrpcapi.md)

m. **IndexAPI**

## Índice de participación

### Constructores

* [constructor](index_auth.indexapi.md#constructor)

### Propiedades de las propiedades

* [baseurl](index_auth.indexapi.md#protected-baseurl)
* [núcleo de la](index_auth.indexapi.md#protected-core)
* [db](index_auth.indexapi.md#protected-db)
* [jrpcVersion](index_auth.indexapi.md#protected-jrpcversion)
* [rpcid](index_auth.indexapi.md#protected-rpcid)

### Métodos de trabajo

* [callMethod](index_auth.indexapi.md#callmethod)
* [getBaseURL](index_auth.indexapi.md#getbaseurl)
* [getContainerByID](index_auth.indexapi.md#getcontainerbyid)
* [getContainerByIndex](index_auth.indexapi.md#getcontainerbyindex)
* [getContainerRange](index_auth.indexapi.md#getcontainerrange)
* [getDB](index_auth.indexapi.md#getdb)
* [getIndex](index_auth.indexapi.md#getindex)
* [getLastAccepted](index_auth.indexapi.md#getlastaccepted)
* [getRPCID](index_auth.indexapi.md#getrpcid)
* [es aceptado](index_auth.indexapi.md#isaccepted)
* [setBaseURL](index_auth.indexapi.md#setbaseurl)

## Constructores

### constructor

\+ **new IndexAPI**(`core`: [AvalancheCore](avalanchecore.avalanchecore-1.md), `baseurl`: string): *[IndexAPI](index_auth.indexapi.md)*

*Superación [JRPCAPI](common_jrpcapi.jrpcapi.md).[constructor](common_jrpcapi.jrpcapi.md#constructor)*

*Definido en [src/apis/index/api.ts:171](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/index/api.ts#L171)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `núcleo de la` | [AvalancheCore](avalanchecore.avalanchecore-1.md) | - |
| `baseurl` | cadena de producción | "/ext/index/X/tx" |

**Retornos:** *[IndexAPI](index_auth.indexapi.md)*

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

### getContainerByID

- **getContainerByID**(`containerID`: string, `encoding`: string, `baseurl`: string): *Promise‹[GetContainerByIDResponse](../interfaces/common_interfaces.getcontainerbyidresponse.md)›*

*Definido en [src/apis/index/api.ts:84](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/index/api.ts#L84)*

Consigue contrainer por ID

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `contenedor-` | cadena de producción | "0" | - |
| `codificación` | cadena de producción | "cb58" | - |
| `baseurl` | cadena de producción | this.getBaseURL() |   |

**Returns:** *Promise‹[GetContainerByIDResponse](../interfaces/common_interfaces.getcontainerbyidresponse.md)›*

Devuelve una promesa<GetContainerByIDResponse>.

___

### getContainerByIndex

- **getContainerByIndex**(`index`: string: `string,` `baseurl`: string): *Promise‹[GetContainerByIndexResponse](../interfaces/common_interfaces.getcontainerbyindexresponse.md)›*

*Definido en [src/apis/index/api.ts:60](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/index/api.ts#L60)*

Obtener contenedor por índice

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `índice de índice` | cadena de producción | "0" | - |
| `codificación` | cadena de producción | "cb58" | - |
| `baseurl` | cadena de producción | this.getBaseURL() |   |

**Returns:** *Promise‹[GetContainerByIndexResponse](../interfaces/common_interfaces.getcontainerbyindexresponse.md)›*

Devuelve una promesa<GetContainerByIndexResponse>.

___

### getContainerRange

- **getContainerRange**(`startIndex`: número, `numToFetch`: número, `codificación`: string, `baseurl`: string): *[]Promise‹[GetContainerRangeResponse](../interfaces/common_interfaces.getcontainerrangeresponse.md)›*

*Definido en [src/apis/index/api.ts:109](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/index/api.ts#L109)*

Obtener el rango de contenedores

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `startIndex` | Número de números | 0 | - |
| `numToFetch` | Número de números | 100 | - |
| `codificación` | cadena de producción | "cb58" | - |
| `baseurl` | cadena de producción | this.getBaseURL() |   |

**Returns:** *Promise‹[GetContainerRangeResponse](../interfaces/common_interfaces.getcontainerrangeresponse.md)[]›*

Devuelve una promesa<GetContainerRangeResponse>.

___

### getDB

- **getDB**(): *StoreAPI*

*Heredada de [APIbase.getDB](common_apibase.apibase.md)[](common_apibase.apibase.md#getdb)*

*Definido en [src/comm/apibase.ts:58](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/apibase.ts#L58)*

Devuelve la base de datos del baseurl's

**Retornos:** *StoreAPI*

___

### getIndex

- **getIndex**(`containerID`: string, `codificación`: string, `baseurl`: string): *Promise‹string›*

*Definido en [src/apis/index/api.ts:134](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/index/api.ts#L134)*

Obtener índice por containerID

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `contenedor-` | cadena de producción | "" | - |
| `codificación` | cadena de producción | "cb58" | - |
| `baseurl` | cadena de producción | this.getBaseURL() |   |

**Returns:** *Promise‹string›*

Devuelve una promesa<GetIndexResponse>.

___

### getLastAccepted

- **getLastAccepted**(`encoding`: string, `baseurl`: string): *Promise‹[GetLastAcceptedResponse](../interfaces/common_interfaces.getlastacceptedresponse.md)›*

*Definido en [src/apis/index/api.ts:37](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/index/api.ts#L37)*

Obtener el último tx, vtx o bloque aceptado

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `codificación` | cadena de producción | "cb58" | - |
| `baseurl` | cadena de producción | this.getBaseURL() |   |

**Returns:** *Promise‹[GetLastAcceptedResponse](../interfaces/common_interfaces.getlastacceptedresponse.md)›*

Devuelve una promesa<GetLastAcceptedResponse>.

___

### getRPCID

- **getRPCID**(): *número*

*Heredada de [JRPCAPI](common_jrpcapi.jrpcapi.md).[getRPCID](common_jrpcapi.jrpcapi.md#getrpcid)*

*Definido en [src/comm/jrpcapi.ts:69](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/jrpcapi.ts#L69)*

Devuelve el rpcid, un número de aumento estricto, a partir de 1, indicando el siguiente solicitar identificación que se enviará.

**Retornos:** *número*

___

### es aceptado

- **isAccepted**(`containerID`: string, `encoding`: string, `baseurl`: string): *Promise‹boolean›*

*Definido en [src/apis/index/api.ts:158](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/index/api.ts#L158)*

Compruebe si el contenedor es aceptado

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `contenedor-` | cadena de producción | "" | - |
| `codificación` | cadena de producción | "cb58" | - |
| `baseurl` | cadena de producción | this.getBaseURL() |   |

**Returns:** *Promise‹boolean›*

Devuelve una promesa<GetIsAcceptedResponse>.

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
