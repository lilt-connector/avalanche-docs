[avalancha](../README.md) › [API-AVM-ImportTx](../modules/api_avm_importtx.md) › [ImportTx](api_avm_importtx.importtx.md)

# Clase: ImportTx

Clase que representa una transacción de importación no firmada.

## Jerarquía

de [BaseTx](api_avm_basetx.basetx.md)

m **ImportTx**

## Índice de participación

### Constructores

* [constructor](api_avm_importtx.importtx.md#constructor)

### Propiedades de las propiedades

* [_codecid](api_avm_importtx.importtx.md#protected-_codecid)
* [_typeID](api_avm_importtx.importtx.md#protected-_typeid)
* [_typeName](api_avm_importtx.importtx.md#protected-_typename)
* [blockchainID](api_avm_importtx.importtx.md#protected-blockchainid)
* [importIns](api_avm_importtx.importtx.md#protected-importins)
* [ins](api_avm_importtx.importtx.md#protected-ins)
* [meme](api_avm_importtx.importtx.md#protected-memo)
* [networkID](api_avm_importtx.importtx.md#protected-networkid)
* [numIns](api_avm_importtx.importtx.md#protected-numins)
* [numero](api_avm_importtx.importtx.md#protected-numins)
* [numouts](api_avm_importtx.importtx.md#protected-numouts)
* [outs](api_avm_importtx.importtx.md#protected-outs)
* [sourceChain](api_avm_importtx.importtx.md#protected-sourcechain)

### Métodos de trabajo

* [clon](api_avm_importtx.importtx.md#clone)
* [crear un entorno de creación](api_avm_importtx.importtx.md#create)
* [deserie](api_avm_importtx.importtx.md#deserialize)
* [deBuffer](api_avm_importtx.importtx.md#frombuffer)
* [getBlockchainID](api_avm_importtx.importtx.md#getblockchainid)
* [getCodecid](api_avm_importtx.importtx.md#getcodecid)
* [getImportInputs](api_avm_importtx.importtx.md#getimportinputs)
* [getIns](api_avm_importtx.importtx.md#getins)
* [getMemo](api_avm_importtx.importtx.md#getmemo)
* [getNetworkID](api_avm_importtx.importtx.md#getnetworkid)
* [gets Outs](api_avm_importtx.importtx.md#getouts)
* [getSourceChain](api_avm_importtx.importtx.md#getsourcechain)
* [getTotalOuts](api_avm_importtx.importtx.md#gettotalouts)
* [getTxType](api_avm_importtx.importtx.md#gettxtype)
* [getTypeID](api_avm_importtx.importtx.md#gettypeid)
* [getTypeName](api_avm_importtx.importtx.md#gettypename)
* [seleccionar](api_avm_importtx.importtx.md#select)
* [serializar](api_avm_importtx.importtx.md#serialize)
* [setCodecid](api_avm_importtx.importtx.md#setcodecid)
* [señal de que la señal de que la](api_avm_importtx.importtx.md#sign)
* [toBuffer](api_avm_importtx.importtx.md#tobuffer)
* [toString](api_avm_importtx.importtx.md#tostring)

## Constructores

### constructor

\+ **nuevo ImportTx(networkID:**`` number, `blockchainID`: Buffer, `outs`: [number](api_avm_outputs.transferableoutput.md)[], `ins`: [TransferableInput](api_avm_inputs.transferableinput.md)[](api_avm_inputs.transferableinput.md), `memo`: Buffer, `sourceChain`: Buffer, `importIns`: [][]ImportTx(networkID: *[ImportTx](api_avm_importtx.importtx.md)*

*Superaciones [BaseTx](api_avm_basetx.basetx.md).[constructor](api_avm_basetx.basetx.md#constructor)*

*Definido en [src/apis/avm/importtx.ts:168](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/importtx.ts#L168)*

Clase que representa una transacción de importación no firmada.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `networkID` | Número de números | DefaultNetworkID | Opcional networkID, [DefaultNetworkID](../modules/utils_constants.md#const-defaultnetworkid) |
| `blockchainID` | Buffer | Buffer.aloc(32, 16) | blockchainID, predeterminado Buffer.aloc(32, 16) |
| `outs` | [Producto transferible](api_avm_outputs.transferableoutput.md)[] | no definido. | Variedad opcional de los [Productos Transferibles](api_platformvm_outputs.transferableoutput.md) |
| `ins` | [Entrada transferible](api_avm_inputs.transferableinput.md)[] | no definido. | Variedad opcional de los [insumos](api_platformvm_inputs.transferableinput.md) transferibles. |
| `meme` | Buffer | no definido. | [Buffer](https://github.com/feross/buffer) opcional para el campo de memorias |
| `sourceChain` | Buffer | no definido. | chainid opcional para las entradas de fuente a importar. plataforma predeterminada. |
| `importIns` | [Entrada transferible](api_avm_inputs.transferableinput.md)[] | no definido. | Conjunto de [entradas transferibles](api_platformvm_inputs.transferableinput.md) utilizadas en la transacción |

**Returns:** *[ImportTx](api_avm_importtx.importtx.md)*

## Propiedades de las propiedades

### _codecid `protegido`

• **_codecid**: *número* = AVMConstants.LATESTCODEC

*Superaciones [BaseTx](api_avm_basetx.basetx.md)[._codecid](api_avm_basetx.basetx.md#protected-_codecid)*

*Definido en [src/apis/avm/importtx.ts:34](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/importtx.ts#L34)*

___

### `Protegido` _typeID

• **_typeID**: *number* = this._codecid === 0 ? AVMConstants.IMPORTTX: AVMConstants.IMPORTTX_CODECONE

*Superaciones [BaseTx](api_avm_basetx.basetx.md).[_typeID](api_avm_basetx.basetx.md#protected-_typeid)*

*Definido en [src/apis/avm/importtx.ts:35](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/importtx.ts#L35)*

___

### _typeName `protegido`

• **_typeName**: *string* = "ImportTx"

*Superaciones [BaseTx](api_avm_basetx.basetx.md).[_typeName](api_avm_basetx.basetx.md#protected-_typename)*

*Definido en [src/apis/avm/importtx.ts:33](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/importtx.ts#L33)*

___

### blockchainID `protegido`

• **blockchainID**: *Buffer* = Buffer.aloc(32)

*Heredada de [StandardBaseTx](common_transactions.standardbasetx.md).[blockchainID](common_transactions.standardbasetx.md#protected-blockchainid)*

*Definido en [src/comm/tx.ts:52](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/tx.ts#L52)*

___

### Importaciones `protegidas`

• **Importantes**: *[Entrada](api_avm_inputs.transferableinput.md)[]* transferible=[]

*Definido en [src/apis/avm/importtx.ts:59](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/importtx.ts#L59)*

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

### NumIns `protegidos`

• **numIns**: *Buffer* = Buffer.aloc(4)

*Definido en [src/apis/avm/importtx.ts:58](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/importtx.ts#L58)*

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

___

### Fuente `protegida` Cadena de cadena de cadena de

• **sourceChain**: de entrada: *Buffer* = Buffer.aloc(32)

*Definido en [src/apis/avm/importtx.ts:57](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/importtx.ts#L57)*

## Métodos de trabajo

### clon

- **clone**(): *esto*

*Superar [BaseTx](api_avm_basetx.basetx.md).[clone](api_avm_basetx.basetx.md#clone)*

*Definido en [src/apis/avm/importtx.ts:135](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/importtx.ts#L135)*

**Returns:** *esto*

___

### crear un entorno de creación

*-* **create**(...`args`: []cualquiera

*Supera [BaseTx](api_avm_basetx.basetx.md).[create](api_avm_basetx.basetx.md#create)*

*Definido en [src/apis/avm/importtx.ts:141](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/importtx.ts#L141)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `..args` | cualquier otra cosa que no sea[] |

**Returns:** *esto*

___

### deserie

- **deserialize**(`fields`: objeto, `codificación`: [SerializedEncoding](../modules/src_utils.md#serializedencoding)): *vacío*

*Superaciones [BaseTx](api_avm_basetx.basetx.md).[deserialize](api_avm_basetx.basetx.md#deserialize)*

*Definido en [src/apis/avm/importtx.ts:45](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/importtx.ts#L45)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `campos de cultivo` | objeto de la operación | - |
| `codificación` | [SerializedEncoding](../modules/src_utils.md#serializedencoding) | "hex" |

**Retornos:** *vacío*

___

### deBuffer

- **fromBuffer**(`bytes`: Buffer, `offset`: número): *número*

*Superaciones [BaseTx](api_avm_basetx.basetx.md).[fromBuffer](api_avm_basetx.basetx.md#frombuffer)*

*Definido en [src/apis/avm/importtx.ts:98](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/importtx.ts#L98)*

Toma un [buffer](https://github.com/feross/buffer) que contiene una [ImportTx](api_avm_importtx.importtx.md), lo analiza, populates la clase y devuelve la longitud de la [ImportTx](api_avm_importtx.importtx.md) en bytes.

**`observaciones`** asuman que no se ha comprobado

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `bytes` | Buffer | - | Un [buffer](https://github.com/feross/buffer) que contiene una [importTx](api_avm_importtx.importtx.md) cruda |
| `offset` | Número de números | 0 | - |

**Retornos:** *número*

La longitud de la [importTx](api_avm_importtx.importtx.md) cruda

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

### getImportInputs

- **getImportInputs**(): *[TransferableInput](api_avm_inputs.transferableinput.md)[]*

*Definido en [src/apis/avm/importtx.ts:131](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/importtx.ts#L131)*

Devuelve una variedad de [entradas transferibles](api_platformvm_inputs.transferableinput.md) en esta transacción.

**Retornos:** *[Input transferible](api_avm_inputs.transferableinput.md)[]*

___

### getIns

- **getIns**(): *[TransferableInput](api_avm_inputs.transferableinput.md)[]*

*Heredada de [BaseTx](api_avm_basetx.basetx.md).[getIns](api_avm_basetx.basetx.md#getins)*

*Overrides [StandardBaseTx](common_transactions.standardbasetx.md).[getIns](common_transactions.standardbasetx.md#abstract-getins)*

*Definido en [src/apis/avm/basetx.ts:58](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/basetx.ts#L58)*

**Retornos:** *[Input transferible](api_avm_inputs.transferableinput.md)[]*

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

- **gets():** *[Producto transferible](api_avm_outputs.transferableoutput.md)[]*

*Heredada de [BaseTx](api_avm_basetx.basetx.md)[.getouts](api_avm_basetx.basetx.md#getouts)*

*Overrides [StandardBaseTx](common_transactions.standardbasetx.md)[.getouts](common_transactions.standardbasetx.md#abstract-getouts)*

*Definido en [src/apis/avm/basetx.ts:54](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/basetx.ts#L54)*

**Retornos:** *[Producto transferible](api_avm_outputs.transferableoutput.md)[]*

___

### getSourceChain

- **getSourceChain**(): *Buffer*

*Definido en [src/apis/avm/importtx.ts:85](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/importtx.ts#L85)*

Devuelve un [Buffer](https://github.com/feross/buffer) para el chainid de origen.

**Returns:** *Buffer*

___

### getTotalOuts

- **getTotalOuts**(): *[TransferableOutput](api_avm_outputs.transferableoutput.md)[]*

*Heredada de [BaseTx](api_avm_basetx.basetx.md).[getTotalOuts](api_avm_basetx.basetx.md#gettotalouts)*

*Overrides [StandardBaseTx](common_transactions.standardbasetx.md).[getTotalOuts](common_transactions.standardbasetx.md#abstract-gettotalouts)*

*Definido en [src/apis/avm/basetx.ts:62](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/basetx.ts#L62)*

**Retornos:** *[Producto transferible](api_avm_outputs.transferableoutput.md)[]*

___

### getTxType

- **getTxType**(): *número*

*Superaciones [BaseTx](api_avm_basetx.basetx.md).[getTxType](api_avm_basetx.basetx.md#gettxtype)*

*Definido en [src/apis/avm/importtx.ts:78](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/importtx.ts#L78)*

Devuelve el id de la [ImportTx](api_avm_importtx.importtx.md)

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

*Heredado de [BaseTx](api_avm_basetx.basetx.md).[select](api_avm_basetx.basetx.md#select)*

*Overrides [StandardBaseTx](common_transactions.standardbasetx.md).[select](common_transactions.standardbasetx.md#abstract-select)*

*Definido en [src/apis/avm/basetx.ts:162](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/basetx.ts#L162)*

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

*Definido en [src/apis/avm/importtx.ts:37](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/importtx.ts#L37)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `codificación` | [SerializedEncoding](../modules/src_utils.md#serializedencoding) | "hex" |

**Return:** *objeto*

___

### setCodecid

- **setCodecid(codecid:**`` número): *vacío*

*Superar [BaseTx](api_avm_basetx.basetx.md)[.setCodecid](api_avm_basetx.basetx.md#setcodecid)*

*Definido en [src/apis/avm/importtx.ts:66](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/importtx.ts#L66)*

Configure el codecid

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `codecid` | Número de números | El codecid para configurar |

**Retornos:** *vacío*

___

### señal de que la señal de que la

- **sign**(`msg`: Buffer, `kc`: [KeyChain](api_avm_keychain.keychain.md)): *[Credencial](common_signature.credential.md)[]*

*Superar [BaseTx](api_avm_basetx.basetx.md).[sign](api_avm_basetx.basetx.md#sign).*

*Definido en [src/apis/avm/importtx.ts:153](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/importtx.ts#L153)*

Toma los bytes de un [UnsignedTx](api_platformvm_transactions.unsignedtx.md) y devuelve una matriz de [Credenciales](common_signature.credential.md)

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `ms.` | Buffer | Un buffer para el [UnsignedTx](api_platformvm_transactions.unsignedtx.md) |
| `kc` | [Llave](api_avm_keychain.keychain.md) | Una [cadena de teclas](api_platformvm_keychain.keychain.md) utilizada en la firma |

**Retornos:** *[Credencial](common_signature.credential.md)[]*

Una serie de [credenciales](common_signature.credential.md)

___

### toBuffer

- **toBuffer** (): *Buffer*

*Overrides [StandardBaseTx](common_transactions.standardbasetx.md).[toBuffer](common_transactions.standardbasetx.md#tobuffer)*

*Definido en [src/apis/avm/importtx.ts:116](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/importtx.ts#L116)*

Devuelve una representación de [Buffer](https://github.com/feross/buffer) de la [ImportTx](api_avm_importtx.importtx.md).

**Returns:** *Buffer*

___

### toString

- **toString**(): *string*

*Heredada de [StandardBaseTx](common_transactions.standardbasetx.md).[toString](common_transactions.standardbasetx.md#tostring)*

*Definido en [src/comm/tx.ts:129](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/tx.ts#L129)*

Devuelve una representación de base 58 de la [StandardBaseTx](common_transactions.standardbasetx.md).

**Return:** *string*
