[avalanche](../README.md) › Transacciones [API-EVM-Transactions](../modules/api_evm_transactions.md) [Tx](api_evm_transactions.tx.md)

# Clase: Tx

## Jerarquía

[↳](common_transactions.evmstandardtx.md)[](api_evm_keychain.keypair.md) [KeyChain](api_evm_keychain.keychain.md), [UnsignedTx](api_evm_transactions.unsignedtx.md)›

de **Tx**

## Índice de participación

### Constructores

* [constructor](api_evm_transactions.tx.md#constructor)

### Propiedades de las propiedades

* [_codecid](api_evm_transactions.tx.md#protected-_codecid)
* [_typeID](api_evm_transactions.tx.md#protected-_typeid)
* [_typeName](api_evm_transactions.tx.md#protected-_typename)
* [credenciales](api_evm_transactions.tx.md#protected-credentials)
* [sin unsignedTx](api_evm_transactions.tx.md#protected-unsignedtx)

### Métodos de trabajo

* [deserie](api_evm_transactions.tx.md#deserialize)
* [deBuffer](api_evm_transactions.tx.md#frombuffer)
* [fromString](api_evm_transactions.tx.md#fromstring)
* [getCodecid](api_evm_transactions.tx.md#getcodecid)
* [getTypeID](api_evm_transactions.tx.md#gettypeid)
* [getTypeName](api_evm_transactions.tx.md#gettypename)
* [getUnsignedTx](api_evm_transactions.tx.md#getunsignedtx)
* [serializar](api_evm_transactions.tx.md#serialize)
* [toBuffer](api_evm_transactions.tx.md#tobuffer)
* [toString](api_evm_transactions.tx.md#tostring)

## Constructores

### constructor

\+ **new Tx**`(unsignedTx: Tx(unsignedTx`: [Tx(unsignedTx:](api_evm_transactions.unsignedtx.md) `credenciales`[:](common_signature.credential.md) []Credencial): *[Tx](api_evm_transactions.tx.md)*

*Heredada de [EVMStandardTx](common_transactions.evmstandardtx.md).[constructor](common_transactions.evmstandardtx.md#constructor)*

*Definido en [src/commtx.ts:298](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/evmtx.ts#L298)*

Clase que representa una transacción firmada.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `sin unsignedTx` | [Sin UnsignedTx](api_evm_transactions.unsignedtx.md) | no definido. | [StandardUnsignedTx](common_transactions.standardunsignedtx.md) Opcional |
| `credenciales` | [Credencial](common_signature.credential.md)[] | no definido. | - |

**Returns:** *[Tx](api_evm_transactions.tx.md)*

## Propiedades de las propiedades

### _codecid `protegido`

• **_codecid**: *número* = indefinido.

*Heredada de [SigIdx](common_signature.sigidx.md)[._codecid](common_signature.sigidx.md#protected-_codecid)*

*Definido en [src/utils/serialización.ts:40](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/serialization.ts#L40)*

___

### `Protegido` _typeID

• **_typeID**: *any* = undefined

*Supera [EVMStandardTx](common_transactions.evmstandardtx.md).[_typeID](common_transactions.evmstandardtx.md#protected-_typeid)*

*Definido en [src/apis/evm/tx.ts:87](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/tx.ts#L87)*

___

### _typeName `protegido`

• **_typeName**: *string* = "Tx"

*Overrides [EVMStandardTx](common_transactions.evmstandardtx.md).[_typeName](common_transactions.evmstandardtx.md#protected-_typename)*

*Definido en [src/apis/evm/tx.ts:86](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/tx.ts#L86)*

___

### Credenciales `y` de las credenciales protegidas

• **credenciales**: *[Credencial](common_signature.credential.md)[]* =[]

*Heredado de [EVMStandardTx](common_transactions.evmstandardtx.md).[credentials](common_transactions.evmstandardtx.md#protected-credentials)*

*Definido en [src/commtx.ts:242](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/evmtx.ts#L242)*

___

### Sin firma `protegida` Tx

• **sin unsignedTx**: *[Sin](api_evm_transactions.unsignedtx.md)* unsignedTx: = sin definir

*Heredada de [EVMStandardTx](common_transactions.evmstandardtx.md).[unsignedTx](common_transactions.evmstandardtx.md#protected-unsignedtx)*

*Definido en [src/commtx.ts:241](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/evmtx.ts#L241)*

## Métodos de trabajo

### deserie

- **deserialize**(`fields`: objeto, `codificación`: [SerializedEncoding](../modules/src_utils.md#serializedencoding)): *vacío*

*Superaciones [StandardParseableInput](common_inputs.standardparseableinput.md).[deserialize](common_inputs.standardparseableinput.md#deserialize)*

*Definido en [src/apis/evm/tx.ts:91](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/tx.ts#L91)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `campos de cultivo` | objeto de la operación | - |
| `codificación` | [SerializedEncoding](../modules/src_utils.md#serializedencoding) | "hex" |

**Retornos:** *vacío*

___

### deBuffer

- **fromBuffer**(`bytes`: Buffer, `offset`: número): *número*

*Supera [EVMStandardTx](common_transactions.evmstandardtx.md).[fromBuffer](common_transactions.evmstandardtx.md#abstract-frombuffer)*

*Definido en [src/apis/evm/tx.ts:112](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/tx.ts#L112)*

Toma un [buffer](https://github.com/feross/buffer) que contiene un [Tx](api_evm_transactions.tx.md), lo pierde, populosa la clase y devuelve la longitud de la Tx en bytes.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `bytes` | Buffer | - | Un [buffer](https://github.com/feross/buffer) que contiene un [Tx](api_evm_transactions.tx.md) crudo. |
| `offset` | Número de números | 0 | Un número que representa el punto de partida de los bytes para comenzar a analizar |

**Retornos:** *número*

La longitud del [Tx](api_evm_transactions.tx.md) crudo.

___

### fromString

- **fromString**(`serialized`: string): *número*

*Heredada de [EVMStandardTx](common_transactions.evmstandardtx.md).[fromString](common_transactions.evmstandardtx.md#fromstring)*

*Definido en [src/commtx.ts:286](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/evmtx.ts#L286)*

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

- **getUnsignedTx():** *[getUnsignedTx():](api_evm_transactions.unsignedtx.md)*

*Heredada de [EVMStandardTx](common_transactions.evmstandardtx.md).[getUnsignedTx](common_transactions.evmstandardtx.md#getunsignedtx)*

*Definido en [src/commtx.ts:247](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/evmtx.ts#L247)*

Devuelve la [StandardUnsignedTx](common_transactions.standardunsignedtx.md)

**Returns:** *[Sin](api_evm_transactions.unsignedtx.md)* Returns:

___

### serializar

- **serialize**(`encoding`: [SerializedEncoding](../modules/src_utils.md#serializedencoding)): *objeto*

*Heredada de [EVMStandardTx](common_transactions.evmstandardtx.md).[serialize](common_transactions.evmstandardtx.md#serialize)*

*Superaciones [Serializable](utils_serialization.serializable.md).[serialize](utils_serialization.serializable.md#serialize)*

*Definido en [src/commtx.ts:232](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/evmtx.ts#L232)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `codificación` | [SerializedEncoding](../modules/src_utils.md#serializedencoding) | "hex" |

**Return:** *objeto*

___

### toBuffer

- **toBuffer** (): *Buffer*

*Heredada de [EVMStandardTx](common_transactions.evmstandardtx.md).[toBuffer](common_transactions.evmstandardtx.md#tobuffer)*

*Definido en [src/commtx.ts:256](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/evmtx.ts#L256)*

Devuelve una representación de [Buffer](https://github.com/feross/buffer) de la [StandardTx](common_transactions.standardtx.md).

**Returns:** *Buffer*

___

### toString

- **toString**(): *string*

*Heredada de [EVMStandardTx](common_transactions.evmstandardtx.md).[toString](common_transactions.evmstandardtx.md#tostring)*

*Definido en [src/commtx.ts:296](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/evmtx.ts#L296)*

Devuelve una representación cb58 de la [StandardTx](common_transactions.standardtx.md).

**`observaciones sobre las observaciones formuladas`** a diferencia de la mayoría de toStrings, esto devuelve en formato de serialización cb58

**Return:** *string*
