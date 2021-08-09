[avalancha](../README.md) › [Common-UTXOs](../modules/common_utxos.md) › [StandardUTXO](common_utxos.standardutxo.md)

# Clase: StandardUTXO

Clase para representar un solo StandardUTXO.

## Jerarquía

* [Serializable](utils_serialization.serializable.md)

   de **StandardUTXO**

   de [UTXO](api_platformvm_utxos.utxo.md)

   de [UTXO](api_avm_utxos.utxo.md)

   de [UTXO](api_evm_utxos.utxo.md)

## Índice de participación

### Constructores

* [constructor](common_utxos.standardutxo.md#constructor)

### Propiedades de las propiedades

* [_codecid](common_utxos.standardutxo.md#protected-_codecid)
* [_typeID](common_utxos.standardutxo.md#protected-_typeid)
* [_typeName](common_utxos.standardutxo.md#protected-_typename)
* [activos](common_utxos.standardutxo.md#protected-assetid)
* [codecid](common_utxos.standardutxo.md#protected-codecid)
* [salida de la salida de la salida](common_utxos.standardutxo.md#protected-output)
* [outputidx](common_utxos.standardutxo.md#protected-outputidx)
* [txid](common_utxos.standardutxo.md#protected-txid)

### Métodos de trabajo

* [clon](common_utxos.standardutxo.md#abstract-clone)
* [crear un entorno de creación](common_utxos.standardutxo.md#abstract-create)
* [deserie](common_utxos.standardutxo.md#deserialize)
* [deBuffer](common_utxos.standardutxo.md#abstract-frombuffer)
* [fromString](common_utxos.standardutxo.md#abstract-fromstring)
* [getAssetID](common_utxos.standardutxo.md#getassetid)
* [getCodecid](common_utxos.standardutxo.md#getcodecid)
* [getCodecidBuffer](common_utxos.standardutxo.md#getcodecidbuffer)
* [getOutput](common_utxos.standardutxo.md#getoutput)
* [getOutputIdx](common_utxos.standardutxo.md#getoutputidx)
* [getTxID](common_utxos.standardutxo.md#gettxid)
* [getTypeID](common_utxos.standardutxo.md#gettypeid)
* [getTypeName](common_utxos.standardutxo.md#gettypename)
* [getUTXOID](common_utxos.standardutxo.md#getutxoid)
* [serializar](common_utxos.standardutxo.md#serialize)
* [toBuffer](common_utxos.standardutxo.md#tobuffer)
* [toString](common_utxos.standardutxo.md#abstract-tostring)

## Constructores

### constructor

\+ **nuevo** `StandardUTXO(codecid`: número, `txID`: Buffer, `outputidx`: Buffer | número, `assetID`: Buffer, `salida`: [Salida):](common_output.output.md) *[StandardUTXO](common_utxos.standardutxo.md)*

*Definido en [src/comm/utxos.ts:125](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/utxos.ts#L125)*

Clase para representar un solo StandardUTXO.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `codecid` | Número de números | 0 | Número opcional que especifica el código de identificación de UTXO. Predeterminado 0 |
| `txID` | Buffer | no definido. | [Buffer](https://github.com/feross/buffer) opcional de identificación de transacción para el StandardUTXO |
| `outputidx` | Buffer &#124; número | no definido. | - |
| `activos` | Buffer | no definido. | [Buffer](https://github.com/feross/buffer) opcional del ID de activos para el StandardUTXO |
| `salida de la salida de la salida` | [Producción de productos](common_output.output.md) | no definido. | - |

**Returns:** *[StandardUTXO](common_utxos.standardutxo.md)*

## Propiedades de las propiedades

### _codecid `protegido`

• **_codecid**: *número* = indefinido.

*Heredada de [SigIdx](common_signature.sigidx.md)[._codecid](common_signature.sigidx.md#protected-_codecid)*

*Definido en [src/utils/serialización.ts:40](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/serialization.ts#L40)*

___

### `Protegido` _typeID

• **_typeID**: *any* = undefined

*Superes [Serializable](utils_serialization.serializable.md).[_typeID](utils_serialization.serializable.md#protected-_typeid)*

*Definido en [src/comm/utxos.ts:25](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/utxos.ts#L25)*

___

### _typeName `protegido`

• **_typeName**: *string* = "StandardUTXO"

*Superes [Serializable](utils_serialization.serializable.md).[_typeName](utils_serialization.serializable.md#protected-_typename)*

*Definido en [src/comm/utxos.ts:24](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/utxos.ts#L24)*

___

### assetID `protegido`

• **assetID**: *Buffer* = Buffer.aloc(32)

*Definido en [src/comm/utxos.ts:49](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/utxos.ts#L49)*

___

### Codecido `protegido`

• **codecidido**: *Buffer* = Buffer.aloc(2)

*Definido en [src/comm/utxos.ts:46](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/utxos.ts#L46)*

___

### Producción `protegida`

• **salida**: *[Salida](common_output.output.md)* = indefinida

*Definido en [src/comm/utxos.ts:50](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/utxos.ts#L50)*

___

### outputidx `protegido`

• **outputidx**: *Buffer* = Buffer.aloc(4)

*Definido en [src/comm/utxos.ts:48](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/utxos.ts#L48)*

___

### Txid `protegido`

• **txid**: *Buffer* = Buffer.aloc(32)

*Definido en [src/comm/utxos.ts:47](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/utxos.ts#L47)*

## Métodos de trabajo

### Clon `abstracto`

- **clone**(): *esto*

*Definido en [src/comm/utxos.ts:120](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/utxos.ts#L120)*

**Returns:** *esto*

___

### `Crear, abstracta,`

- **create**`(codecid?`: número, `txid?`: Buffer, `outputidx?`: Buffer | número, `assetID?`: Buffer, `salida?`: [Output](common_output.output.md)): *this*

*Definido en [src/comm/utxos.ts:122](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/utxos.ts#L122)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `codecidido?` | Número de números |
| `¿Txid?` | Buffer |
| `¿Outputidx?` | Buffer &#124; número |
| `assetID?` | Buffer |
| `¿salida?` | [Producción de productos](common_output.output.md) |

**Returns:** *esto*

___

### deserie

- **deserialize**(`fields`: objeto, `codificación`: [SerializedEncoding](../modules/src_utils.md#serializedencoding)): *vacío*

*Superaciones [StandardParseableInput](common_inputs.standardparseableinput.md).[deserialize](common_inputs.standardparseableinput.md#deserialize)*

*Definido en [src/comm/utxos.ts:38](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/utxos.ts#L38)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `campos de cultivo` | objeto de la operación | - |
| `codificación` | [SerializedEncoding](../modules/src_utils.md#serializedencoding) | "hex" |

**Retornos:** *vacío*

___

### `Resumen` deBuffer

- **fromBuffer**(`bytes`: Buffer, `offset?`: número): *número*

*Definido en [src/comm/utxos.ts:100](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/utxos.ts#L100)*

Toma un [buffer](https://github.com/feross/buffer) que contiene un [StandardUTXO](common_utxos.standardutxo.md), lo analiza, populates la clase y devuelve la longitud de la StandardUTXO en bytes.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `bytes` | Buffer | Un [buffer](https://github.com/feross/buffer) que contiene un [estándar](common_utxos.standardutxo.md) bruto |
| `¿Qué compensación?` | Número de números | - |

**Retornos:** *número*

___

### `Resumen` fromString

- **fromString**(`serialized`: string): *número*

*Definido en [src/comm/utxos.ts:116](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/utxos.ts#L116)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `serializado` | cadena de producción |

**Retornos:** *número*

___

### getAssetID

- **getAssetID**(): *Buffer*

*Definido en [src/comm/utxos.ts:81](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/utxos.ts#L81)*

Devuelve el activo como [Buffer](https://github.com/feross/buffer).

**Returns:** *Buffer*

___

### getCodecid

- **getCodecid():** *número*

*Overrides [SigIdx](common_signature.sigidx.md)[.getCodecid](common_signature.sigidx.md#getcodecid)*

*Definido en [src/comm/utxos.ts:55](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/utxos.ts#L55)*

Devuelve la representación numérica del Codecid.

**Retornos:** *número*

___

### getCodecidBuffer

- **getCodecidBuffer():** *Buffer*

*Definido en [src/comm/utxos.ts:62](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/utxos.ts#L62)*

Devuelve la representación de [Buffer](https://github.com/feross/buffer) del Codecid

**Returns:** *Buffer*

___

### getOutput

- **getOutput**(): *[Producto](common_output.output.md)*

*Definido en [src/comm/utxos.ts:93](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/utxos.ts#L93)*

Devuelve una referencia a la salida

**Retornos:** *[Salida](common_output.output.md)*

___

### getOutputIdx

- **getOutputIdx**(): *Buffer*

*Definido en [src/comm/utxos.ts:74](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/utxos.ts#L74)*

Devuelve un [buffer](https://github.com/feross/buffer) de la OutputIdx.

**Returns:** *Buffer*

___

### getTxID

- **getTxID**(): *Buffer*

*Definido en [src/comm/utxos.ts:67](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/utxos.ts#L67)*

Devuelve un [Buffer](https://github.com/feross/buffer) del TxID.

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

### getUTXOID

- **getUTXOID**(): *string*

*Definido en [src/comm/utxos.ts:86](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/utxos.ts#L86)*

Devuelve el UTXOID como una cadena base-58 (UTXOID es una cadena )

**Return:** *string*

___

### serializar

- **serialize**(`encoding`: [SerializedEncoding](../modules/src_utils.md#serializedencoding)): *objeto*

*Superaciones [Serializable](utils_serialization.serializable.md).[serialize](utils_serialization.serializable.md#serialize)*

*Definido en [src/comm/utxos.ts:27](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/utxos.ts#L27)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `codificación` | [SerializedEncoding](../modules/src_utils.md#serializedencoding) | "hex" |

**Return:** *objeto*

___

### toBuffer

- **toBuffer** (): *Buffer*

*Definido en [src/comm/utxos.ts:105](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/utxos.ts#L105)*

Devuelve una representación de [Buffer](https://github.com/feross/buffer) de la [StandardUTXO](common_utxos.standardutxo.md).

**Returns:** *Buffer*

___

### `Resumen` toString

- **toString**(): *string*

*Definido en [src/comm/utxos.ts:118](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/utxos.ts#L118)*

**Return:** *string*
