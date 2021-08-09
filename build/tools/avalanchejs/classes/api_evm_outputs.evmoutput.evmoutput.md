[avalanche](../README.md) › Salida [API-EVM-Outputs](../modules/api_evm_outputs.md) [EVMOutput](api_evm_outputs.evmoutput.md)

# Clase: EVMOutput

## Jerarquía

* **EVMOutput**

   de [la entrada](api_evm_inputs.evminput.md)

## Índice de participación

### Constructores

* [constructor](api_evm_outputs.evmoutput.md#constructor)

### Propiedades de las propiedades

* [Dirección de la dirección](api_evm_outputs.evmoutput.md#protected-address)
* [importe de la cantidad de dinero](api_evm_outputs.evmoutput.md#protected-amount)
* [amountValue](api_evm_outputs.evmoutput.md#protected-amountvalue)
* [activos](api_evm_outputs.evmoutput.md#protected-assetid)

### Métodos de trabajo

* [clon](api_evm_outputs.evmoutput.md#clone)
* [crear un entorno de creación](api_evm_outputs.evmoutput.md#create)
* [deBuffer](api_evm_outputs.evmoutput.md#frombuffer)
* [getAddress](api_evm_outputs.evmoutput.md#getaddress)
* [getAddressString](api_evm_outputs.evmoutput.md#getaddressstring)
* [getAmount](api_evm_outputs.evmoutput.md#getamount)
* [getAssetID](api_evm_outputs.evmoutput.md#getassetid)
* [toBuffer](api_evm_outputs.evmoutput.md#tobuffer)
* [toString](api_evm_outputs.evmoutput.md#tostring)
* [comparador](api_evm_outputs.evmoutput.md#static-comparator)

## Constructores

### constructor

\+ **new EVMOutput**`(address`: Buffer | string, `EVMOutput(address`: BN | number, `assetID`: Buffer | string): *[EVMOutput](api_evm_outputs.evmoutput.md)*

*Definido en [src/apis/evm/outputs.ts:177](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/outputs.ts#L177)*

Una clase [EVMOutput](api_evm_outputs.evmoutput.md) que contiene dirección, cantidad y assetID.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `Dirección de la dirección` | Buffer &#124; cadena | no definido. | La dirección que recayera el activo como un [Buffer](https://github.com/feross/buffer) o una cadena. |
| `importe de la cantidad de dinero` | BN &#124; número | no definido. | Un [BN](https://github.com/indutny/bn.js/) o número que representa el montante. |
| `activos` | Buffer &#124; cadena | no definido. | El activo que se envía como [Buffer](https://github.com/feross/buffer) o una cadena. |

**Retornos:** *[EVMOutput](api_evm_outputs.evmoutput.md)*

## Propiedades de las propiedades

### Dirección `protegida`

• **dirección**: *Buffer* = Buffer.aloc(20)

*Definido en [src/apis/evm/outputs.ts:99](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/outputs.ts#L99)*

___

### Cantidad `protegida`

• **cantidad**: *Buffer* = Buffer.aloc(8)

*Definido en [src/apis/evm/outputs.ts:100](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/outputs.ts#L100)*

___

### Cantidad `Protected`

• **amountValue**: *BN* = nuevo BN(0)

*Definido en [src/apis/evm/outputs.ts:101](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/outputs.ts#L101)*

___

### assetID `protegido`

• **assetID**: *Buffer* = Buffer.aloc(32)

*Definido en [src/apis/evm/outputs.ts:102](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/outputs.ts#L102)*

## Métodos de trabajo

### clon

- **clone**(): *esto*

*Definido en [src/apis/evm/outputs.ts:173](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/outputs.ts#L173)*

**Returns:** *esto*

___

### crear un entorno de creación

*-* **create**(...`args`: []cualquiera

*Definido en [src/apis/evm/outputs.ts:169](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/outputs.ts#L169)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `..args` | cualquier otra cosa que no sea[] |

**Returns:** *esto*

___

### deBuffer

- **fromBuffer**(`bytes`: Buffer, `offset`: número): *número*

*Definido en [src/apis/evm/outputs.ts:152](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/outputs.ts#L152)*

Decodifica el [EVMOutput](api_evm_outputs.evmoutput.md) como un [Buffer](https://github.com/feross/buffer) y devuelve el tamaño.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `bytes` | Buffer | - |
| `offset` | Número de números | 0 |

**Retornos:** *número*

___

### getAddress

- **getAddress**(): *Buffer*

*Definido en [src/apis/evm/outputs.ts:122](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/outputs.ts#L122)*

Devuelve la dirección de la entrada como [Buffer](https://github.com/feross/buffer)

**Returns:** *Buffer*

___

### getAddressString

- **getAddressString**(): *string*

*Definido en [src/apis/evm/outputs.ts:127](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/outputs.ts#L127)*

Devuelve la dirección como una cadena codificada bech32.

**Return:** *string*

___

### getAmount

- **getAmount**(): *BN*

*Definido en [src/apis/evm/outputs.ts:132](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/outputs.ts#L132)*

Devuelve la cantidad como un [BN](https://github.com/indutny/bn.js/).

**Returns:** *BN*

___

### getAssetID

- **getAssetID**(): *Buffer*

*Definido en [src/apis/evm/outputs.ts:137](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/outputs.ts#L137)*

Devuelve el activo de la entrada como [Buffer](https://github.com/feross/buffer)

**Returns:** *Buffer*

___

### toBuffer

- **toBuffer** (): *Buffer*

*Definido en [src/apis/evm/outputs.ts:142](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/outputs.ts#L142)*

Devuelve una representación de [Buffer](https://github.com/feross/buffer) del [EVMOutput](api_evm_outputs.evmoutput.md).

**Returns:** *Buffer*

___

### toString

- **toString**(): *string*

*Definido en [src/apis/evm/outputs.ts:165](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/outputs.ts#L165)*

Devuelve una representación de base 58 del [EVMOutput](api_evm_outputs.evmoutput.md).

**Return:** *string*

___

### Comparador `estático`

- **comparator**(): *función*

*Definido en [src/apis/evm/outputs.ts:107](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/outputs.ts#L107)*

Devuelve una función utilizada para ordenar una serie de [EVMOutput](api_evm_outputs.evmoutput.md)s

**Retornos:** *función*

- (`a`: [EVMOutput](api_evm_outputs.evmoutput.md) | [EVMInput](api_evm_inputs.evminput.md)[,](api_evm_inputs.evminput.md) `b`: EVMOutput | EVMInput): *1 | -1 | 0*[](api_evm_outputs.evmoutput.md)

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `a a` | [EVMOutput](api_evm_outputs.evmoutput.md) &#124; [EVMInput](api_evm_inputs.evminput.md) |
| `b b` | [EVMOutput](api_evm_outputs.evmoutput.md) &#124; [EVMInput](api_evm_inputs.evminput.md) |
