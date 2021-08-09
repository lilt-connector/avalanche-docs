[avalancha](../README.md) › Operaciones [API-AVM-Operations](../modules/api_avm_operations.md) [NFTTransferOperation](api_avm_operations.nfttransferoperation.md)

# Clase: NFTTransferOperation

Una clase [de operación](api_avm_operations.operation.md) que especifica un Op. de transferencia NFT.

## Jerarquía

de [la operación](api_avm_operations.operation.md)

m. **NFTTransferOperation**

## Índice de participación

### Constructores

* [constructor](api_avm_operations.nfttransferoperation.md#constructor)

### Propiedades de las propiedades

* [_codecid](api_avm_operations.nfttransferoperation.md#protected-_codecid)
* [_typeID](api_avm_operations.nfttransferoperation.md#protected-_typeid)
* [_typeName](api_avm_operations.nfttransferoperation.md#protected-_typename)
* [salida de la salida de la salida](api_avm_operations.nfttransferoperation.md#protected-output)
* [sigCount](api_avm_operations.nfttransferoperation.md#protected-sigcount)
* [sigIdxs](api_avm_operations.nfttransferoperation.md#protected-sigidxs)

### Métodos de trabajo

* [addSignatureIdx](api_avm_operations.nfttransferoperation.md#addsignatureidx)
* [deserie](api_avm_operations.nfttransferoperation.md#deserialize)
* [deBuffer](api_avm_operations.nfttransferoperation.md#frombuffer)
* [getCodecid](api_avm_operations.nfttransferoperation.md#getcodecid)
* [getCredentialID](api_avm_operations.nfttransferoperation.md#getcredentialid)
* [getOperationID](api_avm_operations.nfttransferoperation.md#getoperationid)
* [getOutput](api_avm_operations.nfttransferoperation.md#getoutput)
* [getSigIdxs](api_avm_operations.nfttransferoperation.md#getsigidxs)
* [getTypeID](api_avm_operations.nfttransferoperation.md#gettypeid)
* [getTypeName](api_avm_operations.nfttransferoperation.md#gettypename)
* [serializar](api_avm_operations.nfttransferoperation.md#serialize)
* [setCodecid](api_avm_operations.nfttransferoperation.md#setcodecid)
* [toBuffer](api_avm_operations.nfttransferoperation.md#tobuffer)
* [toString](api_avm_operations.nfttransferoperation.md#tostring)
* [comparador](api_avm_operations.nfttransferoperation.md#static-comparator)

## Constructores

### constructor

\+ **nueva** `NFTTransferOperation(output`*[:](api_avm_operations.nfttransferoperation.md)* [NFTTransferOperation(output:](api_avm_outputs.nfttransferoutput.md) NFTTransferOperation

*Definido en [src/apis/avm/ops.ts:654](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/ops.ts#L654)*

Una clase [de operación](api_avm_operations.operation.md) que contiene un NFT en un activo ID.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `salida de la salida de la salida` | [NFTTransferOutput](api_avm_outputs.nfttransferoutput.md) | no definido. | Un Producto [NFTTransferOutput](api_avm_outputs.nfttransferoutput.md) |

**Retorno:** *[NFTTransferOperation](api_avm_operations.nfttransferoperation.md)*

## Propiedades de las propiedades

### _codecid `protegido`

• **_codecid**: *número* = AVMConstants.LATESTCODEC

*Overrides [SigIdx](common_signature.sigidx.md)[._codecid](common_signature.sigidx.md#protected-_codecid)*

*Definido en [src/apis/avm/ops.ts:577](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/ops.ts#L577)*

___

### `Protegido` _typeID

• **_typeID**: *number* = this._codecid === 0 ? AVMConstants.NFTXFEROPID : AVMConstants.NFTXFEROPID

*Overrides [Operation](api_avm_operations.operation.md).[_typeID](api_avm_operations.operation.md#protected-_typeid)*

*Definido en [src/apis/avm/ops.ts:578](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/ops.ts#L578)*

___

### _typeName `protegido`

• **_typeName**: *string* = "NFTTransferOperation"

*Overrides [Operation](api_avm_operations.operation.md).[_typeName](api_avm_operations.operation.md#protected-_typename)*

*Definido en [src/apis/avm/ops.ts:576](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/ops.ts#L576)*

___

### Producción `protegida`

• **salida**: *[NFTTransferOutput](api_avm_outputs.nfttransferoutput.md)*

*Definido en [src/apis/avm/ops.ts:593](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/ops.ts#L593)*

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

*Definido en [src/apis/avm/ops.ts:587](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/ops.ts#L587)*

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

*Definido en [src/apis/avm/ops.ts:632](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/ops.ts#L632)*

Popuates la instancia de un [Buffer](https://github.com/feross/buffer) que representa la [NFTTransferOperation](api_avm_operations.nfttransferoperation.md) y devuelve el compensatorio actualizado.

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

*Definido en [src/apis/avm/ops.ts:619](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/ops.ts#L619)*

Devuelve la ID de credencial.

**Retornos:** *número*

___

### getOperationID

- **getOperationID**(): *número*

*Superposición [Operation.getOperationID](api_avm_operations.operation.md)[](api_avm_operations.operation.md#abstract-getoperationid)*

*Definido en [src/apis/avm/ops.ts:612](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/ops.ts#L612)*

Devuelve la identificación de operación.

**Retornos:** *número*

___

### getOutput

- **getOutput**(): *[NFTTransferOutput](api_avm_outputs.nfttransferoutput.md)*

*Definido en [src/apis/avm/ops.ts:627](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/ops.ts#L627)*

**Retornos:** *[NFTTransferOutput](api_avm_outputs.nfttransferoutput.md)*

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

*Definido en [src/apis/avm/ops.ts:580](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/ops.ts#L580)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `codificación` | [SerializedEncoding](../modules/src_utils.md#serializedencoding) | "hex" |

**Return:** *objeto*

___

### setCodecid

- **setCodecid(codecid:**`` número): *vacío*

*Definido en [src/apis/avm/ops.ts:600](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/ops.ts#L600)*

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

*Definido en [src/apis/avm/ops.ts:641](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/ops.ts#L641)*

Devuelve el buffer que representa la instancia [NFTTransferOperation](api_avm_operations.nfttransferoperation.md).

**Returns:** *Buffer*

___

### toString

- **toString**(): *string*

*Supera [Operation](api_avm_operations.operation.md).[toString](api_avm_operations.operation.md#tostring)*

*Definido en [src/apis/avm/ops.ts:652](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/ops.ts#L652)*

Devuelve una cadena base-58 que representa la [NFTTransferOperation](api_avm_operations.nfttransferoperation.md).

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
