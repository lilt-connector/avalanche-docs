[avalancha](../README.md) › Operaciones [API-AVM-Operations](../modules/api_avm_operations.md) › [Operación](api_avm_operations.operation.md)

# Clase: Operación

Una clase que representa una operación. Todos los tipos de operaciones deben extenderse en esta clase.

## Jerarquía

* [Serializable](utils_serialization.serializable.md)

   de **la operación**

   [m.](api_avm_operations.secpmintoperation.md)

   [nFTMintOperation](api_avm_operations.nftmintoperation.md)

   m. [NFTTransferOperation](api_avm_operations.nfttransferoperation.md)

## Índice de participación

### Propiedades de las propiedades

* [_codecid](api_avm_operations.operation.md#protected-_codecid)
* [_typeID](api_avm_operations.operation.md#protected-_typeid)
* [_typeName](api_avm_operations.operation.md#protected-_typename)
* [sigCount](api_avm_operations.operation.md#protected-sigcount)
* [sigIdxs](api_avm_operations.operation.md#protected-sigidxs)

### Métodos de trabajo

* [addSignatureIdx](api_avm_operations.operation.md#addsignatureidx)
* [deserie](api_avm_operations.operation.md#deserialize)
* [deBuffer](api_avm_operations.operation.md#frombuffer)
* [getCodecid](api_avm_operations.operation.md#getcodecid)
* [getCredentialID](api_avm_operations.operation.md#abstract-getcredentialid)
* [getOperationID](api_avm_operations.operation.md#abstract-getoperationid)
* [getSigIdxs](api_avm_operations.operation.md#getsigidxs)
* [getTypeID](api_avm_operations.operation.md#gettypeid)
* [getTypeName](api_avm_operations.operation.md#gettypename)
* [serializar](api_avm_operations.operation.md#serialize)
* [toBuffer](api_avm_operations.operation.md#tobuffer)
* [toString](api_avm_operations.operation.md#tostring)
* [comparador](api_avm_operations.operation.md#static-comparator)

## Propiedades de las propiedades

### _codecid `protegido`

• **_codecid**: *número* = indefinido.

*Heredada de [SigIdx](common_signature.sigidx.md)[._codecid](common_signature.sigidx.md#protected-_codecid)*

*Definido en [src/utils/serialización.ts:40](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/serialization.ts#L40)*

___

### `Protegido` _typeID

• **_typeID**: *any* = undefined

*Superes [Serializable](utils_serialization.serializable.md).[_typeID](utils_serialization.serializable.md#protected-_typeid)*

*Definido en [src/apis/avm/ops.ts:50](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/ops.ts#L50)*

___

### _typeName `protegido`

• **_typeName**: *string* = "Operation"

*Superes [Serializable](utils_serialization.serializable.md).[_typeName](utils_serialization.serializable.md#protected-_typename)*

*Definido en [src/apis/avm/ops.ts:49](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/ops.ts#L49)*

___

### sigCount `protegido`

• **sigCount**: *Buffer* = Buffer.aloc(4)

*Definido en [src/apis/avm/ops.ts:69](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/ops.ts#L69)*

___

### SigIdxs `protegidos`

• **sigIdxs**: *[SigIdx](common_signature.sigidx.md)[]* =[]

*Definido en [src/apis/avm/ops.ts:70](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/ops.ts#L70)*

## Métodos de trabajo

### addSignatureIdx

- **addSignatureIdx**(`addressIdx`: número, `dirección`: Buffer): *void*

*Definido en [src/apis/avm/ops.ts:104](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/ops.ts#L104)*

Crea y agrega un [SigIdx](common_signature.sigidx.md) a la [Operación](api_avm_operations.operation.md).

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `addressIdx` | Número de números | El índice de la dirección a la referencia en las firmas |
| `Dirección de la dirección` | Buffer | La dirección de la fuente de la firma |

**Retornos:** *vacío*

___

### deserie

- **deserialize**(`fields`: objeto, `codificación`: [SerializedEncoding](../modules/src_utils.md#serializedencoding)): *vacío*

*Superaciones [StandardParseableInput](common_inputs.standardparseableinput.md).[deserialize](common_inputs.standardparseableinput.md#deserialize)*

*Definido en [src/apis/avm/ops.ts:59](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/ops.ts#L59)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `campos de cultivo` | objeto de la operación | - |
| `codificación` | [SerializedEncoding](../modules/src_utils.md#serializedencoding) | "hex" |

**Retornos:** *vacío*

___

### deBuffer

- **fromBuffer**(`bytes`: Buffer, `offset`: número): *número*

*Definido en [src/apis/avm/ops.ts:114](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/ops.ts#L114)*

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

### `Resumen` getCredentialID

- **getCredentialID**(): *número*

*Definido en [src/apis/avm/ops.ts:96](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/ops.ts#L96)*

Devuelve la ID de credencial.

**Retornos:** *número*

___

### `Resumen` getOperationID

- **getOperationID**(): *número*

*Definido en [src/apis/avm/ops.ts:86](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/ops.ts#L86)*

**Retornos:** *número*

___

### getSigIdxs

- **getSigIdxs**(): *[SigIdx](common_signature.sigidx.md)[]*

*Definido en [src/apis/avm/ops.ts:91](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/ops.ts#L91)*

Devuelve la matriz de [SigIdx](common_signature.sigidx.md) para esta [Operación](api_avm_operations.operation.md)

**Returns:** *[SigIdx](common_signature.sigidx.md)[]*

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

*Definido en [src/apis/avm/ops.ts:52](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/ops.ts#L52)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `codificación` | [SerializedEncoding](../modules/src_utils.md#serializedencoding) | "hex" |

**Return:** *objeto*

___

### toBuffer

- **toBuffer** (): *Buffer*

*Definido en [src/apis/avm/ops.ts:129](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/ops.ts#L129)*

**Returns:** *Buffer*

___

### toString

- **toString**(): *string*

*Definido en [src/apis/avm/ops.ts:144](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/ops.ts#L144)*

Devuelve una cadena base-58 que representa la [NFTMintOperation](api_avm_operations.nftmintoperation.md).

**Return:** *string*

___

### Comparador `estático`

- **comparator**(): *función*

*Definido en [src/apis/avm/ops.ts:72](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/ops.ts#L72)*

**Retornos:** *función*

- (`a`: [Operación](api_avm_operations.operation.md), `b`: [Operación):](api_avm_operations.operation.md) *1 | -1 | 0*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `a a` | [Operación de las Naciones Unidas en Desarrollo](api_avm_operations.operation.md) |
| `b b` | [Operación de las Naciones Unidas en Desarrollo](api_avm_operations.operation.md) |
