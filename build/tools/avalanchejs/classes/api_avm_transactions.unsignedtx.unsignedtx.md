[avalanche](../README.md) › Transacciones [API-AVM-Transactions](../modules/api_avm_transactions.md) [UnsignedTx](api_avm_transactions.unsignedtx.md)

# Clase: Sin firma Tx

## Jerarquía

m [StandardUnsignedTx‹KeyPair, StandardUnsignedTx‹KeyPair,](common_transactions.standardunsignedtx.md)[](api_avm_keychain.keypair.md) [KeyChain](api_avm_keychain.keychain.md), [BaseTx](api_avm_basetx.basetx.md)›

de **la misma**

## Índice de participación

### Constructores

* [constructor](api_avm_transactions.unsignedtx.md#constructor)

### Propiedades de las propiedades

* [_codecid](api_avm_transactions.unsignedtx.md#protected-_codecid)
* [_typeID](api_avm_transactions.unsignedtx.md#protected-_typeid)
* [_typeName](api_avm_transactions.unsignedtx.md#protected-_typename)
* [codecid](api_avm_transactions.unsignedtx.md#protected-codecid)
* [Transmisión de la operación](api_avm_transactions.unsignedtx.md#protected-transaction)

### Métodos de trabajo

* [deserie](api_avm_transactions.unsignedtx.md#deserialize)
* [deBuffer](api_avm_transactions.unsignedtx.md#frombuffer)
* [getBurn](api_avm_transactions.unsignedtx.md#getburn)
* [getCodecid](api_avm_transactions.unsignedtx.md#getcodecid)
* [getCodecidBuffer](api_avm_transactions.unsignedtx.md#getcodecidbuffer)
* [getInputTotal](api_avm_transactions.unsignedtx.md#getinputtotal)
* [getOutputTotal](api_avm_transactions.unsignedtx.md#getoutputtotal)
* [getTransaction](api_avm_transactions.unsignedtx.md#gettransaction)
* [getTypeID](api_avm_transactions.unsignedtx.md#gettypeid)
* [getTypeName](api_avm_transactions.unsignedtx.md#gettypename)
* [serializar](api_avm_transactions.unsignedtx.md#serialize)
* [señal de que la señal de que la](api_avm_transactions.unsignedtx.md#sign)
* [toBuffer](api_avm_transactions.unsignedtx.md#tobuffer)

## Constructores

### constructor

\+ **nuevo UnsignedTx(transaction:**`` [BaseTx](api_avm_basetx.basetx.md), `codecid`: número): *[UnsignedTx(transaction:](api_avm_transactions.unsignedtx.md)*

*Heredada de [StandardUnsignedTx](common_transactions.standardunsignedtx.md).[constructor](common_transactions.standardunsignedtx.md#constructor)*

*Definido en [src/comm/tx.ts:289](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/tx.ts#L289)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `Transmisión de la operación` | [BaseTx](api_avm_basetx.basetx.md) | no definido. |
| `codecid` | Número de números | 0 |

**Returns:** *[Sin](api_avm_transactions.unsignedtx.md)* Returns:

## Propiedades de las propiedades

### _codecid `protegido`

• **_codecid**: *número* = indefinido.

*Heredada de [SigIdx](common_signature.sigidx.md)[._codecid](common_signature.sigidx.md#protected-_codecid)*

*Definido en [src/utils/serialización.ts:40](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/serialization.ts#L40)*

___

### `Protegido` _typeID

• **_typeID**: *any* = undefined

*Overrides [StandardUnsignedTx](common_transactions.standardunsignedtx.md).[_typeID](common_transactions.standardunsignedtx.md#protected-_typeid)*

*Definido en [src/apis/avm/tx.ts:52](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/tx.ts#L52)*

___

### _typeName `protegido`

• **_typeName**: *string* = "UnsignedTx"

*Overrides [StandardUnsignedTx](common_transactions.standardunsignedtx.md).[_typeName](common_transactions.standardunsignedtx.md#protected-_typename)*

*Definido en [src/apis/avm/tx.ts:51](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/tx.ts#L51)*

___

### Codecido `protegido`

• **codecidido**: *número* = 0

*Heredado de [StandardUnsignedTx](common_transactions.standardunsignedtx.md).[codecID](common_transactions.standardunsignedtx.md#protected-codecid)*

*Definido en [src/comm/tx.ts:199](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/tx.ts#L199)*

___

### Transmisión `protegida`

• **transacción**: *[BaseTx](api_avm_basetx.basetx.md)*

*Heredado de [StandardUnsignedTx](common_transactions.standardunsignedtx.md).[transaction](common_transactions.standardunsignedtx.md#protected-transaction)*

*Definido en [src/comm/tx.ts:200](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/tx.ts#L200)*

## Métodos de trabajo

### deserie

- **deserialize**(`fields`: objeto, `codificación`: [SerializedEncoding](../modules/src_utils.md#serializedencoding)): *vacío*

*Overrides [StandardUnsignedTx](common_transactions.standardunsignedtx.md).[deserialize](common_transactions.standardunsignedtx.md#deserialize)*

*Definido en [src/apis/avm/tx.ts:56](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/tx.ts#L56)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `campos de cultivo` | objeto de la operación | - |
| `codificación` | [SerializedEncoding](../modules/src_utils.md#serializedencoding) | "hex" |

**Retornos:** *vacío*

___

### deBuffer

- **fromBuffer**(`bytes`: Buffer, `offset`: número): *número*

*Overrides [StandardUnsignedTx](common_transactions.standardunsignedtx.md).[fromBuffer](common_transactions.standardunsignedtx.md#abstract-frombuffer)*

*Definido en [src/apis/avm/tx.ts:66](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/tx.ts#L66)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `bytes` | Buffer | - |
| `offset` | Número de números | 0 |

**Retornos:** *número*

___

### getBurn

- **getBurn**(`assetID`: Buffer): *BN*

*Heredado de [StandardUnsignedTx](common_transactions.standardunsignedtx.md).[getBurn](common_transactions.standardunsignedtx.md#getburn)*

*Definido en [src/comm/tx.ts:258](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/tx.ts#L258)*

Devuelve el número de tokens quemados como BN

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `activos` | Buffer |

**Returns:** *BN*

___

### getCodecid

- **getCodecid():** *número*

*Heredada de [StandardUnsignedTx](common_transactions.standardunsignedtx.md).[getCodecID](common_transactions.standardunsignedtx.md#getcodecid)*

*Overrides [SigIdx](common_signature.sigidx.md)[.getCodecid](common_signature.sigidx.md#getcodecid)*

*Definido en [src/comm/tx.ts:205](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/tx.ts#L205)*

Devuelve el Codecid como número

**Retornos:** *número*

___

### getCodecidBuffer

- **getCodecidBuffer():** *Buffer*

*Heredado de [StandardUnsignedTx](common_transactions.standardunsignedtx.md).[getCodecIDBuffer](common_transactions.standardunsignedtx.md#getcodecidbuffer)*

*Definido en [src/comm/tx.ts:210](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/tx.ts#L210)*

Devuelve la representación de [Buffer](https://github.com/feross/buffer) del Codecid

**Returns:** *Buffer*

___

### getInputTotal

- **getInputTotal**(`assetID`: Buffer): *BN*

*Heredada de [StandardUnsignedTx](common_transactions.standardunsignedtx.md).[getInputTotal](common_transactions.standardunsignedtx.md#getinputtotal)*

*Definido en [src/comm/tx.ts:219](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/tx.ts#L219)*

Devuelve la inputTotal como BN

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `activos` | Buffer |

**Returns:** *BN*

___

### getOutputTotal

- **getOutputTotal**(`assetID`: Buffer): *BN*

*Heredada de [StandardUnsignedTx](common_transactions.standardunsignedtx.md).[getOutputTotal](common_transactions.standardunsignedtx.md#getoutputtotal)*

*Definido en [src/comm/tx.ts:239](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/tx.ts#L239)*

Devuelve la outputTotal como BN

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `activos` | Buffer |

**Returns:** *BN*

___

### getTransaction

- **getTransaction**(): *[BaseTx](api_avm_basetx.basetx.md)*

*Overrides [StandardUnsignedTx](common_transactions.standardunsignedtx.md).[getTransaction](common_transactions.standardunsignedtx.md#abstract-gettransaction)*

*Definido en [src/apis/avm/tx.ts:62](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/tx.ts#L62)*

**Returns:** *[BaseTx](api_avm_basetx.basetx.md)*

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

*Heredada de [StandardUnsignedTx](common_transactions.standardunsignedtx.md).[serialize](common_transactions.standardunsignedtx.md#serialize)*

*Superaciones [Serializable](utils_serialization.serializable.md).[serialize](utils_serialization.serializable.md#serialize)*

*Definido en [src/comm/tx.ts:185](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/tx.ts#L185)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `codificación` | [SerializedEncoding](../modules/src_utils.md#serializedencoding) | "hex" |

**Return:** *objeto*

___

### señal de que la señal de que la

- **sign**(`kc`: [KeyChain](api_avm_keychain.keychain.md)): *[Tx](api_avm_transactions.tx.md)*

*Superaciones [StandardUnsignedTx](common_transactions.standardunsignedtx.md)[.sign](common_transactions.standardunsignedtx.md#abstract-sign)*

*Definido en [src/apis/avm/tx.ts:82](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/tx.ts#L82)*

Firma este [UnsignedTx](api_avm_transactions.unsignedtx.md) y devuelve firmados [StandardTx](common_transactions.standardtx.md)

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `kc` | [Llave](api_avm_keychain.keychain.md) | Una [cadena de teclas](api_platformvm_keychain.keychain.md) utilizada en la firma |

**Returns:** *[Tx](api_avm_transactions.tx.md)*

Un [estándar](common_transactions.standardtx.md) firmado

___

### toBuffer

- **toBuffer** (): *Buffer*

*Heredada de [StandardUnsignedTx](common_transactions.standardunsignedtx.md).[toBuffer](common_transactions.standardunsignedtx.md#tobuffer)*

*Definido en [src/comm/tx.ts:269](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/tx.ts#L269)*

**Returns:** *Buffer*
