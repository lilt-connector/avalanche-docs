[avalanche](../README.md) › [API-Auth](../modules/api_auth.md) › [AuthAPI](api_auth.authapi.md)

# Clase: AuthAPI

Clase para interactuar con la AuthAPI de un nodo.

**`comentarios`** Esto extiende la clase [JRPCAPI](common_jrpcapi.jrpcapi.md). Esta clase no debe ser llamada directamente. En cambio, utilice la función [Avalanche.addAPI](avalanche.avalanche-1.md#addapi) para registrar esta interfaz con Avalanche.

## Jerarquía

m. [JRPCAPI](common_jrpcapi.jrpcapi.md)

m. **AuthAPI**

## Índice de participación

### Constructores

* [constructor](api_auth.authapi.md#constructor)

### Propiedades de las propiedades

* [baseurl](api_auth.authapi.md#protected-baseurl)
* [núcleo de la](api_auth.authapi.md#protected-core)
* [db](api_auth.authapi.md#protected-db)
* [jrpcVersion](api_auth.authapi.md#protected-jrpcversion)
* [rpcid](api_auth.authapi.md#protected-rpcid)

### Métodos de trabajo

* [callMethod](api_auth.authapi.md#callmethod)
* [cambio contraseña](api_auth.authapi.md#changepassword)
* [getBaseURL](api_auth.authapi.md#getbaseurl)
* [getDB](api_auth.authapi.md#getdb)
* [getRPCID](api_auth.authapi.md#getrpcid)
* [newToken](api_auth.authapi.md#newtoken)
* [revokeToken](api_auth.authapi.md#revoketoken)
* [setBaseURL](api_auth.authapi.md#setbaseurl)

## Constructores

### constructor

\+ **nuevo AuthAPI(core:**`` [AvalancheCore](avalanchecore.avalanchecore-1.md), `baseurl`: string): *[AuthAPI](api_auth.authapi.md)*

*Superación [JRPCAPI](common_jrpcapi.jrpcapi.md).[constructor](common_jrpcapi.jrpcapi.md#constructor)*

*Definido en [src/apis/auth/api.ts:67](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/auth/api.ts#L67)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `núcleo de la` | [AvalancheCore](avalanchecore.avalanchecore-1.md) | - |
| `baseurl` | cadena de producción | "/ext/auth" |

**Returns:** *[AuthAPI](api_auth.authapi.md)*

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

### cambio contraseña

- **changePassword(oldPassword:**`` string, `changePassword(oldPassword`: string): *Promise‹boolean›*

*Definido en [src/apis/auth/api.ts:60](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/auth/api.ts#L60)*

Cambie la contraseña de registro de autorización de este nodo. **Cualquier ficha de autorización creada bajo una contraseña antigua se volverá inválida.**

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `oldPassword oldPassword` | cadena de producción | La contraseña de registro de autorización de este nodo, fijada a través del CLI cuando se lanzó el nodo. |
| `newPassword nueva` | cadena de producción | Una nueva contraseña para la emisión de la ficha de autorización de este nodo. |

**Returns:** *Promise‹boolean›*

Devuelve una promesa<boolean>indicando si la contraseña fue cambiada con éxito.

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

*Heredada de [JRPCAPI](common_jrpcapi.jrpcapi.md).[getRPCID](common_jrpcapi.jrpcapi.md#getrpcid)*

*Definido en [src/comm/jrpcapi.ts:69](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/jrpcapi.ts#L69)*

Devuelve el rpcid, un número de aumento estricto, a partir de 1, indicando el siguiente solicitar identificación que se enviará.

**Retornos:** *número*

___

### newToken

- **newToken**(`password`: string, `endpoints`: []string): *Promise‹string›*

*Definido en [src/apis/auth/api.ts:25](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/auth/api.ts#L25)*

Crea una nueva ficha de autorización que otorga acceso a uno o más puntos finales de API.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `contraseña` | cadena de producción | La contraseña de registro de autorización de este nodo, fijada a través del CLI cuando se lanzó el nodo. |
| `endpoints` | cadena de producción[] | Una lista de puntos de final que será accesible utilizando el token generado. Si hay un elemento que es "*", esta ficha puede alcanzar cualquier punto final. |

**Returns:** *Promise‹string›*

Devuelve una promesa<string>que contiene el token de autorización.

___

### revokeToken

- **revokeToken**(`password`: string, `token`: string): *Promise‹boolean›*

*Definido en [src/apis/auth/api.ts:43](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/auth/api.ts#L43)*

Revoque una indicación de autorización, eliminando todos sus derechos a acceder a los puntos finales.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `contraseña` | cadena de producción | La contraseña de registro de autorización de este nodo, fijada a través del CLI cuando se lanzó el nodo. |
| `token` | cadena de producción | Una ficha de autorización cuyo acceso debe ser revocado. |

**Returns:** *Promise‹boolean›*

Devuelve una promesa<boolean>indicando si una muestra fue revocada con éxito.

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
