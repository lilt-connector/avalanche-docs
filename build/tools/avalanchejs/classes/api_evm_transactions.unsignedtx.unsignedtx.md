[avalanche](../README.md) › Transacciones [API-EVM-Transactions](../modules/api_evm_transactions.md) [UnsignedTx](api_evm_transactions.unsignedtx.md)

# Clase: Sin firma Tx

## Jerarquía

↳ [EVMStandardUnsignedTx](common_transactions.evmstandardunsignedtx.md)‹[KeyPair](api_evm_keychain.keypair.md), [KeyChain](api_evm_keychain.keychain.md), [EVMbaseTx](api_evm_basetx.evmbasetx.md)›

de **la misma**

## Índice de participación

### Constructores

* [constructor](api_evm_transactions.unsignedtx.md#constructor)

### Propiedades de las propiedades

* [_codecid](api_evm_transactions.unsignedtx.md#protected-_codecid)
* [_typeID](api_evm_transactions.unsignedtx.md#protected-_typeid)
* [_typeName](api_evm_transactions.unsignedtx.md#protected-_typename)
* [codecid](api_evm_transactions.unsignedtx.md#protected-codecid)
* [Transmisión de la operación](api_evm_transactions.unsignedtx.md#protected-transaction)

### Métodos de trabajo

* [deserie](api_evm_transactions.unsignedtx.md#deserialize)
* [deBuffer](api_evm_transactions.unsignedtx.md#frombuffer)
* [getBurn](api_evm_transactions.unsignedtx.md#getburn)
* [getCodecid](api_evm_transactions.unsignedtx.md#getcodecid)
* [getCodecidBuffer](api_evm_transactions.unsignedtx.md#getcodecidbuffer)
* [getInputTotal](api_evm_transactions.unsignedtx.md#getinputtotal)
* [getOutputTotal](api_evm_transactions.unsignedtx.md#getoutputtotal)
* [getTransaction](api_evm_transactions.unsignedtx.md#gettransaction)
* [getTypeID](api_evm_transactions.unsignedtx.md#gettypeid)
* [getTypeName](api_evm_transactions.unsignedtx.md#gettypename)
* [serializar](api_evm_transactions.unsignedtx.md#serialize)
* [señal de que la señal de que la](api_evm_transactions.unsignedtx.md#sign)
* [toBuffer](api_evm_transactions.unsignedtx.md#tobuffer)

## Constructores

### constructor

\+ **nuevo UnsignedTx(transaction:**`` [EVMbaseTx](api_evm_basetx.evmbasetx.md), `codecid`: número): *[UnsignedTx(transaction:](api_evm_transactions.unsignedtx.md)*

*Heredado de [EVMStandardUnsignedTx](common_transactions.evmstandardunsignedtx.md).[constructor](common_transactions.evmstandardunsignedtx.md#constructor)*

*Definido en [src/commtx.ts:209](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/evmtx.ts#L209)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `Transmisión de la operación` | [EVMbaseTx](api_evm_basetx.evmbasetx.md) | no definido. |
| `codecid` | Número de números | 0 |

**Returns:** *[Sin](api_evm_transactions.unsignedtx.md)* Returns:

## Propiedades de las propiedades

### _codecid `protegido`

• **_codecid**: *número* = indefinido.

*Heredada de [SigIdx](common_signature.sigidx.md)[._codecid](common_signature.sigidx.md#protected-_codecid)*

*Definido en [src/utils/serialización.ts:40](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/serialization.ts#L40)*

___

### `Protegido` _typeID

• **_typeID**: *any* = undefined

*Supera [EVMStandardUnsignedTx._typeID EVMStandardUnsignedTx._typeID](common_transactions.evmstandardunsignedtx.md)[](common_transactions.evmstandardunsignedtx.md#protected-_typeid)*

*Definido en [src/apis/evm/tx.ts:47](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/tx.ts#L47)*

___

### _typeName `protegido`

• **_typeName**: *string* = "UnsignedTx"

*Supera [EVMStandardUnsignedTx._typeName EVMStandardUnsignedTx._typeName](common_transactions.evmstandardunsignedtx.md)[](common_transactions.evmstandardunsignedtx.md#protected-_typename)*

*Definido en [src/apis/evm/tx.ts:46](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/tx.ts#L46)*

___

### Codecido `protegido`

• **codecidido**: *número* = 0

*Heredada de [EVMStandardUnsignedTx](common_transactions.evmstandardunsignedtx.md).[codecID](common_transactions.evmstandardunsignedtx.md#protected-codecid)*

*Definido en [src/commtx.ts:124](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/evmtx.ts#L124)*

___

### Transmisión `protegida`

• **transacción**: *[EVMBaseTx](api_evm_basetx.evmbasetx.md)*

*Heredado de [EVMStandardUnsignedTx](common_transactions.evmstandardunsignedtx.md).[transaction](common_transactions.evmstandardunsignedtx.md#protected-transaction)*

*Definido en [src/commtx.ts:125](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/evmtx.ts#L125)*

## Métodos de trabajo

### deserie

- **deserialize**(`fields`: objeto, `codificación`: [SerializedEncoding](../modules/src_utils.md#serializedencoding)): *vacío*

*Superaciones [EVMStandardUnsignedTx.deserialize EVMStandardUnsignedTx.deserialize](common_transactions.evmstandardunsignedtx.md)[](common_transactions.evmstandardunsignedtx.md#deserialize)*

*Definido en [src/apis/evm/tx.ts:51](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/tx.ts#L51)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `campos de cultivo` | objeto de la operación | - |
| `codificación` | [SerializedEncoding](../modules/src_utils.md#serializedencoding) | "hex" |

**Retornos:** *vacío*

___

### deBuffer

- **fromBuffer**(`bytes`: Buffer, `offset`: número): *número*

*Supera [EVMStandardUnsignedTx.fromBuffer EVMStandardUnsignedTx.fromBuffer](common_transactions.evmstandardunsignedtx.md)[](common_transactions.evmstandardunsignedtx.md#abstract-frombuffer)*

*Definido en [src/apis/evm/tx.ts:61](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/tx.ts#L61)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `bytes` | Buffer | - |
| `offset` | Número de números | 0 |

**Retornos:** *número*

___

### getBurn

- **getBurn**(`assetID`: Buffer): *BN*

*Heredada de [EVMStandardUnsignedTx](common_transactions.evmstandardunsignedtx.md).[getBurn](common_transactions.evmstandardunsignedtx.md#getburn)*

*Definido en [src/commtx.ts:179](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/evmtx.ts#L179)*

Devuelve el número de tokens quemados como BN

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `activos` | Buffer |

**Returns:** *BN*

___

### getCodecid

- **getCodecid():** *número*

*Heredada de [EVMStandardUnsignedTx](common_transactions.evmstandardunsignedtx.md).[getCodecID](common_transactions.evmstandardunsignedtx.md#getcodecid)*

*Overrides [SigIdx](common_signature.sigidx.md)[.getCodecid](common_signature.sigidx.md#getcodecid)*

*Definido en [src/commtx.ts:130](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/evmtx.ts#L130)*

Devuelve el Codecid como número

**Retornos:** *número*

___

### getCodecidBuffer

- **getCodecidBuffer():** *Buffer*

*Heredado de [EVMStandardUnsignedTx](common_transactions.evmstandardunsignedtx.md).[getCodecIDBuffer](common_transactions.evmstandardunsignedtx.md#getcodecidbuffer)*

*Definido en [src/commtx.ts:135](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/evmtx.ts#L135)*

Devuelve la representación de [Buffer](https://github.com/feross/buffer) del Codecid

**Returns:** *Buffer*

___

### getInputTotal

- **getInputTotal**(`assetID`: Buffer): *BN*

*Heredada de [EVMStandardUnsignedTx](common_transactions.evmstandardunsignedtx.md).[getInputTotal](common_transactions.evmstandardunsignedtx.md#getinputtotal)*

*Definido en [src/commtx.ts:144](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/evmtx.ts#L144)*

Devuelve la inputTotal como BN

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `activos` | Buffer |

**Returns:** *BN*

___

### getOutputTotal

- **getOutputTotal**(`assetID`: Buffer): *BN*

*Heredada de [EVMStandardUnsignedTx](common_transactions.evmstandardunsignedtx.md).[getOutputTotal](common_transactions.evmstandardunsignedtx.md#getoutputtotal)*

*Definido en [src/commtx.ts:161](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/evmtx.ts#L161)*

Devuelve la outputTotal como BN

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `activos` | Buffer |

**Returns:** *BN*

___

### getTransaction

- **getTransaction**(): *[EVMbaseTx](api_evm_basetx.evmbasetx.md)*

*Superar [EVMStandardUnsignedTx.getTransaction EVMStandardUnsignedTx.getTransaction](common_transactions.evmstandardunsignedtx.md)[](common_transactions.evmstandardunsignedtx.md#abstract-gettransaction)*

*Definido en [src/apis/evm/tx.ts:57](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/tx.ts#L57)*

**Returns:** *[EVMbaseTx](api_evm_basetx.evmbasetx.md)*

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

### serializar

- **serialize**(`encoding`: [SerializedEncoding](../modules/src_utils.md#serializedencoding)): *objeto*

*Heredada de [EVMStandardUnsignedTx](common_transactions.evmstandardunsignedtx.md).[serialize](common_transactions.evmstandardunsignedtx.md#serialize)*

*Superaciones [Serializable](utils_serialization.serializable.md).[serialize](utils_serialization.serializable.md#serialize)*

*Definido en [src/commtx.ts:110](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/evmtx.ts#L110)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `codificación` | [SerializedEncoding](../modules/src_utils.md#serializedencoding) | "hex" |

**Return:** *objeto*

___

### señal de que la señal de que la

- **sign**(`kc`: [KeyChain](api_evm_keychain.keychain.md)): *[Tx](api_evm_transactions.tx.md)*

*Superar [EVMStandardUnsignedTx.sign EVMStandardUnsignedTx.sign](common_transactions.evmstandardunsignedtx.md)[](common_transactions.evmstandardunsignedtx.md#abstract-sign)*

*Definido en [src/apis/evm/tx.ts:77](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/tx.ts#L77)*

Firma este [UnsignedTx](api_evm_transactions.unsignedtx.md) y devuelve firmados [StandardTx](common_transactions.standardtx.md)

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `kc` | [Llave](api_evm_keychain.keychain.md) | Una [cadena de teclas](api_platformvm_keychain.keychain.md) utilizada en la firma |

**Returns:** *[Tx](api_evm_transactions.tx.md)*

Un [estándar](common_transactions.standardtx.md) firmado

___

### toBuffer

- **toBuffer** (): *Buffer*

*Heredado de [EVMStandardUnsignedTx](common_transactions.evmstandardunsignedtx.md).[toBuffer](common_transactions.evmstandardunsignedtx.md#tobuffer)*

*Definido en [src/commtx.ts:190](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/evmtx.ts#L190)*

**Returns:** *Buffer*
