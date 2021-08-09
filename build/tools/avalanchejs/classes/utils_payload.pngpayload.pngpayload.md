[avalanche](../README.md) › [Utils-Payload](../modules/utils_payload.md) › [PNGPayload](utils_payload.pngpayload.md)

# Clase: PNGPayload

## Jerarquía

de [BINPayload](utils_payload.binpayload.md)

m. **PNGPayload**

## Índice de participación

### Constructores

* [constructor](utils_payload.pngpayload.md#constructor)

### Propiedades de las propiedades

* [carga útil](utils_payload.pngpayload.md#protected-payload)
* [typeid](utils_payload.pngpayload.md#protected-typeid)

### Métodos de trabajo

* [deBuffer](utils_payload.pngpayload.md#frombuffer)
* [getContent](utils_payload.pngpayload.md#getcontent)
* [getPayload](utils_payload.pngpayload.md#getpayload)
* [retorno.](utils_payload.pngpayload.md#returntype)
* [toBuffer](utils_payload.pngpayload.md#tobuffer)
* [typeID](utils_payload.pngpayload.md#typeid)
* [typeName](utils_payload.pngpayload.md#typename)

## Constructores

### constructor

\+ **nuevo PNGPayload(payload:**`` útil): *[PNGPayload(payload:](utils_payload.pngpayload.md)*

*Heredada de [BINPayload](utils_payload.binpayload.md).[constructor](utils_payload.binpayload.md#constructor)*

*Desgravaciones [PayloadBase](utils_payload.payloadbase.md).[constructor](utils_payload.payloadbase.md#constructor)*

*Definido en [src/utils/payload.ts:247](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/payload.ts#L247)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `carga útil` | cualquier otra cosa que no sea | no definido. | Buffer solo |

**Retornos:** *[PNGPayload](utils_payload.pngpayload.md)*

## Propiedades de las propiedades

### Carga útil `protegida`

• **carga útil**: *Buffer* = Buffer.aloc(0)

*Heredado de [PayloadBase](utils_payload.payloadbase.md).[payload](utils_payload.payloadbase.md#protected-payload)*

*Definido en [src/utils/payload.ts:168](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/payload.ts#L168)*

___

### Tipo `protegido`

• **typeid**: *número* = 19

*Superar [BINPayload](utils_payload.binpayload.md).[typeid](utils_payload.binpayload.md#protected-typeid)*

*Definido en [src/utils/payload.ts:553](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/payload.ts#L553)*

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

- **returnType**(): *Buffer*

*Heredado de [BINPayload](utils_payload.binpayload.md).[returnType](utils_payload.binpayload.md#returntype)*

*Desgravaciones [PayloadBase](utils_payload.payloadbase.md).[returnType](utils_payload.payloadbase.md#abstract-returntype)*

*Definido en [src/utils/payload.ts:245](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/payload.ts#L245)*

Devuelve un [Buffer](https://github.com/feross/buffer) para la carga útil.

**Returns:** *Buffer*

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
