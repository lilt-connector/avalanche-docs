[avalancha](../README.md) › [Transacciones comunes](../modules/common_transactions.md) › [StandardUnsignedTx](common_transactions.standardunsignedtx.md)

# Clase: StandardUnsignedTx ‹**KPClass, KCClass, SBTx**›

Clase que representa una transacción sin firmar.

## Parámetros de tipo

• **KPClass**: *[StandardKeyPair](common_keychain.standardkeypair.md)*

• **KCClass**: *[StandardKeyChain](common_keychain.standardkeychain.md)‹KPClass›*

• **SBTx**: *[StandardBaseTx](common_transactions.standardbasetx.md)‹KPClass, KCClass›*

## Jerarquía

* [Serializable](utils_serialization.serializable.md)

   de **StandardUnsignedTx**

   de [la misma](api_platformvm_transactions.unsignedtx.md)

   de [la misma](api_avm_transactions.unsignedtx.md)

## Índice de participación

### Constructores

* [constructor](common_transactions.standardunsignedtx.md#constructor)

### Propiedades de las propiedades

* [_codecid](common_transactions.standardunsignedtx.md#protected-_codecid)
* [_typeID](common_transactions.standardunsignedtx.md#protected-_typeid)
* [_typeName](common_transactions.standardunsignedtx.md#protected-_typename)
* [codecid](common_transactions.standardunsignedtx.md#protected-codecid)
* [Transmisión de la operación](common_transactions.standardunsignedtx.md#protected-transaction)

### Métodos de trabajo

* [deserie](common_transactions.standardunsignedtx.md#deserialize)
* [deBuffer](common_transactions.standardunsignedtx.md#abstract-frombuffer)
* [getBurn](common_transactions.standardunsignedtx.md#getburn)
* [getCodecid](common_transactions.standardunsignedtx.md#getcodecid)
* [getCodecidBuffer](common_transactions.standardunsignedtx.md#getcodecidbuffer)
* [getInputTotal](common_transactions.standardunsignedtx.md#getinputtotal)
* [getOutputTotal](common_transactions.standardunsignedtx.md#getoutputtotal)
* [getTransaction](common_transactions.standardunsignedtx.md#abstract-gettransaction)
* [getTypeID](common_transactions.standardunsignedtx.md#gettypeid)
* [getTypeName](common_transactions.standardunsignedtx.md#gettypename)
* [serializar](common_transactions.standardunsignedtx.md#serialize)
* [señal de que la señal de que la](common_transactions.standardunsignedtx.md#abstract-sign)
* [toBuffer](common_transactions.standardunsignedtx.md#tobuffer)

## Constructores

### constructor

\+ **nuevo** `StandardUnsignedTx(transaction`*[:](common_transactions.standardunsignedtx.md)* SBTx, `codecid`: número): StandardUnsignedTx(transaction:

*Definido en [src/comm/tx.ts:289](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/tx.ts#L289)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `Transmisión de la operación` | SBTx | no definido. |
| `codecid` | Número de números | 0 |

**Returns:** *[StandardUnsignedTx](common_transactions.standardunsignedtx.md)*

## Propiedades de las propiedades

### _codecid `protegido`

• **_codecid**: *número* = indefinido.

*Heredada de [SigIdx](common_signature.sigidx.md)[._codecid](common_signature.sigidx.md#protected-_codecid)*

*Definido en [src/utils/serialización.ts:40](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/serialization.ts#L40)*

___

### `Protegido` _typeID

• **_typeID**: *any* = undefined

*Superes [Serializable](utils_serialization.serializable.md).[_typeID](utils_serialization.serializable.md#protected-_typeid)*

*Definido en [src/comm/tx.ts:183](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/tx.ts#L183)*

___

### _typeName `protegido`

• **_typeName**: *string* = "StandardUnsignedTx"

*Superes [Serializable](utils_serialization.serializable.md).[_typeName](utils_serialization.serializable.md#protected-_typename)*

*Definido en [src/comm/tx.ts:182](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/tx.ts#L182)*

___

### Codecido `protegido`

• **codecidido**: *número* = 0

*Definido en [src/comm/tx.ts:199](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/tx.ts#L199)*

___

### Transmisión `protegida`

• **transacción**: *SBTx*

*Definido en [src/comm/tx.ts:200](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/tx.ts#L200)*

## Métodos de trabajo

### deserie

- **deserialize**(`fields`: objeto, `codificación`: [SerializedEncoding](../modules/src_utils.md#serializedencoding)): *vacío*

*Superaciones [StandardParseableInput](common_inputs.standardparseableinput.md).[deserialize](common_inputs.standardparseableinput.md#deserialize)*

*Definido en [src/comm/tx.ts:194](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/tx.ts#L194)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `campos de cultivo` | objeto de la operación | - |
| `codificación` | [SerializedEncoding](../modules/src_utils.md#serializedencoding) | "hex" |

**Retornos:** *vacío*

___

### `Resumen` deBuffer

- **fromBuffer**(`bytes`: Buffer, `offset?`: número): *número*

*Definido en [src/comm/tx.ts:267](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/tx.ts#L267)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `bytes` | Buffer |
| `¿Qué compensación?` | Número de números |

**Retornos:** *número*

___

### getBurn

- **getBurn**(`assetID`: Buffer): *BN*

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

*Overrides [SigIdx](common_signature.sigidx.md)[.getCodecid](common_signature.sigidx.md#getcodecid)*

*Definido en [src/comm/tx.ts:205](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/tx.ts#L205)*

Devuelve el Codecid como número

**Retornos:** *número*

___

### getCodecidBuffer

- **getCodecidBuffer():** *Buffer*

*Definido en [src/comm/tx.ts:210](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/tx.ts#L210)*

Devuelve la representación de [Buffer](https://github.com/feross/buffer) del Codecid

**Returns:** *Buffer*

___

### getInputTotal

- **getInputTotal**(`assetID`: Buffer): *BN*

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

*Definido en [src/comm/tx.ts:239](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/tx.ts#L239)*

Devuelve la outputTotal como BN

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `activos` | Buffer |

**Returns:** *BN*

___

### `Obtención` abstracta de transacción

- **getTransaction**(): *SBTx*

*Definido en [src/comm/tx.ts:265](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/tx.ts#L265)*

Devuelve la Transacción

**Returns:** *SBTx*

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

*Superaciones [Serializable](utils_serialization.serializable.md).[serialize](utils_serialization.serializable.md#serialize)*

*Definido en [src/comm/tx.ts:185](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/tx.ts#L185)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `codificación` | [SerializedEncoding](../modules/src_utils.md#serializedencoding) | "hex" |

**Return:** *objeto*

___

### Signo `abstracto`

- **sign**(`kc`: KCClass): *[StandardTx‹KPClass,](common_transactions.standardtx.md)[](common_transactions.standardunsignedtx.md) KCClass, StandardTx‹KPClass, KCClass, SBTx››*

*Definido en [src/comm/tx.ts:285](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/tx.ts#L285)*

Firma este [UnsignedTx](api_platformvm_transactions.unsignedtx.md) y devuelve firmados [StandardTx](common_transactions.standardtx.md)

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `kc` | KCS | Una [cadena de teclas](api_platformvm_keychain.keychain.md) utilizada en la firma |

**Returns:** *[StandardTx‹KPClass,](common_transactions.standardtx.md) KCClass, [StandardTx‹KPClass,](common_transactions.standardunsignedtx.md) KCClass, SBTx››*

Un [estándar](common_transactions.standardtx.md) firmado

___

### toBuffer

- **toBuffer** (): *Buffer*

*Definido en [src/comm/tx.ts:269](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/tx.ts#L269)*

**Returns:** *Buffer*
