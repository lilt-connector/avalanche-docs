[avalancha](../README.md) › [Firma común](../modules/common_signature.md) › [SigIdx](common_signature.sigidx.md)

# Clase: SigIdx

Tipo que representa un índice de [firma](common_signature.signature.md) utilizado en [Input](common_inputs.input.md)

## Jerarquía

[nBytes](common_nbytes.nbytes.md)

de **SigIdx**

## Índice de participación

### Constructores

* [constructor](common_signature.sigidx.md#constructor)

### Propiedades de las propiedades

* [_codecid](common_signature.sigidx.md#protected-_codecid)
* [_typeID](common_signature.sigidx.md#protected-_typeid)
* [_typeName](common_signature.sigidx.md#protected-_typename)
* [b)](common_signature.sigidx.md#protected-bsize)
* [bytes](common_signature.sigidx.md#protected-bytes)
* [fuente de información](common_signature.sigidx.md#protected-source)

### Métodos de trabajo

* [clon](common_signature.sigidx.md#clone)
* [crear un entorno de creación](common_signature.sigidx.md#create)
* [deserie](common_signature.sigidx.md#deserialize)
* [deBuffer](common_signature.sigidx.md#frombuffer)
* [fromString](common_signature.sigidx.md#fromstring)
* [getCodecid](common_signature.sigidx.md#getcodecid)
* [getSize](common_signature.sigidx.md#getsize)
* [getSource](common_signature.sigidx.md#getsource)
* [getTypeID](common_signature.sigidx.md#gettypeid)
* [getTypeName](common_signature.sigidx.md#gettypename)
* [serializar](common_signature.sigidx.md#serialize)
* [setSource](common_signature.sigidx.md#setsource)
* [toBuffer](common_signature.sigidx.md#tobuffer)
* [toString](common_signature.sigidx.md#tostring)

## Constructores

### constructor

\+ **nuevo SigIdx():** *[SigIdx](common_signature.sigidx.md)*

*Definido en [src/común/credenciales.ts:60](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/credentials.ts#L60)*

Tipo que representa un índice de [firma](common_signature.signature.md) utilizado en [Input](common_inputs.input.md)

**Returns:** *[SigIdx](common_signature.sigidx.md)*

## Propiedades de las propiedades

### _codecid `protegido`

• **_codecid**: *número* = indefinido.

*Heredada de [SigIdx](common_signature.sigidx.md)[._codecid](common_signature.sigidx.md#protected-_codecid)*

*Definido en [src/utils/serialización.ts:40](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/serialization.ts#L40)*

___

### `Protegido` _typeID

• **_typeID**: *any* = undefined

*Supera [NBytes](common_nbytes.nbytes.md).[_typeID](common_nbytes.nbytes.md#protected-_typeid)*

*Definido en [src/común/credenciales.ts:22](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/credentials.ts#L22)*

___

### _typeName `protegido`

• **_typeName**: *string* = "SigIdx"

*Overrides [NBytes](common_nbytes.nbytes.md).[_typeName](common_nbytes.nbytes.md#protected-_typename)*

*Definido en [src/común/credenciales.ts:21](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/credentials.ts#L21)*

___

### Tamaño del busto `protegido`

• **bsize**: *número* = 4

*Supera [NBytes](common_nbytes.nbytes.md).[bsize](common_nbytes.nbytes.md#protected-bsize)*

*Definido en [src/común/credenciales.ts:38](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/credentials.ts#L38)*

___

### Bytes `protegidos`

• **bytes**: *Buffer‹›* = Buffer.aloc(4)

*Superar [NBytes](common_nbytes.nbytes.md).[bytes](common_nbytes.nbytes.md#protected-bytes)*

*Definido en [src/común/credenciales.ts:37](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/credentials.ts#L37)*

___

### Fuente `protegida`

• **fuente**: *Buffer* = Buffer.aloc(20)

*Definido en [src/común/credenciales.ts:36](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/credentials.ts#L36)*

## Métodos de trabajo

### clon

- **clone**(): *esto*

*Superar [NBytes](common_nbytes.nbytes.md).[clone](common_nbytes.nbytes.md#abstract-clone)*

*Definido en [src/común/credenciales.ts:52](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/credentials.ts#L52)*

**Returns:** *esto*

___

### crear un entorno de creación

*-* **create**(...`args`: []cualquiera

*Supera [NBytes](common_nbytes.nbytes.md).[create](common_nbytes.nbytes.md#abstract-create)*

*Definido en [src/común/credenciales.ts:58](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/credentials.ts#L58)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `..args` | cualquier otra cosa que no sea[] |

**Returns:** *esto*

___

### deserie

- **deserialize**(`fields`: objeto, `codificación`: [SerializedEncoding](../modules/src_utils.md#serializedencoding)): *vacío*

*Overrides [Signature... Signature.deserialize](common_signature.signature.md)[](common_signature.signature.md#deserialize)*

*Definido en [src/común/credenciales.ts:31](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/credentials.ts#L31)*

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

### getSource

- **getSource**(): *Buffer*

*Definido en [src/común/credenciales.ts:50](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/credentials.ts#L50)*

Recupera la dirección de origen para la firma

**Returns:** *Buffer*

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

*Overrides [Signature](common_signature.signature.md).[serialize](common_signature.signature.md#serialize)*

*Definido en [src/común/credenciales.ts:24](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/credentials.ts#L24)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `codificación` | [SerializedEncoding](../modules/src_utils.md#serializedencoding) | "hex" |

**Return:** *objeto*

___

### setSource

- **setSource**(`address`: Buffer): *nul*

*Definido en [src/común/credenciales.ts:43](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/credentials.ts#L43)*

Establece la dirección de origen para la firma

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `Dirección de la dirección` | Buffer |

**Retornos:** *vacío*

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
