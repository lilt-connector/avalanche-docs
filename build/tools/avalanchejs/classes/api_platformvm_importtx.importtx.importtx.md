[avalanche](../README.md) › [API-PlatformVM-ImportTx](../modules/api_platformvm_importtx.md) › [ImportTx](api_platformvm_importtx.importtx.md)

# Clase: ImportTx

Clase que representa una transacción de importación no firmada.

## Jerarquía

de [BaseTx](api_platformvm_basetx.basetx.md)

m **ImportTx**

## Índice de participación

### Constructores

* [constructor](api_platformvm_importtx.importtx.md#constructor)

### Propiedades de las propiedades

* [_codecid](api_platformvm_importtx.importtx.md#protected-_codecid)
* [_typeID](api_platformvm_importtx.importtx.md#protected-_typeid)
* [_typeName](api_platformvm_importtx.importtx.md#protected-_typename)
* [blockchainID](api_platformvm_importtx.importtx.md#protected-blockchainid)
* [importIns](api_platformvm_importtx.importtx.md#protected-importins)
* [ins](api_platformvm_importtx.importtx.md#protected-ins)
* [meme](api_platformvm_importtx.importtx.md#protected-memo)
* [networkID](api_platformvm_importtx.importtx.md#protected-networkid)
* [numIns](api_platformvm_importtx.importtx.md#protected-numins)
* [numero](api_platformvm_importtx.importtx.md#protected-numins)
* [numouts](api_platformvm_importtx.importtx.md#protected-numouts)
* [outs](api_platformvm_importtx.importtx.md#protected-outs)
* [sourceChain](api_platformvm_importtx.importtx.md#protected-sourcechain)

### Métodos de trabajo

* [clon](api_platformvm_importtx.importtx.md#clone)
* [crear un entorno de creación](api_platformvm_importtx.importtx.md#create)
* [deserie](api_platformvm_importtx.importtx.md#deserialize)
* [deBuffer](api_platformvm_importtx.importtx.md#frombuffer)
* [getBlockchainID](api_platformvm_importtx.importtx.md#getblockchainid)
* [getCodecid](api_platformvm_importtx.importtx.md#getcodecid)
* [getImportInputs](api_platformvm_importtx.importtx.md#getimportinputs)
* [getIns](api_platformvm_importtx.importtx.md#getins)
* [getMemo](api_platformvm_importtx.importtx.md#getmemo)
* [getNetworkID](api_platformvm_importtx.importtx.md#getnetworkid)
* [gets Outs](api_platformvm_importtx.importtx.md#getouts)
* [getTotalOuts](api_platformvm_importtx.importtx.md#gettotalouts)
* [getTxType](api_platformvm_importtx.importtx.md#gettxtype)
* [getTypeID](api_platformvm_importtx.importtx.md#gettypeid)
* [getTypeName](api_platformvm_importtx.importtx.md#gettypename)
* [seleccionar](api_platformvm_importtx.importtx.md#select)
* [serializar](api_platformvm_importtx.importtx.md#serialize)
* [señal de que la señal de que la](api_platformvm_importtx.importtx.md#sign)
* [toBuffer](api_platformvm_importtx.importtx.md#tobuffer)
* [toString](api_platformvm_importtx.importtx.md#tostring)

## Constructores

### constructor

\+ **nuevo ImportTx(networkID:**`` number, `blockchainID`: Buffer, `outs`: [number](api_platformvm_outputs.transferableoutput.md)[], `ins`: [TransferableInput](api_platformvm_inputs.transferableinput.md)[](api_platformvm_inputs.transferableinput.md), `memo`: Buffer, `sourceChain`: Buffer, `importIns`: [][]ImportTx(networkID: *[ImportTx](api_platformvm_importtx.importtx.md)*

*Superaciones [BaseTx](api_platformvm_basetx.basetx.md).[constructor](api_platformvm_basetx.basetx.md#constructor)*

*Definido en [src/apis/platformvm/importtx.ts:142](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/importtx.ts#L142)*

Clase que representa una transacción de importación no firmada.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `networkID` | Número de números | DefaultNetworkID | Opcional networkID, [DefaultNetworkID](../modules/utils_constants.md#const-defaultnetworkid) |
| `blockchainID` | Buffer | Buffer.aloc(32, 16) | blockchainID, predeterminado Buffer.aloc(32, 16) |
| `outs` | [Producto transferible](api_platformvm_outputs.transferableoutput.md)[] | no definido. | Variedad opcional de los [Productos Transferibles](api_platformvm_outputs.transferableoutput.md) |
| `ins` | [Entrada transferible](api_platformvm_inputs.transferableinput.md)[] | no definido. | Variedad opcional de los [insumos](api_platformvm_inputs.transferableinput.md) transferibles. |
| `meme` | Buffer | no definido. | [Buffer](https://github.com/feross/buffer) opcional para el campo de memorias |
| `sourceChain` | Buffer | no definido. | Optiona chainid para las entradas de fuente a importar. plataforma predeterminada. |
| `importIns` | [Entrada transferible](api_platformvm_inputs.transferableinput.md)[] | no definido. | Conjunto de [entradas transferibles](api_platformvm_inputs.transferableinput.md) utilizadas en la transacción |

**Returns:** *[ImportTx](api_platformvm_importtx.importtx.md)*

## Propiedades de las propiedades

### _codecid `protegido`

• **_codecid**: *número* = indefinido.

*Heredada de [SigIdx](common_signature.sigidx.md)[._codecid](common_signature.sigidx.md#protected-_codecid)*

*Definido en [src/utils/serialización.ts:40](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/serialization.ts#L40)*

___

### `Protegido` _typeID

• **_typeID**: *número* = PlatformVMConstants.IMPORTTX

*Superaciones [BaseTx](api_platformvm_basetx.basetx.md).[_typeID](api_platformvm_basetx.basetx.md#protected-_typeid)*

*Definido en [src/apis/platformvm/importtx.ts:30](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/importtx.ts#L30)*

___

### _typeName `protegido`

• **_typeName**: *string* = "ImportTx"

*Superaciones [BaseTx](api_platformvm_basetx.basetx.md).[_typeName](api_platformvm_basetx.basetx.md#protected-_typename)*

*Definido en [src/apis/platformvm/importtx.ts:29](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/importtx.ts#L29)*

___

### blockchainID `protegido`

• **blockchainID**: *Buffer* = Buffer.aloc(32)

*Heredada de [StandardBaseTx](common_transactions.standardbasetx.md).[blockchainID](common_transactions.standardbasetx.md#protected-blockchainid)*

*Definido en [src/comm/tx.ts:52](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/tx.ts#L52)*

___

### Importaciones `protegidas`

• **Importantes**: *[Entrada](api_platformvm_inputs.transferableinput.md)[]* transferible=[]

*Definido en [src/apis/platformvm/importtx.ts:54](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/importtx.ts#L54)*

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

*Definido en [src/apis/platformvm/importtx.ts:53](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/importtx.ts#L53)*

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

*Definido en [src/apis/platformvm/importtx.ts:52](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/importtx.ts#L52)*

## Métodos de trabajo

### clon

- **clone**(): *esto*

*Superar [BaseTx](api_platformvm_basetx.basetx.md).[clone](api_platformvm_basetx.basetx.md#clone)*

*Definido en [src/apis/platformvm/importtx.ts:134](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/importtx.ts#L134)*

**Returns:** *esto*

___

### crear un entorno de creación

*-* **create**(...`args`: []cualquiera

*Supera [BaseTx](api_platformvm_basetx.basetx.md).[create](api_platformvm_basetx.basetx.md#create)*

*Definido en [src/apis/platformvm/importtx.ts:140](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/importtx.ts#L140)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `..args` | cualquier otra cosa que no sea[] |

**Returns:** *esto*

___

### deserie

- **deserialize**(`fields`: objeto, `codificación`: [SerializedEncoding](../modules/src_utils.md#serializedencoding)): *vacío*

*Superaciones [BaseTx](api_platformvm_basetx.basetx.md).[deserialize](api_platformvm_basetx.basetx.md#deserialize)*

*Definido en [src/apis/platformvm/importtx.ts:40](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/importtx.ts#L40)*

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

*Definido en [src/apis/platformvm/importtx.ts:72](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/importtx.ts#L72)*

Toma un [buffer](https://github.com/feross/buffer) que contiene una [ImportTx](api_platformvm_importtx.importtx.md), lo analiza, populates la clase y devuelve la longitud de la [ImportTx](api_platformvm_importtx.importtx.md) en bytes.

**`observaciones`** asuman que no se ha comprobado

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `bytes` | Buffer | - | Un [buffer](https://github.com/feross/buffer) que contiene una [importTx](api_platformvm_importtx.importtx.md) cruda |
| `offset` | Número de números | 0 | - |

**Retornos:** *número*

La longitud de la [importTx](api_platformvm_importtx.importtx.md) cruda

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

- **getImportInputs**(): *[TransferableInput](api_platformvm_inputs.transferableinput.md)[]*

*Definido en [src/apis/platformvm/importtx.ts:105](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/importtx.ts#L105)*

Devuelve una variedad de [entradas transferibles](api_platformvm_inputs.transferableinput.md) en esta transacción.

**Retornos:** *[Input transferible](api_platformvm_inputs.transferableinput.md)[]*

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

*Heredada de [BaseTx](api_platformvm_basetx.basetx.md).[getTotalOuts](api_platformvm_basetx.basetx.md#gettotalouts)*

*Overrides [StandardBaseTx](common_transactions.standardbasetx.md).[getTotalOuts](common_transactions.standardbasetx.md#abstract-gettotalouts)*

*Definido en [src/apis/platformvm/basetx.ts:57](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/basetx.ts#L57)*

**Retornos:** *[Producto transferible](api_platformvm_outputs.transferableoutput.md)[]*

___

### getTxType

- **getTxType**(): *número*

*Superaciones [BaseTx](api_platformvm_basetx.basetx.md).[getTxType](api_platformvm_basetx.basetx.md#gettxtype)*

*Definido en [src/apis/platformvm/importtx.ts:59](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/importtx.ts#L59)*

Devuelve el id de la [ImportTx](api_platformvm_importtx.importtx.md)

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

*Definido en [src/apis/platformvm/importtx.ts:32](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/importtx.ts#L32)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `codificación` | [SerializedEncoding](../modules/src_utils.md#serializedencoding) | "hex" |

**Return:** *objeto*

___

### señal de que la señal de que la

- **sign**(`msg`: Buffer, `kc`: [KeyChain](api_platformvm_keychain.keychain.md)): *[Credencial](common_signature.credential.md)[]*

*Superar [BaseTx](api_platformvm_basetx.basetx.md).[sign](api_platformvm_basetx.basetx.md#sign).*

*Definido en [src/apis/platformvm/importtx.ts:117](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/importtx.ts#L117)*

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

*Definido en [src/apis/platformvm/importtx.ts:90](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/importtx.ts#L90)*

Devuelve una representación de [Buffer](https://github.com/feross/buffer) de la [ImportTx](api_platformvm_importtx.importtx.md).

**Returns:** *Buffer*

___

### toString

- **toString**(): *string*

*Heredada de [StandardBaseTx](common_transactions.standardbasetx.md).[toString](common_transactions.standardbasetx.md#tostring)*

*Definido en [src/comm/tx.ts:129](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/tx.ts#L129)*

Devuelve una representación de base 58 de la [StandardBaseTx](common_transactions.standardbasetx.md).

**Return:** *string*
