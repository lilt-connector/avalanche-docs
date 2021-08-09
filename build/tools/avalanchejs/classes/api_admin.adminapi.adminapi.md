[avalanche](../README.md) › [API-Admin](../modules/api_admin.md) › [AdminAPI](api_admin.adminapi.md)

# Clase: AdminAPI

Clase para interactuar con la AdminAPI de un nodo.

**`comentarios`** Esto extiende la clase [JRPCAPI](common_jrpcapi.jrpcapi.md). Esta clase no debe ser llamada directamente. En cambio, utilice la función [Avalanche.addAPI](avalanche.avalanche-1.md#addapi) para registrar esta interfaz con Avalanche.

## Jerarquía

m. [JRPCAPI](common_jrpcapi.jrpcapi.md)

m. **AdminAPI**

## Índice de participación

### Constructores

* [constructor](api_admin.adminapi.md#constructor)

### Propiedades de las propiedades

* [baseurl](api_admin.adminapi.md#protected-baseurl)
* [núcleo de la](api_admin.adminapi.md#protected-core)
* [db](api_admin.adminapi.md#protected-db)
* [jrpcVersion](api_admin.adminapi.md#protected-jrpcversion)
* [rpcid](api_admin.adminapi.md#protected-rpcid)

### Métodos de trabajo

* [alias](api_admin.adminapi.md#alias)
* [aliasChain](api_admin.adminapi.md#aliaschain)
* [callMethod](api_admin.adminapi.md#callmethod)
* [getBaseURL](api_admin.adminapi.md#getbaseurl)
* [getChainAliases](api_admin.adminapi.md#getchainaliases)
* [getDB](api_admin.adminapi.md#getdb)
* [getRPCID](api_admin.adminapi.md#getrpcid)
* [lockProfile](api_admin.adminapi.md#lockprofile)
* [memoryProfile](api_admin.adminapi.md#memoryprofile)
* [setBaseURL](api_admin.adminapi.md#setbaseurl)
* [startCPUProfiler](api_admin.adminapi.md#startcpuprofiler)
* [stopCPUProfiler](api_admin.adminapi.md#stopcpuprofiler)

## Constructores

### constructor

\+ **nuevo AdminAPI(core:**`` [AvalancheCore](avalanchecore.avalanchecore-1.md), `baseurl`: string): *[AdminAPI](api_admin.adminapi.md)*

*Superación [JRPCAPI](common_jrpcapi.jrpcapi.md).[constructor](common_jrpcapi.jrpcapi.md#constructor)*

*Definido en [src/apis/admin/api.ts:112](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/admin/api.ts#L112)*

Esta clase no debe ser instantiated directamente. En lugar de ello, utilice [Avalanche.addAPI](avalanche.avalanche-1.md#addapi) método.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `núcleo de la` | [AvalancheCore](avalanchecore.avalanchecore-1.md) | - | Una referencia a la clase Avalanche |
| `baseurl` | cadena de producción | "/ext/admin" | Defaults to the string "/ext/admin" como la ruta hacia el baseurl de rpc |

**Returns:** *[AdminAPI](api_admin.adminapi.md)*

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

### alias

- `alias` **(endpoint:**`` string, alias: string): *Promise‹boolean›*

*Definido en [src/apis/admin/api.ts:31](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/admin/api.ts#L31)*

Asignar un alias a una API un punto final diferente para la API. El punto final original seguirá trabajo. Este cambio solo afecta a este nodo otros nodos no sabrán sobre este alias.

La API que se está ext/alias ahora puede llamarse en ext/alias

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `endpoint` | cadena de producción | El punto final original del API. final solo debe incluir la parte del punto final después de /ext/ |
| `alias` | cadena de producción | - |

**Returns:** *Promise‹boolean›*

Devuelve una promesa<boolean>conteniendo éxito, cierto para el éxito, falso para el fracaso.

___

### aliasChain

- **aliasChain**`(chain```: string, alias: string): *Promise‹boolean›*

*Definido en [src/apis/admin/api.ts:49](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/admin/api.ts#L49)*

Dé un blockchain un alias, un nombre diferente que puede ser usado en cualquier lugar del blockchain Se utiliza la identificación.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `cadena de la cadena de producción` | cadena de producción | - |
| `alias` | cadena de producción | Ahora se puede utilizar en lugar del ID de blockchain (en puntos finales de API, por ejemplo) |

**Returns:** *Promise‹boolean›*

Devuelve una promesa<boolean>conteniendo éxito, cierto para el éxito, falso para el fracaso.

___

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

### getChainAliases

- **getChainAliases**(`chain`: string): *[]Promise‹string›*

*Definido en [src/apis/admin/api.ts:65](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/admin/api.ts#L65)*

Obtén todos los alias para blockchain dado

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `cadena de la cadena de producción` | cadena de producción | ID del blockchain |

**Returns:** *Promise‹string[]›*

Devuelve una []Promise<string> que contiene alias de la cadena de bloqueo.

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

*Heredada de [JRPCAPI](common_jrpcapi.jrpcapi.md).[getRPCID](common_jrpcapi.jrpcapi.md#getrpcid)*

*Definido en [src/comm/jrpcapi.ts:69](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/jrpcapi.ts#L69)*

Devuelve el rpcid, un número de aumento estricto, a partir de 1, indicando el siguiente solicitar identificación que se enviará.

**Retornos:** *número*

___

### lockProfile

- **lockProfile**(): *Promise‹boolean›*

*Definido en [src/apis/admin/api.ts:78](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/admin/api.ts#L78)*

Dé las estadísticas de mutex del nodo al archivo especificado.

**Returns:** *Promise‹boolean›*

Promete para un booleano que sea cierto en el éxito.

___

### memoryProfile

- **memoryProfile**(): *Promise‹boolean›*

*Definido en [src/apis/admin/api.ts:88](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/admin/api.ts#L88)*

Derrama la huella de memoria actual del nodo al archivo especificado.

**Returns:** *Promise‹boolean›*

Promete para un booleano que sea cierto en el éxito.

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

___

### startCPUProfiler

- **startCPUProfiler**(): *Promise‹boolean›*

*Definido en [src/apis/admin/api.ts:99](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/admin/api.ts#L99)*

Empieza a perfilar la utilización de cpu del nodo. Derrumbará la información del perfil en el archivo especificado en parar.

**Returns:** *Promise‹boolean›*

Promete para un booleano que sea cierto en el éxito.

___

### stopCPUProfiler

- **stopCPUProfiler**(): *Promise‹boolean›*

*Definido en [src/apis/admin/api.ts:109](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/admin/api.ts#L109)*

Detenga el perfil de CPU que se había iniciado previamente.

**Returns:** *Promise‹boolean›*

Promete para un booleano que sea cierto en el éxito.
