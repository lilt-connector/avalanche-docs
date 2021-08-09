[avalanche](../README.md) › [API-Info](../modules/api_info.md) › [InfoAPI](api_info.infoapi.md)

# Clase: InfoAPI

Clase para interactuar con la InfoAPI de un nodo.

**`comentarios`** Esto extiende la clase [JRPCAPI](common_jrpcapi.jrpcapi.md). Esta clase no debe ser llamada directamente. En cambio, utilice la función [Avalanche.addAPI](avalanche.avalanche-1.md#addapi) para registrar esta interfaz con Avalanche.

## Jerarquía

m. [JRPCAPI](common_jrpcapi.jrpcapi.md)

m. **InfoAPI**

## Índice de participación

### Constructores

* [constructor](api_info.infoapi.md#constructor)

### Propiedades de las propiedades

* [baseurl](api_info.infoapi.md#protected-baseurl)
* [núcleo de la](api_info.infoapi.md#protected-core)
* [db](api_info.infoapi.md#protected-db)
* [jrpcVersion](api_info.infoapi.md#protected-jrpcversion)
* [rpcid](api_info.infoapi.md#protected-rpcid)

### Métodos de trabajo

* [callMethod](api_info.infoapi.md#callmethod)
* [getBaseURL](api_info.infoapi.md#getbaseurl)
* [getBlockchainID](api_info.infoapi.md#getblockchainid)
* [getDB](api_info.infoapi.md#getdb)
* [getNetworkID](api_info.infoapi.md#getnetworkid)
* [getNetworkName](api_info.infoapi.md#getnetworkname)
* [getNodeID](api_info.infoapi.md#getnodeid)
* [getNodeVersion](api_info.infoapi.md#getnodeversion)
* [getRPCID](api_info.infoapi.md#getrpcid)
* [getTxFee](api_info.infoapi.md#gettxfee)
* [isBootstrapped](api_info.infoapi.md#isbootstrapped)
* [pares](api_info.infoapi.md#peers)
* [setBaseURL](api_info.infoapi.md#setbaseurl)

## Constructores

### constructor

\+ **nuevo InfoAPI(core:**`` [AvalancheCore](avalanchecore.avalanchecore-1.md), `baseurl`: string): *[InfoAPI](api_info.infoapi.md)*

*Superación [JRPCAPI](common_jrpcapi.jrpcapi.md).[constructor](common_jrpcapi.jrpcapi.md#constructor)*

*Definido en [src/apis/info/api.ts:121](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/info/api.ts#L121)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `núcleo de la` | [AvalancheCore](avalanchecore.avalanchecore-1.md) | - |
| `baseurl` | cadena de producción | "/ext/info" |

**Returns:** *[InfoAPI](api_info.infoapi.md)*

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

### getBlockchainID

- **getBlockchainID**(`alias`: string): *Promise‹string›*

*Definido en [src/apis/info/api.ts:31](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/info/api.ts#L31)*

Toma el blockchainID del nodo para un alias dado.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `alias` | cadena de producción | El alias de blockchain para obtener el blockchainID |

**Returns:** *Promise‹string›*

Devuelve una promesa<string>conteniendo la representación de cadena de base 58 del blockchainID.

___

### getDB

- **getDB**(): *StoreAPI*

*Heredada de [APIbase.getDB](common_apibase.apibase.md)[](common_apibase.apibase.md#getdb)*

*Definido en [src/comm/apibase.ts:58](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/apibase.ts#L58)*

Devuelve la base de datos del baseurl's

**Retornos:** *StoreAPI*

___

### getNetworkID

- **getNetworkID**(): *Promise‹number›*

*Definido en [src/apis/info/api.ts:45](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/info/api.ts#L45)*

Toma el ID de red del nodo.

**Returns:** *Promise‹number›*

Devuelve una promesa<number>de la redID.

___

### getNetworkName

- **getNetworkName**(): *Promise‹string›*

*Definido en [src/apis/info/api.ts:55](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/info/api.ts#L55)*

Fetches el nombre de la red que este nodo está ejecutando

**Returns:** *Promise‹string›*

Devuelve una promesa<string>que contiene el nombre de la red.

___

### getNodeID

- **getNodeID**(): *Promise‹string›*

*Definido en [src/apis/info/api.ts:65](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/info/api.ts#L65)*

Toma el nodeID del nodo.

**Returns:** *Promise‹string›*

Devuelve una promesa<string>del nodeID.

___

### getNodeVersion

- **getNodeVersion**(): *Promise‹string›*

*Definido en [src/apis/info/api.ts:75](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/info/api.ts#L75)*

Fetches la versión de Gecko este nodo está ejecutando

**Returns:** *Promise‹string›*

Devuelve una promesa<string>conteniendo la versión de Gecko.

___

### getRPCID

- **getRPCID**(): *número*

*Heredada de [JRPCAPI](common_jrpcapi.jrpcapi.md).[getRPCID](common_jrpcapi.jrpcapi.md#getrpcid)*

*Definido en [src/comm/jrpcapi.ts:69](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/jrpcapi.ts#L69)*

Devuelve el rpcid, un número de aumento estricto, a partir de 1, indicando el siguiente solicitar identificación que se enviará.

**Retornos:** *número*

___

### getTxFee

- **getTxFee**(): *Promise‹object›*

*Definido en [src/apis/info/api.ts:85](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/info/api.ts#L85)*

Toma la tarifa de transacción del nodo.

**Returns:** *Promise‹object›*

Devuelve una promesa de la tarifa <object>de transacción en nAVAX.

___

### isBootstrapped

- **isBootstrapped**(`chain`: (cadena: string): *Promise‹boolean›*

*Definido en [src/apis/info/api.ts:99](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/info/api.ts#L99)*

Compruebe si una cadena dada se realiza el arranque

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `cadena de la cadena de producción` | cadena de producción | El ID o alias de una cadena. |

**Returns:** *Promise‹boolean›*

Devuelve una promesa<boolean>de si la cadena ha completado el arranque de arranque.

___

### pares

- **peers**(`nodeIDs`: []string): *[]Promise‹[PeersResponse](../interfaces/common_interfaces.peersresponse.md)›*

*Definido en [src/apis/info/api.ts:115](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/info/api.ts#L115)*

Devuelve a los pares conectados al nodo.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `NodeIDs` | cadena de producción[] | [] | un parámetro opcional para especificar qué descripciones de nodeID's deben ser devueltas Si este parámetro está dejado vacío, se devolverán las descripciones de todas las conexiones activas. Si el nodo no está conectado a un nodo especificado, se omitirá de la respuesta. |

**Returns:** *Promise‹[PeersResponse](../interfaces/common_interfaces.peersresponse.md)[]›*

Promete la lista de pares conectados en formato PeersResponse.

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
