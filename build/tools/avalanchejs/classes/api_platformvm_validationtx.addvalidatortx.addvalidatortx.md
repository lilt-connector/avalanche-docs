[avalanche](../README.md) › [API-PlatformVM-ValidationTx](../modules/api_platformvm_validationtx.md) › [AddValidatorTx](api_platformvm_validationtx.addvalidatortx.md)

# Clase: AddValidatorTx

## Jerarquía

m. [AddDelegatorTx](api_platformvm_validationtx.adddelegatortx.md)

m. **AddValidatorTx**

## Índice de participación

### Constructores

* [constructor](api_platformvm_validationtx.addvalidatortx.md#constructor)

### Propiedades de las propiedades

* [_codecid](api_platformvm_validationtx.addvalidatortx.md#protected-_codecid)
* [_typeID](api_platformvm_validationtx.addvalidatortx.md#protected-_typeid)
* [_typeName](api_platformvm_validationtx.addvalidatortx.md#protected-_typename)
* [blockchainID](api_platformvm_validationtx.addvalidatortx.md#protected-blockchainid)
* [DelegationFee](api_platformvm_validationtx.addvalidatortx.md#protected-delegationfee)
* [endTime](api_platformvm_validationtx.addvalidatortx.md#protected-endtime)
* [ins](api_platformvm_validationtx.addvalidatortx.md#protected-ins)
* [meme](api_platformvm_validationtx.addvalidatortx.md#protected-memo)
* [networkID](api_platformvm_validationtx.addvalidatortx.md#protected-networkid)
* [nodeID](api_platformvm_validationtx.addvalidatortx.md#protected-nodeid)
* [numero](api_platformvm_validationtx.addvalidatortx.md#protected-numins)
* [numouts](api_platformvm_validationtx.addvalidatortx.md#protected-numouts)
* [outs](api_platformvm_validationtx.addvalidatortx.md#protected-outs)
* [rewardOwners](api_platformvm_validationtx.addvalidatortx.md#protected-rewardowners)
* [Las hogueras](api_platformvm_validationtx.addvalidatortx.md#protected-stakeouts)
* [startTime](api_platformvm_validationtx.addvalidatortx.md#protected-starttime)
* [peso](api_platformvm_validationtx.addvalidatortx.md#protected-weight)
* [delegatorMultiplier](api_platformvm_validationtx.addvalidatortx.md#static-private-delegatormultiplier)

### Métodos de trabajo

* [clon](api_platformvm_validationtx.addvalidatortx.md#clone)
* [crear un entorno de creación](api_platformvm_validationtx.addvalidatortx.md#create)
* [deserie](api_platformvm_validationtx.addvalidatortx.md#deserialize)
* [deBuffer](api_platformvm_validationtx.addvalidatortx.md#frombuffer)
* [getBlockchainID](api_platformvm_validationtx.addvalidatortx.md#getblockchainid)
* [getCodecid](api_platformvm_validationtx.addvalidatortx.md#getcodecid)
* [getDelegationFee](api_platformvm_validationtx.addvalidatortx.md#getdelegationfee)
* [getDelegationFeeBuffer](api_platformvm_validationtx.addvalidatortx.md#getdelegationfeebuffer)
* [getEndTime](api_platformvm_validationtx.addvalidatortx.md#getendtime)
* [getIns](api_platformvm_validationtx.addvalidatortx.md#getins)
* [getMemo](api_platformvm_validationtx.addvalidatortx.md#getmemo)
* [getNetworkID](api_platformvm_validationtx.addvalidatortx.md#getnetworkid)
* [getNodeID](api_platformvm_validationtx.addvalidatortx.md#getnodeid)
* [getNodeIDString](api_platformvm_validationtx.addvalidatortx.md#getnodeidstring)
* [gets Outs](api_platformvm_validationtx.addvalidatortx.md#getouts)
* [getRewardOwners](api_platformvm_validationtx.addvalidatortx.md#getrewardowners)
* [getStakeAmount](api_platformvm_validationtx.addvalidatortx.md#getstakeamount)
* [getStakeAmountBuffer](api_platformvm_validationtx.addvalidatortx.md#getstakeamountbuffer)
* [getStakeOuts Outs](api_platformvm_validationtx.addvalidatortx.md#getstakeouts)
* [getStakeOutsTotal](api_platformvm_validationtx.addvalidatortx.md#getstakeoutstotal)
* [getStartTime](api_platformvm_validationtx.addvalidatortx.md#getstarttime)
* [getTotalOuts](api_platformvm_validationtx.addvalidatortx.md#gettotalouts)
* [getTxType](api_platformvm_validationtx.addvalidatortx.md#gettxtype)
* [getTypeID](api_platformvm_validationtx.addvalidatortx.md#gettypeid)
* [getTypeName](api_platformvm_validationtx.addvalidatortx.md#gettypename)
* [getWeight](api_platformvm_validationtx.addvalidatortx.md#getweight)
* [getWeightBuffer](api_platformvm_validationtx.addvalidatortx.md#getweightbuffer)
* [seleccionar](api_platformvm_validationtx.addvalidatortx.md#select)
* [serializar](api_platformvm_validationtx.addvalidatortx.md#serialize)
* [señal de que la señal de que la](api_platformvm_validationtx.addvalidatortx.md#sign)
* [toBuffer](api_platformvm_validationtx.addvalidatortx.md#tobuffer)
* [toString](api_platformvm_validationtx.addvalidatortx.md#tostring)

## Constructores

### constructor

\+ **nuevo** `AddValidatorTx(networkID`: number, `blockchainID`: Buffer, `outs`: [number](api_platformvm_outputs.transferableoutput.md)[](api_platformvm_inputs.transferableinput.md)[](api_platformvm_outputs.transferableoutput.md), `ins`: []number, `memorando`: Buffer, `nodeID`: Buffer, `startTime`: BN, `endTime```: BN, `stakeAmount`: `memo`: [][]number, `AddValidatorTx(networkID`: [number](api_platformvm_outputs.parseableoutput.md), AddValidatorTx(networkID: número): *[AddValidatorTx](api_platformvm_validationtx.addvalidatortx.md)*

*Overrides [AddDelegatorTx](api_platformvm_validationtx.adddelegatortx.md).[constructor](api_platformvm_validationtx.adddelegatortx.md#constructor)*

*Definido en [src/apis/platformvm/validationtx.ts:532](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/validationtx.ts#L532)*

Clase que representa una transacción de AddValidatorTx sin firmar.

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
| `Importe de la participación` | BN | no definido. | Opcional. La cantidad de nAVAX el validador está estancando. |
| `Las hogueras` | [Producto transferible](api_platformvm_outputs.transferableoutput.md)[] | no definido. | Opcional. Los productos utilizados para pagar la hoguera. |
| `rewardOwners` | [Salida ParseableOutput](api_platformvm_outputs.parseableoutput.md) | no definido. | Opcional. La salida [ParseableOutput](api_platformvm_outputs.parseableoutput.md) que contiene la salida [SECPOwnerOutput](api_platformvm_outputs.secpowneroutput.md) para las recompensas. |
| `DelegationFee` | Número de números | no definido. | Opcional. El porcentaje de honorarios que este validador cobra cuando otros delegan en ellos la estaca. Hasta 4 lugares decimales permitidos; se ignoran los lugares decimales adicionales. Debe ser entre 0 y 100, inclusive. Por ejemplo, si la delegationFeeRate es 1.2345 y alguien delega en este validador, entonces cuando el período de delegación haya terminado, el 1.2345% de la recompensa va al validador y el resto va al delegador. |

**Returns:** *[AddValidatorTx](api_platformvm_validationtx.addvalidatortx.md)*

## Propiedades de las propiedades

### _codecid `protegido`

• **_codecid**: *número* = indefinido.

*Heredada de [SigIdx](common_signature.sigidx.md)[._codecid](common_signature.sigidx.md#protected-_codecid)*

*Definido en [src/utils/serialización.ts:40](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/serialization.ts#L40)*

___

### `Protegido` _typeID

• **_typeID**: *número* = PlatformVMConstants.ADDVALIDATORTX

*Overrides [AddDelegatorTx](api_platformvm_validationtx.adddelegatortx.md).[_typeID](api_platformvm_validationtx.adddelegatortx.md#protected-_typeid)*

*Definido en [src/apis/platformvm/validationtx.ts:478](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/validationtx.ts#L478)*

___

### _typeName `protegido`

• **_typeName**: *string* = "AddValidatorTx"

*Overrides [AddDelegatorTx](api_platformvm_validationtx.adddelegatortx.md).[_typeName](api_platformvm_validationtx.adddelegatortx.md#protected-_typename)*

*Definido en [src/apis/platformvm/validationtx.ts:477](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/validationtx.ts#L477)*

___

### blockchainID `protegido`

• **blockchainID**: *Buffer* = Buffer.aloc(32)

*Heredada de [StandardBaseTx](common_transactions.standardbasetx.md).[blockchainID](common_transactions.standardbasetx.md#protected-blockchainid)*

*Definido en [src/comm/tx.ts:52](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/tx.ts#L52)*

___

### Delegaciones `Protected`

• **delegationFee**: *número* = 0

*Definido en [src/apis/platformvm/validationtx.ts:493](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/validationtx.ts#L493)*

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

### recompensas `Protected`

• **rewardOwners**: *[ParseableOutput](api_platformvm_outputs.parseableoutput.md)* = indefinida

*Heredado de [AddDelegatorTx](api_platformvm_validationtx.adddelegatortx.md).[rewardOwners](api_platformvm_validationtx.adddelegatortx.md#protected-rewardowners)*

*Definido en [src/apis/platformvm/validationtx.ts:340](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/validationtx.ts#L340)*

___

### Las hogueras `protegidas`

• **Vigilancia**: *[TransferableOutput](api_platformvm_outputs.transferableoutput.md)[]* =[]

*Heredada de [AddDelegatorTx](api_platformvm_validationtx.adddelegatortx.md).[stakeOuts](api_platformvm_validationtx.adddelegatortx.md#protected-stakeouts)*

*Definido en [src/apis/platformvm/validationtx.ts:339](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/validationtx.ts#L339)*

___

### Tiempo de inicio `protegido`

• **Hora de inicio**: *Buffer* = Buffer.aloc(8)

*Heredada de [ValidatorTx](api_platformvm_validationtx.validatortx.md).[startTime](api_platformvm_validationtx.validatortx.md#protected-starttime)*

*Definido en [src/apis/platformvm/validationtx.ts:49](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/validationtx.ts#L49)*

___

### Peso `protegido`

• **peso**: *Buffer* = Buffer.aloc(8)

*Heredado de [WeightedValidatorTx](api_platformvm_validationtx.weightedvalidatortx.md).[weight](api_platformvm_validationtx.weightedvalidatortx.md#protected-weight)*

*Definido en [src/apis/platformvm/validationtx.ts:138](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/validationtx.ts#L138)*

___

### Delegador `privado` `Static`

• **delegatorMultiplier**: *número* = 10000

*Definido en [src/apis/platformvm/validationtx.ts:494](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/validationtx.ts#L494)*

## Métodos de trabajo

### clon

- **clone**(): *esto*

*Heredada de [AddDelegatorTx](api_platformvm_validationtx.adddelegatortx.md).[clone](api_platformvm_validationtx.adddelegatortx.md#clone)*

*Superar [BaseTx](api_platformvm_basetx.basetx.md).[clone](api_platformvm_basetx.basetx.md#clone)*

*Definido en [src/apis/platformvm/validationtx.ts:430](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/validationtx.ts#L430)*

**Returns:** *esto*

___

### crear un entorno de creación

*-* **create**(...`args`: []cualquiera

*Heredada de [AddDelegatorTx](api_platformvm_validationtx.adddelegatortx.md).[create](api_platformvm_validationtx.adddelegatortx.md#create)*

*Supera [BaseTx](api_platformvm_basetx.basetx.md).[create](api_platformvm_basetx.basetx.md#create)*

*Definido en [src/apis/platformvm/validationtx.ts:436](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/validationtx.ts#L436)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `..args` | cualquier otra cosa que no sea[] |

**Returns:** *esto*

___

### deserie

- **deserialize**(`fields`: objeto, `codificación`: [SerializedEncoding](../modules/src_utils.md#serializedencoding)): *vacío*

*Overrides [AddDelegatorTx](api_platformvm_validationtx.adddelegatortx.md).[deserialize](api_platformvm_validationtx.adddelegatortx.md#deserialize)*

*Definido en [src/apis/platformvm/validationtx.ts:487](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/validationtx.ts#L487)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `campos de cultivo` | objeto de la operación | - |
| `codificación` | [SerializedEncoding](../modules/src_utils.md#serializedencoding) | "hex" |

**Retornos:** *vacío*

___

### deBuffer

- **fromBuffer**(`bytes`: Buffer, `offset`: número): *número*

*Desguace [AddDelegatorTx](api_platformvm_validationtx.adddelegatortx.md).[fromBuffer](api_platformvm_validationtx.adddelegatortx.md#frombuffer)*

*Definido en [src/apis/platformvm/validationtx.ts:520](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/validationtx.ts#L520)*

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

### getDelegationFee

- **getDelegationFee**(): *número*

*Definido en [src/apis/platformvm/validationtx.ts:506](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/validationtx.ts#L506)*

Devuelve la cuota de delegación (representa un porcentaje de 0 a 100);

**Retornos:** *número*

___

### getDelegationFeeBuffer

- **getDelegationFeeBuffer** (): *Buffer*

*Definido en [src/apis/platformvm/validationtx.ts:513](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/validationtx.ts#L513)*

Devuelve la representación binaria de la cuota de delegación como [Buffer](https://github.com/feross/buffer).

**Returns:** *Buffer*

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

### getRewardOwners

- **getRewardOwners**(): *[ParseableOutput](api_platformvm_outputs.parseableoutput.md)*

*Heredado de [AddDelegatorTx](api_platformvm_validationtx.adddelegatortx.md).[getRewardOwners](api_platformvm_validationtx.adddelegatortx.md#getrewardowners)*

*Definido en [src/apis/platformvm/validationtx.ts:384](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/validationtx.ts#L384)*

Devuelve un [buffer](https://github.com/feross/buffer) para la dirección de recompensa.

**Retornos:** Salida *[ParseableOutput](api_platformvm_outputs.parseableoutput.md)*

___

### getStakeAmount

- **getStakeAmount**(): *BN*

*Heredada de [AddDelegatorTx](api_platformvm_validationtx.adddelegatortx.md).[getStakeAmount](api_platformvm_validationtx.adddelegatortx.md#getstakeamount)*

*Definido en [src/apis/platformvm/validationtx.ts:352](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/validationtx.ts#L352)*

Devuelve un [BN](https://github.com/indutny/bn.js/) por el importe de la estaca.

**Returns:** *BN*

___

### getStakeAmountBuffer

- **getStakeAmountBuffer**(): *Buffer*

*Heredada de [AddDelegatorTx](api_platformvm_validationtx.adddelegatortx.md).[getStakeAmountBuffer](api_platformvm_validationtx.adddelegatortx.md#getstakeamountbuffer)*

*Definido en [src/apis/platformvm/validationtx.ts:359](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/validationtx.ts#L359)*

Devuelve un [Buffer](https://github.com/feross/buffer) por la cantidad de la estaca.

**Returns:** *Buffer*

___

### getStakeOuts Outs

- **getStakeOuts**(): *[Producto transferible](api_platformvm_outputs.transferableoutput.md)[]*

*Heredada de [AddDelegatorTx](api_platformvm_validationtx.adddelegatortx.md).[getStakeOuts](api_platformvm_validationtx.adddelegatortx.md#getstakeouts)*

*Definido en [src/apis/platformvm/validationtx.ts:366](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/validationtx.ts#L366)*

Devuelve la variedad de salidas que están en stock.

**Retornos:** *[Producto transferible](api_platformvm_outputs.transferableoutput.md)[]*

___

### getStakeOutsTotal

- **getStakeOutsTotal**(): *BN*

*Heredado de [AddDelegatorTx](api_platformvm_validationtx.adddelegatortx.md).[getStakeOutsTotal](api_platformvm_validationtx.adddelegatortx.md#getstakeoutstotal)*

*Definido en [src/apis/platformvm/validationtx.ts:373](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/validationtx.ts#L373)*

Debería coincidir con la stakeAmount. Utilizado en la verificación de cordura.

**Returns:** *BN*

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

*Heredada de [AddDelegatorTx](api_platformvm_validationtx.adddelegatortx.md).[getTotalOuts](api_platformvm_validationtx.adddelegatortx.md#gettotalouts)*

*Superaciones [BaseTx](api_platformvm_basetx.basetx.md).[getTotalOuts](api_platformvm_basetx.basetx.md#gettotalouts)*

*Definido en [src/apis/platformvm/validationtx.ts:388](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/validationtx.ts#L388)*

**Retornos:** *[Producto transferible](api_platformvm_outputs.transferableoutput.md)[]*

___

### getTxType

- **getTxType**(): *número*

*Overrides [AddDelegatorTx](api_platformvm_validationtx.adddelegatortx.md).[getTxType](api_platformvm_validationtx.adddelegatortx.md#gettxtype)*

*Definido en [src/apis/platformvm/validationtx.ts:499](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/validationtx.ts#L499)*

Devuelve el id del [AddValidatorTx](api_platformvm_validationtx.addvalidatortx.md)

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

*Heredado de [WeightedValidatorTx](api_platformvm_validationtx.weightedvalidatortx.md).[getWeight](api_platformvm_validationtx.weightedvalidatortx.md#getweight)*

*Definido en [src/apis/platformvm/validationtx.ts:143](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/validationtx.ts#L143)*

Devuelve un [BN](https://github.com/indutny/bn.js/) por el importe de la estaca.

**Returns:** *BN*

___

### getWeightBuffer

- **getWeightBuffer**(): *Buffer*

*Heredado de [WeightedValidatorTx](api_platformvm_validationtx.weightedvalidatortx.md).[getWeightBuffer](api_platformvm_validationtx.weightedvalidatortx.md#getweightbuffer)*

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

*Desglose [AddDelegatorTx](api_platformvm_validationtx.adddelegatortx.md).[serialize](api_platformvm_validationtx.adddelegatortx.md#serialize)*

*Definido en [src/apis/platformvm/validationtx.ts:480](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/validationtx.ts#L480)*

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

*Desglose [AddDelegatorTx](api_platformvm_validationtx.adddelegatortx.md).[toBuffer](api_platformvm_validationtx.adddelegatortx.md#tobuffer)*

*Definido en [src/apis/platformvm/validationtx.ts:528](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/validationtx.ts#L528)*

**Returns:** *Buffer*

___

### toString

- **toString**(): *string*

*Heredada de [StandardBaseTx](common_transactions.standardbasetx.md).[toString](common_transactions.standardbasetx.md#tostring)*

*Definido en [src/comm/tx.ts:129](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/tx.ts#L129)*

Devuelve una representación de base 58 de la [StandardBaseTx](common_transactions.standardbasetx.md).

**Return:** *string*
