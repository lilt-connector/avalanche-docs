[avalanche](../README.md) › [Utils-Payload](../modules/utils_payload.md) › [cb58EncodedCarga útil](utils_payload.cb58encodedpayload.md)

# Clase: cb58EncodeCarga Payload

Clase para cargas útiles que representan datos serializados por bintools.cb58Encode().

## Jerarquía

* [Base de datos](utils_payload.payloadbase.md)

   **m. cb58EncodeCarga de la carga de la carga**

   m. [TXIDPayload](utils_payload.txidpayload.md)

   m. [ASSETIDPayload](utils_payload.assetidpayload.md)

   m. [UTXOIDPayload](utils_payload.utxoidpayload.md) útil

   m. [SUBNETIDPayload](utils_payload.subnetidpayload.md) útil

   m. [CHAINIDPayload](utils_payload.chainidpayload.md)

   n.º [NODEIDPayload](utils_payload.nodeidpayload.md) útil

## Índice de participación

### Constructores

* [constructor](utils_payload.cb58encodedpayload.md#constructor)

### Propiedades de las propiedades

* [carga útil](utils_payload.cb58encodedpayload.md#protected-payload)
* [typeid](utils_payload.cb58encodedpayload.md#protected-typeid)

### Métodos de trabajo

* [deBuffer](utils_payload.cb58encodedpayload.md#frombuffer)
* [getContent](utils_payload.cb58encodedpayload.md#getcontent)
* [getPayload](utils_payload.cb58encodedpayload.md#getpayload)
* [retorno.](utils_payload.cb58encodedpayload.md#returntype)
* [toBuffer](utils_payload.cb58encodedpayload.md#tobuffer)
* [typeID](utils_payload.cb58encodedpayload.md#typeid)
* [typeName](utils_payload.cb58encodedpayload.md#typename)

## Constructores

### constructor

\+ **nuevo** `cb58EncodePayload(carga` útil): *[cb58EncodeCarga Payload](utils_payload.cb58encodedpayload.md)*

*Desgravaciones [PayloadBase](utils_payload.payloadbase.md).[constructor](utils_payload.payloadbase.md#constructor)*

*Definido en [src/utils/payload.ts:466](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/payload.ts#L466)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `carga útil` | cualquier otra cosa que no sea | no definido. | Cadena codificada de buffer o cb58 |

**Retornos:** *[cb58EncodeCarga Payload](utils_payload.cb58encodedpayload.md)*

## Propiedades de las propiedades

### Carga útil `protegida`

• **carga útil**: *Buffer* = Buffer.aloc(0)

*Heredado de [PayloadBase](utils_payload.payloadbase.md).[payload](utils_payload.payloadbase.md#protected-payload)*

*Definido en [src/utils/payload.ts:168](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/payload.ts#L168)*

___

### Tipo `protegido`

• **typeid**: *número* = indefinido

*Heredado de [PayloadBase](utils_payload.payloadbase.md).[typeid](utils_payload.payloadbase.md#protected-typeid)*

*Definido en [src/utils/payload.ts:169](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/payload.ts#L169)*

## Métodos de trabajo

### deBuffer

- **fromBuffer**(`bytes`: Buffer, `offset`: número): *número*

*Heredada de [PayloadBase](utils_payload.payloadbase.md).[fromBuffer](utils_payload.payloadbase.md#frombuffer)*

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

*Heredado de [PayloadBase](utils_payload.payloadbase.md).[getContent](utils_payload.payloadbase.md#getcontent)*

*Definido en [src/utils/payload.ts:188](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/payload.ts#L188)*

Devuelve el contenido de carga útil (menos typeID).

**Returns:** *Buffer*

___

### getPayload

- **getPayload**(): *Buffer*

*Heredado de [PayloadBase](utils_payload.payloadbase.md).[getPayload](utils_payload.payloadbase.md#getpayload)*

*Definido en [src/utils/payload.ts:196](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/payload.ts#L196)*

Devuelve la carga útil (con typeID).

**Returns:** *Buffer*

___

### retorno.

- **returnType**(): *cadena*

*Desgravaciones [PayloadBase](utils_payload.payloadbase.md).[returnType](utils_payload.payloadbase.md#abstract-returntype)*

*Definido en [src/utils/payload.ts:464](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/payload.ts#L464)*

Devuelve una cadena codificada para la carga útil. cb58.

**Return:** *string*

___

### toBuffer

- **toBuffer** (): *Buffer*

*Heredada de [PayloadBase](utils_payload.payloadbase.md).[toBuffer](utils_payload.payloadbase.md#tobuffer)*

*Definido en [src/utils/payload.ts:219](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/payload.ts#L219)*

Encodes la carga útil como [Buffer](https://github.com/feross/buffer) incluyendo 4 bytes para la longitud y TypeID.

**Returns:** *Buffer*

___

### typeID

- **typeID**(): *número*

*Heredado de [PayloadBase](utils_payload.payloadbase.md).[typeID](utils_payload.payloadbase.md#typeid)*

*Definido en [src/utils/payload.ts:174](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/payload.ts#L174)*

Devuelve el TypeID para la carga útil.

**Retornos:** *número*

___

### typeName

- **typeName**(): *string*

*Heredado de [PayloadBase](utils_payload.payloadbase.md).[typeName](utils_payload.payloadbase.md#typename)*

*Definido en [src/utils/payload.ts:181](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/payload.ts#L181)*

Devuelve el nombre de cadena para el tipo de carga útil.

**Return:** *string*
