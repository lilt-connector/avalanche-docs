[avalancha](../README.md) › [API-EVM-ExportTx](../modules/api_evm_exporttx.md) › [ExportTx](api_evm_exporttx.exporttx.md)

# Clase: ExportTx

## Jerarquía

de [la](api_evm_basetx.evmbasetx.md) marca EVMbaseTx

m. **ExportTx**

## Índice de participación

### Constructores

* [constructor](api_evm_exporttx.exporttx.md#constructor)

### Propiedades de las propiedades

* [_codecid](api_evm_exporttx.exporttx.md#protected-_codecid)
* [_typeID](api_evm_exporttx.exporttx.md#protected-_typeid)
* [_typeName](api_evm_exporttx.exporttx.md#protected-_typename)
* [blockchainID](api_evm_exporttx.exporttx.md#protected-blockchainid)
* [destinationChain de destino](api_evm_exporttx.exporttx.md#protected-destinationchain)
* [Productos exportados](api_evm_exporttx.exporttx.md#protected-exportedoutputs)
* [entradas](api_evm_exporttx.exporttx.md#protected-inputs)
* [networkID](api_evm_exporttx.exporttx.md#protected-networkid)
* [numExportedOutputs](api_evm_exporttx.exporttx.md#protected-numexportedoutputs)
* [numInputs](api_evm_exporttx.exporttx.md#protected-numinputs)

### Métodos de trabajo

* [clon](api_evm_exporttx.exporttx.md#clone)
* [crear un entorno de creación](api_evm_exporttx.exporttx.md#create)
* [deserie](api_evm_exporttx.exporttx.md#deserialize)
* [deBuffer](api_evm_exporttx.exporttx.md#frombuffer)
* [getBlockchainID](api_evm_exporttx.exporttx.md#getblockchainid)
* [getCodecid](api_evm_exporttx.exporttx.md#getcodecid)
* [getDestinationChain](api_evm_exporttx.exporttx.md#getdestinationchain)
* [getExportedOutputs](api_evm_exporttx.exporttx.md#getexportedoutputs)
* [getInputs](api_evm_exporttx.exporttx.md#getinputs)
* [getNetworkID](api_evm_exporttx.exporttx.md#getnetworkid)
* [getTxType](api_evm_exporttx.exporttx.md#gettxtype)
* [getTypeID](api_evm_exporttx.exporttx.md#gettypeid)
* [getTypeName](api_evm_exporttx.exporttx.md#gettypename)
* [seleccionar](api_evm_exporttx.exporttx.md#select)
* [serializar](api_evm_exporttx.exporttx.md#serialize)
* [señal de que la señal de que la](api_evm_exporttx.exporttx.md#sign)
* [toBuffer](api_evm_exporttx.exporttx.md#tobuffer)
* [toString](api_evm_exporttx.exporttx.md#tostring)

## Constructores

### constructor

\+ **nuevo ExportTx(networkID:**`` number, `blockchainID`: Buffer, `destinationChain`: de `entrada`: Buffer, `entradas`: [EVMInput](api_evm_inputs.evminput.md)[], [ExportTx(networkID:](api_evm_outputs.transferableoutput.md) []ExportTx(networkID: *[ExportTx](api_evm_exporttx.exporttx.md)*

*Superar [EVMbaseTx.constructor](api_evm_basetx.evmbasetx.md)[](api_evm_basetx.evmbasetx.md#constructor)*

*Definido en [src/apis/evm/exporttx.ts:156](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/exporttx.ts#L156)*

Clase que representa una ExportTx.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `networkID` | Número de números | no definido. | ID opcional |
| `blockchainID` | Buffer | Buffer.aloc(32, 16) | blockchainID, predeterminado Buffer.aloc(32, 16) |
| `destinationChain de destino` | Buffer | Buffer.aloc(32, 16) | Destino Optional de destino, predeterminado Buffer.aloc(32, 16) |
| `entradas` | [EVMInput](api_evm_inputs.evminput.md)[] | no definido. | Variedad opcional de los [[EVMInputs]]s |
| `Productos exportados` | [Producto transferible](api_evm_outputs.transferableoutput.md)[] | no definido. | Variedad opcional de los [[EVMOutputs]]s |

**Returns:** *[ExportTx](api_evm_exporttx.exporttx.md)*

## Propiedades de las propiedades

### _codecid `protegido`

• **_codecid**: *número* = indefinido.

*Heredada de [SigIdx](common_signature.sigidx.md)[._codecid](common_signature.sigidx.md#protected-_codecid)*

*Definido en [src/utils/serialización.ts:40](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/serialization.ts#L40)*

___

### `Protegido` _typeID

• **_typeID**: *número* = EVMConstants.EXPORTTX

*Superar [EVMbaseTx._typeID](api_evm_basetx.evmbasetx.md)[](api_evm_basetx.evmbasetx.md#protected-_typeid)*

*Definido en [src/apis/evm/exporttx.ts:33](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/exporttx.ts#L33)*

___

### _typeName `protegido`

• **_typeName**: *string* = "ExportTx"

*Overrides [EVMBaseTx](api_evm_basetx.evmbasetx.md).[_typeName](api_evm_basetx.evmbasetx.md#protected-_typename)*

*Definido en [src/apis/evm/exporttx.ts:32](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/exporttx.ts#L32)*

___

### blockchainID `protegido`

• **blockchainID**: *Buffer* = Buffer.aloc(32)

*Heredada de [EVMStandardBaseTx](common_transactions.evmstandardbasetx.md).[blockchainID](common_transactions.evmstandardbasetx.md#protected-blockchainid)*

*Definido en [src/commtx.ts:45](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/evmtx.ts#L45)*

___

### Destino `protegido:`

• **destinationChain**: *Buffer* = Buffer.aloc(32)

*Definido en [src/apis/evm/exporttx.ts:55](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/exporttx.ts#L55)*

___

### Productos `exportados protegidos`

• **Productos exportados**: *[TransferableOutput](api_evm_outputs.transferableoutput.md)[]* =[]

*Definido en [src/apis/evm/exporttx.ts:59](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/exporttx.ts#L59)*

___

### Instancias `protegidas`

• **entradas**: *[EVMInput](api_evm_inputs.evminput.md)[]* =[]

*Definido en [src/apis/evm/exporttx.ts:57](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/exporttx.ts#L57)*

___

### Red `protegida`

• **networkID**: *Buffer* = Buffer.aloc(4)

*Heredada de [EVMStandardBaseTx](common_transactions.evmstandardbasetx.md).[networkID](common_transactions.evmstandardbasetx.md#protected-networkid)*

*Definido en [src/commtx.ts:44](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/evmtx.ts#L44)*

___

### Salidas numéricas `protegidas`

• **numExportedOutputs**: *Buffer* = Buffer.aloc(4)

*Definido en [src/apis/evm/exporttx.ts:58](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/exporttx.ts#L58)*

___

### numInputs `protegidas`

• **numInputs**: *Buffer* = Buffer.aloc(4)

*Definido en [src/apis/evm/exporttx.ts:56](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/exporttx.ts#L56)*

## Métodos de trabajo

### clon

- **clone**(): *esto*

*Heredada de [EVMbaseTx.clone](api_evm_basetx.evmbasetx.md)[](api_evm_basetx.evmbasetx.md#clone)*

*Superar [EVMStandardBaseTx](common_transactions.evmstandardbasetx.md).[clone](common_transactions.evmstandardbasetx.md#abstract-clone)*

*Definido en [src/apis/evm/basetx.ts:73](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/basetx.ts#L73)*

**Returns:** *esto*

___

### crear un entorno de creación

*-* **create**(...`args`: []cualquiera

*Heredada de [EVMbaseTx.create](api_evm_basetx.evmbasetx.md)[](api_evm_basetx.evmbasetx.md#create)*

*Supera [EVMStandardBaseTx](common_transactions.evmstandardbasetx.md).[create](common_transactions.evmstandardbasetx.md#abstract-create)*

*Definido en [src/apis/evm/basetx.ts:79](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/basetx.ts#L79)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `..args` | cualquier otra cosa que no sea[] |

**Returns:** *esto*

___

### deserie

- **deserialize**(`fields`: objeto, `codificación`: [SerializedEncoding](../modules/src_utils.md#serializedencoding)): *vacío*

*Superaciones [EVMbaseTx.deserialize](api_evm_basetx.evmbasetx.md)[](api_evm_basetx.evmbasetx.md#deserialize)*

*Definido en [src/apis/evm/exporttx.ts:43](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/exporttx.ts#L43)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `campos de cultivo` | objeto de la operación | - |
| `codificación` | [SerializedEncoding](../modules/src_utils.md#serializedencoding) | "hex" |

**Retornos:** *vacío*

___

### deBuffer

- **fromBuffer**(`bytes`: Buffer, `offset`: número): *número*

*Supera [EVMBaseTx](api_evm_basetx.evmbasetx.md).[fromBuffer](api_evm_basetx.evmbasetx.md#frombuffer)*

*Definido en [src/apis/evm/exporttx.ts:103](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/exporttx.ts#L103)*

Decodifica la [ExportTx](api_evm_exporttx.exporttx.md) como un [Buffer](https://github.com/feross/buffer) y devuelve el tamaño.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `bytes` | Buffer | - |
| `offset` | Número de números | 0 |

**Retornos:** *número*

___

### getBlockchainID

- **getBlockchainID**(): *Buffer*

*Heredada de [EVMStandardBaseTx](common_transactions.evmstandardbasetx.md).[getBlockchainID](common_transactions.evmstandardbasetx.md#getblockchainid)*

*Definido en [src/commtx.ts:60](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/evmtx.ts#L60)*

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

### getDestinationChain

- **getDestinationChain**(): *Buffer*

*Definido en [src/apis/evm/exporttx.ts:64](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/exporttx.ts#L64)*

Devuelve la cadena de destinationChain de entrada como [Buffer](https://github.com/feross/buffer)

**Returns:** *Buffer*

___

### getExportedOutputs

- **getExportedOutputs**(): *[TransferableOutput](api_evm_outputs.transferableoutput.md)[]*

*Definido en [src/apis/evm/exporttx.ts:74](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/exporttx.ts#L74)*

Devuelve las salidas como una variedad de [[EVMOutputs]]

**Retornos:** *[Producto transferible](api_evm_outputs.transferableoutput.md)[]*

___

### getInputs

- **getInputs**(): *[EVMInput](api_evm_inputs.evminput.md)[]*

*Definido en [src/apis/evm/exporttx.ts:69](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/exporttx.ts#L69)*

Devuelve las entradas como una variedad de [[EVMInputs]]

**Retornos:** *[EVMInput](api_evm_inputs.evminput.md)[]*

___

### getNetworkID

- **getNetworkID**(): *número*

*Heredada de [EVMStandardBaseTx](common_transactions.evmstandardbasetx.md).[getNetworkID](common_transactions.evmstandardbasetx.md#getnetworkid)*

*Definido en [src/commtx.ts:55](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/evmtx.ts#L55)*

Devuelve el NetworkID como número

**Retornos:** *número*

___

### getTxType

- **getTxType**(): *número*

*Heredada de [EVMbaseTx.getTxType](api_evm_basetx.evmbasetx.md)[](api_evm_basetx.evmbasetx.md#gettxtype)*

*Superar [EVMStandardBaseTx](common_transactions.evmstandardbasetx.md).[getTxType](common_transactions.evmstandardbasetx.md#abstract-gettxtype)*

*Definido en [src/apis/evm/basetx.ts:39](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/basetx.ts#L39)*

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

### seleccionar

- **select**(`id`: número, ...`args`: []cualquier): *esto*

*Heredado de [EVMbaseTx.select](api_evm_basetx.evmbasetx.md)[](api_evm_basetx.evmbasetx.md#select)*

*Supera [EVMStandardBaseTx](common_transactions.evmstandardbasetx.md).[select](common_transactions.evmstandardbasetx.md#abstract-select)*

*Definido en [src/apis/evm/basetx.ts:83](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/basetx.ts#L83)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `I.` | Número de números |
| `..args` | cualquier otra cosa que no sea[] |

**Returns:** *esto*

___

### serializar

- **serialize**(`encoding`: [SerializedEncoding](../modules/src_utils.md#serializedencoding)): *objeto*

*Superar [EVMStandardBaseTx](common_transactions.evmstandardbasetx.md).[serialize](common_transactions.evmstandardbasetx.md#serialize)*

*Definido en [src/apis/evm/exporttx.ts:35](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/exporttx.ts#L35)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `codificación` | [SerializedEncoding](../modules/src_utils.md#serializedencoding) | "hex" |

**Return:** *objeto*

___

### señal de que la señal de que la

- **sign**(`msg`: Buffer, `kc`: [KeyChain](api_evm_keychain.keychain.md)): *[Credencial](common_signature.credential.md)[]*

*Superar [EVMbaseTx.sign](api_evm_basetx.evmbasetx.md)[](api_evm_basetx.evmbasetx.md#sign)*

*Definido en [src/apis/evm/exporttx.ts:141](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/exporttx.ts#L141)*

Toma los bytes de un [UnsignedTx](api_platformvm_transactions.unsignedtx.md) y devuelve una matriz de [Credenciales](common_signature.credential.md)

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `ms.` | Buffer | Un buffer para el [UnsignedTx](api_platformvm_transactions.unsignedtx.md) |
| `kc` | [Llave](api_evm_keychain.keychain.md) | Una [cadena de teclas](api_platformvm_keychain.keychain.md) utilizada en la firma |

**Retornos:** *[Credencial](common_signature.credential.md)[]*

Una serie de [credenciales](common_signature.credential.md)

___

### toBuffer

- **toBuffer** (): *Buffer*

*Supera [EVMStandardBaseTx](common_transactions.evmstandardbasetx.md).[toBuffer](common_transactions.evmstandardbasetx.md#tobuffer)*

*Definido en [src/apis/evm/exporttx.ts:79](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/exporttx.ts#L79)*

Devuelve una representación de [Buffer](https://github.com/feross/buffer) de la [ExportTx](api_evm_exporttx.exporttx.md).

**Returns:** *Buffer*

___

### toString

- **toString**(): *string*

*Supera [EVMStandardBaseTx](common_transactions.evmstandardbasetx.md).[toString](common_transactions.evmstandardbasetx.md#tostring)*

*Definido en [src/apis/evm/exporttx.ts:129](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/exporttx.ts#L129)*

Devuelve una representación base-58 de la [ExportTx](api_evm_exporttx.exporttx.md).

**Return:** *string*
