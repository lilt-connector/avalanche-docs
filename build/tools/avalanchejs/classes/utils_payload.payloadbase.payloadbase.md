[avalanche](../README.md) › [Utils-Payload](../modules/utils_payload.md)[](utils_payload.payloadbase.md)

# Clase: PayloadBase

Clase base para cargas útiles.

## Jerarquía

* **Base de datos**

   de [BINPayload](utils_payload.binpayload.md)

   [m. UTF8Carga útil](utils_payload.utf8payload.md)

   m. [HEXSTRPayload](utils_payload.hexstrpayload.md)

   m. [B58STRPayload](utils_payload.b58strpayload.md)

   m. [B64STRPayload](utils_payload.b64strpayload.md)

   de [BIGNUMPayload](utils_payload.bignumpayload.md)

   m. [ChainAddressPayload](utils_payload.chainaddresspayload.md) útil

   [m. cb58EncodeCarga de la carga de la carga](utils_payload.cb58encodedpayload.md)

   m. [JSONPayload](utils_payload.jsonpayload.md)

## Índice de participación

### Constructores

* [constructor](utils_payload.payloadbase.md#constructor)

### Propiedades de las propiedades

* [carga útil](utils_payload.payloadbase.md#protected-payload)
* [typeid](utils_payload.payloadbase.md#protected-typeid)

### Métodos de trabajo

* [deBuffer](utils_payload.payloadbase.md#frombuffer)
* [getContent](utils_payload.payloadbase.md#getcontent)
* [getPayload](utils_payload.payloadbase.md#getpayload)
* [retorno.](utils_payload.payloadbase.md#abstract-returntype)
* [toBuffer](utils_payload.payloadbase.md#tobuffer)
* [typeID](utils_payload.payloadbase.md#typeid)
* [typeName](utils_payload.payloadbase.md#typename)

## Constructores

### constructor

\+ **nueva PayloadBase():** *[PayloadBase](utils_payload.payloadbase.md)*

*Definido en [src/utils/payload.ts:230](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/payload.ts#L230)*

**Returns:** *[PayloadBase](utils_payload.payloadbase.md)*

## Propiedades de las propiedades

### Carga útil `protegida`

• **carga útil**: *Buffer* = Buffer.aloc(0)

*Definido en [src/utils/payload.ts:168](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/payload.ts#L168)*

___

### Tipo `protegido`

• **typeid**: *número* = indefinido

*Definido en [src/utils/payload.ts:169](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/payload.ts#L169)*

## Métodos de trabajo

### deBuffer

- **fromBuffer**(`bytes`: Buffer, `offset`: número): *número*

*Definido en [src/utils/payload.ts:206](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/payload.ts#L206)*

Decodifica la carga útil como un [Buffer](https://github.com/feross/buffer) incluyendo 4 bytes para la longitud y TypeID.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `bytes` | Buffer | - |
| `offset` | Número de números | 0 |

**Retornos:** *número*

___

### getContent

- **getContent**(): *Buffer*

*Definido en [src/utils/payload.ts:188](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/payload.ts#L188)*

Devuelve el contenido de carga útil (menos typeID).

**Returns:** *Buffer*

___

### getPayload

- **getPayload**(): *Buffer*

*Definido en [src/utils/payload.ts:196](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/payload.ts#L196)*

Devuelve la carga útil (con typeID).

**Returns:** *Buffer*

___

### Reseña `abstracta` Tipo

- **returnType**(...`args`: *any*): cualquier

*Definido en [src/utils/payload.ts:230](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/payload.ts#L230)*

Devuelve el tipo esperado para la carga útil.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `..args` | cualquier otra cosa que no sea |

**Retornos:** *cualquier*

___

### toBuffer

- **toBuffer** (): *Buffer*

*Definido en [src/utils/payload.ts:219](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/payload.ts#L219)*

Encodes la carga útil como [Buffer](https://github.com/feross/buffer) incluyendo 4 bytes para la longitud y TypeID.

**Returns:** *Buffer*

___

### typeID

- **typeID**(): *número*

*Definido en [src/utils/payload.ts:174](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/payload.ts#L174)*

Devuelve el TypeID para la carga útil.

**Retornos:** *número*

___

### typeName

- **typeName**(): *string*

*Definido en [src/utils/payload.ts:181](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/payload.ts#L181)*

Devuelve el nombre de cadena para el tipo de carga útil.

**Return:** *string*
