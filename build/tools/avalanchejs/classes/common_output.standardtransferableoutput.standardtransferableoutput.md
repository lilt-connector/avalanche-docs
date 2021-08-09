[avalancha](../README.md) › Salida [común](../modules/common_output.md) › [Salida estándar Transferible](common_output.standardtransferableoutput.md)

# Clase: Salida estándar transferible:

## Jerarquía

de salida estándar [StandardParseableOutput](common_output.standardparseableoutput.md)

de salida estándar **StandardTransferableOutput**

de salida [TransferableOutput](api_platformvm_outputs.transferableoutput.md)

de salida [TransferableOutput](api_avm_outputs.transferableoutput.md)

de salida [TransferableOutput](api_evm_outputs.transferableoutput.md)

## Índice de participación

### Constructores

* [constructor](common_output.standardtransferableoutput.md#constructor)

### Propiedades de las propiedades

* [_codecid](common_output.standardtransferableoutput.md#protected-_codecid)
* [_typeID](common_output.standardtransferableoutput.md#protected-_typeid)
* [_typeName](common_output.standardtransferableoutput.md#protected-_typename)
* [activos](common_output.standardtransferableoutput.md#protected-assetid)
* [salida de la salida de la salida](common_output.standardtransferableoutput.md#protected-output)

### Métodos de trabajo

* [deserie](common_output.standardtransferableoutput.md#deserialize)
* [deBuffer](common_output.standardtransferableoutput.md#abstract-frombuffer)
* [getAssetID](common_output.standardtransferableoutput.md#getassetid)
* [getCodecid](common_output.standardtransferableoutput.md#getcodecid)
* [getOutput](common_output.standardtransferableoutput.md#getoutput)
* [getTypeID](common_output.standardtransferableoutput.md#gettypeid)
* [getTypeName](common_output.standardtransferableoutput.md#gettypename)
* [serializar](common_output.standardtransferableoutput.md#serialize)
* [toBuffer](common_output.standardtransferableoutput.md#tobuffer)
* [comparador](common_output.standardtransferableoutput.md#static-comparator)

## Constructores

### constructor

\+ **nuevo StandardTransferableOutput(assetID: StandardTransferableOutput(assetID:**```` Buffer, salida: [Salida):](common_output.output.md) *[Producto estándar Transferible](common_output.standardtransferableoutput.md)*

*Superaciones [ParseableOutput](api_platformvm_outputs.parseableoutput.md).[constructor](api_platformvm_outputs.parseableoutput.md#constructor)*

*Definido en [src/comm/output.ts:410](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/output.ts#L410)*

Clase que representa un Producto [StandardTransferableOutput](common_output.standardtransferableoutput.md) una transacción.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `activos` | Buffer | no definido. | Un [buffer](https://github.com/feross/buffer) que representa el activo de la [salida](common_output.output.md) |
| `salida de la salida de la salida` | [Producción de productos](common_output.output.md) | no definido. | Un número que representa la InputID del Producto [StandardTransferableOutput](common_output.standardtransferableoutput.md) |

**Retornos:** *[Producto estándar transferible](common_output.standardtransferableoutput.md)*

## Propiedades de las propiedades

### _codecid `protegido`

• **_codecid**: *número* = indefinido.

*Heredada de [SigIdx](common_signature.sigidx.md)[._codecid](common_signature.sigidx.md#protected-_codecid)*

*Definido en [src/utils/serialización.ts:40](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/serialization.ts#L40)*

___

### `Protegido` _typeID

• **_typeID**: *any* = undefined

*Superpone [StandardParseableOutput](common_output.standardparseableoutput.md).[_typeID](common_output.standardparseableoutput.md#protected-_typeid)*

*Definido en [src/comm/output.ts:385](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/output.ts#L385)*

___

### _typeName `protegido`

• **_typeName**: *string* = "StandardTransferableOutput"

*Overrides [StandardParseableOutput](common_output.standardparseableoutput.md).[_typeName](common_output.standardparseableoutput.md#protected-_typename)*

*Definido en [src/comm/output.ts:384](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/output.ts#L384)*

___

### assetID `protegido`

• **assetID**: *Buffer* = indefinido.

*Definido en [src/comm/output.ts:399](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/output.ts#L399)*

___

### Producción `protegida`

• **salida**: *[Salida](common_output.output.md)*

*Heredado de [TransferableOutput](api_platformvm_outputs.transferableoutput.md).[output](api_platformvm_outputs.transferableoutput.md#protected-output)*

*Definido en [src/comm/output.ts:346](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/output.ts#L346)*

## Métodos de trabajo

### deserie

- **deserialize**(`fields`: objeto, `codificación`: [SerializedEncoding](../modules/src_utils.md#serializedencoding)): *vacío*

*Superaciones [StandardParseableInput](common_inputs.standardparseableinput.md).[deserialize](common_inputs.standardparseableinput.md#deserialize)*

*Definido en [src/comm/output.ts:394](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/output.ts#L394)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `campos de cultivo` | objeto de la operación | - |
| `codificación` | [SerializedEncoding](../modules/src_utils.md#serializedencoding) | "hex" |

**Retornos:** *vacío*

___

### `Resumen` deBuffer

- **fromBuffer**(`bytes`: Buffer, `offset?`: número): *número*

*Overrides [StandardParseableOutput](common_output.standardparseableoutput.md).[fromBuffer](common_output.standardparseableoutput.md#abstract-frombuffer)*

*Definido en [src/comm/output.ts:404](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/output.ts#L404)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `bytes` | Buffer |
| `¿Qué compensación?` | Número de números |

**Retornos:** *número*

___

### getAssetID

- **getAssetID**(): *Buffer*

*Definido en [src/comm/output.ts:401](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/output.ts#L401)*

**Returns:** *Buffer*

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

*Superaciones [ParseableOutput](api_platformvm_outputs.parseableoutput.md).[serialize](api_platformvm_outputs.parseableoutput.md#serialize)*

*Definido en [src/comm/output.ts:387](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/output.ts#L387)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `codificación` | [SerializedEncoding](../modules/src_utils.md#serializedencoding) | "hex" |

**Return:** *objeto*

___

### toBuffer

- **toBuffer** (): *Buffer*

*Supera [ParseableOutput](api_platformvm_outputs.parseableoutput.md).[toBuffer](api_platformvm_outputs.parseableoutput.md#tobuffer)*

*Definido en [src/comm/output.ts:406](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/output.ts#L406)*

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
