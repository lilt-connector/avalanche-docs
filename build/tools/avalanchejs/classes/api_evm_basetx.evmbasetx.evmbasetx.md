[avalancha](../README.md) › [API-EVM-BaseTx](../modules/api_evm_basetx.md) › [EVMbaseTx](api_evm_basetx.evmbasetx.md)

# Clase: EVMbaseTx

Clase que representa una base para todas las transacciones.

## Jerarquía

[↳](common_transactions.evmstandardbasetx.md)[](api_evm_keychain.keypair.md) [KeyChain](api_evm_keychain.keychain.md) ›

de **la** marca EVMbaseTx

m [ImportTx](api_evm_importtx.importtx.md)

m. [ExportTx](api_evm_exporttx.exporttx.md)

## Índice de participación

### Constructores

* [constructor](api_evm_basetx.evmbasetx.md#constructor)

### Propiedades de las propiedades

* [_codecid](api_evm_basetx.evmbasetx.md#protected-_codecid)
* [_typeID](api_evm_basetx.evmbasetx.md#protected-_typeid)
* [_typeName](api_evm_basetx.evmbasetx.md#protected-_typename)
* [blockchainID](api_evm_basetx.evmbasetx.md#protected-blockchainid)
* [networkID](api_evm_basetx.evmbasetx.md#protected-networkid)

### Métodos de trabajo

* [clon](api_evm_basetx.evmbasetx.md#clone)
* [crear un entorno de creación](api_evm_basetx.evmbasetx.md#create)
* [deserie](api_evm_basetx.evmbasetx.md#deserialize)
* [deBuffer](api_evm_basetx.evmbasetx.md#frombuffer)
* [getBlockchainID](api_evm_basetx.evmbasetx.md#getblockchainid)
* [getCodecid](api_evm_basetx.evmbasetx.md#getcodecid)
* [getNetworkID](api_evm_basetx.evmbasetx.md#getnetworkid)
* [getTxType](api_evm_basetx.evmbasetx.md#gettxtype)
* [getTypeID](api_evm_basetx.evmbasetx.md#gettypeid)
* [getTypeName](api_evm_basetx.evmbasetx.md#gettypename)
* [seleccionar](api_evm_basetx.evmbasetx.md#select)
* [serializar](api_evm_basetx.evmbasetx.md#serialize)
* [señal de que la señal de que la](api_evm_basetx.evmbasetx.md#sign)
* [toBuffer](api_evm_basetx.evmbasetx.md#tobuffer)
* [toString](api_evm_basetx.evmbasetx.md#tostring)

## Constructores

### constructor

\+ **nuevo** EVMbaseTx(`networkID`: number, `blockchainID`: Buffer): *[EVMbaseTx](api_evm_basetx.evmbasetx.md)*

*Superar [EVMStandardBaseTx](common_transactions.evmstandardbasetx.md).[constructor](common_transactions.evmstandardbasetx.md#constructor)*

*Definido en [src/apis/evm/basetx.ts:86](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/basetx.ts#L86)*

Clase que representa un EVMbaseTx que es la base para todas las transacciones EVM.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `networkID` | Número de números | DefaultNetworkID | Opcional networkID, [DefaultNetworkID](../modules/utils_constants.md#const-defaultnetworkid) |
| `blockchainID` | Buffer | Buffer.aloc(32, 16) | blockchainID, predeterminado Buffer.aloc(32, 16) |

**Returns:** *[EVMbaseTx](api_evm_basetx.evmbasetx.md)*

## Propiedades de las propiedades

### _codecid `protegido`

• **_codecid**: *número* = indefinido.

*Heredada de [SigIdx](common_signature.sigidx.md)[._codecid](common_signature.sigidx.md#protected-_codecid)*

*Definido en [src/utils/serialización.ts:40](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/serialization.ts#L40)*

___

### `Protegido` _typeID

• **_typeID**: *any* = undefined

*Supera [EVMStandardBaseTx](common_transactions.evmstandardbasetx.md).[_typeID](common_transactions.evmstandardbasetx.md#protected-_typeid)*

*Definido en [src/apis/evm/basetx.ts:28](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/basetx.ts#L28)*

___

### _typeName `protegido`

• **_typeName**: *string* = "BaseTx"

*Supera [EVMStandardBaseTx](common_transactions.evmstandardbasetx.md).[_typeName](common_transactions.evmstandardbasetx.md#protected-_typename)*

*Definido en [src/apis/evm/basetx.ts:27](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/basetx.ts#L27)*

___

### blockchainID `protegido`

• **blockchainID**: *Buffer* = Buffer.aloc(32)

*Heredada de [EVMStandardBaseTx](common_transactions.evmstandardbasetx.md).[blockchainID](common_transactions.evmstandardbasetx.md#protected-blockchainid)*

*Definido en [src/commtx.ts:45](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/evmtx.ts#L45)*

___

### Red `protegida`

• **networkID**: *Buffer* = Buffer.aloc(4)

*Heredada de [EVMStandardBaseTx](common_transactions.evmstandardbasetx.md).[networkID](common_transactions.evmstandardbasetx.md#protected-networkid)*

*Definido en [src/commtx.ts:44](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/evmtx.ts#L44)*

## Métodos de trabajo

### clon

- **clone**(): *esto*

*Superar [EVMStandardBaseTx](common_transactions.evmstandardbasetx.md).[clone](common_transactions.evmstandardbasetx.md#abstract-clone)*

*Definido en [src/apis/evm/basetx.ts:73](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/basetx.ts#L73)*

**Returns:** *esto*

___

### crear un entorno de creación

*-* **create**(...`args`: []cualquiera

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

*Superaciones [EVMStandardBaseTx](common_transactions.evmstandardbasetx.md).[deserialize](common_transactions.evmstandardbasetx.md#deserialize)*

*Definido en [src/apis/evm/basetx.ts:32](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/basetx.ts#L32)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `campos de cultivo` | objeto de la operación | - |
| `codificación` | [SerializedEncoding](../modules/src_utils.md#serializedencoding) | "hex" |

**Retornos:** *vacío*

___

### deBuffer

- **fromBuffer**(`bytes`: Buffer, `offset`: número): *número*

*Definido en [src/apis/evm/basetx.ts:52](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/basetx.ts#L52)*

Toma un [Buffer](https://github.com/feross/buffer) que contiene un [BaseTx](api_platformvm_basetx.basetx.md), lo analiza, populates la clase y devuelve la longitud de la BaseTx en bytes.

**`observaciones`** asuman que no se ha comprobado

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `bytes` | Buffer | - | Un [buffer](https://github.com/feross/buffer) que contiene un [BaseTx](api_platformvm_basetx.basetx.md) crudo. |
| `offset` | Número de números | 0 | - |

**Retornos:** *número*

La longitud de la [base](api_platformvm_basetx.basetx.md) cruda

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

### getNetworkID

- **getNetworkID**(): *número*

*Heredada de [EVMStandardBaseTx](common_transactions.evmstandardbasetx.md).[getNetworkID](common_transactions.evmstandardbasetx.md#getnetworkid)*

*Definido en [src/commtx.ts:55](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/evmtx.ts#L55)*

Devuelve el NetworkID como número

**Retornos:** *número*

___

### getTxType

- **getTxType**(): *número*

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

*Heredada de [EVMStandardBaseTx](common_transactions.evmstandardbasetx.md).[serialize](common_transactions.evmstandardbasetx.md#serialize)*

*Superaciones [Serializable](utils_serialization.serializable.md).[serialize](utils_serialization.serializable.md#serialize)*

*Definido en [src/commtx.ts:29](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/evmtx.ts#L29)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `codificación` | [SerializedEncoding](../modules/src_utils.md#serializedencoding) | "hex" |

**Return:** *objeto*

___

### señal de que la señal de que la

- **sign**(`msg`: Buffer, `kc`: [KeyChain](api_evm_keychain.keychain.md)): *[Credencial](common_signature.credential.md)[]*

*Definido en [src/apis/evm/basetx.ts:68](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/basetx.ts#L68)*

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

*Heredado de [EVMStandardBaseTx](common_transactions.evmstandardbasetx.md).[toBuffer](common_transactions.evmstandardbasetx.md#tobuffer)*

*Definido en [src/commtx.ts:65](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/evmtx.ts#L65)*

Devuelve una representación de [Buffer](https://github.com/feross/buffer) de la [StandardBaseTx](common_transactions.standardbasetx.md).

**Returns:** *Buffer*

___

### toString

- **toString**(): *string*

*Heredada de [EVMStandardBaseTx](common_transactions.evmstandardbasetx.md).[toString](common_transactions.evmstandardbasetx.md#tostring)*

*Definido en [src/commtx.ts:75](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/evmtx.ts#L75)*

Devuelve una representación de base 58 de la [StandardBaseTx](common_transactions.standardbasetx.md).

**Return:** *string*
