[avalancha](../README.md) › [API-AVM-MinterSet](../modules/api_avm_minterset.md) › [MinterSet](api_avm_minterset.minterset.md)

# Clase: MinterSet

Clase para representar un umbral y conjunto de direcciones de menta en Avalanche.

**`typeparam`** incluyendo un umbral y una serie de direcciones

## Jerarquía

* [Serializable](utils_serialization.serializable.md)

   **minterSet**

## Índice de participación

### Constructores

* [constructor](api_avm_minterset.minterset.md#constructor)

### Propiedades de las propiedades

* [_codecid](api_avm_minterset.minterset.md#protected-_codecid)
* [_typeID](api_avm_minterset.minterset.md#protected-_typeid)
* [_typeName](api_avm_minterset.minterset.md#protected-_typename)
* [minters](api_avm_minterset.minterset.md#protected-minters)
* [umbral](api_avm_minterset.minterset.md#protected-threshold)

### Métodos de trabajo

* [_cleanAddresses](api_avm_minterset.minterset.md#protected-_cleanaddresses)
* [deserie](api_avm_minterset.minterset.md#deserialize)
* [getCodecid](api_avm_minterset.minterset.md#getcodecid)
* [getMinters](api_avm_minterset.minterset.md#getminters)
* [getThreshold](api_avm_minterset.minterset.md#getthreshold)
* [getTypeID](api_avm_minterset.minterset.md#gettypeid)
* [getTypeName](api_avm_minterset.minterset.md#gettypename)
* [serializar](api_avm_minterset.minterset.md#serialize)

## Constructores

### constructor

\+ **nuevo MinterSet(threshold:**`` número, `mineros`: string []| []Buffer): *[MinterSet](api_avm_minterset.minterset.md)*

*Definido en [src/apis/avm/minterset.ts:70](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/minterset.ts#L70)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `umbral` | Número de números | 1 1 | El número de firmas necesarias para mintar más de un activo mediante la firma de una operación de minado |
| `minters` | string[] &#124; Buffer[] | [] | Conjunto de direcciones autorizadas para firmar una operación de menta. |

**Retorno:** *[MinterSet](api_avm_minterset.minterset.md)*

## Propiedades de las propiedades

### _codecid `protegido`

• **_codecid**: *número* = indefinido.

*Heredada de [SigIdx](common_signature.sigidx.md)[._codecid](common_signature.sigidx.md#protected-_codecid)*

*Definido en [src/utils/serialización.ts:40](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/serialization.ts#L40)*

___

### `Protegido` _typeID

• **_typeID**: *any* = undefined

*Superes [Serializable](utils_serialization.serializable.md).[_typeID](utils_serialization.serializable.md#protected-_typeid)*

*Definido en [src/apis/avm/minterset.ts:27](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/minterset.ts#L27)*

___

### _typeName `protegido`

• **_typeName**: *string* = "MinterSet"

*Superes [Serializable](utils_serialization.serializable.md).[_typeName](utils_serialization.serializable.md#protected-_typename)*

*Definido en [src/apis/avm/minterset.ts:26](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/minterset.ts#L26)*

___

### Mineros `protegidos`

• **mineros**: *Buffer[]* =[]

*Definido en [src/apis/avm/minterset.ts:44](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/minterset.ts#L44)*

___

### Umbral `protegido`

• **umbral**: *número*

*Definido en [src/apis/avm/minterset.ts:43](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/minterset.ts#L43)*

## Métodos de trabajo

### _cleanAddresses `protegidos`

- **_cleanAddresses**(`addresses`: string []| []Buffer): *Buffer[]*

*Definido en [src/apis/avm/minterset.ts:60](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/minterset.ts#L60)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `direcciones` | string[] &#124; Buffer[] |

**Returns:** *Buffer[]*

___

### deserie

- **deserialize**(`fields`: objeto, `codificación`: [SerializedEncoding](../modules/src_utils.md#serializedencoding)): *vacío*

*Superaciones [StandardParseableInput](common_inputs.standardparseableinput.md).[deserialize](common_inputs.standardparseableinput.md#deserialize)*

*Definido en [src/apis/avm/minterset.ts:37](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/minterset.ts#L37)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `campos de cultivo` | objeto de la operación | - |
| `codificación` | [SerializedEncoding](../modules/src_utils.md#serializedencoding) | "hex" |

**Retornos:** *vacío*

___

### getCodecid

- **getCodecid():** *número*

*Heredada de [SigIdx](common_signature.sigidx.md)[.getCodecid](common_signature.sigidx.md#getcodecid)*

*Definido en [src/utils/serialización.ts:59](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/serialization.ts#L59)*

Utilizado en serialización. Opcional. TypeID es un número para el tipo de identificación de objeto que se está saliendo.

**Retornos:** *número*

___

### getMinters

- **getMinters**(): *Buffer[]*

*Definido en [src/apis/avm/minterset.ts:56](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/minterset.ts#L56)*

Devuelve a los mineros.

**Returns:** *Buffer[]*

___

### getThreshold

- **getThreshold**(): *número*

*Definido en [src/apis/avm/minterset.ts:49](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/minterset.ts#L49)*

Devuelve el umbral.

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

*Definido en [src/apis/avm/minterset.ts:29](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/minterset.ts#L29)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `codificación` | [SerializedEncoding](../modules/src_utils.md#serializedencoding) | "hex" |

**Return:** *objeto*
