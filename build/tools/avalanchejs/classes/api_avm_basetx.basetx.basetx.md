[avalancha](../README.md) › [API-AVM-BaseTx](../modules/api_avm_basetx.md) › [BaseTx](api_avm_basetx.basetx.md)

# Clase: BaseTx

Clase que representa una base para todas las transacciones.

## Jerarquía

m [StandardBaseTx](common_transactions.standardbasetx.md)‹[KeyPair](api_avm_keychain.keypair.md), [KeyChain](api_avm_keychain.keychain.md)›

de **BaseTx**

de [CreateAssetTx](api_avm_createassettx.createassettx.md)

de [OperationTx](api_avm_operationtx.operationtx.md)

m [ImportTx](api_avm_importtx.importtx.md)

m. [ExportTx](api_avm_exporttx.exporttx.md)

## Índice de participación

### Constructores

* [constructor](api_avm_basetx.basetx.md#constructor)

### Propiedades de las propiedades

* [_codecid](api_avm_basetx.basetx.md#protected-_codecid)
* [_typeID](api_avm_basetx.basetx.md#protected-_typeid)
* [_typeName](api_avm_basetx.basetx.md#protected-_typename)
* [blockchainID](api_avm_basetx.basetx.md#protected-blockchainid)
* [ins](api_avm_basetx.basetx.md#protected-ins)
* [meme](api_avm_basetx.basetx.md#protected-memo)
* [networkID](api_avm_basetx.basetx.md#protected-networkid)
* [numero](api_avm_basetx.basetx.md#protected-numins)
* [numouts](api_avm_basetx.basetx.md#protected-numouts)
* [outs](api_avm_basetx.basetx.md#protected-outs)

### Métodos de trabajo

* [clon](api_avm_basetx.basetx.md#clone)
* [crear un entorno de creación](api_avm_basetx.basetx.md#create)
* [deserie](api_avm_basetx.basetx.md#deserialize)
* [deBuffer](api_avm_basetx.basetx.md#frombuffer)
* [getBlockchainID](api_avm_basetx.basetx.md#getblockchainid)
* [getCodecid](api_avm_basetx.basetx.md#getcodecid)
* [getIns](api_avm_basetx.basetx.md#getins)
* [getMemo](api_avm_basetx.basetx.md#getmemo)
* [getNetworkID](api_avm_basetx.basetx.md#getnetworkid)
* [gets Outs](api_avm_basetx.basetx.md#getouts)
* [getTotalOuts](api_avm_basetx.basetx.md#gettotalouts)
* [getTxType](api_avm_basetx.basetx.md#gettxtype)
* [getTypeID](api_avm_basetx.basetx.md#gettypeid)
* [getTypeName](api_avm_basetx.basetx.md#gettypename)
* [seleccionar](api_avm_basetx.basetx.md#select)
* [serializar](api_avm_basetx.basetx.md#serialize)
* [setCodecid](api_avm_basetx.basetx.md#setcodecid)
* [señal de que la señal de que la](api_avm_basetx.basetx.md#sign)
* [toBuffer](api_avm_basetx.basetx.md#tobuffer)
* [toString](api_avm_basetx.basetx.md#tostring)

## Constructores

### constructor

\+ **new BaseTx**(`networkID`: number, `blockchainID`: Buffer, `outs`: [number](api_avm_outputs.transferableoutput.md)[], `ins`: [TransferableInput](api_avm_inputs.transferableinput.md)[], `memo`: Buffer): *[BaseTx](api_avm_basetx.basetx.md)*

*Overrides [StandardBaseTx](common_transactions.standardbasetx.md).[constructor](common_transactions.standardbasetx.md#constructor)*

*Definido en [src/apis/avm/basetx.ts:165](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/basetx.ts#L165)*

Clase que representa un BaseTx que es la base para todas las transacciones.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `networkID` | Número de números | DefaultNetworkID | Opcional networkID, [DefaultNetworkID](../modules/utils_constants.md#const-defaultnetworkid) |
| `blockchainID` | Buffer | Buffer.aloc(32, 16) | blockchainID, predeterminado Buffer.aloc(32, 16) |
| `outs` | [Producto transferible](api_avm_outputs.transferableoutput.md)[] | no definido. | Variedad opcional de los [Productos Transferibles](api_platformvm_outputs.transferableoutput.md) |
| `ins` | [Entrada transferible](api_avm_inputs.transferableinput.md)[] | no definido. | Variedad opcional de los [insumos](api_platformvm_inputs.transferableinput.md) transferibles. |
| `meme` | Buffer | no definido. | [Buffer](https://github.com/feross/buffer) opcional para el campo de memorias |

**Returns:** *[BaseTx](api_avm_basetx.basetx.md)*

## Propiedades de las propiedades

### _codecid `protegido`

• **_codecid**: *número* = AVMConstants.LATESTCODEC

*Overrides [SigIdx](common_signature.sigidx.md)[._codecid](common_signature.sigidx.md#protected-_codecid)*

*Definido en [src/apis/avm/basetx.ts:33](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/basetx.ts#L33)*

___

### `Protegido` _typeID

• **_typeID**: *number* = this._codecid === 0 ? AVMConstants.BASETX : AVMConstants.BASETX_CODECONE

*Superaciones [StandardBaseTx](common_transactions.standardbasetx.md).[_typeID](common_transactions.standardbasetx.md#protected-_typeid)*

*Definido en [src/apis/avm/basetx.ts:34](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/basetx.ts#L34)*

___

### _typeName `protegido`

• **_typeName**: *string* = "BaseTx"

*Overrides [StandardBaseTx](common_transactions.standardbasetx.md).[_typeName](common_transactions.standardbasetx.md#protected-_typename)*

*Definido en [src/apis/avm/basetx.ts:32](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/basetx.ts#L32)*

___

### blockchainID `protegido`

• **blockchainID**: *Buffer* = Buffer.aloc(32)

*Heredada de [StandardBaseTx](common_transactions.standardbasetx.md).[blockchainID](common_transactions.standardbasetx.md#protected-blockchainid)*

*Definido en [src/comm/tx.ts:52](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/tx.ts#L52)*

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

*Superar [StandardBaseTx](common_transactions.standardbasetx.md).[clone](common_transactions.standardbasetx.md#abstract-clone)*

*Definido en [src/apis/avm/basetx.ts:152](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/basetx.ts#L152)*

**Returns:** *esto*

___

### crear un entorno de creación

*-* **create**(...`args`: []cualquiera

*Supera [StandardBaseTx](common_transactions.standardbasetx.md).[create](common_transactions.standardbasetx.md#abstract-create)*

*Definido en [src/apis/avm/basetx.ts:158](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/basetx.ts#L158)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `..args` | cualquier otra cosa que no sea[] |

**Returns:** *esto*

___

### deserie

- **deserialize**(`fields`: objeto, `codificación`: [SerializedEncoding](../modules/src_utils.md#serializedencoding)): *vacío*

*Superaciones [StandardBaseTx](common_transactions.standardbasetx.md).[deserialize](common_transactions.standardbasetx.md#deserialize)*

*Definido en [src/apis/avm/basetx.ts:38](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/basetx.ts#L38)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `campos de cultivo` | objeto de la operación | - |
| `codificación` | [SerializedEncoding](../modules/src_utils.md#serializedencoding) | "hex" |

**Retornos:** *vacío*

___

### deBuffer

- **fromBuffer**(`bytes`: Buffer, `offset`: número): *número*

*Definido en [src/apis/avm/basetx.ts:96](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/basetx.ts#L96)*

Toma un [Buffer](https://github.com/feross/buffer) que contiene un [BaseTx](api_avm_basetx.basetx.md), lo analiza, populates la clase y devuelve la longitud de la BaseTx en bytes.

**`observaciones`** asuman que no se ha comprobado

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `bytes` | Buffer | - | Un [buffer](https://github.com/feross/buffer) que contiene un [BaseTx](api_avm_basetx.basetx.md) crudo. |
| `offset` | Número de números | 0 | - |

**Retornos:** *número*

La longitud de la [base](api_avm_basetx.basetx.md) cruda

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

### getIns

- **getIns**(): *[TransferableInput](api_avm_inputs.transferableinput.md)[]*

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

*Overrides [StandardBaseTx](common_transactions.standardbasetx.md)[.getouts](common_transactions.standardbasetx.md#abstract-getouts)*

*Definido en [src/apis/avm/basetx.ts:54](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/basetx.ts#L54)*

**Retornos:** *[Producto transferible](api_avm_outputs.transferableoutput.md)[]*

___

### getTotalOuts

- **getTotalOuts**(): *[TransferableOutput](api_avm_outputs.transferableoutput.md)[]*

*Overrides [StandardBaseTx](common_transactions.standardbasetx.md).[getTotalOuts](common_transactions.standardbasetx.md#abstract-gettotalouts)*

*Definido en [src/apis/avm/basetx.ts:62](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/basetx.ts#L62)*

**Retornos:** *[Producto transferible](api_avm_outputs.transferableoutput.md)[]*

___

### getTxType

- **getTxType**(): *número*

*Overrides [StandardBaseTx](common_transactions.standardbasetx.md).[getTxType](common_transactions.standardbasetx.md#abstract-gettxtype)*

*Definido en [src/apis/avm/basetx.ts:83](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/basetx.ts#L83)*

Devuelve el id de la [BaseTx](api_avm_basetx.basetx.md)

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

*Heredada de [StandardBaseTx](common_transactions.standardbasetx.md).[serialize](common_transactions.standardbasetx.md#serialize)*

*Superaciones [Serializable](utils_serialization.serializable.md).[serialize](utils_serialization.serializable.md#serialize)*

*Definido en [src/comm/tx.ts:32](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/tx.ts#L32)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `codificación` | [SerializedEncoding](../modules/src_utils.md#serializedencoding) | "hex" |

**Return:** *objeto*

___

### setCodecid

- **setCodecid(codecid:**`` número): *vacío*

*Definido en [src/apis/avm/basetx.ts:71](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/basetx.ts#L71)*

Configure el codecid

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `codecid` | Número de números | El codecid para configurar |

**Retornos:** *vacío*

___

### señal de que la señal de que la

- **sign**(`msg`: Buffer, `kc`: [KeyChain](api_avm_keychain.keychain.md)): *[Credencial](common_signature.credential.md)[]*

*Superar [StandardBaseTx](common_transactions.standardbasetx.md).[sign](common_transactions.standardbasetx.md#abstract-sign)*

*Definido en [src/apis/avm/basetx.ts:135](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/basetx.ts#L135)*

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

*Heredada de [StandardBaseTx](common_transactions.standardbasetx.md).[toBuffer](common_transactions.standardbasetx.md#tobuffer)*

*Definido en [src/comm/tx.ts:97](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/tx.ts#L97)*

Devuelve una representación de [Buffer](https://github.com/feross/buffer) de la [StandardBaseTx](common_transactions.standardbasetx.md).

**Returns:** *Buffer*

___

### toString

- **toString**(): *string*

*Heredada de [StandardBaseTx](common_transactions.standardbasetx.md).[toString](common_transactions.standardbasetx.md#tostring)*

*Definido en [src/comm/tx.ts:129](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/tx.ts#L129)*

Devuelve una representación de base 58 de la [StandardBaseTx](common_transactions.standardbasetx.md).

**Return:** *string*
