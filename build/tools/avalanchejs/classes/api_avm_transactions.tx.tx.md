[avalanche](../README.md) › Transacciones [API-AVM-Transactions](../modules/api_avm_transactions.md) [Tx](api_avm_transactions.tx.md)

# Clase: Tx

## Jerarquía

m [StandardTx](common_transactions.standardtx.md)‹[KeyPair](api_avm_keychain.keypair.md), [KeyChain](api_avm_keychain.keychain.md), [UnsignedTx](api_avm_transactions.unsignedtx.md)›

de **Tx**

## Índice de participación

### Constructores

* [constructor](api_avm_transactions.tx.md#constructor)

### Propiedades de las propiedades

* [_codecid](api_avm_transactions.tx.md#protected-_codecid)
* [_typeID](api_avm_transactions.tx.md#protected-_typeid)
* [_typeName](api_avm_transactions.tx.md#protected-_typename)
* [credenciales](api_avm_transactions.tx.md#protected-credentials)
* [sin unsignedTx](api_avm_transactions.tx.md#protected-unsignedtx)

### Métodos de trabajo

* [deserie](api_avm_transactions.tx.md#deserialize)
* [deBuffer](api_avm_transactions.tx.md#frombuffer)
* [fromString](api_avm_transactions.tx.md#fromstring)
* [getCodecid](api_avm_transactions.tx.md#getcodecid)
* [getCredentials](api_avm_transactions.tx.md#getcredentials)
* [getTypeID](api_avm_transactions.tx.md#gettypeid)
* [getTypeName](api_avm_transactions.tx.md#gettypename)
* [getUnsignedTx](api_avm_transactions.tx.md#getunsignedtx)
* [serializar](api_avm_transactions.tx.md#serialize)
* [toBuffer](api_avm_transactions.tx.md#tobuffer)
* [toString](api_avm_transactions.tx.md#tostring)

## Constructores

### constructor

\+ **new Tx**`(unsignedTx: Tx(unsignedTx`: [Tx(unsignedTx:](api_avm_transactions.unsignedtx.md) `credenciales`[:](common_signature.credential.md) []Credencial): *[Tx](api_avm_transactions.tx.md)*

*Heredada de [StandardTx](common_transactions.standardtx.md).[constructor](common_transactions.standardtx.md#constructor)*

*Definido en [src/comm/tx.ts:388](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/tx.ts#L388)*

Clase que representa una transacción firmada.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `sin unsignedTx` | [Sin UnsignedTx](api_avm_transactions.unsignedtx.md) | no definido. | [StandardUnsignedTx](common_transactions.standardunsignedtx.md) Opcional |
| `credenciales` | [Credencial](common_signature.credential.md)[] | no definido. | - |

**Returns:** *[Tx](api_avm_transactions.tx.md)*

## Propiedades de las propiedades

### _codecid `protegido`

• **_codecid**: *número* = indefinido.

*Heredada de [SigIdx](common_signature.sigidx.md)[._codecid](common_signature.sigidx.md#protected-_codecid)*

*Definido en [src/utils/serialización.ts:40](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/serialization.ts#L40)*

___

### `Protegido` _typeID

• **_typeID**: *any* = undefined

*Overrides [StandardTx](common_transactions.standardtx.md).[_typeID](common_transactions.standardtx.md#protected-_typeid)*

*Definido en [src/apis/avm/tx.ts:93](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/tx.ts#L93)*

___

### _typeName `protegido`

• **_typeName**: *string* = "Tx"

*Overrides [StandardTx](common_transactions.standardtx.md).[_typeName](common_transactions.standardtx.md#protected-_typename)*

*Definido en [src/apis/avm/tx.ts:92](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/tx.ts#L92)*

___

### Credenciales `y` de las credenciales protegidas

• **credenciales**: *[Credencial](common_signature.credential.md)[]* =[]

*Heredado de [StandardTx](common_transactions.standardtx.md).[credentials](common_transactions.standardtx.md#protected-credentials)*

*Definido en [src/comm/tx.ts:322](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/tx.ts#L322)*

___

### Sin firma `protegida` Tx

• **sin unsignedTx**: *[Sin](api_avm_transactions.unsignedtx.md)* unsignedTx: = sin definir

*Heredada de [StandardTx](common_transactions.standardtx.md).[unsignedTx](common_transactions.standardtx.md#protected-unsignedtx)*

*Definido en [src/comm/tx.ts:321](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/tx.ts#L321)*

## Métodos de trabajo

### deserie

- **deserialize**(`fields`: objeto, `codificación`: [SerializedEncoding](../modules/src_utils.md#serializedencoding)): *vacío*

*Superaciones [StandardParseableInput](common_inputs.standardparseableinput.md).[deserialize](common_inputs.standardparseableinput.md#deserialize)*

*Definido en [src/apis/avm/tx.ts:97](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/tx.ts#L97)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `campos de cultivo` | objeto de la operación | - |
| `codificación` | [SerializedEncoding](../modules/src_utils.md#serializedencoding) | "hex" |

**Retornos:** *vacío*

___

### deBuffer

- **fromBuffer**(`bytes`: Buffer, `offset`: número): *número*

*Overrides [StandardTx](common_transactions.standardtx.md).[fromBuffer](common_transactions.standardtx.md#abstract-frombuffer)*

*Definido en [src/apis/avm/tx.ts:117](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/tx.ts#L117)*

Toma un [Buffer](https://github.com/feross/buffer) que contiene un [Tx](api_avm_transactions.tx.md), lo analiza, populates la clase y devuelve la longitud del Tx en bytes.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `bytes` | Buffer | - | Un [buffer](https://github.com/feross/buffer) que contiene un [Tx](api_avm_transactions.tx.md) crudo. |
| `offset` | Número de números | 0 | Un número que representa el punto de partida de los bytes para comenzar a analizar |

**Retornos:** *número*

La longitud del [Tx](api_avm_transactions.tx.md) crudo.

___

### fromString

- **fromString**(`serialized`: string): *número*

*Heredada de [StandardTx](common_transactions.standardtx.md).[fromString](common_transactions.standardtx.md#fromstring)*

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

*Heredado de [StandardTx](common_transactions.standardtx.md).[getCredentials](common_transactions.standardtx.md#getcredentials)*

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

- **getUnsignedTx():** *[getUnsignedTx():](api_avm_transactions.unsignedtx.md)*

*Heredada de [StandardTx](common_transactions.standardtx.md).[getUnsignedTx](common_transactions.standardtx.md#getunsignedtx)*

*Definido en [src/comm/tx.ts:334](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/tx.ts#L334)*

Devuelve la [StandardUnsignedTx](common_transactions.standardunsignedtx.md)

**Returns:** *[Sin](api_avm_transactions.unsignedtx.md)* Returns:

___

### serializar

- **serialize**(`encoding`: [SerializedEncoding](../modules/src_utils.md#serializedencoding)): *objeto*

*Heredada de [StandardTx](common_transactions.standardtx.md).[serialize](common_transactions.standardtx.md#serialize)*

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

*Heredada de [StandardTx](common_transactions.standardtx.md).[toBuffer](common_transactions.standardtx.md#tobuffer)*

*Definido en [src/comm/tx.ts:343](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/tx.ts#L343)*

Devuelve una representación de [Buffer](https://github.com/feross/buffer) de la [StandardTx](common_transactions.standardtx.md).

**Returns:** *Buffer*

___

### toString

- **toString**(): *string*

*Heredada de [StandardTx](common_transactions.standardtx.md).[toString](common_transactions.standardtx.md#tostring)*

*Definido en [src/comm/tx.ts:386](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/tx.ts#L386)*

Devuelve una representación cb58 de la [StandardTx](common_transactions.standardtx.md).

**`observaciones sobre las observaciones formuladas`** a diferencia de la mayoría de toStrings, esto devuelve en formato de serialización cb58

**Return:** *string*
