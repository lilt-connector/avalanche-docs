[avalancha](../README.md) › [API-EVM-ImportTx](../modules/api_evm_importtx.md) › [ImportTx](api_evm_importtx.importtx.md)

# Clase: ImportTx

Clase que representa una transacción de importación no firmada.

## Jerarquía

de [la](api_evm_basetx.evmbasetx.md) marca EVMbaseTx

m **ImportTx**

## Índice de participación

### Constructores

* [constructor](api_evm_importtx.importtx.md#constructor)

### Propiedades de las propiedades

* [_codecid](api_evm_importtx.importtx.md#protected-_codecid)
* [_typeID](api_evm_importtx.importtx.md#protected-_typeid)
* [_typeName](api_evm_importtx.importtx.md#protected-_typename)
* [blockchainID](api_evm_importtx.importtx.md#protected-blockchainid)
* [importIns](api_evm_importtx.importtx.md#protected-importins)
* [networkID](api_evm_importtx.importtx.md#protected-networkid)
* [numIns](api_evm_importtx.importtx.md#protected-numins)
* [numouts](api_evm_importtx.importtx.md#protected-numouts)
* [outs](api_evm_importtx.importtx.md#protected-outs)
* [sourceChain](api_evm_importtx.importtx.md#protected-sourcechain)

### Métodos de trabajo

* [clon](api_evm_importtx.importtx.md#clone)
* [crear un entorno de creación](api_evm_importtx.importtx.md#create)
* [deserie](api_evm_importtx.importtx.md#deserialize)
* [deBuffer](api_evm_importtx.importtx.md#frombuffer)
* [getBlockchainID](api_evm_importtx.importtx.md#getblockchainid)
* [getCodecid](api_evm_importtx.importtx.md#getcodecid)
* [getImportInputs](api_evm_importtx.importtx.md#getimportinputs)
* [getNetworkID](api_evm_importtx.importtx.md#getnetworkid)
* [gets Outs](api_evm_importtx.importtx.md#getouts)
* [getSourceChain](api_evm_importtx.importtx.md#getsourcechain)
* [getTxType](api_evm_importtx.importtx.md#gettxtype)
* [getTypeID](api_evm_importtx.importtx.md#gettypeid)
* [getTypeName](api_evm_importtx.importtx.md#gettypename)
* [seleccionar](api_evm_importtx.importtx.md#select)
* [serializar](api_evm_importtx.importtx.md#serialize)
* [señal de que la señal de que la](api_evm_importtx.importtx.md#sign)
* [toBuffer](api_evm_importtx.importtx.md#tobuffer)
* [toString](api_evm_importtx.importtx.md#tostring)
* [validateOuts](api_evm_importtx.importtx.md#private-validateouts)

## Constructores

### constructor

\+ **nuevo ImportTx(networkID:**`` number, `blockchainID`: Buffer, `sourceChainID`: Buffer, `importIns`: [TransferableInput](api_evm_inputs.transferableinput.md)[], `outs`: [EVMOutput](api_evm_outputs.evmoutput.md)[]): *[ImportTx](api_evm_importtx.importtx.md)*

*Superar [EVMbaseTx.constructor](api_evm_basetx.evmbasetx.md)[](api_evm_basetx.evmbasetx.md#constructor)*

*Definido en [src/apis/evm/importtx.ts:190](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/importtx.ts#L190)*

Clase que representa una transacción de importación no firmada.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `networkID` | Número de números | DefaultNetworkID | Opcional networkID, [DefaultNetworkID](../modules/utils_constants.md#const-defaultnetworkid) |
| `blockchainID` | Buffer | Buffer.aloc(32, 16) | blockchainID, predeterminado Buffer.aloc(32, 16) |
| `sourceChainID` | Buffer | Buffer.aloc(32, 16) | Opcional chainID para las entradas de fuente a importar. plataforma predeterminada. |
| `importIns` | [Entrada transferible](api_evm_inputs.transferableinput.md)[] | no definido. | Conjunto de [entradas transferibles](api_platformvm_inputs.transferableinput.md) utilizadas en la transacción |
| `outs` | [EVMOutput](api_evm_outputs.evmoutput.md)[] | no definido. | Variedad opcional de los [EVMOutput](api_evm_outputs.evmoutput.md)s |

**Returns:** *[ImportTx](api_evm_importtx.importtx.md)*

## Propiedades de las propiedades

### _codecid `protegido`

• **_codecid**: *número* = indefinido.

*Heredada de [SigIdx](common_signature.sigidx.md)[._codecid](common_signature.sigidx.md#protected-_codecid)*

*Definido en [src/utils/serialización.ts:40](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/serialization.ts#L40)*

___

### `Protegido` _typeID

• **_typeID**: *número* = EVMConstants.IMPORTTX

*Superar [EVMbaseTx._typeID](api_evm_basetx.evmbasetx.md)[](api_evm_basetx.evmbasetx.md#protected-_typeid)*

*Definido en [src/apis/evm/importtx.ts:42](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/importtx.ts#L42)*

___

### _typeName `protegido`

• **_typeName**: *string* = "ImportTx"

*Overrides [EVMBaseTx](api_evm_basetx.evmbasetx.md).[_typeName](api_evm_basetx.evmbasetx.md#protected-_typename)*

*Definido en [src/apis/evm/importtx.ts:41](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/importtx.ts#L41)*

___

### blockchainID `protegido`

• **blockchainID**: *Buffer* = Buffer.aloc(32)

*Heredada de [EVMStandardBaseTx](common_transactions.evmstandardbasetx.md).[blockchainID](common_transactions.evmstandardbasetx.md#protected-blockchainid)*

*Definido en [src/commtx.ts:45](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/evmtx.ts#L45)*

___

### Importaciones `protegidas`

• **Importantes**: *[Entrada](api_evm_inputs.transferableinput.md)[]* transferible=[]

*Definido en [src/apis/evm/importtx.ts:66](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/importtx.ts#L66)*

___

### Red `protegida`

• **networkID**: *Buffer* = Buffer.aloc(4)

*Heredada de [EVMStandardBaseTx](common_transactions.evmstandardbasetx.md).[networkID](common_transactions.evmstandardbasetx.md#protected-networkid)*

*Definido en [src/commtx.ts:44](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/evmtx.ts#L44)*

___

### NumIns `protegidos`

• **numIns**: *Buffer* = Buffer.aloc(4)

*Definido en [src/apis/evm/importtx.ts:65](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/importtx.ts#L65)*

___

### NumOuts `protegidos`

• **numOuts**: *Buffer* = Buffer.aloc(4)

*Definido en [src/apis/evm/importtx.ts:67](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/importtx.ts#L67)*

___

### Ojos `protegidos`

• **outs**: *[EVMOutput](api_evm_outputs.evmoutput.md)[]* =[]

*Definido en [src/apis/evm/importtx.ts:68](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/importtx.ts#L68)*

___

### Fuente `protegida` Cadena de cadena de cadena de

• **sourceChain**: de entrada: *Buffer* = Buffer.aloc(32)

*Definido en [src/apis/evm/importtx.ts:64](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/importtx.ts#L64)*

## Métodos de trabajo

### clon

- **clone**(): *esto*

*Superaciones [EVMbaseTx.clone](api_evm_basetx.evmbasetx.md)[](api_evm_basetx.evmbasetx.md#clone)*

*Definido en [src/apis/evm/importtx.ts:157](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/importtx.ts#L157)*

**Returns:** *esto*

___

### crear un entorno de creación

*-* **create**(...`args`: []cualquiera

*Supera [EVMbaseTx.create](api_evm_basetx.evmbasetx.md)[](api_evm_basetx.evmbasetx.md#create)*

*Definido en [src/apis/evm/importtx.ts:163](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/importtx.ts#L163)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `..args` | cualquier otra cosa que no sea[] |

**Returns:** *esto*

___

### deserie

- **deserialize**(`fields`: objeto, `codificación`: [SerializedEncoding](../modules/src_utils.md#serializedencoding)): *vacío*

*Superaciones [EVMbaseTx.deserialize](api_evm_basetx.evmbasetx.md)[](api_evm_basetx.evmbasetx.md#deserialize)*

*Definido en [src/apis/evm/importtx.ts:52](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/importtx.ts#L52)*

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

*Definido en [src/apis/evm/importtx.ts:95](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/importtx.ts#L95)*

Toma un [buffer](https://github.com/feross/buffer) que contiene una [ImportTx](api_evm_importtx.importtx.md), lo pierde, populosa la clase y devuelve la longitud de la [ImportTx](api_evm_importtx.importtx.md) en bytes.

**`observaciones`** asuman que no se ha comprobado

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `bytes` | Buffer | - | Un [buffer](https://github.com/feross/buffer) que contiene una [importTx](api_evm_importtx.importtx.md) cruda |
| `offset` | Número de números | 0 | Un número que representa el compensatorio de byte. Deficiencias a 0. |

**Retornos:** *número*

La longitud de la [importTx](api_evm_importtx.importtx.md) cruda

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

### getImportInputs

- **getImportInputs**(): *[TransferableInput](api_evm_inputs.transferableinput.md)[]*

*Definido en [src/apis/evm/importtx.ts:146](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/importtx.ts#L146)*

Devuelve una variedad de [entradas transferibles](api_platformvm_inputs.transferableinput.md) en esta transacción.

**Retornos:** *[Input transferible](api_evm_inputs.transferableinput.md)[]*

___

### getNetworkID

- **getNetworkID**(): *número*

*Heredada de [EVMStandardBaseTx](common_transactions.evmstandardbasetx.md).[getNetworkID](common_transactions.evmstandardbasetx.md#getnetworkid)*

*Definido en [src/commtx.ts:55](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/evmtx.ts#L55)*

Devuelve el NetworkID como número

**Retornos:** *número*

___

### gets Outs

- **gets():** *[EVMOutput](api_evm_outputs.evmoutput.md)[]*

*Definido en [src/apis/evm/importtx.ts:153](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/importtx.ts#L153)*

Devuelve una variedad de [EVMOutput](api_evm_outputs.evmoutput.md)s en esta transacción.

**Retornos:** *[EVMOutput](api_evm_outputs.evmoutput.md)[]*

___

### getSourceChain

- **getSourceChain**(): *Buffer*

*Definido en [src/apis/evm/importtx.ts:80](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/importtx.ts#L80)*

Devuelve un [Buffer](https://github.com/feross/buffer) para el chainid de origen.

**Returns:** *Buffer*

___

### getTxType

- **getTxType**(): *número*

*Superaciones [EVMbaseTx.getTxType](api_evm_basetx.evmbasetx.md)[](api_evm_basetx.evmbasetx.md#gettxtype)*

*Definido en [src/apis/evm/importtx.ts:73](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/importtx.ts#L73)*

Devuelve el id de la [ImportTx](api_evm_importtx.importtx.md)

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

*Definido en [src/apis/evm/importtx.ts:44](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/importtx.ts#L44)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `codificación` | [SerializedEncoding](../modules/src_utils.md#serializedencoding) | "hex" |

**Return:** *objeto*

___

### señal de que la señal de que la

- **sign**(`msg`: Buffer, `kc`: [KeyChain](api_evm_keychain.keychain.md)): *[Credencial](common_signature.credential.md)[]*

*Superar [EVMbaseTx.sign](api_evm_basetx.evmbasetx.md)[](api_evm_basetx.evmbasetx.md#sign)*

*Definido en [src/apis/evm/importtx.ts:175](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/importtx.ts#L175)*

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

*Definido en [src/apis/evm/importtx.ts:121](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/importtx.ts#L121)*

Devuelve una representación de [Buffer](https://github.com/feross/buffer) de la [ImportTx](api_evm_importtx.importtx.md).

**Returns:** *Buffer*

___

### toString

- **toString**(): *string*

*Heredada de [EVMStandardBaseTx](common_transactions.evmstandardbasetx.md).[toString](common_transactions.evmstandardbasetx.md#tostring)*

*Definido en [src/commtx.ts:75](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/evmtx.ts#L75)*

Devuelve una representación de base 58 de la [StandardBaseTx](common_transactions.standardbasetx.md).

**Return:** *string*

___

### Validar `privado` Outs

- **validateOuts**(): *nulo*

*Definido en [src/apis/evm/importtx.ts:238](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/importtx.ts#L238)*

**Retornos:** *vacío*
