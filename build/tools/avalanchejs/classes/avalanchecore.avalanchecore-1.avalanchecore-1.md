[avalancha](../README.md) › [AvalancheCore](../modules/avalanchecore.md) › [AvalancheCore](avalanchecore.avalanchecore-1.md)

# Clase: AvalancheCore

AvalancheCore es middleware para interactuar con Avalanche node RPC API.

Uso de ejemplo:
```js
let avalanche = new AvalancheCore("127.0.0.1", 9650, "https")
```

## Jerarquía

* **AvalancheCore**

   de [Avalanche](avalanche.avalanche-1.md)

## Índice de participación

### Constructores

* [constructor](avalanchecore.avalanchecore-1.md#constructor)

### Propiedades de las propiedades

* [apsis](avalanchecore.avalanchecore-1.md#protected-apis)
* [aut](avalanchecore.avalanchecore-1.md#protected-auth)
* [cabecera](avalanchecore.avalanchecore-1.md#protected-headers)
* [2000-2000-](avalanchecore.avalanchecore-1.md#protected-host)
* [hrp](avalanchecore.avalanchecore-1.md#protected-hrp)
* [2.](avalanchecore.avalanchecore-1.md#protected-ip)
* [networkID](avalanchecore.avalanchecore-1.md#protected-networkid)
* [puerto de la ciudad](avalanchecore.avalanchecore-1.md#protected-port)
* [Protocolo de Protocolo](avalanchecore.avalanchecore-1.md#protected-protocol)
* [requestConfig](avalanchecore.avalanchecore-1.md#protected-requestconfig)
* [url](avalanchecore.avalanchecore-1.md#protected-url)

### Métodos de trabajo

* [_setHeaders](avalanchecore.avalanchecore-1.md#protected-_setheaders)
* [addAPI](avalanchecore.avalanchecore-1.md#addapi)
* [api](avalanchecore.avalanchecore-1.md#api)
* [eliminar las pérdidas de](avalanchecore.avalanchecore-1.md#delete)
* [Contrade](avalanchecore.avalanchecore-1.md#get)
* [getHRP](avalanchecore.avalanchecore-1.md#gethrp)
* [getHeaders](avalanchecore.avalanchecore-1.md#getheaders)
* [getHost](avalanchecore.avalanchecore-1.md#gethost)
* [getIP](avalanchecore.avalanchecore-1.md#getip)
* [getNetworkID](avalanchecore.avalanchecore-1.md#getnetworkid)
* [getPort](avalanchecore.avalanchecore-1.md#getport)
* [getProtocol](avalanchecore.avalanchecore-1.md#getprotocol)
* [getRequestConfig](avalanchecore.avalanchecore-1.md#getrequestconfig)
* [getURL](avalanchecore.avalanchecore-1.md#geturl)
* [Pareja de la parcela.](avalanchecore.avalanchecore-1.md#patch)
* [2.](avalanchecore.avalanchecore-1.md#post)
* [Pone en marcha](avalanchecore.avalanchecore-1.md#put)
* [removeAllHeaders](avalanchecore.avalanchecore-1.md#removeallheaders)
* [removeAllRequestConfigs](avalanchecore.avalanchecore-1.md#removeallrequestconfigs)
* [Remolque Header](avalanchecore.avalanchecore-1.md#removeheader)
* [removeRequestConfig](avalanchecore.avalanchecore-1.md#removerequestconfig)
* [setAddress](avalanchecore.avalanchecore-1.md#setaddress)
* [setAuthToken](avalanchecore.avalanchecore-1.md#setauthtoken)
* [setHRP](avalanchecore.avalanchecore-1.md#sethrp)
* [setHeader](avalanchecore.avalanchecore-1.md#setheader)
* [setNetworkID](avalanchecore.avalanchecore-1.md#setnetworkid)
* [setRequestConfig Config](avalanchecore.avalanchecore-1.md#setrequestconfig)

## Constructores

### constructor

\+ **nuevo** AvalancheCore(`host`: string: `port`: número, `protocolo`: string): *[AvalancheCore](avalanchecore.avalanchecore-1.md)*

*Definido en [src/avalanche.ts:390](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/avalanche.ts#L390)*

Crea una nueva instancia de Avalanche. Establece la dirección y el puerto del cliente principal de Avalanche.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `2000-2000-` | cadena de producción | - | El nombre de host para resolver llegar a las API de cliente de Avalanche |
| `puerto de la ciudad` | Número de números | - | El puerto para resolver llegar a las API de cliente de Avalanche |
| `Protocolo de Protocolo` | cadena de producción | "http:" | La cadena de protocolo a utilizar antes de una "://" en una petición, ex: "http", "https", "git", "ws", etc... |

**Returns:** *[AvalancheCore](avalanchecore.avalanchecore-1.md)*

## Propiedades de las propiedades

### Aperitivos `protegidos`

• **apis**: *objeto*

*Definido en [src/avalanche.ts:29](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/avalanche.ts#L29)*

#### Declaración de tipo:

* \[ **k**: *string*\]: [APIBase](common_apibase.apibase.md)

___

### Prestaciones `protegidas`

• **auth**: *string* = undefined

*Definido en [src/avalanche.ts:26](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/avalanche.ts#L26)*

___

### Encabezados `protegidos`

• **encabezados**: *objeto*

*Definido en [src/avalanche.ts:27](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/avalanche.ts#L27)*

#### Declaración de tipo:

* \[ **k**: *string*\]: string

___

### Host `protegido`

• **host**: *cadena*

*Definido en [src/avalanche.ts:23](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/avalanche.ts#L23)*

___

### hrp `protegido`

• **hrp**: *cadena* = ""

*Definido en [src/avalanche.ts:20](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/avalanche.ts#L20)*

___

### Lab `protegido`

• **ip**: *cadena*

*Definido en [src/avalanche.ts:22](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/avalanche.ts#L22)*

___

### Red `protegida`

• **networkID**: *número* = 0

*Definido en [src/avalanche.ts:19](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/avalanche.ts#L19)*

___

### Puerto Rico `protegido`

• **puerto**: *número*

*Definido en [src/avalanche.ts:24](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/avalanche.ts#L24)*

___

### Protocolo `protegido`

• **protocolo**: *cadena*

*Definido en [src/avalanche.ts:21](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/avalanche.ts#L21)*

___

### Solicitud `protegida` requestConfig

• **requestConfig**: *AxiosRequestConfig*

*Definido en [src/avalanche.ts:28](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/avalanche.ts#L28)*

___

### Urión `protegida`

• **url**: *cadena*

*Definido en [src/avalanche.ts:25](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/avalanche.ts#L25)*

## Métodos de trabajo

### _setHeaders `protegidos`

- **_setHeaders**(`headers`: objeto): *objeto*

*Definido en [src/avalanche.ts:183](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/avalanche.ts#L183)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `cabecera` | objeto de la operación |

**Return:** *objeto*

___

### addAPI

- **addAPI**‹**GA**›(`apiName`: string, `ConstructorFN`: objeto, `baseurl`: string, ...`args`: []any): *void*

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

*Definido en [src/avalanche.ts:103](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/avalanche.ts#L103)*

Devuelve la parte de la red de lectura humana asociada a esta clave.

**Return:** *string*

Parte de la línea de direccionamiento Bech32 de la red [KeyPair](api_platformvm_keychain.keypair.md)

___

### getHeaders

- **getHeaders**(): *objeto*

*Definido en [src/avalanche.ts:78](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/avalanche.ts#L78)*

Devuelve los encabezados personalizados

**Return:** *objeto*

___

### getHost

- **getHost**(): *string*

*Definido en [src/avalanche.ts:58](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/avalanche.ts#L58)*

Devuelve el anfitrión para el nodo Avalanche.

**Return:** *string*

___

### getIP

- **getIP**(): *cadena*

*Definido en [src/avalanche.ts:63](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/avalanche.ts#L63)*

Devuelve la IP para el nodo Avalanche.

**Return:** *string*

___

### getNetworkID

- **getNetworkID**(): *número*

*Definido en [src/avalanche.ts:88](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/avalanche.ts#L88)*

Devuelve la red ID

**Retornos:** *número*

___

### getPort

- **getPort**(): *número*

*Definido en [src/avalanche.ts:68](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/avalanche.ts#L68)*

Devuelve el puerto para el nodo Avalanche.

**Retornos:** *número*

___

### getProtocol

- **getProtocol**(): *cadena*

*Definido en [src/avalanche.ts:53](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/avalanche.ts#L53)*

Devuelve el protocolo como "http", "https", "git", "ws", etc.

**Return:** *string*

___

### getRequestConfig

- **getRequestConfig**(): *AxiosRequestConfig*

*Definido en [src/avalanche.ts:83](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/avalanche.ts#L83)*

Devuelve la consulta personalizada

**Return:** *AxiosRequestConfig*

___

### getURL

- **getURL**(): *string*

*Definido en [src/avalanche.ts:73](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/avalanche.ts#L73)*

Devuelve la URL del nodo Avalanche (ip + puerto)

**Return:** *string*

___

### Pareja de la parcela.

- **patch**(`baseurl`: string, `getdata`: objeto, `postdata`: string | objeto ArrayBuffer | ArrayBufferView, `encabezados`: objeto, `axiosConfig`: AxiosRequestConfig): *Promise‹[RequestResponseData](common_apibase.requestresponsedata.md)›*

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

*Definido en [src/avalanche.ts:136](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/avalanche.ts#L136)*

Elimina todos los encabezados.

**Retornos:** *vacío*

___

### removeAllRequestConfigs

- **removeAllRequestConfigs**(): *vacío*

*Definido en [src/avalanche.ts:166](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/avalanche.ts#L166)*

Elimina todos los configs de petición.

**Retornos:** *vacío*

___

### Remolque Header

- **removeHeader**(`key`: string): *void*

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

*Definido en [src/avalanche.ts:150](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/avalanche.ts#L150)*

Añade un nuevo valor de config personalizado que se incluirá con todas las peticiones.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `clave` | cadena de producción | Nombre de la confección |
| `valor` | string &#124; boolean | Valor confuso |

**Retornos:** *vacío*
