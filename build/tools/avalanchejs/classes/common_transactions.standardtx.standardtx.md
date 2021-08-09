[avalancha](../README.md) › [Transacciones comunes](../modules/common_transactions.md) › [StandardTx](common_transactions.standardtx.md)

# Clase: StandardTx ‹**KPClass, KCClass, SUBTx**›

Clase que representa una transacción firmada.

## Parámetros de tipo

• **KPClass**: *[StandardKeyPair](common_keychain.standardkeypair.md)*

• **KCClass**: *[StandardKeyChain](common_keychain.standardkeychain.md)‹KPClass›*

• **SUBTx**: *[StandardUnsignedTx‹KPClass, StandardUnsignedTx‹KPClass,](common_transactions.standardunsignedtx.md) KCClass, [StandardUnsignedTx‹KPClass,](common_transactions.standardbasetx.md) KCClass››*

## Jerarquía

* [Serializable](utils_serialization.serializable.md)

   de **StandardTx**

   de [Tx](api_platformvm_transactions.tx.md)

   de [Tx](api_avm_transactions.tx.md)

## Índice de participación

### Constructores

* [constructor](common_transactions.standardtx.md#constructor)

### Propiedades de las propiedades

* [_codecid](common_transactions.standardtx.md#protected-_codecid)
* [_typeID](common_transactions.standardtx.md#protected-_typeid)
* [_typeName](common_transactions.standardtx.md#protected-_typename)
* [credenciales](common_transactions.standardtx.md#protected-credentials)
* [sin unsignedTx](common_transactions.standardtx.md#protected-unsignedtx)

### Métodos de trabajo

* [deserie](common_transactions.standardtx.md#deserialize)
* [deBuffer](common_transactions.standardtx.md#abstract-frombuffer)
* [fromString](common_transactions.standardtx.md#fromstring)
* [getCodecid](common_transactions.standardtx.md#getcodecid)
* [getCredentials](common_transactions.standardtx.md#getcredentials)
* [getTypeID](common_transactions.standardtx.md#gettypeid)
* [getTypeName](common_transactions.standardtx.md#gettypename)
* [getUnsignedTx](common_transactions.standardtx.md#getunsignedtx)
* [serializar](common_transactions.standardtx.md#serialize)
* [toBuffer](common_transactions.standardtx.md#tobuffer)
* [toString](common_transactions.standardtx.md#tostring)

## Constructores

### constructor

\+ **nuevo StandardTx(unsignedTx: StandardTx(unsignedTx:**`` SUBTx, `credenciales`[:](common_signature.credential.md) []Credencial): *[StandardTx](common_transactions.standardtx.md)*

*Definido en [src/comm/tx.ts:388](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/tx.ts#L388)*

Clase que representa una transacción firmada.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `sin unsignedTx` | SUTT | no definido. | [StandardUnsignedTx](common_transactions.standardunsignedtx.md) Opcional |
| `credenciales` | [Credencial](common_signature.credential.md)[] | no definido. | - |

**Returns:** *[StandardTx](common_transactions.standardtx.md)*

## Propiedades de las propiedades

### _codecid `protegido`

• **_codecid**: *número* = indefinido.

*Heredada de [SigIdx](common_signature.sigidx.md)[._codecid](common_signature.sigidx.md#protected-_codecid)*

*Definido en [src/utils/serialización.ts:40](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/serialization.ts#L40)*

___

### `Protegido` _typeID

• **_typeID**: *any* = undefined

*Superes [Serializable](utils_serialization.serializable.md).[_typeID](utils_serialization.serializable.md#protected-_typeid)*

*Definido en [src/comm/tx.ts:310](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/tx.ts#L310)*

___

### _typeName `protegido`

• **_typeName**: *string* = "StandardTx"

*Superes [Serializable](utils_serialization.serializable.md).[_typeName](utils_serialization.serializable.md#protected-_typename)*

*Definido en [src/comm/tx.ts:309](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/tx.ts#L309)*

___

### Credenciales `y` de las credenciales protegidas

• **credenciales**: *[Credencial](common_signature.credential.md)[]* =[]

*Definido en [src/comm/tx.ts:322](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/tx.ts#L322)*

___

### Sin firma `protegida` Tx

• sin **unsignedTx**: *SUBTx* = indefinido.

*Definido en [src/comm/tx.ts:321](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/tx.ts#L321)*

## Métodos de trabajo

### deserie

- **deserialize**(`fields`: objeto, `codificación?`: [SerializedEncoding](../modules/src_utils.md#serializedencoding)): *void*

*Heredada de [StandardParseableInput](common_inputs.standardparseableinput.md).[deserialize](common_inputs.standardparseableinput.md#deserialize)*

*Definido en [src/utils/serialización.ts:72](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/serialization.ts#L72)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `campos de cultivo` | objeto de la operación |
| `¿codificar?` | [SerializedEncoding](../modules/src_utils.md#serializedencoding) |

**Retornos:** *vacío*

___

### `Resumen` deBuffer

- **fromBuffer**(`bytes`: Buffer, `offset?`: número): *número*

*Definido en [src/comm/tx.ts:338](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/tx.ts#L338)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `bytes` | Buffer |
| `¿Qué compensación?` | Número de números |

**Retornos:** *número*

___

### fromString

- **fromString**(`serialized`: string): *número*

*Definido en [src/comm/tx.ts:376](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/tx.ts#L376)*

Toma una cadena base-58 que contiene una [StandardTx](common_transactions.standardtx.md), la analiza, populates la clase y devuelve la longitud del Tx en bytes.

**`observaciones sobre las observaciones formuladas`** a diferencia de la mayoría de las cadenas de Strings, espera que la cadena se serializa en formato cb58

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `serializado` | cadena de producción | Una cadena base-58 que contiene una [StandardTx](common_transactions.standardtx.md) cruda |

**Retornos:** *número*

La longitud de la [StandardTx](common_transactions.standardtx.md) cruda

___

### getCodecid

- **getCodecid():** *número*

*Heredada de [SigIdx](common_signature.sigidx.md)[.getCodecid](common_signature.sigidx.md#getcodecid)*

*Definido en [src/utils/serialización.ts:59](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/serialization.ts#L59)*

Utilizado en serialización. Opcional. TypeID es un número para el tipo de identificación de objeto que se está saliendo.

**Retornos:** *número*

___

### getCredentials

- **getCredentials**(): *[Credencial](common_signature.credential.md)[]*

*Definido en [src/comm/tx.ts:327](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/tx.ts#L327)*

Devuelve [][[Credencial]]

**Retornos:** *[Credencial](common_signature.credential.md)[]*

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

### getUnsignedTx

- **getUnsignedTx**(): *SUBTx*

*Definido en [src/comm/tx.ts:334](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/tx.ts#L334)*

Devuelve la [StandardUnsignedTx](common_transactions.standardunsignedtx.md)

**Returns:** *SUBTx*

___

### serializar

- **serialize**(`encoding`: [SerializedEncoding](../modules/src_utils.md#serializedencoding)): *objeto*

*Superaciones [Serializable](utils_serialization.serializable.md).[serialize](utils_serialization.serializable.md#serialize)*

*Definido en [src/comm/tx.ts:312](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/tx.ts#L312)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `codificación` | [SerializedEncoding](../modules/src_utils.md#serializedencoding) | "hex" |

**Return:** *objeto*

___

### toBuffer

- **toBuffer** (): *Buffer*

*Definido en [src/comm/tx.ts:343](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/tx.ts#L343)*

Devuelve una representación de [Buffer](https://github.com/feross/buffer) de la [StandardTx](common_transactions.standardtx.md).

**Returns:** *Buffer*

___

### toString

- **toString**(): *string*

*Definido en [src/comm/tx.ts:386](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/tx.ts#L386)*

Devuelve una representación cb58 de la [StandardTx](common_transactions.standardtx.md).

**`observaciones sobre las observaciones formuladas`** a diferencia de la mayoría de toStrings, esto devuelve en formato de serialización cb58

**Return:** *string*
