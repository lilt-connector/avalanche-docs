avalancha › [avalanche](../README.md)[](../modules/common_nbytes.md) › [NBytes](common_nbytes.nbytes.md)

# Clase: NBytes

Clase abstracta que implementa funcionalidad básica para gestionar un [Buffer](https://github.com/feross/buffer) de una longitud exacta.

Crear una clase que extiende esta y anule el tamaño bsize para que valida para exactamente la longitud correcta.

## Jerarquía

* [Serializable](utils_serialization.serializable.md)

   **nBytes**

   de [SigIdx](common_signature.sigidx.md)

   m [Firma](common_signature.signature.md)

   [m.](common_output.address.md)

   de [UTXOID](api_avm_operations.utxoid.md)

## Índice de participación

### Propiedades de las propiedades

* [_codecid](common_nbytes.nbytes.md#protected-_codecid)
* [_typeID](common_nbytes.nbytes.md#protected-_typeid)
* [_typeName](common_nbytes.nbytes.md#protected-_typename)
* [b)](common_nbytes.nbytes.md#protected-bsize)
* [bytes](common_nbytes.nbytes.md#protected-bytes)

### Métodos de trabajo

* [clon](common_nbytes.nbytes.md#abstract-clone)
* [crear un entorno de creación](common_nbytes.nbytes.md#abstract-create)
* [deserie](common_nbytes.nbytes.md#deserialize)
* [deBuffer](common_nbytes.nbytes.md#frombuffer)
* [fromString](common_nbytes.nbytes.md#fromstring)
* [getCodecid](common_nbytes.nbytes.md#getcodecid)
* [getSize](common_nbytes.nbytes.md#getsize)
* [getTypeID](common_nbytes.nbytes.md#gettypeid)
* [getTypeName](common_nbytes.nbytes.md#gettypename)
* [serializar](common_nbytes.nbytes.md#serialize)
* [toBuffer](common_nbytes.nbytes.md#tobuffer)
* [toString](common_nbytes.nbytes.md#tostring)

## Propiedades de las propiedades

### _codecid `protegido`

• **_codecid**: *número* = indefinido.

*Heredada de [SigIdx](common_signature.sigidx.md)[._codecid](common_signature.sigidx.md#protected-_codecid)*

*Definido en [src/utils/serialización.ts:40](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/serialization.ts#L40)*

___

### `Protegido` _typeID

• **_typeID**: *any* = undefined

*Superes [Serializable](utils_serialization.serializable.md).[_typeID](utils_serialization.serializable.md#protected-_typeid)*

*Definido en [src/comm/nbytes.ts:26](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/nbytes.ts#L26)*

___

### _typeName `protegido`

• **_typeName**: *string* = "NBytes"

*Superes [Serializable](utils_serialization.serializable.md).[_typeName](utils_serialization.serializable.md#protected-_typename)*

*Definido en [src/comm/nbytes.ts:25](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/nbytes.ts#L25)*

___

### Tamaño del busto `protegido`

• **bsize**: *número*

*Definido en [src/comm/nbytes.ts:43](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/nbytes.ts#L43)*

___

### Bytes `protegidos`

• **bytes**: *Buffer*

*Definido en [src/comm/nbytes.ts:42](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/nbytes.ts#L42)*

## Métodos de trabajo

### Clon `abstracto`

- **clone**(): *esto*

*Definido en [src/comm/nbytes.ts:105](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/nbytes.ts#L105)*

**Returns:** *esto*

___

### `Crear, abstracta,`

*-* **create**(...`args`: []cualquiera

*Definido en [src/comm/nbytes.ts:106](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/nbytes.ts#L106)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `..args` | cualquier otra cosa que no sea[] |

**Returns:** *esto*

___

### deserie

- **deserialize**(`fields`: objeto, `codificación`: [SerializedEncoding](../modules/src_utils.md#serializedencoding)): *vacío*

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

*Definido en [src/comm/nbytes.ts:94](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/nbytes.ts#L94)*

**Returns:** *Buffer*

Una referencia al [buffer](https://github.com/feross/buffer) almacenado

___

### toString

- **toString**(): *string*

*Definido en [src/comm/nbytes.ts:101](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/nbytes.ts#L101)*

**Return:** *string*

Una cadena base-58 del [buffer](https://github.com/feross/buffer) almacenado
