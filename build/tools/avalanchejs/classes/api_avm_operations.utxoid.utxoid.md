[avalancha](../README.md) › [API-AVM-Operations](../modules/api_avm_operations.md) › [UTXOID](api_avm_operations.utxoid.md)

# Clase: UTXOID

Clase para representar a UTXOID utilizado en tipos [[TransferableOp]]

## Jerarquía

[nBytes](common_nbytes.nbytes.md)

de **UTXOID**

## Índice de participación

### Constructores

* [constructor](api_avm_operations.utxoid.md#constructor)

### Propiedades de las propiedades

* [_codecid](api_avm_operations.utxoid.md#protected-_codecid)
* [_typeID](api_avm_operations.utxoid.md#protected-_typeid)
* [_typeName](api_avm_operations.utxoid.md#protected-_typename)
* [b)](api_avm_operations.utxoid.md#protected-bsize)
* [bytes](api_avm_operations.utxoid.md#protected-bytes)

### Métodos de trabajo

* [clon](api_avm_operations.utxoid.md#clone)
* [crear un entorno de creación](api_avm_operations.utxoid.md#create)
* [deserie](api_avm_operations.utxoid.md#deserialize)
* [deBuffer](api_avm_operations.utxoid.md#frombuffer)
* [fromString](api_avm_operations.utxoid.md#fromstring)
* [getCodecid](api_avm_operations.utxoid.md#getcodecid)
* [getSize](api_avm_operations.utxoid.md#getsize)
* [getTypeID](api_avm_operations.utxoid.md#gettypeid)
* [getTypeName](api_avm_operations.utxoid.md#gettypename)
* [serializar](api_avm_operations.utxoid.md#serialize)
* [toBuffer](api_avm_operations.utxoid.md#tobuffer)
* [toString](api_avm_operations.utxoid.md#tostring)
* [comparador](api_avm_operations.utxoid.md#static-comparator)

## Constructores

### constructor

\+ **nuevo UTXOID():** *[UTXOID](api_avm_operations.utxoid.md)*

*Definido en [src/apis/avm/ops.ts:728](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/ops.ts#L728)*

Clase para representar a UTXOID utilizado en tipos [[TransferableOp]]

**Returns:** *[UTXOID](api_avm_operations.utxoid.md)*

## Propiedades de las propiedades

### _codecid `protegido`

• **_codecid**: *número* = indefinido.

*Heredada de [SigIdx](common_signature.sigidx.md)[._codecid](common_signature.sigidx.md#protected-_codecid)*

*Definido en [src/utils/serialización.ts:40](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/serialization.ts#L40)*

___

### `Protegido` _typeID

• **_typeID**: *any* = undefined

*Supera [NBytes](common_nbytes.nbytes.md).[_typeID](common_nbytes.nbytes.md#protected-_typeid)*

*Definido en [src/apis/avm/ops.ts:674](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/ops.ts#L674)*

___

### _typeName `protegido`

• **_typeName**: *string* = "UTXOID"

*Overrides [NBytes](common_nbytes.nbytes.md).[_typeName](common_nbytes.nbytes.md#protected-_typename)*

*Definido en [src/apis/avm/ops.ts:673](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/ops.ts#L673)*

___

### Tamaño del busto `protegido`

• **bsize**: *número* = 36

*Supera [NBytes](common_nbytes.nbytes.md).[bsize](common_nbytes.nbytes.md#protected-bsize)*

*Definido en [src/apis/avm/ops.ts:679](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/ops.ts#L679)*

___

### Bytes `protegidos`

• **bytes**: *Buffer‹›* = Buffer.aloc(36)

*Superar [NBytes](common_nbytes.nbytes.md).[bytes](common_nbytes.nbytes.md#protected-bytes)*

*Definido en [src/apis/avm/ops.ts:678](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/ops.ts#L678)*

## Métodos de trabajo

### clon

- **clone**(): *esto*

*Superar [NBytes](common_nbytes.nbytes.md).[clone](common_nbytes.nbytes.md#abstract-clone)*

*Definido en [src/apis/avm/ops.ts:720](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/ops.ts#L720)*

**Returns:** *esto*

___

### crear un entorno de creación

*-* **create**(...`args`: []cualquiera

*Supera [NBytes](common_nbytes.nbytes.md).[create](common_nbytes.nbytes.md#abstract-create)*

*Definido en [src/apis/avm/ops.ts:726](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/ops.ts#L726)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `..args` | cualquier otra cosa que no sea[] |

**Returns:** *esto*

___

### deserie

- **deserialize**(`fields`: objeto, `codificación`: [SerializedEncoding](../modules/src_utils.md#serializedencoding)): *vacío*

*Heredada de [Signature](common_signature.signature.md).[deserialize](common_signature.signature.md#deserialize)*

*Superaciones [StandardParseableInput](common_inputs.standardparseableinput.md).[deserialize](common_inputs.standardparseableinput.md#deserialize)*

*Definido en [src/comm/nbytes.ts:36](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/nbytes.ts#L36)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `campos de cultivo` | objeto de la operación | - |
| `codificación` | [SerializedEncoding](../modules/src_utils.md#serializedencoding) | "hex" |

**Retornos:** *vacío*

___

### deBuffer

- **fromBuffer**`(buff`: buffer, `offset`: número): *número*

*Heredada de [SigIdx](common_signature.sigidx.md).[fromBuffer](common_signature.sigidx.md#frombuffer)*

*Definido en [src/comm/nbytes.ts:74](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/nbytes.ts#L74)*

Toma un [[Buffer]], verifica su longitud y la almacena.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `buffet` | Buffer | - |
| `offset` | Número de números | 0 |

**Retornos:** *número*

El tamaño del [buffer](https://github.com/feross/buffer)

___

### fromString

- **fromString**(`utxoid`: string): *número*

*Overrides [SigIdx](common_signature.sigidx.md).[fromString](common_signature.sigidx.md#fromstring)*

*Definido en [src/apis/avm/ops.ts:701](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/ops.ts#L701)*

Toma una cadena base-58 que contiene un [UTXOID](api_avm_operations.utxoid.md), la analiza, populates la clase y devuelve la longitud del UTXOID en bytes.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `utxoid` | cadena de producción |

**Retornos:** *número*

La longitud de la [UTXOID](api_avm_operations.utxoid.md) cruda

___

### getCodecid

- **getCodecid():** *número*

*Heredada de [SigIdx](common_signature.sigidx.md)[.getCodecid](common_signature.sigidx.md#getcodecid)*

*Definido en [src/utils/serialización.ts:59](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/serialization.ts#L59)*

Utilizado en serialización. Opcional. TypeID es un número para el tipo de identificación de objeto que se está saliendo.

**Retornos:** *número*

___

### getSize

- **getSize**(): *número*

*Heredada de [SigIdx](common_signature.sigidx.md).[getSize](common_signature.sigidx.md#getsize)*

*Definido en [src/comm/nbytes.ts:50](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/nbytes.ts#L50)*

Devuelve la longitud del [buffer](https://github.com/feross/buffer).

**Retornos:** *número*

El requisito de longitud exacta de esta clase

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

*Heredada de [Signature](common_signature.signature.md).[serialize](common_signature.signature.md#serialize)*

*Superaciones [Serializable](utils_serialization.serializable.md).[serialize](utils_serialization.serializable.md#serialize)*

*Definido en [src/comm/nbytes.ts:28](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/nbytes.ts#L28)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `codificación` | [SerializedEncoding](../modules/src_utils.md#serializedencoding) | "hex" |

**Return:** *objeto*

___

### toBuffer

- **toBuffer** (): *Buffer*

*Heredada de [SigIdx](common_signature.sigidx.md).[toBuffer](common_signature.sigidx.md#tobuffer)*

*Definido en [src/comm/nbytes.ts:94](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/nbytes.ts#L94)*

**Returns:** *Buffer*

Una referencia al [buffer](https://github.com/feross/buffer) almacenado

___

### toString

- **toString**(): *string*

*Supera [SigIdx](common_signature.sigidx.md).[toString](common_signature.sigidx.md#tostring)*

*Definido en [src/apis/avm/ops.ts:690](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/ops.ts#L690)*

Devuelve una representación base-58 del [UTXOID](api_avm_operations.utxoid.md).

**Return:** *string*

___

### Comparador `estático`

- **comparator**(): *función*

*Definido en [src/apis/avm/ops.ts:684](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/ops.ts#L684)*

Devuelve una función utilizada para ordenar una serie de [UTXOID](api_avm_operations.utxoid.md)s

**Retornos:** *función*

- (`a`: [UTXOID](api_avm_operations.utxoid.md)[,](api_avm_operations.utxoid.md) `b`: UTXOID): *1 | -1 | 0*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `a a` | [UTXOID](api_avm_operations.utxoid.md) |
| `b b` | [UTXOID](api_avm_operations.utxoid.md) |
