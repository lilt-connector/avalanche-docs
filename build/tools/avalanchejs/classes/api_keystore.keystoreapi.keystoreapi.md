[avalanche](../README.md) › [API-Keystore](../modules/api_keystore.md) › [KeystoreAPI](api_keystore.keystoreapi.md)

# Clase: KeystoreAPI

Clase para interactuar con una API de nodo que está utilizando KeystoreAPI del nodo.

**ADVERTENCIA**: El KeystoreAPI debe ser utilizado por el propietario de los nodos, ya que los datos se almacenan localmente en el nodo. No confíe en el usuario root. Si no eres el propietario de los nodos, no uses esto como tu cartera.

**`comentarios`** Esto extiende la clase [JRPCAPI](common_jrpcapi.jrpcapi.md). Esta clase no debe ser llamada directamente. En cambio, utilice la función [Avalanche.addAPI](avalanche.avalanche-1.md#addapi) para registrar esta interfaz con Avalanche.

## Jerarquía

m. [JRPCAPI](common_jrpcapi.jrpcapi.md)

m. **KeystoreAPI**

## Índice de participación

### Constructores

* [constructor](api_keystore.keystoreapi.md#constructor)

### Propiedades de las propiedades

* [baseurl](api_keystore.keystoreapi.md#protected-baseurl)
* [núcleo de la](api_keystore.keystoreapi.md#protected-core)
* [db](api_keystore.keystoreapi.md#protected-db)
* [jrpcVersion](api_keystore.keystoreapi.md#protected-jrpcversion)
* [rpcid](api_keystore.keystoreapi.md#protected-rpcid)

### Métodos de trabajo

* [callMethod](api_keystore.keystoreapi.md#callmethod)
* [createUser](api_keystore.keystoreapi.md#createuser)
* [deleteUser](api_keystore.keystoreapi.md#deleteuser)
* [exportUser](api_keystore.keystoreapi.md#exportuser)
* [getBaseURL](api_keystore.keystoreapi.md#getbaseurl)
* [getDB](api_keystore.keystoreapi.md#getdb)
* [getRPCID](api_keystore.keystoreapi.md#getrpcid)
* [importUser](api_keystore.keystoreapi.md#importuser)
* [listUsers](api_keystore.keystoreapi.md#listusers)
* [setBaseURL](api_keystore.keystoreapi.md#setbaseurl)

## Constructores

### constructor

\+ **nuevo** *[KeystoreAPI(core:](api_keystore.keystoreapi.md)*`` [AvalancheCore](avalanchecore.avalanchecore-1.md), `baseurl`: string): KeystoreAPI

*Superación [JRPCAPI](common_jrpcapi.jrpcapi.md).[constructor](common_jrpcapi.jrpcapi.md#constructor)*

*Definido en [src/apis/keystore/api.ts:97](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/keystore/api.ts#L97)*

Esta clase no debe ser instantiated directamente. En lugar de ello, utilice el método [Avalanche.addAPI](avalanche.avalanche-1.md#addapi).

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `núcleo de la` | [AvalancheCore](avalanchecore.avalanchecore-1.md) | - | Una referencia a la clase Avalanche |
| `baseurl` | cadena de producción | "/ext/keystore" | Defaults to the string "/ext/keystore" como la ruta hacia el baseurl de blockchain. |

**Retornos:** *[KeystoreAPI](api_keystore.keystoreapi.md)*

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

### createUser

- **createUser**(`username`: de usuario: string, `contraseña`: string): *Promise‹boolean›*

*Definido en [src/apis/keystore/api.ts:27](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/keystore/api.ts#L27)*

Crea un usuario en la base de datos del nodo.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `Nombre de usuario` | cadena de producción | Nombre del usuario para crear |
| `contraseña` | cadena de producción | Contraseña para el usuario |

**Returns:** *Promise‹boolean›*

Promesa para un booleano con verdadero éxito

___

### deleteUser

- **deleteUser**(`username`: de usuario: string: `contraseña`: string): *Promise‹boolean›*

*Definido en [src/apis/keystore/api.ts:90](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/keystore/api.ts#L90)*

Elimina a un usuario en la base de datos del nodo.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `Nombre de usuario` | cadena de producción | Nombre del usuario para eliminar |
| `contraseña` | cadena de producción | Contraseña para el usuario |

**Returns:** *Promise‹boolean›*

Promesa para un booleano con verdadero éxito

___

### exportUser

- **exportUser**(`username`: de usuario: string: `contraseña`: string): *Promise‹string›*

*Definido en [src/apis/keystore/api.ts:44](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/keystore/api.ts#L44)*

Exporta un usuario. El usuario puede importarse a otro nodo con keystore.importUser .

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `Nombre de usuario` | cadena de producción | El nombre del usuario a exportar |
| `contraseña` | cadena de producción | La contraseña del usuario para exportar |

**Returns:** *Promise‹string›*

Promete con una cadena importUser

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

### importUser

- **importUser**(`username`: de usuario: string, `usuario`: string, `contraseña`: string): *Promise‹boolean›*

*Definido en [src/apis/keystore/api.ts:62](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/keystore/api.ts#L62)*

Importar un archivo de usuario en la base de datos de usuario del nodo y asignarlo a un nombre de usuario.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `Nombre de usuario` | cadena de producción | El nombre del archivo de usuario debe importarse en |
| `usuario` | cadena de producción | cb58 cadena serializada represetning los datos de un usuario |
| `contraseña` | cadena de producción | La contraseña del usuario |

**Returns:** *Promise‹boolean›*

Una promesa con un valor real en el éxito.

___

### listUsers

- **listUsers**(): *[]Promise‹string›*

*Definido en [src/apis/keystore/api.ts:77](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/keystore/api.ts#L77)*

Listas los nombres de todos los usuarios en el nodo.

**Returns:** *Promise‹string[]›*

Promete una matriz con todos los nombres de usuario.

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
