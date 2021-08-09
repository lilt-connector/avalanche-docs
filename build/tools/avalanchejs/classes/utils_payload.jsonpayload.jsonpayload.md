[avalanche](../README.md) › [Utils-Payload](../modules/utils_payload.md) › [JSONPayload](utils_payload.jsonpayload.md)

# Clase: JSONPayload

Clase para cargas útiles que representan las cadenas JSON.

## Jerarquía

* [Base de datos](utils_payload.payloadbase.md)

   m. **JSONPayload**

## Índice de participación

### Constructores

* [constructor](utils_payload.jsonpayload.md#constructor)

### Propiedades de las propiedades

* [carga útil](utils_payload.jsonpayload.md#protected-payload)
* [typeid](utils_payload.jsonpayload.md#protected-typeid)

### Métodos de trabajo

* [deBuffer](utils_payload.jsonpayload.md#frombuffer)
* [getContent](utils_payload.jsonpayload.md#getcontent)
* [getPayload](utils_payload.jsonpayload.md#getpayload)
* [retorno.](utils_payload.jsonpayload.md#returntype)
* [toBuffer](utils_payload.jsonpayload.md#tobuffer)
* [typeID](utils_payload.jsonpayload.md#typeid)
* [typeName](utils_payload.jsonpayload.md#typename)

## Constructores

### constructor

\+ **nuevo** `JSONPayload(payload)`: *[JSONPayload(payload:](utils_payload.jsonpayload.md)*

*Desgravaciones [PayloadBase](utils_payload.payloadbase.md).[constructor](utils_payload.payloadbase.md#constructor)*

*Definido en [src/utils/payload.ts:595](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/payload.ts#L595)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `carga útil` | cualquier otra cosa que no sea | no definido. |

**Returns:** *[JSONPayload](utils_payload.jsonpayload.md)*

## Propiedades de las propiedades

### Carga útil `protegida`

• **carga útil**: *Buffer* = Buffer.aloc(0)

*Heredado de [PayloadBase](utils_payload.payloadbase.md).[payload](utils_payload.payloadbase.md#protected-payload)*

*Definido en [src/utils/payload.ts:168](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/payload.ts#L168)*

___

### Tipo `protegido`

• **typeid**: *número* = 24

*Descubrir [PayloadBase](utils_payload.payloadbase.md).[typeid](utils_payload.payloadbase.md#protected-typeid)*

*Definido en [src/utils/payload.ts:588](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/payload.ts#L588)*

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

- **returnType**(): *cualquier*

*Desgravaciones [PayloadBase](utils_payload.payloadbase.md).[returnType](utils_payload.payloadbase.md#abstract-returntype)*

*Definido en [src/utils/payload.ts:593](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/payload.ts#L593)*

Devuelve un objeto decodificado JSON para la carga útil.

**Retornos:** *cualquier*

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
