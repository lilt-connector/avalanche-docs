[avalancha](../README.md) › [API-PlatformVM-ValidationTx](../modules/api_platformvm_validationtx.md) › [API-PlatformVM-ValidationTx](api_platformvm_validationtx.weightedvalidatortx.md)

# Clase: WeightedValidatorTx

## Jerarquía

m. [ValidatorTx](api_platformvm_validationtx.validatortx.md)

m. **WeightedValidatorTx**

m. [AddDelegatorTx](api_platformvm_validationtx.adddelegatortx.md)

## Índice de participación

### Constructores

* [constructor](api_platformvm_validationtx.weightedvalidatortx.md#constructor)

### Propiedades de las propiedades

* [_codecid](api_platformvm_validationtx.weightedvalidatortx.md#protected-_codecid)
* [_typeID](api_platformvm_validationtx.weightedvalidatortx.md#protected-_typeid)
* [_typeName](api_platformvm_validationtx.weightedvalidatortx.md#protected-_typename)
* [blockchainID](api_platformvm_validationtx.weightedvalidatortx.md#protected-blockchainid)
* [endTime](api_platformvm_validationtx.weightedvalidatortx.md#protected-endtime)
* [ins](api_platformvm_validationtx.weightedvalidatortx.md#protected-ins)
* [meme](api_platformvm_validationtx.weightedvalidatortx.md#protected-memo)
* [networkID](api_platformvm_validationtx.weightedvalidatortx.md#protected-networkid)
* [nodeID](api_platformvm_validationtx.weightedvalidatortx.md#protected-nodeid)
* [numero](api_platformvm_validationtx.weightedvalidatortx.md#protected-numins)
* [numouts](api_platformvm_validationtx.weightedvalidatortx.md#protected-numouts)
* [outs](api_platformvm_validationtx.weightedvalidatortx.md#protected-outs)
* [startTime](api_platformvm_validationtx.weightedvalidatortx.md#protected-starttime)
* [peso](api_platformvm_validationtx.weightedvalidatortx.md#protected-weight)

### Métodos de trabajo

* [clon](api_platformvm_validationtx.weightedvalidatortx.md#clone)
* [crear un entorno de creación](api_platformvm_validationtx.weightedvalidatortx.md#create)
* [deserie](api_platformvm_validationtx.weightedvalidatortx.md#deserialize)
* [deBuffer](api_platformvm_validationtx.weightedvalidatortx.md#frombuffer)
* [getBlockchainID](api_platformvm_validationtx.weightedvalidatortx.md#getblockchainid)
* [getCodecid](api_platformvm_validationtx.weightedvalidatortx.md#getcodecid)
* [getEndTime](api_platformvm_validationtx.weightedvalidatortx.md#getendtime)
* [getIns](api_platformvm_validationtx.weightedvalidatortx.md#getins)
* [getMemo](api_platformvm_validationtx.weightedvalidatortx.md#getmemo)
* [getNetworkID](api_platformvm_validationtx.weightedvalidatortx.md#getnetworkid)
* [getNodeID](api_platformvm_validationtx.weightedvalidatortx.md#getnodeid)
* [getNodeIDString](api_platformvm_validationtx.weightedvalidatortx.md#getnodeidstring)
* [gets Outs](api_platformvm_validationtx.weightedvalidatortx.md#getouts)
* [getStartTime](api_platformvm_validationtx.weightedvalidatortx.md#getstarttime)
* [getTotalOuts](api_platformvm_validationtx.weightedvalidatortx.md#gettotalouts)
* [getTxType](api_platformvm_validationtx.weightedvalidatortx.md#gettxtype)
* [getTypeID](api_platformvm_validationtx.weightedvalidatortx.md#gettypeid)
* [getTypeName](api_platformvm_validationtx.weightedvalidatortx.md#gettypename)
* [getWeight](api_platformvm_validationtx.weightedvalidatortx.md#getweight)
* [getWeightBuffer](api_platformvm_validationtx.weightedvalidatortx.md#getweightbuffer)
* [seleccionar](api_platformvm_validationtx.weightedvalidatortx.md#select)
* [serializar](api_platformvm_validationtx.weightedvalidatortx.md#serialize)
* [señal de que la señal de que la](api_platformvm_validationtx.weightedvalidatortx.md#sign)
* [toBuffer](api_platformvm_validationtx.weightedvalidatortx.md#tobuffer)
* [toString](api_platformvm_validationtx.weightedvalidatortx.md#tostring)

## Constructores

### constructor

\+ **nuevo** WeightedValidatorTx(`networkID`: number, `blockchainID`: Buffer, `outs`: [number](api_platformvm_outputs.transferableoutput.md)[](api_platformvm_inputs.transferableinput.md), `ins`: [][]number, `memorando`: Buffer, `nodeID`: Buffer, `startTime`: BN, `endTime`: BN, `peso`: BN): *[WeightedValidatorTx](api_platformvm_validationtx.weightedvalidatortx.md)*

*Superar [ValidatorTx](api_platformvm_validationtx.validatortx.md).[constructor](api_platformvm_validationtx.validatortx.md#constructor)*

*Definido en [src/apis/platformvm/validationtx.ts:167](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/validationtx.ts#L167)*

Clase que representa una transacción no firmada de AddSubnetValidatorTx.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `networkID` | Número de números | DefaultNetworkID | Opcional. Networkid, [DefaultNetworkID](../modules/utils_constants.md#const-defaultnetworkid) |
| `blockchainID` | Buffer | Buffer.aloc(32, 16) | Opcional. Blockchainid, predeterminado Buffer.aloc(32, 16) |
| `outs` | [Producto transferible](api_platformvm_outputs.transferableoutput.md)[] | no definido. | Opcional. Conjunto de productos [transferibles](api_platformvm_outputs.transferableoutput.md) |
| `ins` | [Entrada transferible](api_platformvm_inputs.transferableinput.md)[] | no definido. | Opcional. Conjunto de las [entradas transferibles](api_platformvm_inputs.transferableinput.md) |
| `meme` | Buffer | no definido. | Opcional. [Buffer](https://github.com/feross/buffer) para el campo de memorias |
| `nodeID` | Buffer | no definido. | Opcional. El ID del nodo del validador que se añade. |
| `startTime` | BN | no definido. | Opcional. El tiempo Unix cuando el validador comienza a validar la Red Primaria. |
| `endTime` | BN | no definido. | Opcional. El tiempo Unix cuando el validador deja de validar la Red Primaria (y se devuelve AVAX almacenado). |
| `peso` | BN | no definido. | Opcional. La cantidad de nAVAX el validador está estancando. |

**Returns:** *[WeightedValidatorTx](api_platformvm_validationtx.weightedvalidatortx.md)*

## Propiedades de las propiedades

### _codecid `protegido`

• **_codecid**: *número* = indefinido.

*Heredada de [SigIdx](common_signature.sigidx.md)[._codecid](common_signature.sigidx.md#protected-_codecid)*

*Definido en [src/utils/serialización.ts:40](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/serialization.ts#L40)*

___

### `Protegido` _typeID

• **_typeID**: *any* = undefined

*Superar [ValidatorTx](api_platformvm_validationtx.validatortx.md).[_typeID](api_platformvm_validationtx.validatortx.md#protected-_typeid)*

*Definido en [src/apis/platformvm/validationtx.ts:124](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/validationtx.ts#L124)*

___

### _typeName `protegido`

• **_typeName**: *string* = "WeightedValidatorTx"

*Overrides [ValidatorTx](api_platformvm_validationtx.validatortx.md).[_typeName](api_platformvm_validationtx.validatortx.md#protected-_typename)*

*Definido en [src/apis/platformvm/validationtx.ts:123](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/validationtx.ts#L123)*

___

### blockchainID `protegido`

• **blockchainID**: *Buffer* = Buffer.aloc(32)

*Heredada de [StandardBaseTx](common_transactions.standardbasetx.md).[blockchainID](common_transactions.standardbasetx.md#protected-blockchainid)*

*Definido en [src/comm/tx.ts:52](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/tx.ts#L52)*

___

### Tiempo de finalización `protegido`

• **endTime**: *Buffer* = Buffer.aloc(8)

*Heredada de [ValidatorTx](api_platformvm_validationtx.validatortx.md).[endTime](api_platformvm_validationtx.validatortx.md#protected-endtime)*

*Definido en [src/apis/platformvm/validationtx.ts:50](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/validationtx.ts#L50)*

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

### nodeID `protegida`

• **NodeID**: *Buffer* = Buffer.aloc(20)

*Heredada de [ValidatorTx](api_platformvm_validationtx.validatortx.md).[nodeID](api_platformvm_validationtx.validatortx.md#protected-nodeid)*

*Definido en [src/apis/platformvm/validationtx.ts:48](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/validationtx.ts#L48)*

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

### Tiempo de inicio `protegido`

• **Hora de inicio**: *Buffer* = Buffer.aloc(8)

*Heredada de [ValidatorTx](api_platformvm_validationtx.validatortx.md).[startTime](api_platformvm_validationtx.validatortx.md#protected-starttime)*

*Definido en [src/apis/platformvm/validationtx.ts:49](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/validationtx.ts#L49)*

___

### Peso `protegido`

• **peso**: *Buffer* = Buffer.aloc(8)

*Definido en [src/apis/platformvm/validationtx.ts:138](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/validationtx.ts#L138)*

## Métodos de trabajo

### clon

- **clone**(): *esto*

*Heredada de [BaseTx](api_platformvm_basetx.basetx.md).[clone](api_platformvm_basetx.basetx.md#clone)*

*Superar [StandardBaseTx](common_transactions.standardbasetx.md).[clone](common_transactions.standardbasetx.md#abstract-clone)*

*Definido en [src/apis/platformvm/basetx.ts:133](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/basetx.ts#L133)*

**Returns:** *esto*

___

### crear un entorno de creación

*-* **create**(...`args`: []cualquiera

*Heredada de [BaseTx](api_platformvm_basetx.basetx.md).[create](api_platformvm_basetx.basetx.md#create)*

*Supera [StandardBaseTx](common_transactions.standardbasetx.md).[create](common_transactions.standardbasetx.md#abstract-create)*

*Definido en [src/apis/platformvm/basetx.ts:139](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/basetx.ts#L139)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `..args` | cualquier otra cosa que no sea[] |

**Returns:** *esto*

___

### deserie

- **deserialize**(`fields`: objeto, `codificación`: [SerializedEncoding](../modules/src_utils.md#serializedencoding)): *vacío*

*[ValidatorTx](api_platformvm_validationtx.validatortx.md).[deserialize](api_platformvm_validationtx.validatortx.md#deserialize)*

*Definido en [src/apis/platformvm/validationtx.ts:133](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/validationtx.ts#L133)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `campos de cultivo` | objeto de la operación | - |
| `codificación` | [SerializedEncoding](../modules/src_utils.md#serializedencoding) | "hex" |

**Retornos:** *vacío*

___

### deBuffer

- **fromBuffer**(`bytes`: Buffer, `offset`: número): *número*

*Overrides [ValidatorTx](api_platformvm_validationtx.validatortx.md).[fromBuffer](api_platformvm_validationtx.validatortx.md#frombuffer)*

*Definido en [src/apis/platformvm/validationtx.ts:154](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/validationtx.ts#L154)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `bytes` | Buffer | - |
| `offset` | Número de números | 0 |

**Retornos:** *número*

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

### getEndTime

- **getEndTime**(): *BN‹›*

*Heredada de [ValidatorTx](api_platformvm_validationtx.validatortx.md).[getEndTime](api_platformvm_validationtx.validatortx.md#getendtime)*

*Definido en [src/apis/platformvm/validationtx.ts:75](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/validationtx.ts#L75)*

Devuelve un [BN](https://github.com/indutny/bn.js/) por el importe de la estaca.

**Returns:** *BN‹›*

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

### getNodeID

- **getNodeID**(): *Buffer*

*Heredada de [ValidatorTx](api_platformvm_validationtx.validatortx.md).[getNodeID](api_platformvm_validationtx.validatortx.md#getnodeid)*

*Definido en [src/apis/platformvm/validationtx.ts:55](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/validationtx.ts#L55)*

Devuelve un [Buffer](https://github.com/feross/buffer) por la cantidad de la estaca.

**Returns:** *Buffer*

___

### getNodeIDString

- **getNodeIDString**(): *string*

*Heredada de [ValidatorTx](api_platformvm_validationtx.validatortx.md).[getNodeIDString](api_platformvm_validationtx.validatortx.md#getnodeidstring)*

*Definido en [src/apis/platformvm/validationtx.ts:62](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/validationtx.ts#L62)*

Devuelve una cadena para la cantidad de nodeID.

**Return:** *string*

___

### gets Outs

- **gets():** *[Producto transferible](api_platformvm_outputs.transferableoutput.md)[]*

*Heredada de [BaseTx](api_platformvm_basetx.basetx.md)[.getouts](api_platformvm_basetx.basetx.md#getouts)*

*Overrides [StandardBaseTx](common_transactions.standardbasetx.md)[.getouts](common_transactions.standardbasetx.md#abstract-getouts)*

*Definido en [src/apis/platformvm/basetx.ts:48](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/basetx.ts#L48)*

**Retornos:** *[Producto transferible](api_platformvm_outputs.transferableoutput.md)[]*

___

### getStartTime

- **getStartTime**(): *BN‹›*

*Heredada de [ValidatorTx](api_platformvm_validationtx.validatortx.md).[getStartTime](api_platformvm_validationtx.validatortx.md#getstarttime)*

*Definido en [src/apis/platformvm/validationtx.ts:68](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/validationtx.ts#L68)*

Devuelve un [BN](https://github.com/indutny/bn.js/) por el importe de la estaca.

**Returns:** *BN‹›*

___

### getTotalOuts

- **getTotalOuts**(): *[TransferableOutput](api_platformvm_outputs.transferableoutput.md)[]*

*Heredada de [BaseTx](api_platformvm_basetx.basetx.md).[getTotalOuts](api_platformvm_basetx.basetx.md#gettotalouts)*

*Overrides [StandardBaseTx](common_transactions.standardbasetx.md).[getTotalOuts](common_transactions.standardbasetx.md#abstract-gettotalouts)*

*Definido en [src/apis/platformvm/basetx.ts:57](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/basetx.ts#L57)*

**Retornos:** *[Producto transferible](api_platformvm_outputs.transferableoutput.md)[]*

___

### getTxType

- **getTxType**(): *número*

*Heredada de [BaseTx](api_platformvm_basetx.basetx.md).[getTxType](api_platformvm_basetx.basetx.md#gettxtype)*

*Overrides [StandardBaseTx](common_transactions.standardbasetx.md).[getTxType](common_transactions.standardbasetx.md#abstract-gettxtype)*

*Definido en [src/apis/platformvm/basetx.ts:64](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/basetx.ts#L64)*

Devuelve el id de la [BaseTx](api_platformvm_basetx.basetx.md)

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

### getWeight

- **getWeight**(): *BN*

*Definido en [src/apis/platformvm/validationtx.ts:143](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/validationtx.ts#L143)*

Devuelve un [BN](https://github.com/indutny/bn.js/) por el importe de la estaca.

**Returns:** *BN*

___

### getWeightBuffer

- **getWeightBuffer**(): *Buffer*

*Definido en [src/apis/platformvm/validationtx.ts:150](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/validationtx.ts#L150)*

Devuelve un [Buffer](https://github.com/feross/buffer) por la cantidad de la estaca.

**Returns:** *Buffer*

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

*Superaciones [ValidatorTx](api_platformvm_validationtx.validatortx.md).[serialize](api_platformvm_validationtx.validatortx.md#serialize)*

*Definido en [src/apis/platformvm/validationtx.ts:126](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/validationtx.ts#L126)*

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

*Overrides [ValidatorTx](api_platformvm_validationtx.validatortx.md).[toBuffer](api_platformvm_validationtx.validatortx.md#tobuffer)*

*Definido en [src/apis/platformvm/validationtx.ts:164](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/validationtx.ts#L164)*

Devuelve una representación de [Buffer](https://github.com/feross/buffer) del [[AddSubnetValidatorTx]].

**Returns:** *Buffer*

___

### toString

- **toString**(): *string*

*Heredada de [StandardBaseTx](common_transactions.standardbasetx.md).[toString](common_transactions.standardbasetx.md#tostring)*

*Definido en [src/comm/tx.ts:129](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/tx.ts#L129)*

Devuelve una representación de base 58 de la [StandardBaseTx](common_transactions.standardbasetx.md).

**Return:** *string*
