[avalancha](../README.md) › [Transacciones comunes](../modules/common_transactions.md) › [EVMStandardUnsignedTx](common_transactions.evmstandardunsignedtx.md)

# Clase: EVMStandardUnsignedTx ‹**KPClass, KCClass, SBTx**›

Clase que representa una transacción sin firmar.

## Parámetros de tipo

• **KPClass**: *[StandardKeyPair](common_keychain.standardkeypair.md)*

• **KCClass**: *[StandardKeyChain](common_keychain.standardkeychain.md)‹KPClass›*

• **SBTx**: *[EVMStandardBaseTx](common_transactions.evmstandardbasetx.md)‹KPClass, KCClass›*

## Jerarquía

* [Serializable](utils_serialization.serializable.md)

   de **EVMStandardUnsignedTx**

   de [la misma](api_evm_transactions.unsignedtx.md)

## Índice de participación

### Constructores

* [constructor](common_transactions.evmstandardunsignedtx.md#constructor)

### Propiedades de las propiedades

* [_codecid](common_transactions.evmstandardunsignedtx.md#protected-_codecid)
* [_typeID](common_transactions.evmstandardunsignedtx.md#protected-_typeid)
* [_typeName](common_transactions.evmstandardunsignedtx.md#protected-_typename)
* [codecid](common_transactions.evmstandardunsignedtx.md#protected-codecid)
* [Transmisión de la operación](common_transactions.evmstandardunsignedtx.md#protected-transaction)

### Métodos de trabajo

* [deserie](common_transactions.evmstandardunsignedtx.md#deserialize)
* [deBuffer](common_transactions.evmstandardunsignedtx.md#abstract-frombuffer)
* [getBurn](common_transactions.evmstandardunsignedtx.md#getburn)
* [getCodecid](common_transactions.evmstandardunsignedtx.md#getcodecid)
* [getCodecidBuffer](common_transactions.evmstandardunsignedtx.md#getcodecidbuffer)
* [getInputTotal](common_transactions.evmstandardunsignedtx.md#getinputtotal)
* [getOutputTotal](common_transactions.evmstandardunsignedtx.md#getoutputtotal)
* [getTransaction](common_transactions.evmstandardunsignedtx.md#abstract-gettransaction)
* [getTypeID](common_transactions.evmstandardunsignedtx.md#gettypeid)
* [getTypeName](common_transactions.evmstandardunsignedtx.md#gettypename)
* [serializar](common_transactions.evmstandardunsignedtx.md#serialize)
* [señal de que la señal de que la](common_transactions.evmstandardunsignedtx.md#abstract-sign)
* [toBuffer](common_transactions.evmstandardunsignedtx.md#tobuffer)

## Constructores

### constructor

\+ **nuevo EVMStandardUnsignedTx(transaction:**`` SBTx, `codecid`: número): *[EVMStandardUnsignedTx(transaction:](common_transactions.evmstandardunsignedtx.md)*

*Definido en [src/commtx.ts:209](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/evmtx.ts#L209)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `Transmisión de la operación` | SBTx | no definido. |
| `codecid` | Número de números | 0 |

**Return:** *[EVMStandardUnsignedTx](common_transactions.evmstandardunsignedtx.md)*

## Propiedades de las propiedades

### _codecid `protegido`

• **_codecid**: *número* = indefinido.

*Heredada de [SigIdx](common_signature.sigidx.md)[._codecid](common_signature.sigidx.md#protected-_codecid)*

*Definido en [src/utils/serialización.ts:40](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/serialization.ts#L40)*

___

### `Protegido` _typeID

• **_typeID**: *any* = undefined

*Superes [Serializable](utils_serialization.serializable.md).[_typeID](utils_serialization.serializable.md#protected-_typeid)*

*Definido en [src/commtx.ts:108](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/evmtx.ts#L108)*

___

### _typeName `protegido`

• **_typeName**: *string* = "StandardUnsignedTx"

*Superes [Serializable](utils_serialization.serializable.md).[_typeName](utils_serialization.serializable.md#protected-_typename)*

*Definido en [src/commtx.ts:107](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/evmtx.ts#L107)*

___

### Codecido `protegido`

• **codecidido**: *número* = 0

*Definido en [src/commtx.ts:124](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/evmtx.ts#L124)*

___

### Transmisión `protegida`

• **transacción**: *SBTx*

*Definido en [src/commtx.ts:125](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/evmtx.ts#L125)*

## Métodos de trabajo

### deserie

- **deserialize**(`fields`: objeto, `codificación`: [SerializedEncoding](../modules/src_utils.md#serializedencoding)): *vacío*

*Superaciones [StandardParseableInput](common_inputs.standardparseableinput.md).[deserialize](common_inputs.standardparseableinput.md#deserialize)*

*Definido en [src/commtx.ts:119](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/evmtx.ts#L119)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `campos de cultivo` | objeto de la operación | - |
| `codificación` | [SerializedEncoding](../modules/src_utils.md#serializedencoding) | "hex" |

**Retornos:** *vacío*

___

### `Resumen` deBuffer

- **fromBuffer**(`bytes`: Buffer, `offset?`: número): *número*

*Definido en [src/commtx.ts:188](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/evmtx.ts#L188)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `bytes` | Buffer |
| `¿Qué compensación?` | Número de números |

**Retornos:** *número*

___

### getBurn

- **getBurn**(`assetID`: Buffer): *BN*

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

*Overrides [SigIdx](common_signature.sigidx.md)[.getCodecid](common_signature.sigidx.md#getcodecid)*

*Definido en [src/commtx.ts:130](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/evmtx.ts#L130)*

Devuelve el Codecid como número

**Retornos:** *número*

___

### getCodecidBuffer

- **getCodecidBuffer():** *Buffer*

*Definido en [src/commtx.ts:135](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/evmtx.ts#L135)*

Devuelve la representación de [Buffer](https://github.com/feross/buffer) del Codecid

**Returns:** *Buffer*

___

### getInputTotal

- **getInputTotal**(`assetID`: Buffer): *BN*

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

*Definido en [src/commtx.ts:161](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/evmtx.ts#L161)*

Devuelve la outputTotal como BN

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `activos` | Buffer |

**Returns:** *BN*

___

### `Obtención` abstracta de transacción

- **getTransaction**(): *SBTx*

*Definido en [src/commtx.ts:186](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/evmtx.ts#L186)*

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

*Definido en [src/commtx.ts:110](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/evmtx.ts#L110)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `codificación` | [SerializedEncoding](../modules/src_utils.md#serializedencoding) | "hex" |

**Return:** *objeto*

___

### Signo `abstracto`

- **sign**(`kc`: KCClass): *[EVMStandardTx‹KPClass,](common_transactions.evmstandardtx.md)[](common_transactions.evmstandardunsignedtx.md) KCClass, EVMStandardTx‹KPClass, KCClass): KCClass, SBTx››*

*Definido en [src/commtx.ts:205](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/evmtx.ts#L205)*

Firma este [UnsignedTx](api_platformvm_transactions.unsignedtx.md) y devuelve firmados [StandardTx](common_transactions.standardtx.md)

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `kc` | KCS | Una [cadena de teclas](api_platformvm_keychain.keychain.md) utilizada en la firma |

**Returns:** *[EVMStandardTx‹KPClass,](common_transactions.evmstandardtx.md) KCClass, [EVMStandardTx‹KPClass,](common_transactions.evmstandardunsignedtx.md) EVMStandardTx‹KPClass, KCClass, SBTx››*

Un [estándar](common_transactions.standardtx.md) firmado

___

### toBuffer

- **toBuffer** (): *Buffer*

*Definido en [src/commtx.ts:190](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/evmtx.ts#L190)*

**Returns:** *Buffer*
