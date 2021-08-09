[avalanche](../README.md) › [API-PlatformVM-UTXOS](../modules/api_platformvm_utxos.md) › [UTXO](api_platformvm_utxos.utxo.md)

# Clase: UTXO

Clase para representar un único UTXO.

## Jerarquía

de [StandardUTXO](common_utxos.standardutxo.md)

de **UTXO**

## Índice de participación

### Constructores

* [constructor](api_platformvm_utxos.utxo.md#constructor)

### Propiedades de las propiedades

* [_codecid](api_platformvm_utxos.utxo.md#protected-_codecid)
* [_typeID](api_platformvm_utxos.utxo.md#protected-_typeid)
* [_typeName](api_platformvm_utxos.utxo.md#protected-_typename)
* [activos](api_platformvm_utxos.utxo.md#protected-assetid)
* [codecid](api_platformvm_utxos.utxo.md#protected-codecid)
* [salida de la salida de la salida](api_platformvm_utxos.utxo.md#protected-output)
* [outputidx](api_platformvm_utxos.utxo.md#protected-outputidx)
* [txid](api_platformvm_utxos.utxo.md#protected-txid)

### Métodos de trabajo

* [clon](api_platformvm_utxos.utxo.md#clone)
* [crear un entorno de creación](api_platformvm_utxos.utxo.md#create)
* [deserie](api_platformvm_utxos.utxo.md#deserialize)
* [deBuffer](api_platformvm_utxos.utxo.md#frombuffer)
* [fromString](api_platformvm_utxos.utxo.md#fromstring)
* [getAssetID](api_platformvm_utxos.utxo.md#getassetid)
* [getCodecid](api_platformvm_utxos.utxo.md#getcodecid)
* [getCodecidBuffer](api_platformvm_utxos.utxo.md#getcodecidbuffer)
* [getOutput](api_platformvm_utxos.utxo.md#getoutput)
* [getOutputIdx](api_platformvm_utxos.utxo.md#getoutputidx)
* [getTxID](api_platformvm_utxos.utxo.md#gettxid)
* [getTypeID](api_platformvm_utxos.utxo.md#gettypeid)
* [getTypeName](api_platformvm_utxos.utxo.md#gettypename)
* [getUTXOID](api_platformvm_utxos.utxo.md#getutxoid)
* [serializar](api_platformvm_utxos.utxo.md#serialize)
* [toBuffer](api_platformvm_utxos.utxo.md#tobuffer)
* [toString](api_platformvm_utxos.utxo.md#tostring)

## Constructores

### constructor

\+ **nuevo UTXO(codecid:**`` número, `txID`: Buffer, `outputidx`: Buffer | número, `assetID`: Buffer, `salida`: [Output](common_output.output.md)): *[UTXO](api_platformvm_utxos.utxo.md)*

*Heredada de [StandardUTXO](common_utxos.standardutxo.md).[constructor](common_utxos.standardutxo.md#constructor)*

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

**Returns:** *[UTXO](api_platformvm_utxos.utxo.md)*

## Propiedades de las propiedades

### _codecid `protegido`

• **_codecid**: *número* = indefinido.

*Heredada de [SigIdx](common_signature.sigidx.md)[._codecid](common_signature.sigidx.md#protected-_codecid)*

*Definido en [src/utils/serialización.ts:40](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/serialization.ts#L40)*

___

### `Protegido` _typeID

• **_typeID**: *any* = undefined

*Overrides [StandardUTXO](common_utxos.standardutxo.md).[_typeID](common_utxos.standardutxo.md#protected-_typeid)*

*Definido en [src/apis/platformvm/utxos.ts:41](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/utxos.ts#L41)*

___

### _typeName `protegido`

• **_typeName**: *string* = "UTXO"

*Overrides [StandardUTXO](common_utxos.standardutxo.md).[_typeName](common_utxos.standardutxo.md#protected-_typename)*

*Definido en [src/apis/platformvm/utxos.ts:40](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/utxos.ts#L40)*

___

### assetID `protegido`

• **assetID**: *Buffer* = Buffer.aloc(32)

*Heredada de [StandardUTXO](common_utxos.standardutxo.md).[assetID](common_utxos.standardutxo.md#protected-assetid)*

*Definido en [src/comm/utxos.ts:49](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/utxos.ts#L49)*

___

### Codecido `protegido`

• **codecidido**: *Buffer* = Buffer.aloc(2)

*Heredada de [StandardUTXO](common_utxos.standardutxo.md)[.codecid](common_utxos.standardutxo.md#protected-codecid)*

*Definido en [src/comm/utxos.ts:46](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/utxos.ts#L46)*

___

### Producción `protegida`

• **salida**: *[Salida](common_output.output.md)* = indefinida

*Heredada de [StandardUTXO](common_utxos.standardutxo.md).[output](common_utxos.standardutxo.md#protected-output).*

*Definido en [src/comm/utxos.ts:50](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/utxos.ts#L50)*

___

### outputidx `protegido`

• **outputidx**: *Buffer* = Buffer.aloc(4)

*Heredada de [StandardUTXO](common_utxos.standardutxo.md).[outputidx](common_utxos.standardutxo.md#protected-outputidx)*

*Definido en [src/comm/utxos.ts:48](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/utxos.ts#L48)*

___

### Txid `protegido`

• **txid**: *Buffer* = Buffer.aloc(32)

*Heredada de [StandardUTXO](common_utxos.standardutxo.md).[txid](common_utxos.standardutxo.md#protected-txid)*

*Definido en [src/comm/utxos.ts:47](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/utxos.ts#L47)*

## Métodos de trabajo

### clon

- **clone**(): *esto*

*Superaciones [StandardUTXO](common_utxos.standardutxo.md).[clone](common_utxos.standardutxo.md#abstract-clone)*

*Definido en [src/apis/platformvm/utxos.ts:92](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/utxos.ts#L92)*

**Returns:** *esto*

___

### crear un entorno de creación

- **create**`(codecid`: número, `txid`: Buffer, `outputidx`: Buffer | número, `assetID`: Buffer, `salida`: [Output](common_output.output.md)): *this*

*Overrides [StandardUTXO](common_utxos.standardutxo.md).[create](common_utxos.standardutxo.md#abstract-create)*

*Definido en [src/apis/platformvm/utxos.ts:98](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/utxos.ts#L98)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `codecid` | Número de números | PlatformVMConstants.LATESTCODEC PlatformVMConstants.LATESTCODEC |
| `txid` | Buffer | no definido. |
| `outputidx` | Buffer &#124; número | no definido. |
| `activos` | Buffer | no definido. |
| `salida de la salida de la salida` | [Producción de productos](common_output.output.md) | no definido. |

**Returns:** *esto*

___

### deserie

- **deserialize**(`fields`: objeto, `codificación`: [SerializedEncoding](../modules/src_utils.md#serializedencoding)): *vacío*

*Overrides [StandardUTXO](common_utxos.standardutxo.md).[deserialize](common_utxos.standardutxo.md#deserialize)*

*Definido en [src/apis/platformvm/utxos.ts:45](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/utxos.ts#L45)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `campos de cultivo` | objeto de la operación | - |
| `codificación` | [SerializedEncoding](../modules/src_utils.md#serializedencoding) | "hex" |

**Retornos:** *vacío*

___

### deBuffer

- **fromBuffer**(`bytes`: Buffer, `offset`: número): *número*

*Overrides [StandardUTXO](common_utxos.standardutxo.md).[fromBuffer](common_utxos.standardutxo.md#abstract-frombuffer)*

*Definido en [src/apis/platformvm/utxos.ts:51](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/utxos.ts#L51)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `bytes` | Buffer | - |
| `offset` | Número de números | 0 |

**Retornos:** *número*

___

### fromString

- **fromString**(`serialized`: string): *número*

*Overrides [StandardUTXO](common_utxos.standardutxo.md).[fromString](common_utxos.standardutxo.md#abstract-fromstring)*

*Definido en [src/apis/platformvm/utxos.ts:76](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/utxos.ts#L76)*

Toma una cadena base-58 que contiene un [UTXO](api_platformvm_utxos.utxo.md), la analiza, populates la clase, y devuelve la longitud de la StandardUTXO en bytes.

**`observaciones sobre las observaciones formuladas`** a diferencia de la mayoría de las cadenas de Strings, espera que la cadena se serializa en formato cb58

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `serializado` | cadena de producción | Una cadena base-58 que contiene [UTXO](api_platformvm_utxos.utxo.md) cruda |

**Retornos:** *número*

La longitud de la [UTXO](api_platformvm_utxos.utxo.md) cruda

___

### getAssetID

- **getAssetID**(): *Buffer*

*Heredada de [StandardUTXO](common_utxos.standardutxo.md).[getAssetID](common_utxos.standardutxo.md#getassetid)*

*Definido en [src/comm/utxos.ts:81](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/utxos.ts#L81)*

Devuelve el activo como [Buffer](https://github.com/feross/buffer).

**Returns:** *Buffer*

___

### getCodecid

- **getCodecid():** *número*

*Heredada de [StandardUTXO](common_utxos.standardutxo.md)[.getCodecid](common_utxos.standardutxo.md#getcodecid)*

*Overrides [SigIdx](common_signature.sigidx.md)[.getCodecid](common_signature.sigidx.md#getcodecid)*

*Definido en [src/comm/utxos.ts:55](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/utxos.ts#L55)*

Devuelve la representación numérica del Codecid.

**Retornos:** *número*

___

### getCodecidBuffer

- **getCodecidBuffer():** *Buffer*

*Heredado de [StandardUTXO](common_utxos.standardutxo.md)[.getCodecidBuffer](common_utxos.standardutxo.md#getcodecidbuffer)*

*Definido en [src/comm/utxos.ts:62](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/utxos.ts#L62)*

Devuelve la representación de [Buffer](https://github.com/feross/buffer) del Codecid

**Returns:** *Buffer*

___

### getOutput

- **getOutput**(): *[Producto](common_output.output.md)*

*Heredada de [StandardUTXO](common_utxos.standardutxo.md).[getOutput](common_utxos.standardutxo.md#getoutput)*

*Definido en [src/comm/utxos.ts:93](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/utxos.ts#L93)*

Devuelve una referencia a la salida

**Retornos:** *[Salida](common_output.output.md)*

___

### getOutputIdx

- **getOutputIdx**(): *Buffer*

*Heredada de [StandardUTXO](common_utxos.standardutxo.md).[getOutputIdx](common_utxos.standardutxo.md#getoutputidx)*

*Definido en [src/comm/utxos.ts:74](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/utxos.ts#L74)*

Devuelve un [buffer](https://github.com/feross/buffer) de la OutputIdx.

**Returns:** *Buffer*

___

### getTxID

- **getTxID**(): *Buffer*

*Heredada de [StandardUTXO](common_utxos.standardutxo.md).[getTxID](common_utxos.standardutxo.md#gettxid)*

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

*Heredada de [StandardUTXO](common_utxos.standardutxo.md).[getUTXOID](common_utxos.standardutxo.md#getutxoid)*

*Definido en [src/comm/utxos.ts:86](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/utxos.ts#L86)*

Devuelve el UTXOID como una cadena base-58 (UTXOID es una cadena )

**Return:** *string*

___

### serializar

- **serialize**(`encoding`: [SerializedEncoding](../modules/src_utils.md#serializedencoding)): *objeto*

*Heredada de [StandardUTXO](common_utxos.standardutxo.md).[serialize](common_utxos.standardutxo.md#serialize)*

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

*Heredada de [StandardUTXO](common_utxos.standardutxo.md).[toBuffer](common_utxos.standardutxo.md#tobuffer)*

*Definido en [src/comm/utxos.ts:105](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/utxos.ts#L105)*

Devuelve una representación de [Buffer](https://github.com/feross/buffer) de la [StandardUTXO](common_utxos.standardutxo.md).

**Returns:** *Buffer*

___

### toString

- **toString**(): *string*

*Overrides [StandardUTXO](common_utxos.standardutxo.md).[toString](common_utxos.standardutxo.md#abstract-tostring)*

*Definido en [src/apis/platformvm/utxos.ts:87](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/utxos.ts#L87)*

Devuelve una representación de base 58 de [UTXO](api_platformvm_utxos.utxo.md).

**`observaciones sobre las observaciones formuladas`** a diferencia de la mayoría de toStrings, esto devuelve en formato de serialización cb58

**Return:** *string*
