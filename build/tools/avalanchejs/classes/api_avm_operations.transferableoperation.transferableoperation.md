[avalanche](../README.md) › Operaciones [API-AVM-Operations](../modules/api_avm_operations.md) [Operación Transferible](api_avm_operations.transferableoperation.md)

# Clase: Operación Transferible

Una clase que contiene una [Operación](api_avm_operations.operation.md) para transferencias.

## Jerarquía

* [Serializable](utils_serialization.serializable.md)

   de **la operación transferible**

## Índice de participación

### Constructores

* [constructor](api_avm_operations.transferableoperation.md#constructor)

### Propiedades de las propiedades

* [_codecid](api_avm_operations.transferableoperation.md#protected-_codecid)
* [_typeID](api_avm_operations.transferableoperation.md#protected-_typeid)
* [_typeName](api_avm_operations.transferableoperation.md#protected-_typename)
* [activos](api_avm_operations.transferableoperation.md#protected-assetid)
* [operación de operación](api_avm_operations.transferableoperation.md#protected-operation)
* [utxoIDs](api_avm_operations.transferableoperation.md#protected-utxoids)

### Métodos de trabajo

* [deserie](api_avm_operations.transferableoperation.md#deserialize)
* [deBuffer](api_avm_operations.transferableoperation.md#frombuffer)
* [getAssetID](api_avm_operations.transferableoperation.md#getassetid)
* [getCodecid](api_avm_operations.transferableoperation.md#getcodecid)
* [getOperation](api_avm_operations.transferableoperation.md#getoperation)
* [getTypeID](api_avm_operations.transferableoperation.md#gettypeid)
* [getTypeName](api_avm_operations.transferableoperation.md#gettypename)
* [getUTXOIDs](api_avm_operations.transferableoperation.md#getutxoids)
* [serializar](api_avm_operations.transferableoperation.md#serialize)
* [toBuffer](api_avm_operations.transferableoperation.md#tobuffer)
* [comparador](api_avm_operations.transferableoperation.md#static-comparator)

## Constructores

### constructor

\+ **nuevo** `TransferableOperation(assetID`: Buffer, `TransferableOperation(assetID`: [UTXOID](api_avm_operations.utxoid.md) []| string []| []Buffer, `operación`: [Operación):](api_avm_operations.operation.md) *[TransferableOperation](api_avm_operations.transferableoperation.md)*

*Definido en [src/apis/avm/ops.ts:242](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/ops.ts#L242)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `activos` | Buffer | no definido. |
| `utxoids` | [UTXOID](api_avm_operations.utxoid.md) &#124; cadena [][]&#124; Buffer[] | no definido. |
| `operación de operación` | [Operación de las Naciones Unidas en Desarrollo](api_avm_operations.operation.md) | no definido. |

**Retornos:** *[Operación Transferible](api_avm_operations.transferableoperation.md)*

## Propiedades de las propiedades

### _codecid `protegido`

• **_codecid**: *número* = indefinido.

*Heredada de [SigIdx](common_signature.sigidx.md)[._codecid](common_signature.sigidx.md#protected-_codecid)*

*Definido en [src/utils/serialización.ts:40](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/serialization.ts#L40)*

___

### `Protegido` _typeID

• **_typeID**: *any* = undefined

*Superes [Serializable](utils_serialization.serializable.md).[_typeID](utils_serialization.serializable.md#protected-_typeid)*

*Definido en [src/apis/avm/ops.ts:156](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/ops.ts#L156)*

___

### _typeName `protegido`

• **_typeName**: *string* = "TransferableOperation"

*Superes [Serializable](utils_serialization.serializable.md).[_typeName](utils_serialization.serializable.md#protected-_typename)*

*Definido en [src/apis/avm/ops.ts:155](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/ops.ts#L155)*

___

### assetID `protegido`

• **assetID**: *Buffer* = Buffer.aloc(32)

*Definido en [src/apis/avm/ops.ts:179](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/ops.ts#L179)*

___

### Operación `protegida`

• **operación***[: Operación](api_avm_operations.operation.md)*

*Definido en [src/apis/avm/ops.ts:181](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/ops.ts#L181)*

___

### UtxoIDs `protegidos`

• **utxoID**: *[UTXOID](api_avm_operations.utxoid.md)[]* =[]

*Definido en [src/apis/avm/ops.ts:180](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/ops.ts#L180)*

## Métodos de trabajo

### deserie

- **deserialize**(`fields`: objeto, `codificación`: [SerializedEncoding](../modules/src_utils.md#serializedencoding)): *vacío*

*Superaciones [StandardParseableInput](common_inputs.standardparseableinput.md).[deserialize](common_inputs.standardparseableinput.md#deserialize)*

*Definido en [src/apis/avm/ops.ts:167](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/ops.ts#L167)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `campos de cultivo` | objeto de la operación | - |
| `codificación` | [SerializedEncoding](../modules/src_utils.md#serializedencoding) | "hex" |

**Retornos:** *vacío*

___

### deBuffer

- **fromBuffer**(`bytes`: Buffer, `offset`: número): *número*

*Definido en [src/apis/avm/ops.ts:206](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/ops.ts#L206)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `bytes` | Buffer | - |
| `offset` | Número de números | 0 |

**Retornos:** *número*

___

### getAssetID

- **getAssetID**(): *Buffer*

*Definido en [src/apis/avm/ops.ts:194](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/ops.ts#L194)*

Devuelve el activo como [Buffer](https://github.com/feross/buffer).

**Returns:** *Buffer*

___

### getCodecid

- **getCodecid():** *número*

*Heredada de [SigIdx](common_signature.sigidx.md)[.getCodecid](common_signature.sigidx.md#getcodecid)*

*Definido en [src/utils/serialización.ts:59](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/serialization.ts#L59)*

Utilizado en serialización. Opcional. TypeID es un número para el tipo de identificación de objeto que se está saliendo.

**Retornos:** *número*

___

### getOperation

- **getOperation**(): *[Operación](api_avm_operations.operation.md)*

*Definido en [src/apis/avm/ops.ts:204](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/ops.ts#L204)*

Devuelve la operación

**Retornos:** *[Operación](api_avm_operations.operation.md)*

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

### getUTXOIDs

- **getUTXOIDs**(): *[UTXOID](api_avm_operations.utxoid.md)[]*

*Definido en [src/apis/avm/ops.ts:199](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/ops.ts#L199)*

Devuelve una serie de UTXOIDs en esta operación.

**Returns:** *[UTXOID](api_avm_operations.utxoid.md)[]*

___

### serializar

- **serialize**(`encoding`: [SerializedEncoding](../modules/src_utils.md#serializedencoding)): *objeto*

*Superaciones [Serializable](utils_serialization.serializable.md).[serialize](utils_serialization.serializable.md#serialize)*

*Definido en [src/apis/avm/ops.ts:158](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/ops.ts#L158)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `codificación` | [SerializedEncoding](../modules/src_utils.md#serializedencoding) | "hex" |

**Return:** *objeto*

___

### toBuffer

- **toBuffer** (): *Buffer*

*Definido en [src/apis/avm/ops.ts:223](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/ops.ts#L223)*

**Returns:** *Buffer*

___

### Comparador `estático`

- **comparator**(): *función*

*Definido en [src/apis/avm/ops.ts:186](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/ops.ts#L186)*

Devuelve una función utilizada para ordenar una serie de [operaciones](api_avm_operations.transferableoperation.md) transferibles.

**Retornos:** *función*

- (`a`: [TransferableOperation](api_avm_operations.transferableoperation.md)[](api_avm_operations.transferableoperation.md), `b`: (a: *1 | -1 | 0*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `a a` | [Operación Transferible](api_avm_operations.transferableoperation.md) |
| `b b` | [Operación Transferible](api_avm_operations.transferableoperation.md) |
