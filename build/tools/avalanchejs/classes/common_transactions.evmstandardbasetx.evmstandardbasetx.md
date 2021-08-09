[avalancha](../README.md) › [Transacciones comunes](../modules/common_transactions.md) › [EVMStandardBaseTx](common_transactions.evmstandardbasetx.md)

# Clase: EVMStandardBaseTx ‹**KPClass, KCClass**›

Clase que representa una base para todas las transacciones.

## Parámetros de tipo

• **KPClass**: *[StandardKeyPair](common_keychain.standardkeypair.md)*

• **KCClass**: *[StandardKeyChain](common_keychain.standardkeychain.md)‹KPClass›*

## Jerarquía

* [Serializable](utils_serialization.serializable.md)

   de la marca **EVMStandardBaseTx**

   de [la](api_evm_basetx.evmbasetx.md) marca EVMbaseTx

## Índice de participación

### Constructores

* [constructor](common_transactions.evmstandardbasetx.md#constructor)

### Propiedades de las propiedades

* [_codecid](common_transactions.evmstandardbasetx.md#protected-_codecid)
* [_typeID](common_transactions.evmstandardbasetx.md#protected-_typeid)
* [_typeName](common_transactions.evmstandardbasetx.md#protected-_typename)
* [blockchainID](common_transactions.evmstandardbasetx.md#protected-blockchainid)
* [getTxType](common_transactions.evmstandardbasetx.md#abstract-gettxtype)
* [networkID](common_transactions.evmstandardbasetx.md#protected-networkid)

### Métodos de trabajo

* [clon](common_transactions.evmstandardbasetx.md#abstract-clone)
* [crear un entorno de creación](common_transactions.evmstandardbasetx.md#abstract-create)
* [deserie](common_transactions.evmstandardbasetx.md#deserialize)
* [getBlockchainID](common_transactions.evmstandardbasetx.md#getblockchainid)
* [getCodecid](common_transactions.evmstandardbasetx.md#getcodecid)
* [getNetworkID](common_transactions.evmstandardbasetx.md#getnetworkid)
* [getTypeID](common_transactions.evmstandardbasetx.md#gettypeid)
* [getTypeName](common_transactions.evmstandardbasetx.md#gettypename)
* [seleccionar](common_transactions.evmstandardbasetx.md#abstract-select)
* [serializar](common_transactions.evmstandardbasetx.md#serialize)
* [toBuffer](common_transactions.evmstandardbasetx.md#tobuffer)
* [toString](common_transactions.evmstandardbasetx.md#tostring)

## Constructores

### constructor

\+ **nuevo EVMStandardBaseTx(networkID:**`` number, `blockchainID`: Buffer): *[EVMStandardBaseTx](common_transactions.evmstandardbasetx.md)*

*Definido en [src/commtx.ts:83](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/evmtx.ts#L83)*

Clase que representa un StandardBaseTx que es la base para todas las transacciones.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `networkID` | Número de números | DefaultNetworkID | Opcional networkID, [DefaultNetworkID](../modules/utils_constants.md#const-defaultnetworkid) |
| `blockchainID` | Buffer | Buffer.aloc(32, 16) | blockchainID, predeterminado Buffer.aloc(32, 16) |

**Returns:** *[EVMStandardBaseTx](common_transactions.evmstandardbasetx.md)*

## Propiedades de las propiedades

### _codecid `protegido`

• **_codecid**: *número* = indefinido.

*Heredada de [SigIdx](common_signature.sigidx.md)[._codecid](common_signature.sigidx.md#protected-_codecid)*

*Definido en [src/utils/serialización.ts:40](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/serialization.ts#L40)*

___

### `Protegido` _typeID

• **_typeID**: *any* = undefined

*Superes [Serializable](utils_serialization.serializable.md).[_typeID](utils_serialization.serializable.md#protected-_typeid)*

*Definido en [src/commtx.ts:27](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/evmtx.ts#L27)*

___

### _typeName `protegido`

• **_typeName**: *string* = "EVMStandardBaseTx"

*Superes [Serializable](utils_serialization.serializable.md).[_typeName](utils_serialization.serializable.md#protected-_typename)*

*Definido en [src/commtx.ts:26](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/evmtx.ts#L26)*

___

### blockchainID `protegido`

• **blockchainID**: *Buffer* = Buffer.aloc(32)

*Definido en [src/commtx.ts:45](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/evmtx.ts#L45)*

___

### `Resumen` getTxType

• **getTxType**: *función*

*Definido en [src/commtx.ts:50](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/evmtx.ts#L50)*

Devuelve el id de la [StandardBaseTx](common_transactions.standardbasetx.md)

#### Declaración de tipo:

- (): *número*

___

### Red `protegida`

• **networkID**: *Buffer* = Buffer.aloc(4)

*Definido en [src/commtx.ts:44](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/evmtx.ts#L44)*

## Métodos de trabajo

### Clon `abstracto`

- **clone**(): *esto*

*Definido en [src/commtx.ts:79](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/evmtx.ts#L79)*

**Returns:** *esto*

___

### `Crear, abstracta,`

*-* **create**(...`args`: []cualquiera

*Definido en [src/commtx.ts:81](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/evmtx.ts#L81)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `..args` | cualquier otra cosa que no sea[] |

**Returns:** *esto*

___

### deserie

- **deserialize**(`fields`: objeto, `codificación`: [SerializedEncoding](../modules/src_utils.md#serializedencoding)): *vacío*

*Superaciones [StandardParseableInput](common_inputs.standardparseableinput.md).[deserialize](common_inputs.standardparseableinput.md#deserialize)*

*Definido en [src/commtx.ts:38](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/evmtx.ts#L38)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `campos de cultivo` | objeto de la operación | - |
| `codificación` | [SerializedEncoding](../modules/src_utils.md#serializedencoding) | "hex" |

**Retornos:** *vacío*

___

### getBlockchainID

- **getBlockchainID**(): *Buffer*

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

*Definido en [src/commtx.ts:55](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/evmtx.ts#L55)*

Devuelve el NetworkID como número

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

### `Seleccione abstracto`

- **select**(`id`: número, ...`args`: []cualquier): *esto*

*Definido en [src/commtx.ts:83](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/evmtx.ts#L83)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `I.` | Número de números |
| `..args` | cualquier otra cosa que no sea[] |

**Returns:** *esto*

___

### serializar

- **serialize**(`encoding`: [SerializedEncoding](../modules/src_utils.md#serializedencoding)): *objeto*

*Superaciones [Serializable](utils_serialization.serializable.md).[serialize](utils_serialization.serializable.md#serialize)*

*Definido en [src/commtx.ts:29](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/evmtx.ts#L29)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `codificación` | [SerializedEncoding](../modules/src_utils.md#serializedencoding) | "hex" |

**Return:** *objeto*

___

### toBuffer

- **toBuffer** (): *Buffer*

*Definido en [src/commtx.ts:65](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/evmtx.ts#L65)*

Devuelve una representación de [Buffer](https://github.com/feross/buffer) de la [StandardBaseTx](common_transactions.standardbasetx.md).

**Returns:** *Buffer*

___

### toString

- **toString**(): *string*

*Definido en [src/commtx.ts:75](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/evmtx.ts#L75)*

Devuelve una representación de base 58 de la [StandardBaseTx](common_transactions.standardbasetx.md).

**Return:** *string*
