[avalancha](../README.md) › [Insumos comunes](../modules/common_inputs.md) › Entrada [StandardTransferableInput](common_inputs.standardtransferableinput.md)

# Clase: Entrada Class:

## Jerarquía

de la posición [StandardParseableInput](common_inputs.standardparseableinput.md)

**m**

de [entrada transferible](api_platformvm_inputs.transferableinput.md)

de [entrada transferible](api_avm_inputs.transferableinput.md)

de [entrada transferible](api_evm_inputs.transferableinput.md)

## Índice de participación

### Constructores

* [constructor](common_inputs.standardtransferableinput.md#constructor)

### Propiedades de las propiedades

* [_codecid](common_inputs.standardtransferableinput.md#protected-_codecid)
* [_typeID](common_inputs.standardtransferableinput.md#protected-_typeid)
* [_typeName](common_inputs.standardtransferableinput.md#protected-_typename)
* [activos](common_inputs.standardtransferableinput.md#protected-assetid)
* [entrada en vigor de la entrada](common_inputs.standardtransferableinput.md#protected-input)
* [outputidx](common_inputs.standardtransferableinput.md#protected-outputidx)
* [txid](common_inputs.standardtransferableinput.md#protected-txid)

### Métodos de trabajo

* [deserie](common_inputs.standardtransferableinput.md#deserialize)
* [deBuffer](common_inputs.standardtransferableinput.md#abstract-frombuffer)
* [getAssetID](common_inputs.standardtransferableinput.md#getassetid)
* [getCodecid](common_inputs.standardtransferableinput.md#getcodecid)
* [getInput](common_inputs.standardtransferableinput.md#getinput)
* [getOutputIdx](common_inputs.standardtransferableinput.md#getoutputidx)
* [getTxID](common_inputs.standardtransferableinput.md#gettxid)
* [getTypeID](common_inputs.standardtransferableinput.md#gettypeid)
* [getTypeName](common_inputs.standardtransferableinput.md#gettypename)
* [getUTXOID](common_inputs.standardtransferableinput.md#getutxoid)
* [serializar](common_inputs.standardtransferableinput.md#serialize)
* [toBuffer](common_inputs.standardtransferableinput.md#tobuffer)
* [toString](common_inputs.standardtransferableinput.md#tostring)
* [comparador](common_inputs.standardtransferableinput.md#static-comparator)

## Constructores

### constructor

\+ **nuevo** [StandardTransferableInput(txid:](common_inputs.input.md)`` Buffer, `outputidx`: Buffer, `assetID`: Buffer, `entrada`: Entrada): *[Entrada StandardTransferableInput](common_inputs.standardtransferableinput.md)*

*Superadas [StandardParseableInput](common_inputs.standardparseableinput.md).[constructor](common_inputs.standardparseableinput.md#constructor)*

*Definido en [src/comm/input.ts:244](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/input.ts#L244)*

Clase que representa una entrada estándar [StandardTransferableInput](common_inputs.standardtransferableinput.md) una transacción.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `txid` | Buffer | no definido. | Un [Buffer](https://github.com/feross/buffer) que contiene el ID de transacción del UTXO referenciado |
| `outputidx` | Buffer | no definido. | Un [buffer](https://github.com/feross/buffer) que contiene el índice de la salida en la transacción consumida en la Entrada [StandardTransferableInput](common_inputs.standardtransferableinput.md) |
| `activos` | Buffer | no definido. | Un [buffer](https://github.com/feross/buffer) que representa el activo de la [entrada](common_inputs.input.md) |
| `entrada en vigor de la entrada` | [Entrada](common_inputs.input.md) | no definido. | Una [entrada](common_inputs.input.md) que se hará transferible |

**Retornos:** Entrada *[StandardTransferableInput](common_inputs.standardtransferableinput.md)*

## Propiedades de las propiedades

### _codecid `protegido`

• **_codecid**: *número* = indefinido.

*Heredada de [SigIdx](common_signature.sigidx.md)[._codecid](common_signature.sigidx.md#protected-_codecid)*

*Definido en [src/utils/serialización.ts:40](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/serialization.ts#L40)*

___

### `Protegido` _typeID

• **_typeID**: *any* = undefined

*Superaciones [StandardParseableInput](common_inputs.standardparseableinput.md).[_typeID](common_inputs.standardparseableinput.md#protected-_typeid)*

*Definido en [src/comm/input.ts:173](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/input.ts#L173)*

___

### _typeName `protegido`

• **_typeName**: *string* = "StandardTransferableInput"

*Overrides [StandardParseableInput](common_inputs.standardparseableinput.md).[_typeName](common_inputs.standardparseableinput.md#protected-_typename)*

*Definido en [src/comm/input.ts:172](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/input.ts#L172)*

___

### assetID `protegido`

• **assetID**: *Buffer* = Buffer.aloc(32)

*Definido en [src/comm/input.ts:194](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/input.ts#L194)*

___

### Entrada `protegida`

• **entrada**: *[Entrada](common_inputs.input.md)*

*Heredado de [StandardParseableInput](common_inputs.standardparseableinput.md).[input](common_inputs.standardparseableinput.md#protected-input)*

*Definido en [src/comm/input.ts:134](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/input.ts#L134)*

___

### outputidx `protegido`

• **outputidx**: *Buffer* = Buffer.aloc(4)

*Definido en [src/comm/input.ts:193](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/input.ts#L193)*

___

### Txid `protegido`

• **txid**: *Buffer* = Buffer.aloc(32)

*Definido en [src/comm/input.ts:192](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/input.ts#L192)*

## Métodos de trabajo

### deserie

- **deserialize**(`fields`: objeto, `codificación`: [SerializedEncoding](../modules/src_utils.md#serializedencoding)): *vacío*

*Superaciones [StandardParseableInput](common_inputs.standardparseableinput.md).[deserialize](common_inputs.standardparseableinput.md#deserialize)*

*Definido en [src/comm/input.ts:184](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/input.ts#L184)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `campos de cultivo` | objeto de la operación | - |
| `codificación` | [SerializedEncoding](../modules/src_utils.md#serializedencoding) | "hex" |

**Retornos:** *vacío*

___

### `Resumen` deBuffer

- **fromBuffer**(`bytes`: Buffer, `offset?`: número): *número*

*Overrides [StandardParseableInput](common_inputs.standardparseableinput.md).[fromBuffer](common_inputs.standardparseableinput.md#abstract-frombuffer)*

*Definido en [src/comm/input.ts:225](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/input.ts#L225)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `bytes` | Buffer |
| `¿Qué compensación?` | Número de números |

**Retornos:** *número*

___

### getAssetID

- **getAssetID**(): *Buffer*

*Definido en [src/comm/input.ts:223](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/input.ts#L223)*

Devuelve el activo de la entrada.

**Returns:** *Buffer*

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

*Superaciones [StandardParseableInput](common_inputs.standardparseableinput.md).[getInput](common_inputs.standardparseableinput.md#getinput)*

*Definido en [src/comm/input.ts:218](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/input.ts#L218)*

Devuelve la entrada.

**Retornos:** *[Entrada](common_inputs.input.md)*

___

### getOutputIdx

- **getOutputIdx**(): *Buffer*

*Definido en [src/comm/input.ts:206](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/input.ts#L206)*

Devuelve un [buffer](https://github.com/feross/buffer) de la OutputIdx.

**Returns:** *Buffer*

___

### getTxID

- **getTxID**(): *Buffer*

*Definido en [src/comm/input.ts:199](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/input.ts#L199)*

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

*Definido en [src/comm/input.ts:213](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/input.ts#L213)*

Devuelve una representación de cadena base-58 de UTXOID esta referencia de entrada [StandardTransferableInput](common_inputs.standardtransferableinput.md)

**Return:** *string*

___

### serializar

- **serialize**(`encoding`: [SerializedEncoding](../modules/src_utils.md#serializedencoding)): *objeto*

*Superaciones [StandardParseableInput](common_inputs.standardparseableinput.md)[.serialize serialize](common_inputs.standardparseableinput.md#serialize)*

*Definido en [src/comm/input.ts:175](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/input.ts#L175)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `codificación` | [SerializedEncoding](../modules/src_utils.md#serializedencoding) | "hex" |

**Return:** *objeto*

___

### toBuffer

- **toBuffer** (): *Buffer*

*Superaciones [StandardParseableInput](common_inputs.standardparseableinput.md).[toBuffer](common_inputs.standardparseableinput.md#tobuffer)*

*Definido en [src/comm/input.ts:230](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/input.ts#L230)*

Devuelve una representación de [Buffer](https://github.com/feross/buffer) de la Entrada [StandardTransferableInput](common_inputs.standardtransferableinput.md).

**Returns:** *Buffer*

___

### toString

- **toString**(): *string*

*Definido en [src/comm/input.ts:241](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/input.ts#L241)*

Devuelve una representación de base 58 de la Entrada [StandardTransferableInput](common_inputs.standardtransferableinput.md).

**Return:** *string*

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
