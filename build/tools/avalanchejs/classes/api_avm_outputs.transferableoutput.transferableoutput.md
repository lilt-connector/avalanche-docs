[avalanche](../README.md) › Productos [API-AVM-Outputs](../modules/api_avm_outputs.md) › [Salida transferible](api_avm_outputs.transferableoutput.md)

# Clase: Salida transferible

## Jerarquía

de salida estándar [StandardTransferableOutput](common_output.standardtransferableoutput.md)

de salida **TransferableOutput**

## Índice de participación

### Constructores

* [constructor](api_avm_outputs.transferableoutput.md#constructor)

### Propiedades de las propiedades

* [_codecid](api_avm_outputs.transferableoutput.md#protected-_codecid)
* [_typeID](api_avm_outputs.transferableoutput.md#protected-_typeid)
* [_typeName](api_avm_outputs.transferableoutput.md#protected-_typename)
* [activos](api_avm_outputs.transferableoutput.md#protected-assetid)
* [salida de la salida de la salida](api_avm_outputs.transferableoutput.md#protected-output)

### Métodos de trabajo

* [deserie](api_avm_outputs.transferableoutput.md#deserialize)
* [deBuffer](api_avm_outputs.transferableoutput.md#frombuffer)
* [getAssetID](api_avm_outputs.transferableoutput.md#getassetid)
* [getCodecid](api_avm_outputs.transferableoutput.md#getcodecid)
* [getOutput](api_avm_outputs.transferableoutput.md#getoutput)
* [getTypeID](api_avm_outputs.transferableoutput.md#gettypeid)
* [getTypeName](api_avm_outputs.transferableoutput.md#gettypename)
* [serializar](api_avm_outputs.transferableoutput.md#serialize)
* [toBuffer](api_avm_outputs.transferableoutput.md#tobuffer)
* [comparador](api_avm_outputs.transferableoutput.md#static-comparator)

## Constructores

### constructor

\+ **nueva** `TransferableOutput(assetID```: Buffer, salida: [Producto):](common_output.output.md) *[TransferableOutput](api_avm_outputs.transferableoutput.md)*

*Heredado de [TransferableOutput](api_platformvm_outputs.transferableoutput.md).[constructor](api_platformvm_outputs.transferableoutput.md#constructor)*

*Superaciones [ParseableOutput](api_platformvm_outputs.parseableoutput.md).[constructor](api_platformvm_outputs.parseableoutput.md#constructor)*

*Definido en [src/comm/output.ts:410](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/output.ts#L410)*

Clase que representa un Producto [StandardTransferableOutput](../modules/src_common.md#standardtransferableoutput) una transacción.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `activos` | Buffer | no definido. | Un [buffer](https://github.com/feross/buffer) que representa el activo de la [salida](../modules/src_common.md#output) |
| `salida de la salida de la salida` | [Producción de productos](common_output.output.md) | no definido. | Un número que representa la InputID del Producto [StandardTransferableOutput](../modules/src_common.md#standardtransferableoutput) |

**Retornos:** *[Producto transferible](api_avm_outputs.transferableoutput.md)*

## Propiedades de las propiedades

### _codecid `protegido`

• **_codecid**: *número* = indefinido.

*Heredada de [SigIdx](common_signature.sigidx.md)[._codecid](common_signature.sigidx.md#protected-_codecid)*

*Definido en [src/utils/serialización.ts:40](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/serialization.ts#L40)*

___

### `Protegido` _typeID

• **_typeID**: *any* = undefined

*Superpone [StandardTransferableOutput](common_output.standardtransferableoutput.md).[_typeID](common_output.standardtransferableoutput.md#protected-_typeid)*

*Definido en [src/apis/avm/outputs.ts:38](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/outputs.ts#L38)*

___

### _typeName `protegido`

• **_typeName**: *string* = "TransferableOutput"

*Superpone [StandardTransferableOutput](common_output.standardtransferableoutput.md).[_typeName](common_output.standardtransferableoutput.md#protected-_typename)*

*Definido en [src/apis/avm/outputs.ts:37](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/outputs.ts#L37)*

___

### assetID `protegido`

• **assetID**: *Buffer* = indefinido.

*Heredado de [TransferableOutput](api_platformvm_outputs.transferableoutput.md).[assetID](api_platformvm_outputs.transferableoutput.md#protected-assetid)*

*Definido en [src/comm/output.ts:399](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/output.ts#L399)*

___

### Producción `protegida`

• **salida**: *[Salida](common_output.output.md)*

*Heredado de [TransferableOutput](api_platformvm_outputs.transferableoutput.md).[output](api_platformvm_outputs.transferableoutput.md#protected-output)*

*Definido en [src/comm/output.ts:346](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/output.ts#L346)*

## Métodos de trabajo

### deserie

- **deserialize**(`fields`: objeto, `codificación`: [SerializedEncoding](../modules/src_utils.md#serializedencoding)): *vacío*

*Superaciones [StandardTransferableOutput](common_output.standardtransferableoutput.md).[deserialize](common_output.standardtransferableoutput.md#deserialize)*

*Definido en [src/apis/avm/outputs.ts:42](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/outputs.ts#L42)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `campos de cultivo` | objeto de la operación | - |
| `codificación` | [SerializedEncoding](../modules/src_utils.md#serializedencoding) | "hex" |

**Retornos:** *vacío*

___

### deBuffer

- **fromBuffer**(`bytes`: Buffer, `offset`: número): *número*

*Overrides [StandardTransferableOutput](common_output.standardtransferableoutput.md).[fromBuffer](common_output.standardtransferableoutput.md#abstract-frombuffer)*

*Definido en [src/apis/avm/outputs.ts:48](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/outputs.ts#L48)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `bytes` | Buffer | - |
| `offset` | Número de números | 0 |

**Retornos:** *número*

___

### getAssetID

- **getAssetID**(): *Buffer*

*Heredado de [TransferableOutput](api_platformvm_outputs.transferableoutput.md).[getAssetID](api_platformvm_outputs.transferableoutput.md#getassetid)*

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

*Heredado de [TransferableOutput](api_platformvm_outputs.transferableoutput.md).[serialize](api_platformvm_outputs.transferableoutput.md#serialize)*

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

*Heredado de [TransferableOutput](api_platformvm_outputs.transferableoutput.md).[toBuffer](api_platformvm_outputs.transferableoutput.md#tobuffer)*

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
