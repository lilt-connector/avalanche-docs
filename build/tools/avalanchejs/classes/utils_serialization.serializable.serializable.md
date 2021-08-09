[avalancha](../README.md) › [Utils-Serialization](../modules/utils_serialization.md) › [Serializable](utils_serialization.serializable.md)

# Clase: Serializable

## Jerarquía

* **Serializable**

   [m. Credencial](common_signature.credential.md)

   [,,](common_inputs.input.md)

   de la posición [StandardParseableInput](common_inputs.standardparseableinput.md)

   de la marca [EVMStandardBaseTx](common_transactions.evmstandardbasetx.md)

   de [EVMStandardUnsignedTx](common_transactions.evmstandardunsignedtx.md)

   de la marca [EVMStandardTx](common_transactions.evmstandardtx.md)

   de [StandardBaseTx](common_transactions.standardbasetx.md)

   de [StandardUnsignedTx](common_transactions.standardunsignedtx.md)

   de [StandardTx](common_transactions.standardtx.md)

   de [StandardUTXO](common_utxos.standardutxo.md)

   de la norma [StandardUTXOSet](common_utxos.standardutxoset.md)

   [nBytes](common_nbytes.nbytes.md)

   m [OutputOwners](common_output.outputowners.md)

   de salida estándar [StandardParseableOutput](common_output.standardparseableoutput.md)

   de [inicio](api_avm_initialstates.initialstates.md)

   de [la operación](api_avm_operations.operation.md)

   de [la operación transferible](api_avm_operations.transferableoperation.md)

   [minterSet](api_avm_minterset.minterset.md)

   [m.](api_avm_genesisdata.genesisdata.md)

## Índice de participación

### Propiedades de las propiedades

* [_codecid](utils_serialization.serializable.md#protected-_codecid)
* [_typeID](utils_serialization.serializable.md#protected-_typeid)
* [_typeName](utils_serialization.serializable.md#protected-_typename)

### Métodos de trabajo

* [deserie](utils_serialization.serializable.md#deserialize)
* [getCodecid](utils_serialization.serializable.md#getcodecid)
* [getTypeID](utils_serialization.serializable.md#gettypeid)
* [getTypeName](utils_serialization.serializable.md#gettypename)
* [serializar](utils_serialization.serializable.md#serialize)

## Propiedades de las propiedades

### _codecid `protegido`

• **_codecid**: *número* = indefinido.

*Definido en [src/utils/serialización.ts:40](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/serialization.ts#L40)*

___

### `Protegido` _typeID

• **_typeID**: *número* = indefinido.

*Definido en [src/utils/serialización.ts:39](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/serialization.ts#L39)*

___

### _typeName `protegido`

• **_typeName**: *string* = undefined

*Definido en [src/utils/serialización.ts:38](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/serialization.ts#L38)*

## Métodos de trabajo

### deserie

- **deserialize**(`fields`: objeto, `codificación?`: [SerializedEncoding](../modules/utils_serialization.md#serializedencoding)): *void*

*Definido en [src/utils/serialización.ts:72](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/serialization.ts#L72)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `campos de cultivo` | objeto de la operación |
| `¿codificar?` | [SerializedEncoding](../modules/utils_serialization.md#serializedencoding) |

**Retornos:** *vacío*

___

### getCodecid

- **getCodecid():** *número*

*Definido en [src/utils/serialización.ts:59](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/serialization.ts#L59)*

Utilizado en serialización. Opcional. TypeID es un número para el tipo de identificación de objeto que se está saliendo.

**Retornos:** *número*

___

### getTypeID

- **getTypeID**(): *número*

*Definido en [src/utils/serialización.ts:52](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/serialization.ts#L52)*

Utilizado en serialización. Opcional. TypeID es un número para el tipo de identificación de objeto que se está saliendo.

**Retornos:** *número*

___

### getTypeName

- **getTypeName**(): *string*

*Definido en [src/utils/serialización.ts:45](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/serialization.ts#L45)*

Utilizado en serialización. TypeName es un nombre de cadena para el tipo de objeto que se está saliendo.

**Return:** *string*

___

### serializar

- **serialize**(`encoding?`: [SerializedEncoding](../modules/utils_serialization.md#serializedencoding)): *objeto*

*Definido en [src/utils/serialización.ts:65](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/serialization.ts#L65)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `¿codificar?` | [SerializedEncoding](../modules/utils_serialization.md#serializedencoding) |

**Return:** *objeto*
