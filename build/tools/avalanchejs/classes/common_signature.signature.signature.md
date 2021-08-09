[avalancha](../README.md) › [Firma común](../modules/common_signature.md) › [Firma](common_signature.signature.md)

# Clase: Firma

Firma para un [Tx](api_platformvm_transactions.tx.md)

## Jerarquía

[nBytes](common_nbytes.nbytes.md)

m **Firma**

## Índice de participación

### Constructores

* [constructor](common_signature.signature.md#constructor)

### Propiedades de las propiedades

* [_codecid](common_signature.signature.md#protected-_codecid)
* [_typeID](common_signature.signature.md#protected-_typeid)
* [_typeName](common_signature.signature.md#protected-_typename)
* [b)](common_signature.signature.md#protected-bsize)
* [bytes](common_signature.signature.md#protected-bytes)

### Métodos de trabajo

* [clon](common_signature.signature.md#clone)
* [crear un entorno de creación](common_signature.signature.md#create)
* [deserie](common_signature.signature.md#deserialize)
* [deBuffer](common_signature.signature.md#frombuffer)
* [fromString](common_signature.signature.md#fromstring)
* [getCodecid](common_signature.signature.md#getcodecid)
* [getSize](common_signature.signature.md#getsize)
* [getTypeID](common_signature.signature.md#gettypeid)
* [getTypeName](common_signature.signature.md#gettypename)
* [serializar](common_signature.signature.md#serialize)
* [toBuffer](common_signature.signature.md#tobuffer)
* [toString](common_signature.signature.md#tostring)

## Constructores

### constructor

\+ **nueva Firma():** *[Firma](common_signature.signature.md)*

*Definido en [src/común/credenciales.ts:91](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/credentials.ts#L91)*

Firma para un [Tx](api_platformvm_transactions.tx.md)

**Returns:** *[Firma](common_signature.signature.md)*

## Propiedades de las propiedades

### _codecid `protegido`

• **_codecid**: *número* = indefinido.

*Heredada de [SigIdx](common_signature.sigidx.md)[._codecid](common_signature.sigidx.md#protected-_codecid)*

*Definido en [src/utils/serialización.ts:40](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/serialization.ts#L40)*

___

### `Protegido` _typeID

• **_typeID**: *any* = undefined

*Supera [NBytes](common_nbytes.nbytes.md).[_typeID](common_nbytes.nbytes.md#protected-_typeid)*

*Definido en [src/común/credenciales.ts:76](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/credentials.ts#L76)*

___

### _typeName `protegido`

• **_typeName**: *string* = "Firma"

*Overrides [NBytes](common_nbytes.nbytes.md).[_typeName](common_nbytes.nbytes.md#protected-_typename)*

*Definido en [src/común/credenciales.ts:75](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/credentials.ts#L75)*

___

### Tamaño del busto `protegido`

• **bsize**: *número* = 65

*Supera [NBytes](common_nbytes.nbytes.md).[bsize](common_nbytes.nbytes.md#protected-bsize)*

*Definido en [src/común/credenciales.ts:81](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/credentials.ts#L81)*

___

### Bytes `protegidos`

• **bytes**: *Buffer‹›* = Buffer.aloc(65)

*Superar [NBytes](common_nbytes.nbytes.md).[bytes](common_nbytes.nbytes.md#protected-bytes)*

*Definido en [src/común/credenciales.ts:80](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/credentials.ts#L80)*

## Métodos de trabajo

### clon

- **clone**(): *esto*

*Superar [NBytes](common_nbytes.nbytes.md).[clone](common_nbytes.nbytes.md#abstract-clone)*

*Definido en [src/común/credenciales.ts:83](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/credentials.ts#L83)*

**Returns:** *esto*

___

### crear un entorno de creación

*-* **create**(...`args`: []cualquiera

*Supera [NBytes](common_nbytes.nbytes.md).[create](common_nbytes.nbytes.md#abstract-create)*

*Definido en [src/común/credenciales.ts:89](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/credentials.ts#L89)*

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

- **deString(b58str:**`` string): *número*

*Heredada de [SigIdx](common_signature.sigidx.md).[fromString](common_signature.sigidx.md#fromstring)*

*Definido en [src/comm/nbytes.ts:57](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/nbytes.ts#L57)*

Toma una cadena codificada base-58, verifica su longitud y la almacena.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `b58str` | cadena de producción |

**Retornos:** *número*

El tamaño del [buffer](https://github.com/feross/buffer)

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

*Heredada de [SigIdx](common_signature.sigidx.md).[toString](common_signature.sigidx.md#tostring)*

*Definido en [src/comm/nbytes.ts:101](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/nbytes.ts#L101)*

**Return:** *string*

Una cadena base-58 del [buffer](https://github.com/feross/buffer) almacenado
