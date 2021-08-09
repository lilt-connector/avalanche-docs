[avalancha](../README.md) › [API-AVM-Operations](../modules/api_avm_operations.md) › [SECPMintOperation](api_avm_operations.secpmintoperation.md)

# Clase: SECPMintOperation

Una clase [de operación](api_avm_operations.operation.md) que especifica un SECP256k1 Mint Op.

## Jerarquía

de [la operación](api_avm_operations.operation.md)

**m.**

## Índice de participación

### Constructores

* [constructor](api_avm_operations.secpmintoperation.md#constructor)

### Propiedades de las propiedades

* [_codecid](api_avm_operations.secpmintoperation.md#protected-_codecid)
* [_typeID](api_avm_operations.secpmintoperation.md#protected-_typeid)
* [_typeName](api_avm_operations.secpmintoperation.md#protected-_typename)
* [Salida de menta](api_avm_operations.secpmintoperation.md#protected-mintoutput)
* [sigCount](api_avm_operations.secpmintoperation.md#protected-sigcount)
* [sigIdxs](api_avm_operations.secpmintoperation.md#protected-sigidxs)
* [transferOutput](api_avm_operations.secpmintoperation.md#protected-transferoutput)

### Métodos de trabajo

* [addSignatureIdx](api_avm_operations.secpmintoperation.md#addsignatureidx)
* [deserie](api_avm_operations.secpmintoperation.md#deserialize)
* [deBuffer](api_avm_operations.secpmintoperation.md#frombuffer)
* [getCodecid](api_avm_operations.secpmintoperation.md#getcodecid)
* [getCredentialID](api_avm_operations.secpmintoperation.md#getcredentialid)
* [getMintOutput](api_avm_operations.secpmintoperation.md#getmintoutput)
* [getOperationID](api_avm_operations.secpmintoperation.md#getoperationid)
* [getSigIdxs](api_avm_operations.secpmintoperation.md#getsigidxs)
* [getTransferOutput](api_avm_operations.secpmintoperation.md#gettransferoutput)
* [getTypeID](api_avm_operations.secpmintoperation.md#gettypeid)
* [getTypeName](api_avm_operations.secpmintoperation.md#gettypename)
* [serializar](api_avm_operations.secpmintoperation.md#serialize)
* [setCodecid](api_avm_operations.secpmintoperation.md#setcodecid)
* [toBuffer](api_avm_operations.secpmintoperation.md#tobuffer)
* [toString](api_avm_operations.secpmintoperation.md#tostring)
* [comparador](api_avm_operations.secpmintoperation.md#static-comparator)

## Constructores

### constructor

\+ **nuevo SECPMintOperation(mintOutput:**`` [SECPMintOperation(mintOutput:](api_avm_outputs.secpmintoutput.md) `SECPMintOperation(mintOutput`[:](api_avm_outputs.secptransferoutput.md) SECPMintOperation(mintOutput: *[SECPMintOperation](api_avm_operations.secpmintoperation.md)*

*Definido en [src/apis/avm/ops.ts:372](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/ops.ts#L372)*

Una clase [de operación](api_avm_operations.operation.md) que acude a nuevas fichas en un activo ID.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `Salida de menta` | [SECPMintOutput](api_avm_outputs.secpmintoutput.md) | no definido. | La [SECPMintOutput](api_avm_outputs.secpmintoutput.md) que será producida por esta transacción. |
| `transferOutput` | [SECPTransferOutput](api_avm_outputs.secptransferoutput.md) | no definido. | Un [SECPTransferOutput](api_platformvm_outputs.secptransferoutput.md) que se producirá a partir de esta operación de menta. |

**Retornos:** *[SECPMintOperation](api_avm_operations.secpmintoperation.md)*

## Propiedades de las propiedades

### _codecid `protegido`

• **_codecid**: *número* = AVMConstants.LATESTCODEC

*Overrides [SigIdx](common_signature.sigidx.md)[._codecid](common_signature.sigidx.md#protected-_codecid)*

*Definido en [src/apis/avm/ops.ts:273](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/ops.ts#L273)*

___

### `Protegido` _typeID

• **_typeID**: *number* = this._codecid === 0 ? AVMConstants.SECPMINTOPID : AVMConstants.SECPMINTOPID AVMConstants.SECPMINTOPID_CODECONE

*Overrides [Operation](api_avm_operations.operation.md).[_typeID](api_avm_operations.operation.md#protected-_typeid)*

*Definido en [src/apis/avm/ops.ts:274](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/ops.ts#L274)*

___

### _typeName `protegido`

• **_typeName**: *string* = "SECPMintOperation"

*Overrides [Operation](api_avm_operations.operation.md).[_typeName](api_avm_operations.operation.md#protected-_typename)*

*Definido en [src/apis/avm/ops.ts:272](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/ops.ts#L272)*

___

### Salida `de` menta protegida

• **Salida**: *[SECPMintOutput](api_avm_outputs.secpmintoutput.md)* = undefined

*Definido en [src/apis/avm/ops.ts:292](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/ops.ts#L292)*

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

___

### Transferencia `protegida.`

• **transferOutput**: *[SECPTransferOutput](api_avm_outputs.secptransferoutput.md)* = indefinido.

*Definido en [src/apis/avm/ops.ts:293](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/ops.ts#L293)*

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

*Definido en [src/apis/avm/ops.ts:284](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/ops.ts#L284)*

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

*Definido en [src/apis/avm/ops.ts:344](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/ops.ts#L344)*

Popuates la instancia de un [Buffer](https://github.com/feross/buffer) que representa a la [SECPMintOperation](api_avm_operations.secpmintoperation.md) y devuelve el compensatorio actualizado.

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

*Definido en [src/apis/avm/ops.ts:319](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/ops.ts#L319)*

Devuelve la ID de credencial.

**Retornos:** *número*

___

### getMintOutput

- **getMintOutput**(): *[SECPMintOutput](api_avm_outputs.secpmintoutput.md)*

*Definido en [src/apis/avm/ops.ts:330](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/ops.ts#L330)*

Devuelve la salida [SECPMintOutput](api_avm_outputs.secpmintoutput.md) que debe producir esta operación.

**Retornos:** *[SECPMintOutput](api_avm_outputs.secpmintoutput.md)*

___

### getOperationID

- **getOperationID**(): *número*

*Superposición [Operation.getOperationID](api_avm_operations.operation.md)[](api_avm_operations.operation.md#abstract-getoperationid)*

*Definido en [src/apis/avm/ops.ts:312](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/ops.ts#L312)*

Devuelve la identificación de operación.

**Retornos:** *número*

___

### getSigIdxs

- **getSigIdxs**(): *[SigIdx](common_signature.sigidx.md)[]*

*Heredado de [Operation](api_avm_operations.operation.md).[getSigIdxs](api_avm_operations.operation.md#getsigidxs)*

*Definido en [src/apis/avm/ops.ts:91](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/ops.ts#L91)*

Devuelve la matriz de [SigIdx](common_signature.sigidx.md) para esta [Operación](api_avm_operations.operation.md)

**Returns:** *[SigIdx](common_signature.sigidx.md)[]*

___

### getTransferOutput

- **getTransferOutput**(): *[SECPTransferOutput](api_avm_outputs.secptransferoutput.md)*

*Definido en [src/apis/avm/ops.ts:337](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/ops.ts#L337)*

Devuelve [SECPTransferOutput](api_platformvm_outputs.secptransferoutput.md) que debe producir esta operación.

**Retornos:** *[SECPTransferOutput](api_avm_outputs.secptransferoutput.md)*

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

*Definido en [src/apis/avm/ops.ts:276](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/ops.ts#L276)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `codificación` | [SerializedEncoding](../modules/src_utils.md#serializedencoding) | "hex" |

**Return:** *objeto*

___

### setCodecid

- **setCodecid(codecid:**`` número): *vacío*

*Definido en [src/apis/avm/ops.ts:300](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/ops.ts#L300)*

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

*Definido en [src/apis/avm/ops.ts:356](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/ops.ts#L356)*

Devuelve el buffer que representa la instancia [SECPMintOperation](api_avm_operations.secpmintoperation.md).

**Returns:** *Buffer*

___

### toString

- **toString**(): *string*

*Heredada de [Operation](api_avm_operations.operation.md).[toString](api_avm_operations.operation.md#tostring)*

*Definido en [src/apis/avm/ops.ts:144](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/ops.ts#L144)*

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
