[avalancha](../README.md) › [API-AVM-InitialStates](../modules/api_avm_initialstates.md) › [InitialStates](api_avm_initialstates.initialstates.md)

# Clase: Estados iniciales:

Clase para crear estados de salida iniciales utilizados en la creación de activos

## Jerarquía

* [Serializable](utils_serialization.serializable.md)

   de **inicio**

## Índice de participación

### Propiedades de las propiedades

* [_codecid](api_avm_initialstates.initialstates.md#protected-_codecid)
* [_typeID](api_avm_initialstates.initialstates.md#protected-_typeid)
* [_typeName](api_avm_initialstates.initialstates.md#protected-_typename)
* [fxs](api_avm_initialstates.initialstates.md#protected-fxs)

### Métodos de trabajo

* [addOutput](api_avm_initialstates.initialstates.md#addoutput)
* [deserie](api_avm_initialstates.initialstates.md#deserialize)
* [deBuffer](api_avm_initialstates.initialstates.md#frombuffer)
* [getCodecid](api_avm_initialstates.initialstates.md#getcodecid)
* [getTypeID](api_avm_initialstates.initialstates.md#gettypeid)
* [getTypeName](api_avm_initialstates.initialstates.md#gettypename)
* [serializar](api_avm_initialstates.initialstates.md#serialize)
* [toBuffer](api_avm_initialstates.initialstates.md#tobuffer)

## Propiedades de las propiedades

### _codecid `protegido`

• **_codecid**: *número* = indefinido.

*Heredada de [SigIdx](common_signature.sigidx.md)[._codecid](common_signature.sigidx.md#protected-_codecid)*

*Definido en [src/utils/serialización.ts:40](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/serialization.ts#L40)*

___

### `Protegido` _typeID

• **_typeID**: *any* = undefined

*Superes [Serializable](utils_serialization.serializable.md).[_typeID](utils_serialization.serializable.md#protected-_typeid)*

*Definido en [src/apis/avm/iniciales.ts:22](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/initialstates.ts#L22)*

___

### _typeName `protegido`

• **_typeName**: *string* = "InitialStates"

*Superes [Serializable](utils_serialization.serializable.md).[_typeName](utils_serialization.serializable.md#protected-_typename)*

*Definido en [src/apis/avm/iniciales.ts:21](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/initialstates.ts#L21)*

___

### Fxs `protegidos`

• **fxs**: *objeto*

*Definido en [src/apis/avm/iniciales.ts:48](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/initialstates.ts#L48)*

#### Declaración de tipo:

* \[ **fxid**: *número\]:* [Salida](common_output.output.md)[]

## Métodos de trabajo

### addOutput

- **addOutput**(`out`: [Output](common_output.output.md), `fxid`: número): *vacío*

*Definido en [src/apis/avm/iniciales.ts:55](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/initialstates.ts#L55)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `Fuera de la zona` | [Producción de productos](common_output.output.md) | - | El estado de salida a añadir a la colección |
| `fxid` | Número de números | AVMConstants.SECPFXID AVMConstants.SECPFXID | El FxID que se utilizará para esta salida, AVMConstants.SECPFXID |

**Retornos:** *vacío*

___

### deserie

- **deserialize**(`fields`: objeto, `codificación`: [SerializedEncoding](../modules/src_utils.md#serializedencoding)): *vacío*

*Superaciones [StandardParseableInput](common_inputs.standardparseableinput.md).[deserialize](common_inputs.standardparseableinput.md#deserialize)*

*Definido en [src/apis/avm/iniciales.ts:35](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/initialstates.ts#L35)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `campos de cultivo` | objeto de la operación | - |
| `codificación` | [SerializedEncoding](../modules/src_utils.md#serializedencoding) | "hex" |

**Retornos:** *vacío*

___

### deBuffer

- **fromBuffer**(`bytes`: Buffer, `offset`: número): *número*

*Definido en [src/apis/avm/iniciales.ts:62](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/initialstates.ts#L62)*

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

*Definido en [src/apis/avm/iniciales.ts:24](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/initialstates.ts#L24)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `codificación` | [SerializedEncoding](../modules/src_utils.md#serializedencoding) | "hex" |

**Return:** *objeto*

___

### toBuffer

- **toBuffer** (): *Buffer*

*Definido en [src/apis/avm/iniciales.ts:87](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/initialstates.ts#L87)*

**Returns:** *Buffer*
