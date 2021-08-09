[avalancha](../README.md) › Salida [común](../modules/common_output.md) › [Salida estándar](common_output.standardparseableoutput.md)

# Clase: StandardParseableOutput

## Jerarquía

* [Serializable](utils_serialization.serializable.md)

   de salida estándar **StandardParseableOutput**

   de [salida](api_platformvm_outputs.parseableoutput.md)

   de salida estándar [StandardTransferableOutput](common_output.standardtransferableoutput.md)

## Índice de participación

### Constructores

* [constructor](common_output.standardparseableoutput.md#constructor)

### Propiedades de las propiedades

* [_codecid](common_output.standardparseableoutput.md#protected-_codecid)
* [_typeID](common_output.standardparseableoutput.md#protected-_typeid)
* [_typeName](common_output.standardparseableoutput.md#protected-_typename)
* [salida de la salida de la salida](common_output.standardparseableoutput.md#protected-output)

### Métodos de trabajo

* [deserie](common_output.standardparseableoutput.md#deserialize)
* [deBuffer](common_output.standardparseableoutput.md#abstract-frombuffer)
* [getCodecid](common_output.standardparseableoutput.md#getcodecid)
* [getOutput](common_output.standardparseableoutput.md#getoutput)
* [getTypeID](common_output.standardparseableoutput.md#gettypeid)
* [getTypeName](common_output.standardparseableoutput.md#gettypename)
* [serializar](common_output.standardparseableoutput.md#serialize)
* [toBuffer](common_output.standardparseableoutput.md#tobuffer)
* [comparador](common_output.standardparseableoutput.md#static-comparator)

## Constructores

### constructor

\+ **nuevo StandardParseableOutput(output:**`` [salida):](common_output.output.md) *[StandardParseableOutput(output:](common_output.standardparseableoutput.md)*

*Definido en [src/comm/output.ts:368](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/output.ts#L368)*

Clase que representa un [ParseableOutput](api_platformvm_outputs.parseableoutput.md) para una transacción.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `salida de la salida de la salida` | [Producción de productos](common_output.output.md) | no definido. | Número que representa la InputID de la salida [ParseableOutput](api_platformvm_outputs.parseableoutput.md) |

**Retornos:** *[StandardParseableOutput](common_output.standardparseableoutput.md)*

## Propiedades de las propiedades

### _codecid `protegido`

• **_codecid**: *número* = indefinido.

*Heredada de [SigIdx](common_signature.sigidx.md)[._codecid](common_signature.sigidx.md#protected-_codecid)*

*Definido en [src/utils/serialización.ts:40](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/serialization.ts#L40)*

___

### `Protegido` _typeID

• **_typeID**: *any* = undefined

*Superes [Serializable](utils_serialization.serializable.md).[_typeID](utils_serialization.serializable.md#protected-_typeid)*

*Definido en [src/comm/output.ts:336](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/output.ts#L336)*

___

### _typeName `protegido`

• **_typeName**: *string* = "StandardParseableOutput"

*Superes [Serializable](utils_serialization.serializable.md).[_typeName](utils_serialization.serializable.md#protected-_typename)*

*Definido en [src/comm/output.ts:335](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/output.ts#L335)*

___

### Producción `protegida`

• **salida**: *[Salida](common_output.output.md)*

*Definido en [src/comm/output.ts:346](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/output.ts#L346)*

## Métodos de trabajo

### deserie

- **deserialize**(`fields`: objeto, `codificación?`: [SerializedEncoding](../modules/src_utils.md#serializedencoding)): *void*

*Heredada de [StandardParseableInput](common_inputs.standardparseableinput.md).[deserialize](common_inputs.standardparseableinput.md#deserialize)*

*Definido en [src/utils/serialización.ts:72](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/serialization.ts#L72)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `campos de cultivo` | objeto de la operación |
| `¿codificar?` | [SerializedEncoding](../modules/src_utils.md#serializedencoding) |

**Retornos:** *vacío*

___

### `Resumen` deBuffer

- **fromBuffer**(`bytes`: Buffer, `offset?`: número): *número*

*Definido en [src/comm/output.ts:360](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/output.ts#L360)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `bytes` | Buffer |
| `¿Qué compensación?` | Número de números |

**Retornos:** *número*

___

### getCodecid

- **getCodecid():** *número*

*Heredada de [SigIdx](common_signature.sigidx.md)[.getCodecid](common_signature.sigidx.md#getcodecid)*

*Definido en [src/utils/serialización.ts:59](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/serialization.ts#L59)*

Utilizado en serialización. Opcional. TypeID es un número para el tipo de identificación de objeto que se está saliendo.

**Retornos:** *número*

___

### getOutput

- **getOutput**(): *[Producto](common_output.output.md)*

*Definido en [src/comm/output.ts:357](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/output.ts#L357)*

**Retornos:** *[Salida](common_output.output.md)*

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

*Superaciones [Serializable](utils_serialization.serializable.md).[serialize](utils_serialization.serializable.md#serialize)*

*Definido en [src/comm/output.ts:338](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/output.ts#L338)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `codificación` | [SerializedEncoding](../modules/src_utils.md#serializedencoding) | "hex" |

**Return:** *objeto*

___

### toBuffer

- **toBuffer** (): *Buffer*

*Definido en [src/comm/output.ts:362](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/output.ts#L362)*

**Returns:** *Buffer*

___

### Comparador `estático`

- **comparator**(): *función*

*Definido en [src/comm/output.ts:351](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/output.ts#L351)*

Devuelve una función utilizada para ordenar una serie de [salidas de parseableOutputs](api_platformvm_outputs.parseableoutput.md)

**Retornos:** *función*

- (`a`: [StandardParseableOutput](common_output.standardparseableoutput.md), `b`: [StandardParseableOutput):](common_output.standardparseableoutput.md) *1 | -1 | 0*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `a a` | [Salida StandardParseableOutput](common_output.standardparseableoutput.md) |
| `b b` | [Salida StandardParseableOutput](common_output.standardparseableoutput.md) |
