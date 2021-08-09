[avalancha](../README.md) › [Insumos comunes](../modules/common_inputs.md) › Entrada [StandardParseableInput](common_inputs.standardparseableinput.md)

# Clase: StandardParseableInput

## Jerarquía

* [Serializable](utils_serialization.serializable.md)

   de la posición **StandardParseableInput**

   [m](common_inputs.standardtransferableinput.md)

   de [entrada](api_platformvm_inputs.parseableinput.md)

## Índice de participación

### Constructores

* [constructor](common_inputs.standardparseableinput.md#constructor)

### Propiedades de las propiedades

* [_codecid](common_inputs.standardparseableinput.md#protected-_codecid)
* [_typeID](common_inputs.standardparseableinput.md#protected-_typeid)
* [_typeName](common_inputs.standardparseableinput.md#protected-_typename)
* [entrada en vigor de la entrada](common_inputs.standardparseableinput.md#protected-input)

### Métodos de trabajo

* [deserie](common_inputs.standardparseableinput.md#deserialize)
* [deBuffer](common_inputs.standardparseableinput.md#abstract-frombuffer)
* [getCodecid](common_inputs.standardparseableinput.md#getcodecid)
* [getInput](common_inputs.standardparseableinput.md#getinput)
* [getTypeID](common_inputs.standardparseableinput.md#gettypeid)
* [getTypeName](common_inputs.standardparseableinput.md#gettypename)
* [serializar](common_inputs.standardparseableinput.md#serialize)
* [toBuffer](common_inputs.standardparseableinput.md#tobuffer)
* [comparador](common_inputs.standardparseableinput.md#static-comparator)

## Constructores

### constructor

\+ **nuevo** [StandardParseableInput(input:](common_inputs.input.md)*[ StandardParseableInput(input: Entrada](common_inputs.standardparseableinput.md)* `estándar`

*Definido en [src/comm/input.ts:156](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/input.ts#L156)*

Clase que representa un [StandardParseableInput](common_inputs.standardparseableinput.md) para una transacción.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `entrada en vigor de la entrada` | [Entrada](common_inputs.input.md) | no definido. | Un número que representa la InputID de la Entrada [StandardParseableInput](common_inputs.standardparseableinput.md) |

**Retornos:** *[StandardParseableInput](common_inputs.standardparseableinput.md)*

## Propiedades de las propiedades

### _codecid `protegido`

• **_codecid**: *número* = indefinido.

*Heredada de [SigIdx](common_signature.sigidx.md)[._codecid](common_signature.sigidx.md#protected-_codecid)*

*Definido en [src/utils/serialización.ts:40](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/serialization.ts#L40)*

___

### `Protegido` _typeID

• **_typeID**: *any* = undefined

*Superes [Serializable](utils_serialization.serializable.md).[_typeID](utils_serialization.serializable.md#protected-_typeid)*

*Definido en [src/comm/input.ts:124](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/input.ts#L124)*

___

### _typeName `protegido`

• **_typeName**: *string* = "StandardParseableInput"

*Superes [Serializable](utils_serialization.serializable.md).[_typeName](utils_serialization.serializable.md#protected-_typename)*

*Definido en [src/comm/input.ts:123](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/input.ts#L123)*

___

### Entrada `protegida`

• **entrada**: *[Entrada](common_inputs.input.md)*

*Definido en [src/comm/input.ts:134](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/input.ts#L134)*

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

*Definido en [src/comm/input.ts:148](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/input.ts#L148)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `bytes` | Buffer |
| `¿Qué compensación?` | Número de números |

**Retornos:** *número*

___

### getCodecid

- **getCodecid():** *número*

*Heredada de [SigIdx](common_signature.sigidx.md)[.getCodecid](common_signature.sigidx.md#getcodecid)*

*Definido en [src/utils/serialización.ts:59](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/serialization.ts#L59)*

Utilizado en serialización. Opcional. TypeID es un número para el tipo de identificación de objeto que se está saliendo.

**Retornos:** *número*

___

### getInput

- **getInput**(): *[Entrada](common_inputs.input.md)*

*Definido en [src/comm/input.ts:145](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/input.ts#L145)*

**Retornos:** *[Entrada](common_inputs.input.md)*

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

*Definido en [src/comm/input.ts:126](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/input.ts#L126)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `codificación` | [SerializedEncoding](../modules/src_utils.md#serializedencoding) | "hex" |

**Return:** *objeto*

___

### toBuffer

- **toBuffer** (): *Buffer*

*Definido en [src/comm/input.ts:150](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/input.ts#L150)*

**Returns:** *Buffer*

___

### Comparador `estático`

- **comparator**(): *función*

*Definido en [src/comm/input.ts:139](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/input.ts#L139)*

Devuelve una función utilizada para ordenar una serie de [entradas estándar](common_inputs.standardparseableinput.md)

**Retornos:** *función*

- (`a`: [StandardParseableInput](common_inputs.standardparseableinput.md)[,](common_inputs.standardparseableinput.md) `b`: StandardParseableInput): *1 | -1 | 0*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `a a` | [StandardParseableInput](common_inputs.standardparseableinput.md) |
| `b b` | [StandardParseableInput](common_inputs.standardparseableinput.md) |
