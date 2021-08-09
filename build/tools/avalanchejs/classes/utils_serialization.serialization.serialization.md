[avalancha](../README.md) › [Utils-Serialization](../modules/utils_serialization.md)[](utils_serialization.serialization.md) › Serialización

# Clase: Serialización

## Jerarquía

* **Serialization**

## Índice de participación

### Constructores

* [constructor](utils_serialization.serialization.md#private-constructor)

### Propiedades de las propiedades

* [bintools](utils_serialization.serialization.md#private-bintools)
* [instancia de parte de la](utils_serialization.serialization.md#static-private-instance)

### Métodos de trabajo

* [bufferToType](utils_serialization.serialization.md#buffertotype)
* [decodificador](utils_serialization.serialization.md#decoder)
* [deserie](utils_serialization.serialization.md#deserialize)
* [codificador](utils_serialization.serialization.md#encoder)
* [serializar](utils_serialization.serialization.md#serialize)
* [typeToBuffer](utils_serialization.serialization.md#typetobuffer)
* [getInstance](utils_serialization.serialization.md#static-getinstance)

## Constructores

### Constructor `privado`

\+ **nueva Serialización():** *[Serialización](utils_serialization.serialization.md)*

*Definido en [src/utils/serialización.ts:99](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/serialization.ts#L99)*

**Retornos:** *[Serialización](utils_serialization.serialization.md)*

## Propiedades de las propiedades

### Bintools `privados`

• **bintools**: *[BinTools](utils_bintools.bintools.md)*

*Definido en [src/utils/serialización.ts:104](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/serialization.ts#L104)*

___

### Casación `privada` `estática`

• **instancia de la** *[serialización](utils_serialization.serialization.md)*

*Definido en [src/utils/serialización.ts:99](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/serialization.ts#L99)*

## Métodos de trabajo

### bufferToType

- **bufferToType(vb:**`` Buffer, `tipo`: [bufferToType(vb:](../modules/utils_serialization.md#serializedtype) ...`args`: []cualquiera): *cualquier*

*Definido en [src/utils/serialización.ts:124](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/serialization.ts#L124)*

Convertir [Buffer](https://github.com/feross/buffer) en [SerializedType](../modules/utils_serialization.md#serializedtype)

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `vb` | Buffer | [Buffer](https://github.com/feross/buffer) |
| `Tipo de cambio` | [Tipo de serie](../modules/utils_serialization.md#serializedtype) | [Tipo de serie](../modules/utils_serialization.md#serializedtype) |
| `..args` | cualquier otra cosa que no sea[] | - |

**Retornos:** *cualquier*

tipo de [type](../modules/utils_serialization.md#serializedtype)

___

### decodificador

- **decoder**(`value`: string: `codificación`[:](../modules/utils_serialization.md#serializedtype) [SerializedEncoding](../modules/utils_serialization.md#serializedencoding)[](../modules/utils_serialization.md#serializedtype), `intype`: SerializedType, `outtype`: SerializedType, ...`args`: []*any*

*Definido en [src/utils/serialización.ts:244](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/serialization.ts#L244)*

Convertir valor a tipo de codificación [SerializedType](../modules/utils_serialization.md#serializedtype) o [SerializedEncoding](../modules/utils_serialization.md#serializedencoding)

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `valor` | cadena de producción | - |
| `codificación` | [SerializedEncoding](../modules/utils_serialization.md#serializedencoding) | [SerializedEncoding](../modules/utils_serialization.md#serializedencoding) |
| `intype` | [Tipo de serie](../modules/utils_serialization.md#serializedtype) | [Tipo de serie](../modules/utils_serialization.md#serializedtype) |
| `outtype` | [Tipo de serie](../modules/utils_serialization.md#serializedtype) | [Tipo de serie](../modules/utils_serialization.md#serializedtype) |
| `..args` | cualquier otra cosa que no sea[] | - |

**Retornos:** *cualquier*

tipo de codificación [SerializedType](../modules/utils_serialization.md#serializedtype) o [SerializedEncoding](../modules/utils_serialization.md#serializedencoding)

___

### deserie

- **deserialize**(`input`: [Serializado](../interfaces/common_interfaces.serialized.md), `salida`: [Serializable](utils_serialization.serializable.md)): *vacío*

*Definido en [src/utils/serialización.ts:268](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/serialization.ts#L268)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `entrada en vigor de la entrada` | [Serializado](../interfaces/common_interfaces.serialized.md) |
| `salida de la salida de la salida` | [Serializable](utils_serialization.serializable.md) |

**Retornos:** *vacío*

___

### codificador

- **encoder**(`value`: cualquier, `codificación`[:](../modules/utils_serialization.md#serializedtype) [SerializedEncoding](../modules/utils_serialization.md#serializedencoding)[](../modules/utils_serialization.md#serializedtype), `intype`: SerializedType, `outtype`: SerializedType, ..`args`: []*any*): cualquier

*Definido en [src/utils/serialización.ts:223](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/serialization.ts#L223)*

Convertir valor a tipo de codificación [SerializedType](../modules/utils_serialization.md#serializedtype) o [SerializedEncoding](../modules/utils_serialization.md#serializedencoding)

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `valor` | cualquier otra cosa que no sea | - |
| `codificación` | [SerializedEncoding](../modules/utils_serialization.md#serializedencoding) | [SerializedEncoding](../modules/utils_serialization.md#serializedencoding) |
| `intype` | [Tipo de serie](../modules/utils_serialization.md#serializedtype) | [Tipo de serie](../modules/utils_serialization.md#serializedtype) |
| `outtype` | [Tipo de serie](../modules/utils_serialization.md#serializedtype) | [Tipo de serie](../modules/utils_serialization.md#serializedtype) |
| `..args` | cualquier otra cosa que no sea[] | - |

**Retornos:** *cualquier*

tipo de codificación [SerializedType](../modules/utils_serialization.md#serializedtype) o [SerializedEncoding](../modules/utils_serialization.md#serializedencoding)

___

### serializar

- **serialize(serialize:**`` [Serializable](utils_serialization.serializable.md), `vm`: string, `codificación`: [SerializedEncoding](../modules/utils_serialization.md#serializedencoding), `notas`: string): *[Serializado](../interfaces/common_interfaces.serialized.md)*

*Definido en [src/utils/serialización.ts:255](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/serialization.ts#L255)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `serializar` | [Serializable](utils_serialization.serializable.md) | - |
| `vm` | cadena de producción | - |
| `codificación` | [SerializedEncoding](../modules/utils_serialization.md#serializedencoding) | "exhibir" |
| `notas de notas` | cadena de producción | no definido. |

**Retornos:** *[Serializado](../interfaces/common_interfaces.serialized.md)*

___

### typeToBuffer

- **typeToBuffer**`(v: (v`: cualquier, `tipo`: [SerializedType](../modules/utils_serialization.md#serializedtype), ...`args`: []any): *Buffer*

*Definido en [src/utils/serialización.ts:164](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/serialization.ts#L164)*

Convertir [SerializedType](../modules/utils_serialization.md#serializedtype) en [Buffer](https://github.com/feross/buffer)

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `v` | cualquier otra cosa que no sea | tipo de [type](../modules/utils_serialization.md#serializedtype) |
| `Tipo de cambio` | [Tipo de serie](../modules/utils_serialization.md#serializedtype) | [Tipo de serie](../modules/utils_serialization.md#serializedtype) |
| `..args` | cualquier otra cosa que no sea[] | - |

**Returns:** *Buffer*

[Buffer](https://github.com/feross/buffer)

___

### GetInstance `estática`

- **getInstance**(): *[Serialización](utils_serialization.serialization.md)*

*Definido en [src/utils/serialización.ts:109](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/serialization.ts#L109)*

Retrieves el singleton de Serialización.

**Retornos:** *[Serialización](utils_serialization.serialization.md)*
