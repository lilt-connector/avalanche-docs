[avalancha](../README.md) › [Transacciones comunes](../modules/common_transactions.md) › [EVMStandardTx](common_transactions.evmstandardtx.md)

# Clase: EVMStandardTx ‹**KPClass, KCClass, SUBTx**›

Clase que representa una transacción firmada.

## Parámetros de tipo

• **KPClass**: *[StandardKeyPair](common_keychain.standardkeypair.md)*

• **KCClass**: *[StandardKeyChain](common_keychain.standardkeychain.md)‹KPClass›*

• **SUBTx**: *[EVMStandardUnsignedTx‹KPClass, EVMStandardUnsignedTx‹KPClass,](common_transactions.evmstandardunsignedtx.md) KCClass, [EVMStandardUnsignedTx‹KPClass,](common_transactions.evmstandardbasetx.md) KCClass››*

## Jerarquía

* [Serializable](utils_serialization.serializable.md)

   de la marca **EVMStandardTx**

   de [Tx](api_evm_transactions.tx.md)

## Índice de participación

### Constructores

* [constructor](common_transactions.evmstandardtx.md#constructor)

### Propiedades de las propiedades

* [_codecid](common_transactions.evmstandardtx.md#protected-_codecid)
* [_typeID](common_transactions.evmstandardtx.md#protected-_typeid)
* [_typeName](common_transactions.evmstandardtx.md#protected-_typename)
* [credenciales](common_transactions.evmstandardtx.md#protected-credentials)
* [sin unsignedTx](common_transactions.evmstandardtx.md#protected-unsignedtx)

### Métodos de trabajo

* [deserie](common_transactions.evmstandardtx.md#deserialize)
* [deBuffer](common_transactions.evmstandardtx.md#abstract-frombuffer)
* [fromString](common_transactions.evmstandardtx.md#fromstring)
* [getCodecid](common_transactions.evmstandardtx.md#getcodecid)
* [getTypeID](common_transactions.evmstandardtx.md#gettypeid)
* [getTypeName](common_transactions.evmstandardtx.md#gettypename)
* [getUnsignedTx](common_transactions.evmstandardtx.md#getunsignedtx)
* [serializar](common_transactions.evmstandardtx.md#serialize)
* [toBuffer](common_transactions.evmstandardtx.md#tobuffer)
* [toString](common_transactions.evmstandardtx.md#tostring)

## Constructores

### constructor

\+ **nuevo EVMStandardTx(unsignedTx: EVMStandardTx(unsignedTx:**`` SUBTx, `credenciales`[:](common_signature.credential.md) []Credencial): *[EVMStandardTx](common_transactions.evmstandardtx.md)*

*Definido en [src/commtx.ts:298](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/evmtx.ts#L298)*

Clase que representa una transacción firmada.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `sin unsignedTx` | SUTT | no definido. | [StandardUnsignedTx](common_transactions.standardunsignedtx.md) Opcional |
| `credenciales` | [Credencial](common_signature.credential.md)[] | no definido. | - |

**Returns:** *[EVMStandardTx](common_transactions.evmstandardtx.md)*

## Propiedades de las propiedades

### _codecid `protegido`

• **_codecid**: *número* = indefinido.

*Heredada de [SigIdx](common_signature.sigidx.md)[._codecid](common_signature.sigidx.md#protected-_codecid)*

*Definido en [src/utils/serialización.ts:40](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/serialization.ts#L40)*

___

### `Protegido` _typeID

• **_typeID**: *any* = undefined

*Superes [Serializable](utils_serialization.serializable.md).[_typeID](utils_serialization.serializable.md#protected-_typeid)*

*Definido en [src/commtx.ts:230](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/evmtx.ts#L230)*

___

### _typeName `protegido`

• **_typeName**: *string* = "StandardTx"

*Superes [Serializable](utils_serialization.serializable.md).[_typeName](utils_serialization.serializable.md#protected-_typename)*

*Definido en [src/commtx.ts:229](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/evmtx.ts#L229)*

___

### Credenciales `y` de las credenciales protegidas

• **credenciales**: *[Credencial](common_signature.credential.md)[]* =[]

*Definido en [src/commtx.ts:242](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/evmtx.ts#L242)*

___

### Sin firma `protegida` Tx

• sin **unsignedTx**: *SUBTx* = indefinido.

*Definido en [src/commtx.ts:241](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/evmtx.ts#L241)*

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

*Definido en [src/commtx.ts:251](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/evmtx.ts#L251)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `bytes` | Buffer |
| `¿Qué compensación?` | Número de números |

**Retornos:** *número*

___

### fromString

- **fromString**(`serialized`: string): *número*

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

- **getUnsignedTx**(): *SUBTx*

*Definido en [src/commtx.ts:247](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/evmtx.ts#L247)*

Devuelve la [StandardUnsignedTx](common_transactions.standardunsignedtx.md)

**Returns:** *SUBTx*

___

### serializar

- **serialize**(`encoding`: [SerializedEncoding](../modules/src_utils.md#serializedencoding)): *objeto*

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

*Definido en [src/commtx.ts:256](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/evmtx.ts#L256)*

Devuelve una representación de [Buffer](https://github.com/feross/buffer) de la [StandardTx](common_transactions.standardtx.md).

**Returns:** *Buffer*

___

### toString

- **toString**(): *string*

*Definido en [src/commtx.ts:296](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/evmtx.ts#L296)*

Devuelve una representación cb58 de la [StandardTx](common_transactions.standardtx.md).

**`observaciones sobre las observaciones formuladas`** a diferencia de la mayoría de toStrings, esto devuelve en formato de serialización cb58

**Return:** *string*
