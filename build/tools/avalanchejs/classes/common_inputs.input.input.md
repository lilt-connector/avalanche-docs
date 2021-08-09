[avalancha](../README.md) › [Insumos comunes](../modules/common_inputs.md) › [Entrada](common_inputs.input.md)

# Clase: Entrada

## Jerarquía

* [Serializable](utils_serialization.serializable.md)

   **,,**

   m [Estándar Importe](common_inputs.standardamountinput.md)

## Índice de participación

### Propiedades de las propiedades

* [_codecid](common_inputs.input.md#protected-_codecid)
* [_typeID](common_inputs.input.md#protected-_typeid)
* [_typeName](common_inputs.input.md#protected-_typename)
* [sigCount](common_inputs.input.md#protected-sigcount)
* [sigIdxs](common_inputs.input.md#protected-sigidxs)

### Métodos de trabajo

* [addSignatureIdx](common_inputs.input.md#addsignatureidx)
* [clon](common_inputs.input.md#abstract-clone)
* [crear un entorno de creación](common_inputs.input.md#abstract-create)
* [deserie](common_inputs.input.md#deserialize)
* [deBuffer](common_inputs.input.md#frombuffer)
* [getCodecid](common_inputs.input.md#getcodecid)
* [getCredentialID](common_inputs.input.md#abstract-getcredentialid)
* [getInputID](common_inputs.input.md#abstract-getinputid)
* [getSigIdxs](common_inputs.input.md#getsigidxs)
* [getTypeID](common_inputs.input.md#gettypeid)
* [getTypeName](common_inputs.input.md#gettypename)
* [seleccionar](common_inputs.input.md#abstract-select)
* [serializar](common_inputs.input.md#serialize)
* [toBuffer](common_inputs.input.md#tobuffer)
* [toString](common_inputs.input.md#tostring)
* [comparador](common_inputs.input.md#static-comparator)

## Propiedades de las propiedades

### _codecid `protegido`

• **_codecid**: *número* = indefinido.

*Heredada de [SigIdx](common_signature.sigidx.md)[._codecid](common_signature.sigidx.md#protected-_codecid)*

*Definido en [src/utils/serialización.ts:40](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/serialization.ts#L40)*

___

### `Protegido` _typeID

• **_typeID**: *any* = undefined

*Superes [Serializable](utils_serialization.serializable.md).[_typeID](utils_serialization.serializable.md#protected-_typeid)*

*Definido en [src/comm/input.ts:19](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/input.ts#L19)*

___

### _typeName `protegido`

• **_typeName**: *string* = "Input"

*Superes [Serializable](utils_serialization.serializable.md).[_typeName](utils_serialization.serializable.md#protected-_typename)*

*Definido en [src/comm/input.ts:18](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/input.ts#L18)*

___

### sigCount `protegido`

• **sigCount**: *Buffer* = Buffer.aloc(4)

*Definido en [src/comm/input.ts:38](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/input.ts#L38)*

___

### SigIdxs `protegidos`

• **sigIdxs**: *[SigIdx](common_signature.sigidx.md)[]* =[]

*Definido en [src/comm/input.ts:39](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/input.ts#L39)*

## Métodos de trabajo

### addSignatureIdx

- **addSignatureIdx**(`addressIdx`: número, `dirección`: Buffer): *void*

*Definido en [src/comm/input.ts:70](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/input.ts#L70)*

Crea y agrega un [SigIdx](common_signature.sigidx.md) a la [entrada](common_inputs.input.md).

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `addressIdx` | Número de números | El índice de la dirección a la referencia en las firmas |
| `Dirección de la dirección` | Buffer | La dirección de la fuente de la firma |

**Retornos:** *vacío*

___

### Clon `abstracto`

- **clone**(): *esto*

*Definido en [src/comm/input.ts:114](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/input.ts#L114)*

**Returns:** *esto*

___

### `Crear, abstracta,`

*-* **create**(...`args`: []cualquiera

*Definido en [src/comm/input.ts:116](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/input.ts#L116)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `..args` | cualquier otra cosa que no sea[] |

**Returns:** *esto*

___

### deserie

- **deserialize**(`fields`: objeto, `codificación`: [SerializedEncoding](../modules/src_utils.md#serializedencoding)): *vacío*

*Superaciones [StandardParseableInput](common_inputs.standardparseableinput.md).[deserialize](common_inputs.standardparseableinput.md#deserialize)*

*Definido en [src/comm/input.ts:28](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/input.ts#L28)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `campos de cultivo` | objeto de la operación | - |
| `codificación` | [SerializedEncoding](../modules/src_utils.md#serializedencoding) | "hex" |

**Retornos:** *vacío*

___

### deBuffer

- **fromBuffer**(`bytes`: Buffer, `offset`: número): *número*

*Definido en [src/comm/input.ts:80](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/input.ts#L80)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `bytes` | Buffer | - |
| `offset` | Número de números | 0 |

**Retornos:** *número*

___

### getCodecid

- **getCodecid():** *número*

*Heredada de [SigIdx](common_signature.sigidx.md)[.getCodecid](common_signature.sigidx.md#getcodecid)*

*Definido en [src/utils/serialización.ts:59](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/serialization.ts#L59)*

Utilizado en serialización. Opcional. TypeID es un número para el tipo de identificación de objeto que se está saliendo.

**Retornos:** *número*

___

### `Resumen` getCredentialID

- **getCredentialID**(): *número*

*Definido en [src/comm/input.ts:62](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/input.ts#L62)*

**Retornos:** *número*

___

### `Resumen` getInputID

- **getInputID**(): *número*

*Definido en [src/comm/input.ts:55](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/input.ts#L55)*

**Retornos:** *número*

___

### getSigIdxs

- **getSigIdxs**(): *[SigIdx](common_signature.sigidx.md)[]*

*Definido en [src/comm/input.ts:60](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/input.ts#L60)*

Devuelve la matriz de [SigIdx](common_signature.sigidx.md) para esta [entrada](common_inputs.input.md)

**Returns:** *[SigIdx](common_signature.sigidx.md)[]*

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

### `Seleccione abstracto`

- **select**(`id`: número, ...`args`: []cualquier): *[Entrada](common_inputs.input.md)*

*Definido en [src/comm/input.ts:118](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/input.ts#L118)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `I.` | Número de números |
| `..args` | cualquier otra cosa que no sea[] |

**Retornos:** *[Entrada](common_inputs.input.md)*

___

### serializar

- **serialize**(`encoding`: [SerializedEncoding](../modules/src_utils.md#serializedencoding)): *objeto*

*Superaciones [Serializable](utils_serialization.serializable.md).[serialize](utils_serialization.serializable.md#serialize)*

*Definido en [src/comm/input.ts:21](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/input.ts#L21)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `codificación` | [SerializedEncoding](../modules/src_utils.md#serializedencoding) | "hex" |

**Return:** *objeto*

___

### toBuffer

- **toBuffer** (): *Buffer*

*Definido en [src/comm/input.ts:95](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/input.ts#L95)*

**Returns:** *Buffer*

___

### toString

- **toString**(): *string*

*Definido en [src/comm/input.ts:110](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/input.ts#L110)*

Devuelve una representación de base 58 de la [Entrada](common_inputs.input.md).

**Return:** *string*

___

### Comparador `estático`

- **comparator**(): *función*

*Definido en [src/comm/input.ts:41](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/input.ts#L41)*

**Retornos:** *función*

- (`a`: [Entrada](common_inputs.input.md), `b`: [Entrada):](common_inputs.input.md) *1 | -1 | 0*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `a a` | [Entrada](common_inputs.input.md) |
| `b b` | [Entrada](common_inputs.input.md) |
