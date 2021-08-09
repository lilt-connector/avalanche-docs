[avalanche](../README.md) › [API-PlatformVM-ExportTx](../modules/api_platformvm_exporttx.md) › [ExportTx](api_platformvm_exporttx.exporttx.md)

# Clase: ExportTx

Clase que representa una transacción de exportación no firmada.

## Jerarquía

de [BaseTx](api_platformvm_basetx.basetx.md)

m. **ExportTx**

## Índice de participación

### Constructores

* [constructor](api_platformvm_exporttx.exporttx.md#constructor)

### Propiedades de las propiedades

* [_codecid](api_platformvm_exporttx.exporttx.md#protected-_codecid)
* [_typeID](api_platformvm_exporttx.exporttx.md#protected-_typeid)
* [_typeName](api_platformvm_exporttx.exporttx.md#protected-_typename)
* [blockchainID](api_platformvm_exporttx.exporttx.md#protected-blockchainid)
* [destinationChain de destino](api_platformvm_exporttx.exporttx.md#protected-destinationchain)
* [exportOuts](api_platformvm_exporttx.exporttx.md#protected-exportouts)
* [ins](api_platformvm_exporttx.exporttx.md#protected-ins)
* [meme](api_platformvm_exporttx.exporttx.md#protected-memo)
* [networkID](api_platformvm_exporttx.exporttx.md#protected-networkid)
* [numouts](api_platformvm_exporttx.exporttx.md#protected-numouts)
* [numero](api_platformvm_exporttx.exporttx.md#protected-numins)
* [numouts](api_platformvm_exporttx.exporttx.md#protected-numouts)
* [outs](api_platformvm_exporttx.exporttx.md#protected-outs)

### Métodos de trabajo

* [clon](api_platformvm_exporttx.exporttx.md#clone)
* [crear un entorno de creación](api_platformvm_exporttx.exporttx.md#create)
* [deserie](api_platformvm_exporttx.exporttx.md#deserialize)
* [deBuffer](api_platformvm_exporttx.exporttx.md#frombuffer)
* [getBlockchainID](api_platformvm_exporttx.exporttx.md#getblockchainid)
* [getCodecid](api_platformvm_exporttx.exporttx.md#getcodecid)
* [getExportOutputs](api_platformvm_exporttx.exporttx.md#getexportoutputs)
* [getExportTotal](api_platformvm_exporttx.exporttx.md#getexporttotal)
* [getIns](api_platformvm_exporttx.exporttx.md#getins)
* [getMemo](api_platformvm_exporttx.exporttx.md#getmemo)
* [getNetworkID](api_platformvm_exporttx.exporttx.md#getnetworkid)
* [gets Outs](api_platformvm_exporttx.exporttx.md#getouts)
* [getTotalOuts](api_platformvm_exporttx.exporttx.md#gettotalouts)
* [getTxType](api_platformvm_exporttx.exporttx.md#gettxtype)
* [getTypeID](api_platformvm_exporttx.exporttx.md#gettypeid)
* [getTypeName](api_platformvm_exporttx.exporttx.md#gettypename)
* [seleccionar](api_platformvm_exporttx.exporttx.md#select)
* [serializar](api_platformvm_exporttx.exporttx.md#serialize)
* [señal de que la señal de que la](api_platformvm_exporttx.exporttx.md#sign)
* [toBuffer](api_platformvm_exporttx.exporttx.md#tobuffer)
* [toString](api_platformvm_exporttx.exporttx.md#tostring)

## Constructores

### constructor

[]\+ **nuevo ExportTx(networkID:**`` number, `blockchainID`: Buffer, `outs`: [number](api_platformvm_outputs.transferableoutput.md)[], `ins`: [TransferableInput](api_platformvm_inputs.transferableinput.md)[], `memo`: Buffer, `destinationChain`: [de](api_platformvm_outputs.transferableoutput.md) `producción`: Buffer, ExportTx(networkID: *[ExportTx](api_platformvm_exporttx.exporttx.md)*

*Superaciones [BaseTx](api_platformvm_basetx.basetx.md).[constructor](api_platformvm_basetx.basetx.md#constructor)*

*Definido en [src/apis/platformvm/exporttx.ts:131](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/exporttx.ts#L131)*

Clase que representa una transacción de exportación no firmada.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `networkID` | Número de números | DefaultNetworkID | Opcional networkID, [DefaultNetworkID](../modules/utils_constants.md#const-defaultnetworkid) |
| `blockchainID` | Buffer | Buffer.aloc(32, 16) | blockchainID, predeterminado Buffer.aloc(32, 16) |
| `outs` | [Producto transferible](api_platformvm_outputs.transferableoutput.md)[] | no definido. | Variedad opcional de los [Productos Transferibles](api_platformvm_outputs.transferableoutput.md) |
| `ins` | [Entrada transferible](api_platformvm_inputs.transferableinput.md)[] | no definido. | Variedad opcional de los [insumos](api_platformvm_inputs.transferableinput.md) transferibles. |
| `meme` | Buffer | no definido. | [Buffer](https://github.com/feross/buffer) opcional para el campo de memorias |
| `destinationChain de destino` | Buffer | no definido. | El chainid opcional que identifica a dónde enviarán los fondos. |
| `exportOuts` | [Producto transferible](api_platformvm_outputs.transferableoutput.md)[] | no definido. | Conjunto de [[Productos transferibles]] utilizados en la transacción |

**Returns:** *[ExportTx](api_platformvm_exporttx.exporttx.md)*

## Propiedades de las propiedades

### _codecid `protegido`

• **_codecid**: *número* = indefinido.

*Heredada de [SigIdx](common_signature.sigidx.md)[._codecid](common_signature.sigidx.md#protected-_codecid)*

*Definido en [src/utils/serialización.ts:40](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/serialization.ts#L40)*

___

### `Protegido` _typeID

• **_typeID**: *número* = PlatformVMConstants.EXPORTTX

*Superaciones [BaseTx](api_platformvm_basetx.basetx.md).[_typeID](api_platformvm_basetx.basetx.md#protected-_typeid)*

*Definido en [src/apis/platformvm/exporttx.ts:28](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/exporttx.ts#L28)*

___

### _typeName `protegido`

• **_typeName**: *string* = "ExportTx"

*Superaciones [BaseTx](api_platformvm_basetx.basetx.md).[_typeName](api_platformvm_basetx.basetx.md#protected-_typename)*

*Definido en [src/apis/platformvm/exporttx.ts:27](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/exporttx.ts#L27)*

___

### blockchainID `protegido`

• **blockchainID**: *Buffer* = Buffer.aloc(32)

*Heredada de [StandardBaseTx](common_transactions.standardbasetx.md).[blockchainID](common_transactions.standardbasetx.md#protected-blockchainid)*

*Definido en [src/comm/tx.ts:52](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/tx.ts#L52)*

___

### Destino `protegido:`

• **destinationChain**: *Buffer* = Buffer.aloc(32)

*Definido en [src/apis/platformvm/exporttx.ts:50](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/exporttx.ts#L50)*

___

### Exportaciones `protegidas` Outs

• **exportOuts**: *[TransferableOutput](api_platformvm_outputs.transferableoutput.md)[]* =[]

*Definido en [src/apis/platformvm/exporttx.ts:52](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/exporttx.ts#L52)*

___

### Inmuebles `protegidos`

• **ins**: Entrada *[StandardTransferableInput](common_inputs.standardtransferableinput.md)[]*

*Heredado de [StandardBaseTx](common_transactions.standardbasetx.md).[ins](common_transactions.standardbasetx.md#protected-ins)*

*Definido en [src/comm/tx.ts:56](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/tx.ts#L56)*

___

### Memorias `protegidas`

• **memo**: *Buffer* = Buffer.aloc(0)

*Heredada de [StandardBaseTx](common_transactions.standardbasetx.md).[memo](common_transactions.standardbasetx.md#protected-memo)*

*Definido en [src/comm/tx.ts:57](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/tx.ts#L57)*

___

### Red `protegida`

• **networkID**: *Buffer* = Buffer.aloc(4)

*Heredada de [StandardBaseTx](common_transactions.standardbasetx.md).[networkID](common_transactions.standardbasetx.md#protected-networkid)*

*Definido en [src/comm/tx.ts:51](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/tx.ts#L51)*

___

### NumOuts `protegidos`

• **numOuts**: *Buffer* = Buffer.aloc(4)

*Definido en [src/apis/platformvm/exporttx.ts:51](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/exporttx.ts#L51)*

___

### numins `protegidas`

• **numins**: *Buffer* = Buffer.aloc(4)

*Heredado de [StandardBaseTx](common_transactions.standardbasetx.md).[numins](common_transactions.standardbasetx.md#protected-numins)*

*Definido en [src/comm/tx.ts:55](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/tx.ts#L55)*

___

### numouts `protegidas`

• **numouts**: *Buffer* = Buffer.aloc(4)

*Heredado de [StandardBaseTx](common_transactions.standardbasetx.md).[numouts](common_transactions.standardbasetx.md#protected-numouts)*

*Definido en [src/comm/tx.ts:53](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/tx.ts#L53)*

___

### Ojos `protegidos`

• **outs**: Producto *[StandardTransferableOutput](common_output.standardtransferableoutput.md)[]*

*Heredado de [StandardBaseTx](common_transactions.standardbasetx.md).[outs](common_transactions.standardbasetx.md#protected-outs)*

*Definido en [src/comm/tx.ts:54](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/tx.ts#L54)*

## Métodos de trabajo

### clon

- **clone**(): *esto*

*Superar [BaseTx](api_platformvm_basetx.basetx.md).[clone](api_platformvm_basetx.basetx.md#clone)*

*Definido en [src/apis/platformvm/exporttx.ts:123](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/exporttx.ts#L123)*

**Returns:** *esto*

___

### crear un entorno de creación

*-* **create**(...`args`: []cualquiera

*Supera [BaseTx](api_platformvm_basetx.basetx.md).[create](api_platformvm_basetx.basetx.md#create)*

*Definido en [src/apis/platformvm/exporttx.ts:129](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/exporttx.ts#L129)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `..args` | cualquier otra cosa que no sea[] |

**Returns:** *esto*

___

### deserie

- **deserialize**(`fields`: objeto, `codificación`: [SerializedEncoding](../modules/src_utils.md#serializedencoding)): *vacío*

*Superaciones [BaseTx](api_platformvm_basetx.basetx.md).[deserialize](api_platformvm_basetx.basetx.md#deserialize)*

*Definido en [src/apis/platformvm/exporttx.ts:38](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/exporttx.ts#L38)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `campos de cultivo` | objeto de la operación | - |
| `codificación` | [SerializedEncoding](../modules/src_utils.md#serializedencoding) | "hex" |

**Retornos:** *vacío*

___

### deBuffer

- **fromBuffer**(`bytes`: Buffer, `offset`: número): *número*

*Superaciones [BaseTx](api_platformvm_basetx.basetx.md).[fromBuffer](api_platformvm_basetx.basetx.md#frombuffer)*

*Definido en [src/apis/platformvm/exporttx.ts:92](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/exporttx.ts#L92)*

Toma un [buffer](https://github.com/feross/buffer) que contiene una [ExportTx](api_platformvm_exporttx.exporttx.md)[,](api_platformvm_exporttx.exporttx.md) lo analiza, populates la clase y devuelve la longitud de la ExportTx en bytes.

**`observaciones`** asuman que no se ha comprobado

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `bytes` | Buffer | - | Un [buffer](https://github.com/feross/buffer) que contiene una [ExportTx](api_platformvm_exporttx.exporttx.md) cruda |
| `offset` | Número de números | 0 | - |

**Retornos:** *número*

La longitud de la [exportación](api_platformvm_exporttx.exporttx.md) cruda

___

### getBlockchainID

- **getBlockchainID**(): *Buffer*

*Heredada de [StandardBaseTx](common_transactions.standardbasetx.md).[getBlockchainID](common_transactions.standardbasetx.md#getblockchainid)*

*Definido en [src/comm/tx.ts:72](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/tx.ts#L72)*

Devuelve la representación de Buffer del BlockchainID

**Returns:** *Buffer*

___

### getCodecid

- **getCodecid():** *número*

*Heredada de [SigIdx](common_signature.sigidx.md)[.getCodecid](common_signature.sigidx.md#getcodecid)*

*Definido en [src/utils/serialización.ts:59](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/serialization.ts#L59)*

Utilizado en serialización. Opcional. TypeID es un número para el tipo de identificación de objeto que se está saliendo.

**Retornos:** *número*

___

### getExportOutputs

- **getExportOutputs**(): *[TransferableOutput](api_platformvm_outputs.transferableoutput.md)[]*

*Definido en [src/apis/platformvm/exporttx.ts:64](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/exporttx.ts#L64)*

Devuelve una variedad de [Productos Transferibles](api_platformvm_outputs.transferableoutput.md) en esta transacción.

**Retornos:** *[Producto transferible](api_platformvm_outputs.transferableoutput.md)[]*

___

### getExportTotal

- **getExportTotal**(): *BN*

*Definido en [src/apis/platformvm/exporttx.ts:71](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/exporttx.ts#L71)*

Devuelve la cantidad total exportada como [BN](https://github.com/indutny/bn.js/).

**Returns:** *BN*

___

### getIns

- **getIns**(): *[TransferableInput](api_platformvm_inputs.transferableinput.md)[]*

*Heredada de [BaseTx](api_platformvm_basetx.basetx.md).[getIns](api_platformvm_basetx.basetx.md#getins)*

*Overrides [StandardBaseTx](common_transactions.standardbasetx.md).[getIns](common_transactions.standardbasetx.md#abstract-getins)*

*Definido en [src/apis/platformvm/basetx.ts:52](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/basetx.ts#L52)*

**Retornos:** *[Input transferible](api_platformvm_inputs.transferableinput.md)[]*

___

### getMemo

- **getMemo**(): *Buffer*

*Heredada de [StandardBaseTx](common_transactions.standardbasetx.md).[getMemo](common_transactions.standardbasetx.md#getmemo)*

*Definido en [src/comm/tx.ts:92](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/tx.ts#L92)*

Devuelve la representación [Buffer](https://github.com/feross/buffer) del memo

**Returns:** *Buffer*

___

### getNetworkID

- **getNetworkID**(): *número*

*Heredada de [StandardBaseTx](common_transactions.standardbasetx.md).[getNetworkID](common_transactions.standardbasetx.md#getnetworkid)*

*Definido en [src/comm/tx.ts:67](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/tx.ts#L67)*

Devuelve el NetworkID como número

**Retornos:** *número*

___

### gets Outs

- **gets():** *[Producto transferible](api_platformvm_outputs.transferableoutput.md)[]*

*Heredada de [BaseTx](api_platformvm_basetx.basetx.md)[.getouts](api_platformvm_basetx.basetx.md#getouts)*

*Overrides [StandardBaseTx](common_transactions.standardbasetx.md)[.getouts](common_transactions.standardbasetx.md#abstract-getouts)*

*Definido en [src/apis/platformvm/basetx.ts:48](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/basetx.ts#L48)*

**Retornos:** *[Producto transferible](api_platformvm_outputs.transferableoutput.md)[]*

___

### getTotalOuts

- **getTotalOuts**(): *[TransferableOutput](api_platformvm_outputs.transferableoutput.md)[]*

*Superaciones [BaseTx](api_platformvm_basetx.basetx.md).[getTotalOuts](api_platformvm_basetx.basetx.md#gettotalouts)*

*Definido en [src/apis/platformvm/exporttx.ts:79](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/exporttx.ts#L79)*

**Retornos:** *[Producto transferible](api_platformvm_outputs.transferableoutput.md)[]*

___

### getTxType

- **getTxType**(): *número*

*Superaciones [BaseTx](api_platformvm_basetx.basetx.md).[getTxType](api_platformvm_basetx.basetx.md#gettxtype)*

*Definido en [src/apis/platformvm/exporttx.ts:57](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/exporttx.ts#L57)*

Devuelve el id de la [ExportTx](api_platformvm_exporttx.exporttx.md)

**Retornos:** *número*

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

### seleccionar

- **select**(`id`: número, ...`args`: []cualquier): *esto*

*Heredado de [BaseTx](api_platformvm_basetx.basetx.md).[select](api_platformvm_basetx.basetx.md#select)*

*Overrides [StandardBaseTx](common_transactions.standardbasetx.md).[select](common_transactions.standardbasetx.md#abstract-select)*

*Definido en [src/apis/platformvm/basetx.ts:143](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/basetx.ts#L143)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `I.` | Número de números |
| `..args` | cualquier otra cosa que no sea[] |

**Returns:** *esto*

___

### serializar

- **serialize**(`encoding`: [SerializedEncoding](../modules/src_utils.md#serializedencoding)): *objeto*

*Superaciones [StandardBaseTx](common_transactions.standardbasetx.md).[serialize](common_transactions.standardbasetx.md#serialize)*

*Definido en [src/apis/platformvm/exporttx.ts:30](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/exporttx.ts#L30)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `codificación` | [SerializedEncoding](../modules/src_utils.md#serializedencoding) | "hex" |

**Return:** *objeto*

___

### señal de que la señal de que la

- **sign**(`msg`: Buffer, `kc`: [KeyChain](api_platformvm_keychain.keychain.md)): *[Credencial](common_signature.credential.md)[]*

*Heredada de [BaseTx](api_platformvm_basetx.basetx.md).[sign](api_platformvm_basetx.basetx.md#sign)*

*Superar [StandardBaseTx](common_transactions.standardbasetx.md).[sign](common_transactions.standardbasetx.md#abstract-sign)*

*Definido en [src/apis/platformvm/basetx.ts:116](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/basetx.ts#L116)*

Toma los bytes de un [UnsignedTx](api_platformvm_transactions.unsignedtx.md) y devuelve una matriz de [Credenciales](common_signature.credential.md)

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `ms.` | Buffer | Un buffer para el [UnsignedTx](api_platformvm_transactions.unsignedtx.md) |
| `kc` | [Llave](api_platformvm_keychain.keychain.md) | Una [cadena de teclas](api_platformvm_keychain.keychain.md) utilizada en la firma |

**Retornos:** *[Credencial](common_signature.credential.md)[]*

Una serie de [credenciales](common_signature.credential.md)

___

### toBuffer

- **toBuffer** (): *Buffer*

*Overrides [StandardBaseTx](common_transactions.standardbasetx.md).[toBuffer](common_transactions.standardbasetx.md#tobuffer)*

*Definido en [src/apis/platformvm/exporttx.ts:110](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/exporttx.ts#L110)*

Devuelve una representación de [Buffer](https://github.com/feross/buffer) de la [ExportTx](api_platformvm_exporttx.exporttx.md).

**Returns:** *Buffer*

___

### toString

- **toString**(): *string*

*Heredada de [StandardBaseTx](common_transactions.standardbasetx.md).[toString](common_transactions.standardbasetx.md#tostring)*

*Definido en [src/comm/tx.ts:129](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/tx.ts#L129)*

Devuelve una representación de base 58 de la [StandardBaseTx](common_transactions.standardbasetx.md).

**Return:** *string*
