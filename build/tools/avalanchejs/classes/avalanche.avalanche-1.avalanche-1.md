[avalancha](../README.md)[](avalanche.avalanche-1.md) › [Avalanche](../modules/avalanche.md) › Avalanche

# Clase: Avalanche

AvalanchejS es middleware para interactuar con Avalanche node RPC API.

Uso de ejemplo:
```js
let avalanche = new Avalanche("127.0.0.1", 9650, "https")
```

## Jerarquía

* [AvalancheCore](avalanchecore.avalanchecore-1.md)

   de **Avalanche**

## Índice de participación

### Constructores

* [constructor](avalanche.avalanche-1.md#constructor)

### Propiedades de las propiedades

* [apsis](avalanche.avalanche-1.md#protected-apis)
* [aut](avalanche.avalanche-1.md#protected-auth)
* [cabecera](avalanche.avalanche-1.md#protected-headers)
* [2000-2000-](avalanche.avalanche-1.md#protected-host)
* [hrp](avalanche.avalanche-1.md#protected-hrp)
* [2.](avalanche.avalanche-1.md#protected-ip)
* [networkID](avalanche.avalanche-1.md#protected-networkid)
* [puerto de la ciudad](avalanche.avalanche-1.md#protected-port)
* [Protocolo de Protocolo](avalanche.avalanche-1.md#protected-protocol)
* [requestConfig](avalanche.avalanche-1.md#protected-requestconfig)
* [url](avalanche.avalanche-1.md#protected-url)

### Métodos de trabajo

* [Admin](avalanche.avalanche-1.md#admin)
* [Auth](avalanche.avalanche-1.md#auth)
* [CChain](avalanche.avalanche-1.md#cchain)
* [Salud y Salud](avalanche.avalanche-1.md#health)
* [Índice de participación](avalanche.avalanche-1.md#index)
* [Información sobre la información](avalanche.avalanche-1.md#info)
* [Métricas](avalanche.avalanche-1.md#metrics)
* [NodeKeys](avalanche.avalanche-1.md#nodekeys)
* [PChain](avalanche.avalanche-1.md#pchain)
* [XChain](avalanche.avalanche-1.md#xchain)
* [_setHeaders](avalanche.avalanche-1.md#protected-_setheaders)
* [addAPI](avalanche.avalanche-1.md#addapi)
* [api](avalanche.avalanche-1.md#api)
* [eliminar las pérdidas de](avalanche.avalanche-1.md#delete)
* [Contrade](avalanche.avalanche-1.md#get)
* [getHRP](avalanche.avalanche-1.md#gethrp)
* [getHeaders](avalanche.avalanche-1.md#getheaders)
* [getHost](avalanche.avalanche-1.md#gethost)
* [getIP](avalanche.avalanche-1.md#getip)
* [getNetworkID](avalanche.avalanche-1.md#getnetworkid)
* [getPort](avalanche.avalanche-1.md#getport)
* [getProtocol](avalanche.avalanche-1.md#getprotocol)
* [getRequestConfig](avalanche.avalanche-1.md#getrequestconfig)
* [getURL](avalanche.avalanche-1.md#geturl)
* [Pareja de la parcela.](avalanche.avalanche-1.md#patch)
* [2.](avalanche.avalanche-1.md#post)
* [Pone en marcha](avalanche.avalanche-1.md#put)
* [removeAllHeaders](avalanche.avalanche-1.md#removeallheaders)
* [removeAllRequestConfigs](avalanche.avalanche-1.md#removeallrequestconfigs)
* [Remolque Header](avalanche.avalanche-1.md#removeheader)
* [removeRequestConfig](avalanche.avalanche-1.md#removerequestconfig)
* [setAddress](avalanche.avalanche-1.md#setaddress)
* [setAuthToken](avalanche.avalanche-1.md#setauthtoken)
* [setHRP](avalanche.avalanche-1.md#sethrp)
* [setHeader](avalanche.avalanche-1.md#setheader)
* [setNetworkID](avalanche.avalanche-1.md#setnetworkid)
* [setRequestConfig Config](avalanche.avalanche-1.md#setrequestconfig)

## Constructores

### constructor

\+ **new Avalanche**(`host`: string: `port`: number, `protocolo`: string, `networkID`: number, `XChainID`: string, `CChainID`: string, `hrp`: string, `skipinit`: boolean): *[Avalanche](avalanche.avalanche-1.md)*

*Overrides [AvalancheCore](avalanchecore.avalanchecore-1.md).[constructor](avalanchecore.avalanchecore-1.md#constructor)*

*Definido en [src/index.ts:88](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/index.ts#L88)*

Crea una nueva instancia de Avalanche. Establece la dirección y el puerto del cliente principal de Avalanche.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `2000-2000-` | cadena de producción | - | El nombre de host para resolver llegar a las API de Avalanche Client RPC |
| `puerto de la ciudad` | Número de números | - | El puerto para resolver llegar a las API de Avalanche Client RPC |
| `Protocolo de Protocolo` | cadena de producción | "http:" | La cadena de protocolo a utilizar antes de una "://" en una petición, ex: "http", "https", "git", "ws", etc... |
| `networkID` | Número de números | DefaultNetworkID | Establece el NetworkID de la clase. [DefaultNetworkID](../modules/utils_constants.md#const-defaultnetworkid) |
| `XChainID` | cadena de producción | no definido. | Establece el blockchainID para el AVM. Tratará de detectar, de lo contrario predeterminado "4R5p2RXDGLqaifZE4hHWH9owe34pfoBULn1DrQTWivjg8o4aH" |
| `CChainid` | cadena de producción | no definido. | Establece el blockchainID para el EVM. Tratará de detectar, de lo contrario predeterminado "2q9e4r6Mu3U68nU1fYjgbR6JvwrRx36CohpAX5UQxse55x1Q5" |
| `hrp` | cadena de producción | no definido. | La parte legible por el hombre de las direcciones bech32 |
| `skipinit` | booleano | falso | Las hojas creando las API |

**Returns:** *[Avalanche](avalanche.avalanche-1.md)*

## Propiedades de las propiedades

### Aperitivos `protegidos`

• **apis**: *objeto*

*Heredada de [AvalancheCore](avalanchecore.avalanchecore-1.md).[apis](avalanchecore.avalanchecore-1.md#protected-apis)*

*Definido en [src/avalanche.ts:29](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/avalanche.ts#L29)*

#### Declaración de tipo:

* \[ **k**: *string*\]: [APIBase](common_apibase.apibase.md)

___

### Prestaciones `protegidas`

• **auth**: *string* = undefined

*Heredada de [AvalancheCore](avalanchecore.avalanchecore-1.md).[auth](avalanchecore.avalanchecore-1.md#protected-auth)*

*Definido en [src/avalanche.ts:26](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/avalanche.ts#L26)*

___

### Encabezados `protegidos`

• **encabezados**: *objeto*

*Heredados de [AvalancheCore](avalanchecore.avalanchecore-1.md).[headers](avalanchecore.avalanchecore-1.md#protected-headers)*

*Definido en [src/avalanche.ts:27](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/avalanche.ts#L27)*

#### Declaración de tipo:

* \[ **k**: *string*\]: string

___

### Host `protegido`

• **host**: *cadena*

*Heredado de [AvalancheCore](avalanchecore.avalanchecore-1.md).[host](avalanchecore.avalanchecore-1.md#protected-host)*

*Definido en [src/avalanche.ts:23](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/avalanche.ts#L23)*

___

### hrp `protegido`

• **hrp**: *cadena* = ""

*Heredada de [AvalancheCore](avalanchecore.avalanchecore-1.md).[hrp](avalanchecore.avalanchecore-1.md#protected-hrp)*

*Definido en [src/avalanche.ts:20](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/avalanche.ts#L20)*

___

### Lab `protegido`

• **ip**: *cadena*

*Heredada de [AvalancheCore](avalanchecore.avalanchecore-1.md).[ip](avalanchecore.avalanchecore-1.md#protected-ip)*

*Definido en [src/avalanche.ts:22](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/avalanche.ts#L22)*

___

### Red `protegida`

• **networkID**: *número* = 0

*Heredada de [AvalancheCore](avalanchecore.avalanchecore-1.md).[networkID](avalanchecore.avalanchecore-1.md#protected-networkid)*

*Definido en [src/avalanche.ts:19](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/avalanche.ts#L19)*

___

### Puerto Rico `protegido`

• **puerto**: *número*

*Heredada de [AvalancheCore](avalanchecore.avalanchecore-1.md).[port](avalanchecore.avalanchecore-1.md#protected-port)*

*Definido en [src/avalanche.ts:24](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/avalanche.ts#L24)*

___

### Protocolo `protegido`

• **protocolo**: *cadena*

*Heredado de [AvalancheCore](avalanchecore.avalanchecore-1.md).[protocol](avalanchecore.avalanchecore-1.md#protected-protocol)*

*Definido en [src/avalanche.ts:21](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/avalanche.ts#L21)*

___

### Solicitud `protegida` requestConfig

• **requestConfig**: *AxiosRequestConfig*

*Heredado de [AvalancheCore](avalanchecore.avalanchecore-1.md).[requestConfig](avalanchecore.avalanchecore-1.md#protected-requestconfig)*

*Definido en [src/avalanche.ts:28](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/avalanche.ts#L28)*

___

### Urión `protegida`

• **url**: *cadena*

*Heredada de [AvalancheCore](avalanchecore.avalanchecore-1.md).[url](avalanchecore.avalanchecore-1.md#protected-url)*

*Definido en [src/avalanche.ts:25](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/avalanche.ts#L25)*

## Métodos de trabajo

### Admin

- **Admin():** *[AdminAPI](api_admin.adminapi.md)‹›*

*Definido en [src/index.ts:42](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/index.ts#L42)*

Devuelve una referencia al RPC de administración.

**Returns:** *[AdminAPI](api_admin.adminapi.md)‹›*

___

### Auth

- **Auth():** *[AuthAPI](api_auth.authapi.md)‹›*

*Definido en [src/index.ts:47](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/index.ts#L47)*

Devuelve una referencia al Auth RPC.

**Returns:** *[AuthAPI](api_auth.authapi.md)‹›*

___

### CChain

- **CChain**(): *[EVMAPI](api_evm.evmapi.md)‹›*

*Definido en [src/index.ts:52](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/index.ts#L52)*

Devuelve una referencia al EVMAPI RPC apuntado en la cadena C.

**Returns:** *[EVMAPI](api_evm.evmapi.md)‹›*

___

### Salud y Salud

- **Health():** *[HealthAPI](api_health.healthapi.md)‹›*

*Definido en [src/index.ts:62](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/index.ts#L62)*

Devuelve una referencia al RPC de Salud para un nodo.

**Returns:** *[HealthAPI](api_health.healthapi.md)‹›*

___

### Índice de participación

- **Index():** *[IndexAPI](index_auth.indexapi.md)‹›*

*Definido en [src/index.ts:67](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/index.ts#L67)*

Devuelve una referencia al Index RPC para un nodo.

**Returns:** *[IndexAPI](index_auth.indexapi.md)‹›*

___

### Información sobre la información

- **Info():** *[InfoAPI](api_info.infoapi.md)‹›*

*Definido en [src/index.ts:72](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/index.ts#L72)*

Devuelve una referencia al Info RPC para un nodo.

**Returns:** *[InfoAPI](api_info.infoapi.md)‹›*

___

### Métricas

- **Metrics():** *[MetricsAPI](api_metrics.metricsapi.md)‹›*

*Definido en [src/index.ts:77](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/index.ts#L77)*

Devuelve una referencia al RPC de Metrics.

**Returns:** *[MetricsAPI](api_metrics.metricsapi.md)‹›*

___

### NodeKeys

- **NodeKeys**(): *[KeystoreAPI](api_keystore.keystoreapi.md)‹›*

*Definido en [src/index.ts:83](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/index.ts#L83)*

Devuelve una referencia al Keystore RPC para un nodo. Lo etiquetamos "NodeKeys" para reducir confusión sobre lo que está accediendo.

**Returns:** *[KeystoreAPI](api_keystore.keystoreapi.md)‹›*

___

### PChain

- **PChain**(): *[PlatformVMAPI](api_platformvm.platformvmapi.md)‹›*

*Definido en [src/index.ts:88](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/index.ts#L88)*

Devuelve una referencia al RPC de PlatformVM apuntado en la cadena P.

**Returns:** *[PlatformVMAPI](api_platformvm.platformvmapi.md)‹›*

___

### XChain

- **XChain**(): *[AVMAPI](api_avm.avmapi.md)‹›*

*Definido en [src/index.ts:57](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/index.ts#L57)*

Devuelve una referencia al AVM RPC apuntado en la cadena X.

**Returns:** *[AVMAPI](api_avm.avmapi.md)‹›*

___

### _setHeaders `protegidos`

- **_setHeaders**(`headers`: objeto): *objeto*

*Heredado de [AvalancheCore](avalanchecore.avalanchecore-1.md).[_setHeaders](avalanchecore.avalanchecore-1.md#protected-_setheaders)*

*Definido en [src/avalanche.ts:183](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/avalanche.ts#L183)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `cabecera` | objeto de la operación |

**Return:** *objeto*

___

### addAPI

- **addAPI**‹**GA**›(`apiName`: string, `ConstructorFN`: objeto, `baseurl`: string, ...`args`: []any): *void*

*Heredado de [AvalancheCore](avalanchecore.avalanchecore-1.md).[addAPI](avalanchecore.avalanchecore-1.md#addapi)*

*Definido en [src/avalanche.ts:215](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/avalanche.ts#L215)*

Añade una API a la media deware. La API se resuelve a un RPC de un blockchain registrado.

En TypeScript:
```js
avalanche.addAPI<MyVMClass>("mychain", MyVMClass, "/ext/bc/mychain")
```

En Javascript:
```js
avalanche.addAPI("mychain", MyVMClass, "/ext/bc/mychain")
```

**Parámetros del tipo:**

- **GA**: *[APIBase](common_apibase.apibase.md)*

Clase de la API que se añade

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `apiName` | cadena de producción | - | Una etiqueta para referenciar la API en el futuro |
| `ConstructorFN` | objeto de la operación | - | Una referencia a la clase que instantiates la API |
| `baseurl` | cadena de producción | no definido. | Camino para resolver llegar a la API |
| `..args` | cualquier otra cosa que no sea[] | - | - |

**Retornos:** *vacío*

___

### api

- **api‹GA›(apiName:******`` string): *GA*

*Heredada de [AvalancheCore](avalanchecore.avalanchecore-1.md).[api](avalanchecore.avalanchecore-1.md#api)*

*Definido en [src/avalanche.ts:231](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/avalanche.ts#L231)*

Recupera una referencia a una API por su etiqueta apiName.

**Parámetros del tipo:**

- **GA**: *[APIBase](common_apibase.apibase.md)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `apiName` | cadena de producción | Nombre de la API para regresar |

**Returns:** *GA*

___

### eliminar las pérdidas de

- **delete**(`baseurl`: string: `getdata`: objeto, `encabezados`: objeto, `axiosConfig`: AxiosRequestConfig): *Promise‹[RequestResponseData](common_apibase.requestresponsedata.md)›*

*Heredado de [AvalancheCore](avalanchecore.avalanchecore-1.md).[delete](avalanchecore.avalanchecore-1.md#delete)*

*Definido en [src/avalanche.ts:306](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/avalanche.ts#L306)*

Hace una llamada DELETE a una API.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `baseurl` | cadena de producción | - | Camino a la API |
| `getdata` | objeto de la operación | - | Objeto que contiene los pares de valores clave enviados en DELETE |
| `cabecera` | objeto de la operación | {} | Una matriz de cabeceras de solicitud HTTP |
| `axiosConfig` | AxiosRequestConfig | no definido. | Configuración para la biblioteca de axios javascript que será la base del resto de parámetros |

**Return:** *Promise‹[RequestResponseData](common_apibase.requestresponsedata.md)›*

Una promesa de [RequestResponseData](common_apibase.requestresponsedata.md)

___

### Contrade

- **get(baseurl:**`` string, `getdata`: objeto, `encabezados`: objeto, `axiosConfig`: AxiosRequestConfig): *Promise‹[RequestResponseData](common_apibase.requestresponsedata.md)›*

*Heredada de [AvalancheCore](avalanchecore.avalanchecore-1.md).[get](avalanchecore.avalanchecore-1.md#get)*

*Definido en [src/avalanche.ts:283](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/avalanche.ts#L283)*

Hace una llamada de GET a una API.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `baseurl` | cadena de producción | - | Camino hacia el api |
| `getdata` | objeto de la operación | - | Objeto que contiene los pares de valores clave enviados en GET |
| `cabecera` | objeto de la operación | {} | Una matriz de cabeceras de solicitud HTTP |
| `axiosConfig` | AxiosRequestConfig | no definido. | Configuración para la biblioteca de axios javascript que será la base del resto de parámetros |

**Return:** *Promise‹[RequestResponseData](common_apibase.requestresponsedata.md)›*

Una promesa de [RequestResponseData](common_apibase.requestresponsedata.md)

___

### getHRP

- **getHRP**(): *string*

*Heredada de [AvalancheCore](avalanchecore.avalanchecore-1.md).[getHRP](avalanchecore.avalanchecore-1.md#gethrp)*

*Definido en [src/avalanche.ts:103](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/avalanche.ts#L103)*

Devuelve la parte de la red de lectura humana asociada a esta clave.

**Return:** *string*

Parte de la línea de direccionamiento Bech32 de la red [KeyPair](api_platformvm_keychain.keypair.md)

___

### getHeaders

- **getHeaders**(): *objeto*

*Heredado de [AvalancheCore](avalanchecore.avalanchecore-1.md).[getHeaders](avalanchecore.avalanchecore-1.md#getheaders)*

*Definido en [src/avalanche.ts:78](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/avalanche.ts#L78)*

Devuelve los encabezados personalizados

**Return:** *objeto*

___

### getHost

- **getHost**(): *string*

*Heredada de [AvalancheCore](avalanchecore.avalanchecore-1.md).[getHost](avalanchecore.avalanchecore-1.md#gethost)*

*Definido en [src/avalanche.ts:58](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/avalanche.ts#L58)*

Devuelve el anfitrión para el nodo Avalanche.

**Return:** *string*

___

### getIP

- **getIP**(): *cadena*

*Heredada de [AvalancheCore](avalanchecore.avalanchecore-1.md).[getIP](avalanchecore.avalanchecore-1.md#getip)*

*Definido en [src/avalanche.ts:63](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/avalanche.ts#L63)*

Devuelve la IP para el nodo Avalanche.

**Return:** *string*

___

### getNetworkID

- **getNetworkID**(): *número*

*Heredada de [AvalancheCore](avalanchecore.avalanchecore-1.md).[getNetworkID](avalanchecore.avalanchecore-1.md#getnetworkid)*

*Definido en [src/avalanche.ts:88](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/avalanche.ts#L88)*

Devuelve la red ID

**Retornos:** *número*

___

### getPort

- **getPort**(): *número*

*Heredada de [AvalancheCore](avalanchecore.avalanchecore-1.md).[getPort](avalanchecore.avalanchecore-1.md#getport)*

*Definido en [src/avalanche.ts:68](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/avalanche.ts#L68)*

Devuelve el puerto para el nodo Avalanche.

**Retornos:** *número*

___

### getProtocol

- **getProtocol**(): *cadena*

*Heredado de [AvalancheCore](avalanchecore.avalanchecore-1.md).[getProtocol](avalanchecore.avalanchecore-1.md#getprotocol)*

*Definido en [src/avalanche.ts:53](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/avalanche.ts#L53)*

Devuelve el protocolo como "http", "https", "git", "ws", etc.

**Return:** *string*

___

### getRequestConfig

- **getRequestConfig**(): *AxiosRequestConfig*

*Heredada de [AvalancheCore](avalanchecore.avalanchecore-1.md).[getRequestConfig](avalanchecore.avalanchecore-1.md#getrequestconfig)*

*Definido en [src/avalanche.ts:83](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/avalanche.ts#L83)*

Devuelve la consulta personalizada

**Return:** *AxiosRequestConfig*

___

### getURL

- **getURL**(): *string*

*Heredada de [AvalancheCore](avalanchecore.avalanchecore-1.md).[getURL](avalanchecore.avalanchecore-1.md#geturl)*

*Definido en [src/avalanche.ts:73](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/avalanche.ts#L73)*

Devuelve la URL del nodo Avalanche (ip + puerto)

**Return:** *string*

___

### Pareja de la parcela.

- **patch**(`baseurl`: string, `getdata`: objeto, `postdata`: string | objeto ArrayBuffer | ArrayBufferView, `encabezados`: objeto, `axiosConfig`: AxiosRequestConfig): *Promise‹[RequestResponseData](common_apibase.requestresponsedata.md)›*

*Heredado de [AvalancheCore](avalanchecore.avalanchecore-1.md).[patch](avalanchecore.avalanchecore-1.md#patch)*

*Definido en [src/avalanche.ts:380](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/avalanche.ts#L380)*

Hace una llamada de PATCH a una API.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `baseurl` | cadena de producción | - | Camino hacia el baseurl |
| `getdata` | objeto de la operación | - | Objeto que contiene los pares de valores clave enviados en PATCH |
| `postdata` | string &#124; objeto &#124; ArrayBuffer &#124; ArrayBufferView | - | Objeto que contiene los pares de valores clave enviados en PATCH |
| `cabecera` | objeto de la operación | {} | Una matriz de cabeceras de solicitud HTTP |
| `axiosConfig` | AxiosRequestConfig | no definido. | Configuración para la biblioteca de axios javascript que será la base del resto de parámetros |

**Return:** *Promise‹[RequestResponseData](common_apibase.requestresponsedata.md)›*

Una promesa de [RequestResponseData](common_apibase.requestresponsedata.md)

___

### 2.

- **post(baseurl:**`` string, `getdata`: objeto, `postdata`: string | objeto ArrayBuffer | ArrayBufferView, `encabezados`: objeto, `axiosConfig`: AxiosRequestConfig): *Promise‹[RequestResponseData](common_apibase.requestresponsedata.md)›*

*Heredado de [AvalancheCore](avalanchecore.avalanchecore-1.md).[post](avalanchecore.avalanchecore-1.md#post)*

*Definido en [src/avalanche.ts:330](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/avalanche.ts#L330)*

Hace una llamada POST a una API.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `baseurl` | cadena de producción | - | Camino a la API |
| `getdata` | objeto de la operación | - | Objeto que contiene los pares de valores clave enviados en POST |
| `postdata` | string &#124; objeto &#124; ArrayBuffer &#124; ArrayBufferView | - | Objeto que contiene los pares de valores clave enviados en POST |
| `cabecera` | objeto de la operación | {} | Una matriz de cabeceras de solicitud HTTP |
| `axiosConfig` | AxiosRequestConfig | no definido. | Configuración para la biblioteca de axios javascript que será la base del resto de parámetros |

**Return:** *Promise‹[RequestResponseData](common_apibase.requestresponsedata.md)›*

Una promesa de [RequestResponseData](common_apibase.requestresponsedata.md)

___

### Pone en marcha

- **put**(`baseurl`: string, `getdata`: objeto, `postdata`: string | objeto ArrayBuffer | ArrayBufferView, `encabezados`: objeto, `axiosConfig`: AxiosRequestConfig): *Promise‹[RequestResponseData](common_apibase.requestresponsedata.md)›*

*Heredada de [AvalancheCore](avalanchecore.avalanchecore-1.md).[put](avalanchecore.avalanchecore-1.md#put)*

*Definido en [src/avalanche.ts:355](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/avalanche.ts#L355)*

Hace una llamada de PUT a una API.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `baseurl` | cadena de producción | - | Camino hacia el baseurl |
| `getdata` | objeto de la operación | - | Objeto que contiene los pares de valores clave enviados en PUT |
| `postdata` | string &#124; objeto &#124; ArrayBuffer &#124; ArrayBufferView | - | Objeto que contiene los pares de valores clave enviados en PUT |
| `cabecera` | objeto de la operación | {} | Una matriz de cabeceras de solicitud HTTP |
| `axiosConfig` | AxiosRequestConfig | no definido. | Configuración para la biblioteca de axios javascript que será la base del resto de parámetros |

**Return:** *Promise‹[RequestResponseData](common_apibase.requestresponsedata.md)›*

Una promesa de [RequestResponseData](common_apibase.requestresponsedata.md)

___

### removeAllHeaders

- **removeAllHeaders**(): *vacío*

*Heredado de [AvalancheCore](avalanchecore.avalanchecore-1.md).[removeAllHeaders](avalanchecore.avalanchecore-1.md#removeallheaders)*

*Definido en [src/avalanche.ts:136](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/avalanche.ts#L136)*

Elimina todos los encabezados.

**Retornos:** *vacío*

___

### removeAllRequestConfigs

- **removeAllRequestConfigs**(): *vacío*

*Heredado de [AvalancheCore](avalanchecore.avalanchecore-1.md).[removeAllRequestConfigs](avalanchecore.avalanchecore-1.md#removeallrequestconfigs)*

*Definido en [src/avalanche.ts:166](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/avalanche.ts#L166)*

Elimina todos los configs de petición.

**Retornos:** *vacío*

___

### Remolque Header

- **removeHeader**(`key`: string): *void*

*Heredado de [AvalancheCore](avalanchecore.avalanchecore-1.md).[removeHeader](avalanchecore.avalanchecore-1.md#removeheader)*

*Definido en [src/avalanche.ts:129](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/avalanche.ts#L129)*

Elimina un encabezado personalizado previamente añadido.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `clave` | cadena de producción | Nombre de la cabecera |

**Retornos:** *vacío*

___

### removeRequestConfig

- **removeRequestConfig**(`key`: string): *void*

*Heredada de [AvalancheCore](avalanchecore.avalanchecore-1.md).[removeRequestConfig](avalanchecore.avalanchecore-1.md#removerequestconfig)*

*Definido en [src/avalanche.ts:159](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/avalanche.ts#L159)*

Elimina una solicitud previamente añadida.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `clave` | cadena de producción | Nombre de la cabecera |

**Retornos:** *vacío*

___

### setAddress

- **setAddress**(`host`: string: `port`: número, `protocolo`: string): *void*

*Heredada de [AvalancheCore](avalanchecore.avalanchecore-1.md).[setAddress](avalanchecore.avalanchecore-1.md#setaddress)*

*Definido en [src/avalanche.ts:39](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/avalanche.ts#L39)*

Establece la dirección y el puerto del cliente principal de Avalanche.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `2000-2000-` | cadena de producción | - | El nombre de host para resolver llegar a las API de Avalanche Client RPC |
| `puerto de la ciudad` | Número de números | - | El puerto para resolver llegar a las API de Avalanche Client RPC |
| `Protocolo de Protocolo` | cadena de producción | "http:" | La cadena de protocolo a utilizar antes de una "://" en una petición, ex: "http", "https", "git", "ws", etc... |

**Retornos:** *vacío*

___

### setAuthToken

- **setAuthToken**(`auth`: string): *void*

*Heredada de [AvalancheCore](avalanchecore.avalanchecore-1.md).[setAuthToken](avalanchecore.avalanchecore-1.md#setauthtoken)*

*Definido en [src/avalanche.ts:179](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/avalanche.ts#L179)*

Establece la muestra temporal de la auth utilizada para comunicarse con el nodo.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `aut` | cadena de producción | Una muestra temporal proporcionada por el nodo que permite el acceso a los puntos finales del nodo. |

**Retornos:** *vacío*

___

### setHRP

- **setHRP**(`hrp`: string): *void*

*Heredada de [AvalancheCore](avalanchecore.avalanchecore-1.md).[setHRP](avalanchecore.avalanchecore-1.md#sethrp)*

*Definido en [src/avalanche.ts:110](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/avalanche.ts#L110)*

Establece la parte de la red de lectura humana asociada a esta clave.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `hrp` | cadena de producción | Cadena para las direcciones de Bech32 legibles de lectura humana. |

**Retornos:** *vacío*

___

### setHeader

- **setHeader**(`key`: string, `valor`: string): *void*

*Heredado de [AvalancheCore](avalanchecore.avalanchecore-1.md).[setHeader](avalanchecore.avalanchecore-1.md#setheader)*

*Definido en [src/avalanche.ts:120](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/avalanche.ts#L120)*

Añade un nuevo encabezado personalizado para que se incluya con todas las peticiones.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `clave` | cadena de producción | Nombre de la cabecera |
| `valor` | cadena de producción | Valor de la cabecera |

**Retornos:** *vacío*

___

### setNetworkID

- **setNetworkID**(`netid`: número): *nul*

*Heredada de [AvalancheCore](avalanchecore.avalanchecore-1.md).[setNetworkID](avalanchecore.avalanchecore-1.md#setnetworkid)*

*Definido en [src/avalanche.ts:93](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/avalanche.ts#L93)*

Establece el networkID

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `netid` | Número de números |

**Retornos:** *vacío*

___

### setRequestConfig Config

- **setRequestConfig**(`key`: string, `valor`: string | boolean): *void*

*Heredada de [AvalancheCore](avalanchecore.avalanchecore-1.md).[setRequestConfig](avalanchecore.avalanchecore-1.md#setrequestconfig)*

*Definido en [src/avalanche.ts:150](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/avalanche.ts#L150)*

Añade un nuevo valor de config personalizado que se incluirá con todas las peticiones.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `clave` | cadena de producción | Nombre de la confección |
| `valor` | string &#124; boolean | Valor confuso |

**Retornos:** *vacío*
