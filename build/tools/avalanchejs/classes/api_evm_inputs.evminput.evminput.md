[avalancha](../README.md) › Insumos [API-EVM-Inputs](../modules/api_evm_inputs.md) [EVMInput](api_evm_inputs.evminput.md)

# Clase: EVMInput

## Jerarquía

* [EVMOutput](api_evm_outputs.evmoutput.md)

   de **la entrada**

## Índice de participación

### Constructores

* [constructor](api_evm_inputs.evminput.md#constructor)

### Propiedades de las propiedades

* [Dirección de la dirección](api_evm_inputs.evminput.md#protected-address)
* [importe de la cantidad de dinero](api_evm_inputs.evminput.md#protected-amount)
* [amountValue](api_evm_inputs.evminput.md#protected-amountvalue)
* [activos](api_evm_inputs.evminput.md#protected-assetid)
* [Nocy](api_evm_inputs.evminput.md#protected-nonce)
* [nonceValue](api_evm_inputs.evminput.md#protected-noncevalue)
* [sigCount](api_evm_inputs.evminput.md#protected-sigcount)
* [sigIdxs](api_evm_inputs.evminput.md#protected-sigidxs)

### Métodos de trabajo

* [addSignatureIdx](api_evm_inputs.evminput.md#addsignatureidx)
* [clon](api_evm_inputs.evminput.md#clone)
* [crear un entorno de creación](api_evm_inputs.evminput.md#create)
* [deBuffer](api_evm_inputs.evminput.md#frombuffer)
* [getAddress](api_evm_inputs.evminput.md#getaddress)
* [getAddressString](api_evm_inputs.evminput.md#getaddressstring)
* [getAmount](api_evm_inputs.evminput.md#getamount)
* [getAssetID](api_evm_inputs.evminput.md#getassetid)
* [getCredentialID](api_evm_inputs.evminput.md#getcredentialid)
* [getNonce](api_evm_inputs.evminput.md#getnonce)
* [getSigIdxs](api_evm_inputs.evminput.md#getsigidxs)
* [toBuffer](api_evm_inputs.evminput.md#tobuffer)
* [toString](api_evm_inputs.evminput.md#tostring)
* [comparador](api_evm_inputs.evminput.md#static-comparator)

## Constructores

### constructor

\+ **new EVMInput**`(address`: Buffer | string, `EVMInput(address`: BN | number, `assetID`: Buffer | string, `nonce`: BN | number): *[EVMInput](api_evm_inputs.evminput.md)*

*Supera [EVMOutput](api_evm_outputs.evmoutput.md).[constructor](api_evm_outputs.evmoutput.md#constructor)*

*Definido en [src/apis/evm/inputs.ts:183](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/inputs.ts#L183)*

Una clase [EVMInput](api_evm_inputs.evminput.md) que contiene dirección, cantidad, assetID, no ce.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `Dirección de la dirección` | Buffer &#124; cadena | no definido. | es la dirección EVM desde la que transferir fondos. |
| `importe de la cantidad de dinero` | BN &#124; número | no definido. | es el importe del activo que debe transferirse (especificado en nAVAX para AVAX y la denominación más pequeña para todos los demás activos). |
| `activos` | Buffer &#124; cadena | no definido. | El activo que se envía como [Buffer](https://github.com/feross/buffer) o como una cadena. |
| `Nocy` | BN &#124; número | no definido. | Una [BN](https://github.com/indutny/bn.js/) o un número que representa la noce. |

**Retornos:** *[EVMInput](api_evm_inputs.evminput.md)*

## Propiedades de las propiedades

### Dirección `protegida`

• **dirección**: *Buffer* = Buffer.aloc(20)

*Heredada de [EVMInput](api_evm_inputs.evminput.md).[address](api_evm_inputs.evminput.md#protected-address)*

*Definido en [src/apis/evm/outputs.ts:99](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/outputs.ts#L99)*

___

### Cantidad `protegida`

• **cantidad**: *Buffer* = Buffer.aloc(8)

*Heredado de [EVMInput](api_evm_inputs.evminput.md).[amount](api_evm_inputs.evminput.md#protected-amount)*

*Definido en [src/apis/evm/outputs.ts:100](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/outputs.ts#L100)*

___

### Cantidad `Protected`

• **amountValue**: *BN* = nuevo BN(0)

*Heredado de [EVMInput](api_evm_inputs.evminput.md).[amountValue](api_evm_inputs.evminput.md#protected-amountvalue)*

*Definido en [src/apis/evm/outputs.ts:101](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/outputs.ts#L101)*

___

### assetID `protegido`

• **assetID**: *Buffer* = Buffer.aloc(32)

*Heredada de [EVMInput](api_evm_inputs.evminput.md).[assetID](api_evm_inputs.evminput.md#protected-assetid)*

*Definido en [src/apis/evm/outputs.ts:102](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/outputs.ts#L102)*

___

### Nocera `protegida`

• **once**: *Buffer* = Buffer.aloc(8)

*Definido en [src/apis/evm/inputs.ts:111](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/inputs.ts#L111)*

___

### Valor no ceValor `protegido`

• **nonceValue**: *BN* = nuevo BN(0)

*Definido en [src/apis/evm/inputs.ts:112](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/inputs.ts#L112)*

___

### sigCount `protegido`

• **sigCount**: *Buffer* = Buffer.aloc(4)

*Definido en [src/apis/evm/inputs.ts:113](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/inputs.ts#L113)*

___

### SigIdxs `protegidos`

• **sigIdxs**: *[SigIdx](common_signature.sigidx.md)[]* =[]

*Definido en [src/apis/evm/inputs.ts:114](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/inputs.ts#L114)*

## Métodos de trabajo

### addSignatureIdx

- **addSignatureIdx**(`addressIdx`: número, `dirección`: Buffer): *void*

*Definido en [src/apis/evm/inputs.ts:127](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/inputs.ts#L127)*

Crea y agrega un [SigIdx](common_signature.sigidx.md) a la [entrada](common_inputs.input.md).

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `addressIdx` | Número de números | El índice de la dirección a la referencia en las firmas |
| `Dirección de la dirección` | Buffer | La dirección de la fuente de la firma |

**Retornos:** *vacío*

___

### clon

- **clone**(): *esto*

*Superar [EVMOutput](api_evm_outputs.evmoutput.md).[clone](api_evm_outputs.evmoutput.md#clone)*

*Definido en [src/apis/evm/inputs.ts:179](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/inputs.ts#L179)*

**Returns:** *esto*

___

### crear un entorno de creación

*-* **create**(...`args`: []cualquiera

*Supera [EVMOutput](api_evm_outputs.evmoutput.md).[create](api_evm_outputs.evmoutput.md#create)*

*Definido en [src/apis/evm/inputs.ts:175](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/inputs.ts#L175)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `..args` | cualquier otra cosa que no sea[] |

**Returns:** *esto*

___

### deBuffer

- **fromBuffer**(`bytes`: Buffer, `offset`: número): *número*

*Supera [EVMOutput](api_evm_outputs.evmoutput.md).[fromBuffer](api_evm_outputs.evmoutput.md#frombuffer)*

*Definido en [src/apis/evm/inputs.ts:161](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/inputs.ts#L161)*

Decodifica el [EVMInput](api_evm_inputs.evminput.md) como un [Buffer](https://github.com/feross/buffer) y devuelve el tamaño.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `bytes` | Buffer | - | Los bytes como [Buffer](https://github.com/feross/buffer) |
| `offset` | Número de números | 0 | Un offset como número. |

**Retornos:** *número*

___

### getAddress

- **getAddress**(): *Buffer*

*Heredada de [EVMInput](api_evm_inputs.evminput.md).[getAddress](api_evm_inputs.evminput.md#getaddress)*

*Definido en [src/apis/evm/outputs.ts:122](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/outputs.ts#L122)*

Devuelve la dirección de la entrada como [Buffer](https://github.com/feross/buffer)

**Returns:** *Buffer*

___

### getAddressString

- **getAddressString**(): *string*

*Heredada de [EVMInput](api_evm_inputs.evminput.md).[getAddressString](api_evm_inputs.evminput.md#getaddressstring)*

*Definido en [src/apis/evm/outputs.ts:127](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/outputs.ts#L127)*

Devuelve la dirección como una cadena codificada bech32.

**Return:** *string*

___

### getAmount

- **getAmount**(): *BN*

*Heredada de [EVMInput](api_evm_inputs.evminput.md).[getAmount](api_evm_inputs.evminput.md#getamount)*

*Definido en [src/apis/evm/outputs.ts:132](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/outputs.ts#L132)*

Devuelve la cantidad como un [BN](https://github.com/indutny/bn.js/).

**Returns:** *BN*

___

### getAssetID

- **getAssetID**(): *Buffer*

*Heredada de [EVMInput](api_evm_inputs.evminput.md).[getAssetID](api_evm_inputs.evminput.md#getassetid)*

*Definido en [src/apis/evm/outputs.ts:137](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/outputs.ts#L137)*

Devuelve el activo de la entrada como [Buffer](https://github.com/feross/buffer)

**Returns:** *Buffer*

___

### getCredentialID

- **getCredentialID**(): *número*

*Definido en [src/apis/evm/inputs.ts:153](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/inputs.ts#L153)*

**Retornos:** *número*

___

### getNonce

- **getNonce**(): *BN*

*Definido en [src/apis/evm/inputs.ts:141](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/inputs.ts#L141)*

Devuelve la noza como un [BN](https://github.com/indutny/bn.js/).

**Returns:** *BN*

___

### getSigIdxs

- **getSigIdxs**(): *[SigIdx](common_signature.sigidx.md)[]*

*Definido en [src/apis/evm/inputs.ts:119](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/inputs.ts#L119)*

Devuelve la matriz de [SigIdx](common_signature.sigidx.md) para esta [entrada](common_inputs.input.md)

**Returns:** *[SigIdx](common_signature.sigidx.md)[]*

___

### toBuffer

- **toBuffer** (): *Buffer*

*Supera [EVMOutput](api_evm_outputs.evmoutput.md).[toBuffer](api_evm_outputs.evmoutput.md#tobuffer)*

*Definido en [src/apis/evm/inputs.ts:146](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/inputs.ts#L146)*

Devuelve una representación de [Buffer](https://github.com/feross/buffer) del [EVMOutput](api_evm_outputs.evmoutput.md).

**Returns:** *Buffer*

___

### toString

- **toString**(): *string*

*Supera [EVMOutput](api_evm_outputs.evmoutput.md).[toString](api_evm_outputs.evmoutput.md#tostring)*

*Definido en [src/apis/evm/inputs.ts:171](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/inputs.ts#L171)*

Devuelve una representación de base 58 del [EVMInput](api_evm_inputs.evminput.md).

**Return:** *string*

___

### Comparador `estático`

- **comparator**(): *función*

*Heredada de [EVMInput](api_evm_inputs.evminput.md).[comparator](api_evm_inputs.evminput.md#static-comparator)*

*Definido en [src/apis/evm/outputs.ts:107](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/outputs.ts#L107)*

Devuelve una función utilizada para ordenar una serie de [EVMOutput](api_evm_outputs.evmoutput.md)s

**Retornos:** *función*

- (`a`: [EVMOutput](api_evm_outputs.evmoutput.md) | [EVMInput](api_evm_inputs.evminput.md)[,](api_evm_inputs.evminput.md) `b`: EVMOutput | EVMInput): *1 | -1 | 0*[](api_evm_outputs.evmoutput.md)

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `a a` | [EVMOutput](api_evm_outputs.evmoutput.md) &#124; [EVMInput](api_evm_inputs.evminput.md) |
| `b b` | [EVMOutput](api_evm_outputs.evmoutput.md) &#124; [EVMInput](api_evm_inputs.evminput.md) |
