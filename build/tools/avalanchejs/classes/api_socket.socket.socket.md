[avalancha](../README.md) › [API-Socket](../modules/api_socket.md) › [Socket](api_socket.socket.md)

# Clase: Socket

## Jerarquía

* cualquier otra cosa que no sea

   -**Socket**

## Índice de participación

### Constructores

* [constructor](api_socket.socket.md#constructor)

### Propiedades de las propiedades

* [ondear](api_socket.socket.md#onclose)
* [onerror](api_socket.socket.md#onerror)
* [onmessage](api_socket.socket.md#onmessage)
* [ondeado](api_socket.socket.md#onopen)

### Métodos de trabajo

* [cierre de la sesión](api_socket.socket.md#close)
* [enviar a un correo electrónico](api_socket.socket.md#send)

## Constructores

### constructor

\+ **new Socket**(`url`: string | URL, `opciones?`: WebSocket.ClientOptions | ClientRequestArgs): *[Socket](api_socket.socket.md)*

*Definido en [src/apis/socket/socket.ts:36](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/socket/socket.ts#L36)*

Proporciona la API para crear y gestionar una conexión de WebSocket a un servidor, así como para enviar y recibir datos sobre la conexión.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `url` | string &#124; URL | `ws://${MainnetAPI}:443/ext/bc/X/eventos` | Defaults a [MainnetAPI](../modules/utils_constants.md#const-mainnetapi) |
| `¿opciones?` | WebSocket.ClientOptions &#124; ClientRequestArgs | - | Opcional |

**Return:** *[Socket](api_socket.socket.md)*

## Propiedades de las propiedades

### ondear

• **cerca**: *cualquier*

*Definido en [src/apis/socket/socket.ts:14](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/socket/socket.ts#L14)*

___

### onerror

• **onerror**: *cualquier*

*Definido en [src/apis/socket/socket.ts:16](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/socket/socket.ts#L16)*

___

### onmessage

• **onmessage**: *cualquier*

*Definido en [src/apis/socket/socket.ts:12](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/socket/socket.ts#L12)*

___

### ondeado

• **onopen**: *cualquier*

*Definido en [src/apis/socket/socket.ts:10](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/socket/socket.ts#L10)*

## Métodos de trabajo

### cierre de la sesión

- **close**(`mcode?`: número, `datos?`: string): *void*

*Definido en [src/apis/socket/socket.ts:34](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/socket/socket.ts#L34)*

Termina la conexión completamente

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `¿Mcode?` | Número de números | Opcional |
| `¿datos?` | cadena de producción | Opcional |

**Retornos:** *vacío*

___

### enviar a un correo electrónico

- **send**(`data`: cualquiera de los datos, `cb?`: any): *nulo*

*Definido en [src/apis/socket/socket.ts:24](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/socket/socket.ts#L24)*

Enviar un mensaje al servidor

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `datos de datos` | cualquier otra cosa que no sea | - |
| `¿Cb?` | cualquier otra cosa que no sea | Opcional |

**Retornos:** *vacío*
