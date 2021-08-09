[avalancha](../README.md) › [Salida común](../modules/common_output.md) › [Dirección](common_output.address.md)

# Clase: Dirección

Clase para representar una dirección utilizada en tipos de [salida](common_output.output.md)

## Jerarquía

[nBytes](common_nbytes.nbytes.md)

**m.**

## Índice de participación

### Constructores

* [constructor](common_output.address.md#constructor)

### Propiedades de las propiedades

* [_codecid](common_output.address.md#protected-_codecid)
* [_typeID](common_output.address.md#protected-_typeid)
* [_typeName](common_output.address.md#protected-_typename)
* [b)](common_output.address.md#protected-bsize)
* [bytes](common_output.address.md#protected-bytes)

### Métodos de trabajo

* [clon](common_output.address.md#clone)
* [crear un entorno de creación](common_output.address.md#create)
* [deserie](common_output.address.md#deserialize)
* [deBuffer](common_output.address.md#frombuffer)
* [fromString](common_output.address.md#fromstring)
* [getCodecid](common_output.address.md#getcodecid)
* [getSize](common_output.address.md#getsize)
* [getTypeID](common_output.address.md#gettypeid)
* [getTypeName](common_output.address.md#gettypename)
* [serializar](common_output.address.md#serialize)
* [toBuffer](common_output.address.md#tobuffer)
* [toString](common_output.address.md#tostring)
* [comparador](common_output.address.md#static-comparator)

## Constructores

### constructor

\+ **nueva dirección():** *[Dirección](common_output.address.md)*

*Definido en [src/comm/output.ts:79](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/output.ts#L79)*

Clase para representar una dirección utilizada en tipos de [salida](common_output.output.md)

**Returns:** *[Dirección](common_output.address.md)*

## Propiedades de las propiedades

### _codecid `protegido`

• **_codecid**: *número* = indefinido.

*Heredada de [SigIdx](common_signature.sigidx.md)[._codecid](common_signature.sigidx.md#protected-_codecid)*

*Definido en [src/utils/serialización.ts:40](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/serialization.ts#L40)*

___

### `Protegido` _typeID

• **_typeID**: *any* = undefined

*Supera [NBytes](common_nbytes.nbytes.md).[_typeID](common_nbytes.nbytes.md#protected-_typeid)*

*Definido en [src/comm/output.ts:25](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/output.ts#L25)*

___

### _typeName `protegido`

• **_typeName**: *string* = "Dirección"

*Overrides [NBytes](common_nbytes.nbytes.md).[_typeName](common_nbytes.nbytes.md#protected-_typename)*

*Definido en [src/comm/output.ts:24](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/output.ts#L24)*

___

### Tamaño del busto `protegido`

• **bsize**: *número* = 20

*Supera [NBytes](common_nbytes.nbytes.md).[bsize](common_nbytes.nbytes.md#protected-bsize)*

*Definido en [src/comm/output.ts:30](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/output.ts#L30)*

___

### Bytes `protegidos`

• **bytes**: *Buffer‹›* = Buffer.aloc(20)

*Superar [NBytes](common_nbytes.nbytes.md).[bytes](common_nbytes.nbytes.md#protected-bytes)*

*Definido en [src/comm/output.ts:29](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/output.ts#L29)*

## Métodos de trabajo

### clon

- **clone**(): *esto*

*Superar [NBytes](common_nbytes.nbytes.md).[clone](common_nbytes.nbytes.md#abstract-clone)*

*Definido en [src/comm/output.ts:71](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/output.ts#L71)*

**Returns:** *esto*

___

### crear un entorno de creación

*-* **create**(...`args`: []cualquiera

*Supera [NBytes](common_nbytes.nbytes.md).[create](common_nbytes.nbytes.md#abstract-create)*

*Definido en [src/comm/output.ts:77](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/output.ts#L77)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `..args` | cualquier otra cosa que no sea[] |

**Returns:** *esto*

___

### deserie

- **deserialize**(`fields`: objeto, `codificación`: [SerializedEncoding](../modules/src_utils.md#serializedencoding)): *vacío*

*Heredada de [Signature](common_signature.signature.md).[deserialize](common_signature.signature.md#deserialize)*

*Superaciones [StandardParseableInput](common_inputs.standardparseableinput.md).[deserialize](common_inputs.standardparseableinput.md#deserialize)*

*Definido en [src/comm/nbytes.ts:36](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/nbytes.ts#L36)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `campos de cultivo` | objeto de la operación | - |
| `codificación` | [SerializedEncoding](../modules/src_utils.md#serializedencoding) | "hex" |

**Retornos:** *vacío*

___

### deBuffer

- **fromBuffer**`(buff`: buffer, `offset`: número): *número*

*Heredada de [SigIdx](common_signature.sigidx.md).[fromBuffer](common_signature.sigidx.md#frombuffer)*

*Definido en [src/comm/nbytes.ts:74](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/nbytes.ts#L74)*

Toma un [[Buffer]], verifica su longitud y la almacena.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `buffet` | Buffer | - |
| `offset` | Número de números | 0 |

**Retornos:** *número*

El tamaño del [buffer](https://github.com/feross/buffer)

___

### fromString

- **fromString**(`addr`: string): *número*

*Overrides [SigIdx](common_signature.sigidx.md).[fromString](common_signature.sigidx.md#fromstring)*

*Definido en [src/comm/output.ts:53](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/output.ts#L53)*

Toma una cadena base-58 que contiene una [Dirección](common_output.address.md), la analiza, populates la clase y devuelve la longitud de la Dirección en bytes.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `addr` | cadena de producción |

**Retornos:** *número*

La longitud de la [dirección](common_output.address.md) cruda

___

### getCodecid

- **getCodecid():** *número*

*Heredada de [SigIdx](common_signature.sigidx.md)[.getCodecid](common_signature.sigidx.md#getcodecid)*

*Definido en [src/utils/serialización.ts:59](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/serialization.ts#L59)*

Utilizado en serialización. Opcional. TypeID es un número para el tipo de identificación de objeto que se está saliendo.

**Retornos:** *número*

___

### getSize

- **getSize**(): *número*

*Heredada de [SigIdx](common_signature.sigidx.md).[getSize](common_signature.sigidx.md#getsize)*

*Definido en [src/comm/nbytes.ts:50](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/nbytes.ts#L50)*

Devuelve la longitud del [buffer](https://github.com/feross/buffer).

**Retornos:** *número*

El requisito de longitud exacta de esta clase

___

### getTypeID

- **getTypeID**(): *número*

*Heredada de [SigIdx](common_signature.sigidx.md).[getTypeID](common_signature.sigidx.md#gettypeid)*

*Definido en [src/utils/serialización.ts:52](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/serialization.ts#L52)*

Utilizado en serialización. Opcional. TypeID es un número para el tipo de identificación de objeto que se está saliendo.

**Retornos:** *número*

___

### getTypeName

- **getTypeName**(): *string*

*Heredada de [SigIdx](common_signature.sigidx.md).[getTypeName](common_signature.sigidx.md#gettypename)*

*Definido en [src/utils/serialización.ts:45](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/serialization.ts#L45)*

Utilizado en serialización. TypeName es un nombre de cadena para el tipo de objeto que se está saliendo.

**Return:** *string*

___

### serializar

- **serialize**(`encoding`: [SerializedEncoding](../modules/src_utils.md#serializedencoding)): *objeto*

*Heredada de [Signature](common_signature.signature.md).[serialize](common_signature.signature.md#serialize)*

*Superaciones [Serializable](utils_serialization.serializable.md).[serialize](utils_serialization.serializable.md#serialize)*

*Definido en [src/comm/nbytes.ts:28](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/nbytes.ts#L28)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `codificación` | [SerializedEncoding](../modules/src_utils.md#serializedencoding) | "hex" |

**Return:** *objeto*

___

### toBuffer

- **toBuffer** (): *Buffer*

*Heredada de [SigIdx](common_signature.sigidx.md).[toBuffer](common_signature.sigidx.md#tobuffer)*

*Definido en [src/comm/nbytes.ts:94](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/nbytes.ts#L94)*

**Returns:** *Buffer*

Una referencia al [buffer](https://github.com/feross/buffer) almacenado

___

### toString

- **toString**(): *string*

*Supera [SigIdx](common_signature.sigidx.md).[toString](common_signature.sigidx.md#tostring)*

*Definido en [src/comm/output.ts:42](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/output.ts#L42)*

Devuelve una representación base-58 de la [Dirección](common_output.address.md).

**Return:** *string*

___

### Comparador `estático`

- **comparator**(): *función*

*Definido en [src/comm/output.ts:35](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/output.ts#L35)*

Devuelve una función utilizada para ordenar una serie de [direcciones](common_output.address.md)

**Retornos:** *función*

- (`a`: [Dirección](common_output.address.md), `b`: [Dirección):](common_output.address.md) *1 | -1 | 0*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `a a` | [Dirección General de Dirección](common_output.address.md) |
| `b b` | [Dirección General de Dirección](common_output.address.md) |
