[avalanche](../README.md) › [API-PlatformVM-Inputs](../modules/api_platformvm_inputs.md) › [ParseableInput](api_platformvm_inputs.parseableinput.md)

# Clase: Entrada ParseableInput

## Jerarquía

de la posición [StandardParseableInput](common_inputs.standardparseableinput.md)

de **entrada**

## Índice de participación

### Constructores

* [constructor](api_platformvm_inputs.parseableinput.md#constructor)

### Propiedades de las propiedades

* [_codecid](api_platformvm_inputs.parseableinput.md#protected-_codecid)
* [_typeID](api_platformvm_inputs.parseableinput.md#protected-_typeid)
* [_typeName](api_platformvm_inputs.parseableinput.md#protected-_typename)
* [entrada en vigor de la entrada](api_platformvm_inputs.parseableinput.md#protected-input)

### Métodos de trabajo

* [deserie](api_platformvm_inputs.parseableinput.md#deserialize)
* [deBuffer](api_platformvm_inputs.parseableinput.md#frombuffer)
* [getCodecid](api_platformvm_inputs.parseableinput.md#getcodecid)
* [getInput](api_platformvm_inputs.parseableinput.md#getinput)
* [getTypeID](api_platformvm_inputs.parseableinput.md#gettypeid)
* [getTypeName](api_platformvm_inputs.parseableinput.md#gettypename)
* [serializar](api_platformvm_inputs.parseableinput.md#serialize)
* [toBuffer](api_platformvm_inputs.parseableinput.md#tobuffer)
* [comparador](api_platformvm_inputs.parseableinput.md#static-comparator)

## Constructores

### constructor

\+ **nuevo** `ParseableInput(input`[:](common_inputs.input.md) Entrada: *[Entrada](api_platformvm_inputs.parseableinput.md)* ParseableInput(input:

*Heredado de [StandardParseableInput](common_inputs.standardparseableinput.md).[constructor](common_inputs.standardparseableinput.md#constructor)*

*Definido en [src/comm/input.ts:156](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/input.ts#L156)*

Clase que representa un [StandardParseableInput](common_inputs.standardparseableinput.md) para una transacción.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `entrada en vigor de la entrada` | [Entrada](common_inputs.input.md) | no definido. | Un número que representa la InputID de la Entrada [StandardParseableInput](common_inputs.standardparseableinput.md) |

**Retornos:** Entrada *[ParseableInput](api_platformvm_inputs.parseableinput.md)*

## Propiedades de las propiedades

### _codecid `protegido`

• **_codecid**: *número* = indefinido.

*Heredada de [SigIdx](common_signature.sigidx.md)[._codecid](common_signature.sigidx.md#protected-_codecid)*

*Definido en [src/utils/serialización.ts:40](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/serialization.ts#L40)*

___

### `Protegido` _typeID

• **_typeID**: *any* = undefined

*Superaciones [StandardParseableInput](common_inputs.standardparseableinput.md).[_typeID](common_inputs.standardparseableinput.md#protected-_typeid)*

*Definido en [src/apis/platformvm/inputs.ts:38](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/inputs.ts#L38)*

___

### _typeName `protegido`

• **_typeName**: *string* = "ParseableInput"

*Overrides [StandardParseableInput](common_inputs.standardparseableinput.md).[_typeName](common_inputs.standardparseableinput.md#protected-_typename)*

*Definido en [src/apis/platformvm/inputs.ts:37](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/inputs.ts#L37)*

___

### Entrada `protegida`

• **entrada**: *[Entrada](common_inputs.input.md)*

*Heredado de [StandardParseableInput](common_inputs.standardparseableinput.md).[input](common_inputs.standardparseableinput.md#protected-input)*

*Definido en [src/comm/input.ts:134](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/input.ts#L134)*

## Métodos de trabajo

### deserie

- **deserialize**(`fields`: objeto, `codificación`: [SerializedEncoding](../modules/src_utils.md#serializedencoding)): *vacío*

*Superaciones [StandardParseableInput](common_inputs.standardparseableinput.md).[deserialize](common_inputs.standardparseableinput.md#deserialize)*

*Definido en [src/apis/platformvm/inputs.ts:42](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/inputs.ts#L42)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `campos de cultivo` | objeto de la operación | - |
| `codificación` | [SerializedEncoding](../modules/src_utils.md#serializedencoding) | "hex" |

**Retornos:** *vacío*

___

### deBuffer

- **fromBuffer**(`bytes`: Buffer, `offset`: número): *número*

*Overrides [StandardParseableInput](common_inputs.standardparseableinput.md).[fromBuffer](common_inputs.standardparseableinput.md#abstract-frombuffer)*

*Definido en [src/apis/platformvm/inputs.ts:48](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/inputs.ts#L48)*

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

### getInput

- **getInput**(): *[Entrada](common_inputs.input.md)*

*Heredado de [StandardParseableInput](common_inputs.standardparseableinput.md).[getInput](common_inputs.standardparseableinput.md#getinput)*

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

*Heredado de [StandardParseableInput](common_inputs.standardparseableinput.md).[serialize](common_inputs.standardparseableinput.md#serialize)*

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

*Heredado de [StandardParseableInput](common_inputs.standardparseableinput.md).[toBuffer](common_inputs.standardparseableinput.md#tobuffer)*

*Definido en [src/comm/input.ts:150](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/input.ts#L150)*

**Returns:** *Buffer*

___

### Comparador `estático`

- **comparator**(): *función*

*Heredado de [StandardParseableInput](common_inputs.standardparseableinput.md).[comparator](common_inputs.standardparseableinput.md#static-comparator)*

*Definido en [src/comm/input.ts:139](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/input.ts#L139)*

Devuelve una función utilizada para ordenar una serie de [entradas estándar](common_inputs.standardparseableinput.md)

**Retornos:** *función*

- (`a`: [StandardParseableInput](common_inputs.standardparseableinput.md)[,](common_inputs.standardparseableinput.md) `b`: StandardParseableInput): *1 | -1 | 0*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `a a` | [StandardParseableInput](common_inputs.standardparseableinput.md) |
| `b b` | [StandardParseableInput](common_inputs.standardparseableinput.md) |
