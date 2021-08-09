[avalanche](../README.md) › Salida [API-PlatformVM-Outputs](../modules/api_platformvm_outputs.md) Salida [ParseableOutput](api_platformvm_outputs.parseableoutput.md)

# Clase: ParseableOutput

## Jerarquía

de salida estándar [StandardParseableOutput](common_output.standardparseableoutput.md)

de **salida**

## Índice de participación

### Constructores

* [constructor](api_platformvm_outputs.parseableoutput.md#constructor)

### Propiedades de las propiedades

* [_codecid](api_platformvm_outputs.parseableoutput.md#protected-_codecid)
* [_typeID](api_platformvm_outputs.parseableoutput.md#protected-_typeid)
* [_typeName](api_platformvm_outputs.parseableoutput.md#protected-_typename)
* [salida de la salida de la salida](api_platformvm_outputs.parseableoutput.md#protected-output)

### Métodos de trabajo

* [deserie](api_platformvm_outputs.parseableoutput.md#deserialize)
* [deBuffer](api_platformvm_outputs.parseableoutput.md#frombuffer)
* [getCodecid](api_platformvm_outputs.parseableoutput.md#getcodecid)
* [getOutput](api_platformvm_outputs.parseableoutput.md#getoutput)
* [getTypeID](api_platformvm_outputs.parseableoutput.md#gettypeid)
* [getTypeName](api_platformvm_outputs.parseableoutput.md#gettypename)
* [serializar](api_platformvm_outputs.parseableoutput.md#serialize)
* [toBuffer](api_platformvm_outputs.parseableoutput.md#tobuffer)
* [comparador](api_platformvm_outputs.parseableoutput.md#static-comparator)

## Constructores

### constructor

\+ **nuevo ParseableOutput(output:**`` [salida):](common_output.output.md) *[salida](api_platformvm_outputs.parseableoutput.md)* ParseableOutput(output:

*Heredado de [ParseableOutput](api_platformvm_outputs.parseableoutput.md).[constructor](api_platformvm_outputs.parseableoutput.md#constructor)*

*Definido en [src/comm/output.ts:368](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/output.ts#L368)*

Clase que representa un [ParseableOutput](api_platformvm_outputs.parseableoutput.md) para una transacción.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `salida de la salida de la salida` | [Producción de productos](common_output.output.md) | no definido. | Número que representa la InputID de la salida [ParseableOutput](api_platformvm_outputs.parseableoutput.md) |

**Retornos:** Salida *[ParseableOutput](api_platformvm_outputs.parseableoutput.md)*

## Propiedades de las propiedades

### _codecid `protegido`

• **_codecid**: *número* = indefinido.

*Heredada de [SigIdx](common_signature.sigidx.md)[._codecid](common_signature.sigidx.md#protected-_codecid)*

*Definido en [src/utils/serialización.ts:40](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/serialization.ts#L40)*

___

### `Protegido` _typeID

• **_typeID**: *any* = undefined

*Superpone [StandardParseableOutput](common_output.standardparseableoutput.md).[_typeID](common_output.standardparseableoutput.md#protected-_typeid)*

*Definido en [src/apis/platformvm/outputs.ts:59](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/outputs.ts#L59)*

___

### _typeName `protegido`

• **_typeName**: *string* = "ParseableOutput"

*Overrides [StandardParseableOutput](common_output.standardparseableoutput.md).[_typeName](common_output.standardparseableoutput.md#protected-_typename)*

*Definido en [src/apis/platformvm/outputs.ts:58](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/outputs.ts#L58)*

___

### Producción `protegida`

• **salida**: *[Salida](common_output.output.md)*

*Heredado de [TransferableOutput](api_platformvm_outputs.transferableoutput.md).[output](api_platformvm_outputs.transferableoutput.md#protected-output)*

*Definido en [src/comm/output.ts:346](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/output.ts#L346)*

## Métodos de trabajo

### deserie

- **deserialize**(`fields`: objeto, `codificación`: [SerializedEncoding](../modules/src_utils.md#serializedencoding)): *vacío*

*Superaciones [StandardParseableInput](common_inputs.standardparseableinput.md).[deserialize](common_inputs.standardparseableinput.md#deserialize)*

*Definido en [src/apis/platformvm/outputs.ts:63](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/outputs.ts#L63)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `campos de cultivo` | objeto de la operación | - |
| `codificación` | [SerializedEncoding](../modules/src_utils.md#serializedencoding) | "hex" |

**Retornos:** *vacío*

___

### deBuffer

- **fromBuffer**(`bytes`: Buffer, `offset`: número): *número*

*Overrides [StandardParseableOutput](common_output.standardparseableoutput.md).[fromBuffer](common_output.standardparseableoutput.md#abstract-frombuffer)*

*Definido en [src/apis/platformvm/outputs.ts:69](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/outputs.ts#L69)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `bytes` | Buffer | - |
| `offset` | Número de números | 0 |

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

*Heredada de [TransferableOutput](api_platformvm_outputs.transferableoutput.md).[getOutput](api_platformvm_outputs.transferableoutput.md#getoutput)*

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

*Heredado de [ParseableOutput](api_platformvm_outputs.parseableoutput.md).[serialize](api_platformvm_outputs.parseableoutput.md#serialize)*

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

*Heredado de [ParseableOutput](api_platformvm_outputs.parseableoutput.md).[toBuffer](api_platformvm_outputs.parseableoutput.md#tobuffer)*

*Definido en [src/comm/output.ts:362](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/output.ts#L362)*

**Returns:** *Buffer*

___

### Comparador `estático`

- **comparator**(): *función*

*Heredado de [TransferableOutput](api_platformvm_outputs.transferableoutput.md).[comparator](api_platformvm_outputs.transferableoutput.md#static-comparator)*

*Definido en [src/comm/output.ts:351](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/output.ts#L351)*

Devuelve una función utilizada para ordenar una serie de [salidas de parseableOutputs](api_platformvm_outputs.parseableoutput.md)

**Retornos:** *función*

- (`a`: [StandardParseableOutput](common_output.standardparseableoutput.md), `b`: [StandardParseableOutput):](common_output.standardparseableoutput.md) *1 | -1 | 0*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `a a` | [Salida StandardParseableOutput](common_output.standardparseableoutput.md) |
| `b b` | [Salida StandardParseableOutput](common_output.standardparseableoutput.md) |
