[avalancha](../README.md) › [Common-APIBase](../modules/common_apibase.md)[](common_apibase.apibase.md) › Common-APIBase

# Clase: APIBase

Clase abstracta que define un punto de extremo genérico que todos los puntos de final deben implementar (ampliar).

## Jerarquía

* **APIBA**

   m. [JRPCAPI](common_jrpcapi.jrpcapi.md)

   m. [RESTAPI](common_restapi.restapi.md)

## Índice de participación

### Constructores

* [constructor](common_apibase.apibase.md#constructor)

### Propiedades de las propiedades

* [baseurl](common_apibase.apibase.md#protected-baseurl)
* [núcleo de la](common_apibase.apibase.md#protected-core)
* [db](common_apibase.apibase.md#protected-db)

### Métodos de trabajo

* [getBaseURL](common_apibase.apibase.md#getbaseurl)
* [getDB](common_apibase.apibase.md#getdb)
* [setBaseURL](common_apibase.apibase.md#setbaseurl)

## Constructores

### constructor

\+ **nuevo APIbase(core:**`` [AvalancheCore](avalanchecore.avalanchecore-1.md), `baseurl`: string): *[APIbase](common_apibase.apibase.md)*

*Definido en [src/comm/apibase.ts:58](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/apibase.ts#L58)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `núcleo de la` | [AvalancheCore](avalanchecore.avalanchecore-1.md) | Referencia a la instancia de Avalanche utilizando este baseurl |
| `baseurl` | cadena de producción | Camino hacia el baseurl - ex: "/ext/bc/X" |

**Returns:** *[APIBase](common_apibase.apibase.md)*

## Propiedades de las propiedades

### Base `protegida`

• **baseurl**: *cadena*

*Definido en [src/comm/apibase.ts:28](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/apibase.ts#L28)*

___

### Correa `protegida`

• **núcleo**: *[AvalancheCore](avalanchecore.avalanchecore-1.md)*

*Definido en [src/comm/apibase.ts:26](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/apibase.ts#L26)*

___

### db `protegido`

• **db**: *StoreAPI*

*Definido en [src/comm/apibase.ts:30](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/apibase.ts#L30)*

## Métodos de trabajo

### getBaseURL

- **getBaseURL**(): *string*

*Definido en [src/comm/apibase.ts:53](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/apibase.ts#L53)*

Devuelve el camino del baseurl's

**Return:** *string*

___

### getDB

- **getDB**(): *StoreAPI*

*Definido en [src/comm/apibase.ts:58](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/apibase.ts#L58)*

Devuelve la base de datos del baseurl's

**Retornos:** *StoreAPI*

___

### setBaseURL

- **setBaseURL**(`baseurl`: string): *void*

*Definido en [src/comm/apibase.ts:37](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/apibase.ts#L37)*

Establece el camino de las API baseurl.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `baseurl` | cadena de producción | Camino de las API baseurl - ex: "/ext/bc/X" |

**Retornos:** *vacío*
