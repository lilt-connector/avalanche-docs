[avalanche](../README.md) › [Utils-Payload](../modules/utils_payload.md) › [UTF8Payload](utils_payload.utf8payload.md)

# Clase: UTF8Payload

Clase para cargas útiles que representan el codificación UTF8.

## Jerarquía

* [Base de datos](utils_payload.payloadbase.md)

   **m. UTF8Carga útil**

   de. [SVGPayload](utils_payload.svgpayload.md)

   m. [CSVPayload](utils_payload.csvpayload.md)

   m. [YAMLPayload](utils_payload.yamlpayload.md)

   m. [EMAILPayload](utils_payload.emailpayload.md) de pago

   m. [URLPayload](utils_payload.urlpayload.md)

   [g.](utils_payload.onionpayload.md)

   m. [MAGNETPayload](utils_payload.magnetpayload.md) de pago

## Índice de participación

### Constructores

* [constructor](utils_payload.utf8payload.md#constructor)

### Propiedades de las propiedades

* [carga útil](utils_payload.utf8payload.md#protected-payload)
* [typeid](utils_payload.utf8payload.md#protected-typeid)

### Métodos de trabajo

* [deBuffer](utils_payload.utf8payload.md#frombuffer)
* [getContent](utils_payload.utf8payload.md#getcontent)
* [getPayload](utils_payload.utf8payload.md#getpayload)
* [retorno.](utils_payload.utf8payload.md#returntype)
* [toBuffer](utils_payload.utf8payload.md#tobuffer)
* [typeID](utils_payload.utf8payload.md#typeid)
* [typeName](utils_payload.utf8payload.md#typename)

## Constructores

### constructor

\+ **nuevo UTF8Payload(carga**`` útil): *[UTF8Payload](utils_payload.utf8payload.md)*

*Desgravaciones [PayloadBase](utils_payload.payloadbase.md).[constructor](utils_payload.payloadbase.md#constructor)*

*Definido en [src/utils/payload.ts:272](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/payload.ts#L272)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `carga útil` | cualquier otra cosa que no sea | no definido. | Cadena de buffer utf8 |

**Retornos:** *[UTF8Payload](utils_payload.utf8payload.md)*

## Propiedades de las propiedades

### Carga útil `protegida`

• **carga útil**: *Buffer* = Buffer.aloc(0)

*Heredado de [PayloadBase](utils_payload.payloadbase.md).[payload](utils_payload.payloadbase.md#protected-payload)*

*Definido en [src/utils/payload.ts:168](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/payload.ts#L168)*

___

### Tipo `protegido`

• **typeid**: *número* = 1

*Descubrir [PayloadBase](utils_payload.payloadbase.md).[typeid](utils_payload.payloadbase.md#protected-typeid)*

*Definido en [src/utils/payload.ts:265](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/payload.ts#L265)*

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

*Definido en [src/utils/payload.ts:270](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/payload.ts#L270)*

Devuelve una cadena para la carga útil.

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
