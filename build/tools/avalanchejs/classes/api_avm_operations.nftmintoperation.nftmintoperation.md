[avalancha](../README.md) › Operaciones [API-AVM-Operations](../modules/api_avm_operations.md) [NFTMintOperation](api_avm_operations.nftmintoperation.md)

# Clase: NFTMintOperation

Una clase [de operación](api_avm_operations.operation.md) que especifica un NFT Mint Op.

## Jerarquía

de [la operación](api_avm_operations.operation.md)

**nFTMintOperation**

## Índice de participación

### Constructores

* [constructor](api_avm_operations.nftmintoperation.md#constructor)

### Propiedades de las propiedades

* [_codecid](api_avm_operations.nftmintoperation.md#protected-_codecid)
* [_typeID](api_avm_operations.nftmintoperation.md#protected-_typeid)
* [_typeName](api_avm_operations.nftmintoperation.md#protected-_typename)
* [groupID](api_avm_operations.nftmintoperation.md#protected-groupid)
* [outputOwners](api_avm_operations.nftmintoperation.md#protected-outputowners)
* [carga útil](api_avm_operations.nftmintoperation.md#protected-payload)
* [sigCount](api_avm_operations.nftmintoperation.md#protected-sigcount)
* [sigIdxs](api_avm_operations.nftmintoperation.md#protected-sigidxs)

### Métodos de trabajo

* [addSignatureIdx](api_avm_operations.nftmintoperation.md#addsignatureidx)
* [deserie](api_avm_operations.nftmintoperation.md#deserialize)
* [deBuffer](api_avm_operations.nftmintoperation.md#frombuffer)
* [getCodecid](api_avm_operations.nftmintoperation.md#getcodecid)
* [getCredentialID](api_avm_operations.nftmintoperation.md#getcredentialid)
* [getGroupID](api_avm_operations.nftmintoperation.md#getgroupid)
* [getOperationID](api_avm_operations.nftmintoperation.md#getoperationid)
* [getOutputOwners](api_avm_operations.nftmintoperation.md#getoutputowners)
* [getPayload](api_avm_operations.nftmintoperation.md#getpayload)
* [getPayloadBuffer](api_avm_operations.nftmintoperation.md#getpayloadbuffer)
* [getSigIdxs](api_avm_operations.nftmintoperation.md#getsigidxs)
* [getTypeID](api_avm_operations.nftmintoperation.md#gettypeid)
* [getTypeName](api_avm_operations.nftmintoperation.md#gettypename)
* [serializar](api_avm_operations.nftmintoperation.md#serialize)
* [setCodecid](api_avm_operations.nftmintoperation.md#setcodecid)
* [toBuffer](api_avm_operations.nftmintoperation.md#tobuffer)
* [toString](api_avm_operations.nftmintoperation.md#tostring)
* [comparador](api_avm_operations.nftmintoperation.md#static-comparator)

## Constructores

### constructor

\+ **nuevo NFTMintOperation(groupID:**`` `número,` `carga` útil: Buffer, Propietarios: [OutputOwners](common_output.outputowners.md)[]): *[NFTMintOperation](api_avm_operations.nftmintoperation.md)*

*Definido en [src/apis/avm/ops.ts:553](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/ops.ts#L553)*

Una clase [de operación](api_avm_operations.operation.md) que contiene un NFT en un activo ID.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `groupID` | Número de números | no definido. | El grupo al que emitir la salida NFT |
| `carga útil` | Buffer | no definido. | Un [buffer](https://github.com/feross/buffer) de la carga útil NFT |
| `outputOwners` | [Propietarios](common_output.outputowners.md)[] | no definido. | Una serie de propietarios de salidas |

**Retorno:** *[NFTMintOperation](api_avm_operations.nftmintoperation.md)*

## Propiedades de las propiedades

### _codecid `protegido`

• **_codecid**: *número* = AVMConstants.LATESTCODEC

*Overrides [SigIdx](common_signature.sigidx.md)[._codecid](common_signature.sigidx.md#protected-_codecid)*

*Definido en [src/apis/avm/ops.ts:397](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/ops.ts#L397)*

___

### `Protegido` _typeID

• **_typeID**: *number* = this._codecid === 0 ? AVMConstants.NFTMINTOPID : AVMConstants.NFTMINTOPID_CODECONE

*Overrides [Operation](api_avm_operations.operation.md).[_typeID](api_avm_operations.operation.md#protected-_typeid)*

*Definido en [src/apis/avm/ops.ts:398](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/ops.ts#L398)*

___

### _typeName `protegido`

• **_typeName**: *string* = "NFTMintOperation"

*Overrides [Operation](api_avm_operations.operation.md).[_typeName](api_avm_operations.operation.md#protected-_typename)*

*Definido en [src/apis/avm/ops.ts:396](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/ops.ts#L396)*

___

### Grupo `protegido`

• **groupID**: *Buffer* = Buffer.aloc(4)

*Definido en [src/apis/avm/ops.ts:425](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/ops.ts#L425)*

___

### Salidas `Protected`

• **Propietarios***[:](common_output.outputowners.md)[]* OutputOwners: OutputOwners =[]

*Definido en [src/apis/avm/ops.ts:427](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/ops.ts#L427)*

___

### Carga útil `protegida`

• **Carga útil**: *Buffer*

*Definido en [src/apis/avm/ops.ts:426](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/ops.ts#L426)*

___

### sigCount `protegido`

• **sigCount**: *Buffer* = Buffer.aloc(4)

*Heredado de [Operation](api_avm_operations.operation.md).[sigCount](api_avm_operations.operation.md#protected-sigcount)*

*Definido en [src/apis/avm/ops.ts:69](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/ops.ts#L69)*

___

### SigIdxs `protegidos`

• **sigIdxs**: *[SigIdx](common_signature.sigidx.md)[]* =[]

*Heredado de [Operation](api_avm_operations.operation.md).[sigIdxs](api_avm_operations.operation.md#protected-sigidxs)*

*Definido en [src/apis/avm/ops.ts:70](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/ops.ts#L70)*

## Métodos de trabajo

### addSignatureIdx

- **addSignatureIdx**(`addressIdx`: número, `dirección`: Buffer): *void*

*Heredada de [Operation](api_avm_operations.operation.md).[addSignatureIdx](api_avm_operations.operation.md#addsignatureidx)*

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

*Superaciones [Operation... Operation.deserialize](api_avm_operations.operation.md)[](api_avm_operations.operation.md#deserialize)*

*Definido en [src/apis/avm/ops.ts:409](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/ops.ts#L409)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `campos de cultivo` | objeto de la operación | - |
| `codificación` | [SerializedEncoding](../modules/src_utils.md#serializedencoding) | "hex" |

**Retornos:** *vacío*

___

### deBuffer

- **fromBuffer**(`bytes`: Buffer, `offset`: número): *número*

*Overrides [Operation](api_avm_operations.operation.md).[fromBuffer](api_avm_operations.operation.md#frombuffer)*

*Definido en [src/apis/avm/ops.ts:494](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/ops.ts#L494)*

Popuates la instancia de un [Buffer](https://github.com/feross/buffer) que representa a la [NFTMintOperation](api_avm_operations.nftmintoperation.md) y devuelve el compensatorio actualizado.

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

### getCredentialID

- **getCredentialID**(): *número*

*Overrides [Operation](api_avm_operations.operation.md).[getCredentialID](api_avm_operations.operation.md#abstract-getcredentialid)*

*Definido en [src/apis/avm/ops.ts:453](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/ops.ts#L453)*

Devuelve la ID de credencial.

**Retornos:** *número*

___

### getGroupID

- **getGroupID**(): *Buffer*

*Definido en [src/apis/avm/ops.ts:464](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/ops.ts#L464)*

Devuelve la carga útil.

**Returns:** *Buffer*

___

### getOperationID

- **getOperationID**(): *número*

*Superposición [Operation.getOperationID](api_avm_operations.operation.md)[](api_avm_operations.operation.md#abstract-getoperationid)*

*Definido en [src/apis/avm/ops.ts:446](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/ops.ts#L446)*

Devuelve la identificación de operación.

**Retornos:** *número*

___

### getOutputOwners

- **getOutputOwners**(): *[OutputOwners](common_output.outputowners.md)[]*

*Definido en [src/apis/avm/ops.ts:487](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/ops.ts#L487)*

Devuelve los propietarios de salida.

**Retornos:** *[Propietarios](common_output.outputowners.md)[]*

___

### getPayload

- **getPayload**(): *Buffer*

*Definido en [src/apis/avm/ops.ts:471](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/ops.ts#L471)*

Devuelve la carga útil.

**Returns:** *Buffer*

___

### getPayloadBuffer

- **getPayloadBuffer**(): *Buffer*

*Definido en [src/apis/avm/ops.ts:478](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/ops.ts#L478)*

Devuelve el [buffer](https://github.com/feross/buffer) bruto de la carga útil con longitud preparada, para su uso con [PayloadBase](utils_payload.payloadbase.md)'s deBuffer

**Returns:** *Buffer*

___

### getSigIdxs

- **getSigIdxs**(): *[SigIdx](common_signature.sigidx.md)[]*

*Heredado de [Operation](api_avm_operations.operation.md).[getSigIdxs](api_avm_operations.operation.md#getsigidxs)*

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

*Overrides [Operation](api_avm_operations.operation.md).[serialize](api_avm_operations.operation.md#serialize)*

*Definido en [src/apis/avm/ops.ts:400](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/ops.ts#L400)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `codificación` | [SerializedEncoding](../modules/src_utils.md#serializedencoding) | "hex" |

**Return:** *objeto*

___

### setCodecid

- **setCodecid(codecid:**`` número): *vacío*

*Definido en [src/apis/avm/ops.ts:434](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/ops.ts#L434)*

Configure el codecid

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `codecid` | Número de números | El codecid para configurar |

**Retornos:** *vacío*

___

### toBuffer

- **toBuffer** (): *Buffer*

*Supera [Operation](api_avm_operations.operation.md).[toBuffer](api_avm_operations.operation.md#tobuffer)*

*Definido en [src/apis/avm/ops.ts:516](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/ops.ts#L516)*

Devuelve el buffer que representa la instancia [NFTMintOperation](api_avm_operations.nftmintoperation.md).

**Returns:** *Buffer*

___

### toString

- **toString**(): *string*

*Supera [Operation](api_avm_operations.operation.md).[toString](api_avm_operations.operation.md#tostring)*

*Definido en [src/apis/avm/ops.ts:551](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/ops.ts#L551)*

Devuelve una cadena base-58 que representa la [NFTMintOperation](api_avm_operations.nftmintoperation.md).

**Return:** *string*

___

### Comparador `estático`

- **comparator**(): *función*

*Heredado de [Operation](api_avm_operations.operation.md).[comparator](api_avm_operations.operation.md#static-comparator)*

*Definido en [src/apis/avm/ops.ts:72](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/ops.ts#L72)*

**Retornos:** *función*

- (`a`: [Operación](api_avm_operations.operation.md), `b`: [Operación):](api_avm_operations.operation.md) *1 | -1 | 0*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `a a` | [Operación de las Naciones Unidas en Desarrollo](api_avm_operations.operation.md) |
| `b b` | [Operación de las Naciones Unidas en Desarrollo](api_avm_operations.operation.md) |
