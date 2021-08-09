[avalanche](../README.md) › [API-AVM-GenesisData](../modules/api_avm_genesisdata.md) › [GenesisData](api_avm_genesisdata.genesisdata.md)

# Clase: GenesisData

## Jerarquía

* [Serializable](utils_serialization.serializable.md)

   **m.**

## Índice de participación

### Constructores

* [constructor](api_avm_genesisdata.genesisdata.md#constructor)

### Propiedades de las propiedades

* [_codecid](api_avm_genesisdata.genesisdata.md#protected-_codecid)
* [_typeID](api_avm_genesisdata.genesisdata.md#protected-_typeid)
* [_typeName](api_avm_genesisdata.genesisdata.md#protected-_typename)
* [genesisAssets](api_avm_genesisdata.genesisdata.md#protected-genesisassets)
* [networkID](api_avm_genesisdata.genesisdata.md#protected-networkid)

### Métodos de trabajo

* [deserie](api_avm_genesisdata.genesisdata.md#deserialize)
* [deBuffer](api_avm_genesisdata.genesisdata.md#frombuffer)
* [getCodecid](api_avm_genesisdata.genesisdata.md#getcodecid)
* [getGenesisAssets](api_avm_genesisdata.genesisdata.md#getgenesisassets)
* [getNetworkID](api_avm_genesisdata.genesisdata.md#getnetworkid)
* [getTypeID](api_avm_genesisdata.genesisdata.md#gettypeid)
* [getTypeName](api_avm_genesisdata.genesisdata.md#gettypename)
* [serializar](api_avm_genesisdata.genesisdata.md#serialize)
* [toBuffer](api_avm_genesisdata.genesisdata.md#tobuffer)

## Constructores

### constructor

\+ **nuevo GenesisData(genesisAssets:**`` GenesisData(genesisAssets: `networkID`: número): [GenesisAsset](api_avm_genesisasset.genesisasset.md)[]*[,](api_avm_genesisdata.genesisdata.md)*

*Definido en [src/apis/avm/génesisdata.ts:105](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/genesisdata.ts#L105)*

Clase representando a AVM GenesisData

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `genesisAssets` | [GenesisAsset](api_avm_genesisasset.genesisasset.md)[] | [] | GenesisAsset Opcional[] |
| `networkID` | Número de números | DefaultNetworkID | DefaultNetworkID opcional |

**Retornos:** *[GenesisData](api_avm_genesisdata.genesisdata.md)*

## Propiedades de las propiedades

### _codecid `protegido`

• **_codecid**: *número* = AVMConstants.LATESTCODEC

*Overrides [SigIdx](common_signature.sigidx.md)[._codecid](common_signature.sigidx.md#protected-_codecid)*

*Definido en [src/apis/avm/génesisdata.ts:22](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/genesisdata.ts#L22)*

___

### `Protegido` _typeID

• **_typeID**: *número* = indefinido.

*Heredada de [Serializable](utils_serialization.serializable.md).[_typeID](utils_serialization.serializable.md#protected-_typeid)*

*Definido en [src/utils/serialización.ts:39](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/serialization.ts#L39)*

___

### _typeName `protegido`

• **_typeName**: *string* = "GenesisData"

*Superes [Serializable](utils_serialization.serializable.md).[_typeName](utils_serialization.serializable.md#protected-_typename)*

*Definido en [src/apis/avm/génesisdata.ts:21](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/genesisdata.ts#L21)*

___

### Génesis, `activos protegidos`

• **genesisAssets**: *[GenesisAsset](api_avm_genesisasset.genesisasset.md)[]*

*Definido en [src/apis/avm/génesisdata.ts:44](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/genesisdata.ts#L44)*

___

### Red `protegida`

• **networkID**: *Buffer* = Buffer.aloc(4)

*Definido en [src/apis/avm/génesisdata.ts:45](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/genesisdata.ts#L45)*

## Métodos de trabajo

### deserie

- **deserialize**(`fields`: objeto, `codificación`: [SerializedEncoding](../modules/src_utils.md#serializedencoding)): *vacío*

*Superaciones [StandardParseableInput](common_inputs.standardparseableinput.md).[deserialize](common_inputs.standardparseableinput.md#deserialize)*

*Definido en [src/apis/avm/génesisdata.ts:34](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/genesisdata.ts#L34)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `campos de cultivo` | objeto de la operación | - |
| `codificación` | [SerializedEncoding](../modules/src_utils.md#serializedencoding) | "hex" |

**Retornos:** *vacío*

___

### deBuffer

- **fromBuffer**(`bytes`: Buffer, `offset`: número): *número*

*Definido en [src/apis/avm/génesisdata.ts:66](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/genesisdata.ts#L66)*

Toma un [Buffer](https://github.com/feross/buffer) que contiene un conjunto de Génesis, lo analiza, populates la clase y devuelve la longitud del conjunto de [GenesisAsset](api_avm_genesisasset.genesisasset.md)[](api_avm_genesisasset.genesisasset.md) en bytes.

**`observaciones`** asuman que no se ha comprobado

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `bytes` | Buffer | - | Un [buffer](https://github.com/feross/buffer) que contiene un conjunto de [GenesisAsset](api_avm_genesisasset.genesisasset.md) crudos |
| `offset` | Número de números | 0 | - |

**Retornos:** *número*

La longitud del conjunto crudo, de [GenesisAsset](api_avm_genesisasset.genesisasset.md)

___

### getCodecid

- **getCodecid():** *número*

*Heredada de [SigIdx](common_signature.sigidx.md)[.getCodecid](common_signature.sigidx.md#getcodecid)*

*Definido en [src/utils/serialización.ts:59](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/serialization.ts#L59)*

Utilizado en serialización. Opcional. TypeID es un número para el tipo de identificación de objeto que se está saliendo.

**Retornos:** *número*

___

### getGenesisAssets

- **getGenesisAssets():***[](api_avm_genesisasset.genesisasset.md)[]* getGenesisAssets():

*Definido en [src/apis/avm/génesisdata.ts:50](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/genesisdata.ts#L50)*

Devuelve el GenesisAssets[]

**Retornos:** *[GenesisAsset](api_avm_genesisasset.genesisasset.md)[]*

___

### getNetworkID

- **getNetworkID**(): *número*

*Definido en [src/apis/avm/génesisdata.ts:55](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/genesisdata.ts#L55)*

Devuelve el NetworkID como número

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

*Definido en [src/apis/avm/génesisdata.ts:25](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/genesisdata.ts#L25)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `codificación` | [SerializedEncoding](../modules/src_utils.md#serializedencoding) | "hex" |

**Return:** *objeto*

___

### toBuffer

- **toBuffer** (): *Buffer*

*Definido en [src/apis/avm/génesisdata.ts:87](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/genesisdata.ts#L87)*

Devuelve una representación de [Buffer](https://github.com/feross/buffer) de [GenesisData](api_avm_genesisdata.genesisdata.md).

**Returns:** *Buffer*
