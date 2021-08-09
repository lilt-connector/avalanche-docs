[avalancha](../README.md) › [Transacciones comunes](../modules/common_transactions.md) › [StandardBaseTx](common_transactions.standardbasetx.md)

# Clase: StandardBaseTx ‹**KPClass, KCClass**›

Clase que representa una base para todas las transacciones.

## Parámetros de tipo

• **KPClass**: *[StandardKeyPair](common_keychain.standardkeypair.md)*

• **KCClass**: *[StandardKeyChain](common_keychain.standardkeychain.md)‹KPClass›*

## Jerarquía

* [Serializable](utils_serialization.serializable.md)

   de **StandardBaseTx**

   de [BaseTx](api_platformvm_basetx.basetx.md)

   de [BaseTx](api_avm_basetx.basetx.md)

## Índice de participación

### Constructores

* [constructor](common_transactions.standardbasetx.md#constructor)

### Propiedades de las propiedades

* [_codecid](common_transactions.standardbasetx.md#protected-_codecid)
* [_typeID](common_transactions.standardbasetx.md#protected-_typeid)
* [_typeName](common_transactions.standardbasetx.md#protected-_typename)
* [blockchainID](common_transactions.standardbasetx.md#protected-blockchainid)
* [getTxType](common_transactions.standardbasetx.md#abstract-gettxtype)
* [ins](common_transactions.standardbasetx.md#protected-ins)
* [meme](common_transactions.standardbasetx.md#protected-memo)
* [networkID](common_transactions.standardbasetx.md#protected-networkid)
* [numero](common_transactions.standardbasetx.md#protected-numins)
* [numouts](common_transactions.standardbasetx.md#protected-numouts)
* [outs](common_transactions.standardbasetx.md#protected-outs)

### Métodos de trabajo

* [clon](common_transactions.standardbasetx.md#abstract-clone)
* [crear un entorno de creación](common_transactions.standardbasetx.md#abstract-create)
* [deserie](common_transactions.standardbasetx.md#deserialize)
* [getBlockchainID](common_transactions.standardbasetx.md#getblockchainid)
* [getCodecid](common_transactions.standardbasetx.md#getcodecid)
* [getIns](common_transactions.standardbasetx.md#abstract-getins)
* [getMemo](common_transactions.standardbasetx.md#getmemo)
* [getNetworkID](common_transactions.standardbasetx.md#getnetworkid)
* [gets Outs](common_transactions.standardbasetx.md#abstract-getouts)
* [getTotalOuts](common_transactions.standardbasetx.md#abstract-gettotalouts)
* [getTypeID](common_transactions.standardbasetx.md#gettypeid)
* [getTypeName](common_transactions.standardbasetx.md#gettypename)
* [seleccionar](common_transactions.standardbasetx.md#abstract-select)
* [serializar](common_transactions.standardbasetx.md#serialize)
* [señal de que la señal de que la](common_transactions.standardbasetx.md#abstract-sign)
* [toBuffer](common_transactions.standardbasetx.md#tobuffer)
* [toString](common_transactions.standardbasetx.md#tostring)

## Constructores

### constructor

\+ **nuevo** *[StandardBaseTx(networkID:](common_transactions.standardbasetx.md)*`` number, `blockchainID`: Buffer, `outs`: [number](common_output.standardtransferableoutput.md)[], `ins`: [StandardTransferableInput](common_inputs.standardtransferableinput.md)[], `memo`: Buffer): StandardBaseTx

*Definido en [src/comm/tx.ts:147](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/tx.ts#L147)*

Clase que representa un StandardBaseTx que es la base para todas las transacciones.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `networkID` | Número de números | DefaultNetworkID | Opcional networkID, [DefaultNetworkID](../modules/utils_constants.md#const-defaultnetworkid) |
| `blockchainID` | Buffer | Buffer.aloc(32, 16) | blockchainID, predeterminado Buffer.aloc(32, 16) |
| `outs` | [Producto StandardTransferableOutput](common_output.standardtransferableoutput.md)[] | no definido. | Variedad opcional de los [Productos Transferibles](api_platformvm_outputs.transferableoutput.md) |
| `ins` | [Entrada StandardTransferableInput](common_inputs.standardtransferableinput.md)[] | no definido. | Variedad opcional de los [insumos](api_platformvm_inputs.transferableinput.md) transferibles. |
| `meme` | Buffer | no definido. | [Buffer](https://github.com/feross/buffer) opcional para el campo de memorias |

**Returns:** *[StandardBaseTx](common_transactions.standardbasetx.md)*

## Propiedades de las propiedades

### _codecid `protegido`

• **_codecid**: *número* = indefinido.

*Heredada de [SigIdx](common_signature.sigidx.md)[._codecid](common_signature.sigidx.md#protected-_codecid)*

*Definido en [src/utils/serialización.ts:40](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/serialization.ts#L40)*

___

### `Protegido` _typeID

• **_typeID**: *any* = undefined

*Superes [Serializable](utils_serialization.serializable.md).[_typeID](utils_serialization.serializable.md#protected-_typeid)*

*Definido en [src/comm/tx.ts:30](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/tx.ts#L30)*

___

### _typeName `protegido`

• **_typeName**: *string* = "StandardBaseTx"

*Superes [Serializable](utils_serialization.serializable.md).[_typeName](utils_serialization.serializable.md#protected-_typename)*

*Definido en [src/comm/tx.ts:29](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/tx.ts#L29)*

___

### blockchainID `protegido`

• **blockchainID**: *Buffer* = Buffer.aloc(32)

*Definido en [src/comm/tx.ts:52](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/tx.ts#L52)*

___

### `Resumen` getTxType

• **getTxType**: *función*

*Definido en [src/comm/tx.ts:62](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/tx.ts#L62)*

Devuelve el id de la [StandardBaseTx](common_transactions.standardbasetx.md)

#### Declaración de tipo:

- (): *número*

___

### Inmuebles `protegidos`

• **ins**: Entrada *[StandardTransferableInput](common_inputs.standardtransferableinput.md)[]*

*Definido en [src/comm/tx.ts:56](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/tx.ts#L56)*

___

### Memorias `protegidas`

• **memo**: *Buffer* = Buffer.aloc(0)

*Definido en [src/comm/tx.ts:57](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/tx.ts#L57)*

___

### Red `protegida`

• **networkID**: *Buffer* = Buffer.aloc(4)

*Definido en [src/comm/tx.ts:51](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/tx.ts#L51)*

___

### numins `protegidas`

• **numins**: *Buffer* = Buffer.aloc(4)

*Definido en [src/comm/tx.ts:55](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/tx.ts#L55)*

___

### numouts `protegidas`

• **numouts**: *Buffer* = Buffer.aloc(4)

*Definido en [src/comm/tx.ts:53](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/tx.ts#L53)*

___

### Ojos `protegidos`

• **outs**: Producto *[StandardTransferableOutput](common_output.standardtransferableoutput.md)[]*

*Definido en [src/comm/tx.ts:54](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/tx.ts#L54)*

## Métodos de trabajo

### Clon `abstracto`

- **clone**(): *esto*

*Definido en [src/comm/tx.ts:143](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/tx.ts#L143)*

**Returns:** *esto*

___

### `Crear, abstracta,`

*-* **create**(...`args`: []cualquiera

*Definido en [src/comm/tx.ts:145](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/tx.ts#L145)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `..args` | cualquier otra cosa que no sea[] |

**Returns:** *esto*

___

### deserie

- **deserialize**(`fields`: objeto, `codificación`: [SerializedEncoding](../modules/src_utils.md#serializedencoding)): *vacío*

*Superaciones [StandardParseableInput](common_inputs.standardparseableinput.md).[deserialize](common_inputs.standardparseableinput.md#deserialize)*

*Definido en [src/comm/tx.ts:44](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/tx.ts#L44)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `campos de cultivo` | objeto de la operación | - |
| `codificación` | [SerializedEncoding](../modules/src_utils.md#serializedencoding) | "hex" |

**Retornos:** *vacío*

___

### getBlockchainID

- **getBlockchainID**(): *Buffer*

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

### `Resumen` getIns

- **getIns():** *[Entrada](common_inputs.standardtransferableinput.md)[]* getIns():

*Definido en [src/comm/tx.ts:77](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/tx.ts#L77)*

Devuelve la gama de [entradas estándar transferibles.](common_inputs.standardtransferableinput.md)

**Retornos:** Entrada *[StandardTransferableInput](common_inputs.standardtransferableinput.md)[]*

___

### getMemo

- **getMemo**(): *Buffer*

*Definido en [src/comm/tx.ts:92](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/tx.ts#L92)*

Devuelve la representación [Buffer](https://github.com/feross/buffer) del memo

**Returns:** *Buffer*

___

### getNetworkID

- **getNetworkID**(): *número*

*Definido en [src/comm/tx.ts:67](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/tx.ts#L67)*

Devuelve el NetworkID como número

**Retornos:** *número*

___

### `Resumen` obtenciones

- **gets():** Producto *[StandardTransferableOutput](common_output.standardtransferableoutput.md)[]*

*Definido en [src/comm/tx.ts:82](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/tx.ts#L82)*

Devuelve la gama de Productos [StandardTransferableOutput](../modules/src_common.md#standardtransferableoutput)s

**Retornos:** *[Producto estándar transferible](common_output.standardtransferableoutput.md)[]*

___

### `Resumen` getTotalOuts

- **getTotalOuts**(): *[Producto estándar](common_output.standardtransferableoutput.md)[]* transferible.

*Definido en [src/comm/tx.ts:87](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/tx.ts#L87)*

Devuelve la gama de [productos estándar](../modules/src_common.md#standardtransferableoutput) totales combinados

**Retornos:** *[Producto estándar transferible](common_output.standardtransferableoutput.md)[]*

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

*Definido en [src/comm/tx.ts:147](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/tx.ts#L147)*

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

*Definido en [src/comm/tx.ts:32](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/tx.ts#L32)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `codificación` | [SerializedEncoding](../modules/src_utils.md#serializedencoding) | "hex" |

**Return:** *objeto*

___

### Signo `abstracto`

- **sign**(`msg`: Buffer, `kc`: [StandardKeyChain](common_keychain.standardkeychain.md)‹KPClass›): *[Credencial](common_signature.credential.md)[]*

*Definido en [src/comm/tx.ts:141](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/tx.ts#L141)*

Toma los bytes de un [UnsignedTx](api_platformvm_transactions.unsignedtx.md) y devuelve una matriz de [Credenciales](common_signature.credential.md)

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `ms.` | Buffer | Un buffer para el [UnsignedTx](api_platformvm_transactions.unsignedtx.md) |
| `kc` | [StandardKeyChain](common_keychain.standardkeychain.md)‹KPClass› | Una [cadena de teclas](api_platformvm_keychain.keychain.md) utilizada en la firma |

**Retornos:** *[Credencial](common_signature.credential.md)[]*

Una serie de [credenciales](common_signature.credential.md)

___

### toBuffer

- **toBuffer** (): *Buffer*

*Definido en [src/comm/tx.ts:97](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/tx.ts#L97)*

Devuelve una representación de [Buffer](https://github.com/feross/buffer) de la [StandardBaseTx](common_transactions.standardbasetx.md).

**Returns:** *Buffer*

___

### toString

- **toString**(): *string*

*Definido en [src/comm/tx.ts:129](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/tx.ts#L129)*

Devuelve una representación de base 58 de la [StandardBaseTx](common_transactions.standardbasetx.md).

**Return:** *string*
