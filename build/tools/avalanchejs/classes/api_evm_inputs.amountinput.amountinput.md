[avalanche](../README.md) › Insumos [API-EVM-Inputs](../modules/api_evm_inputs.md) [AmountInput](api_evm_inputs.amountinput.md)

# Clase: Importe de la cantidad

## Jerarquía

m [Estándar Importe](common_inputs.standardamountinput.md)

m **AmountInput**

de la [SECPTransferInput](api_evm_inputs.secptransferinput.md)

## Índice de participación

### Constructores

* [constructor](api_evm_inputs.amountinput.md#constructor)

### Propiedades de las propiedades

* [_codecid](api_evm_inputs.amountinput.md#protected-_codecid)
* [_typeID](api_evm_inputs.amountinput.md#protected-_typeid)
* [_typeName](api_evm_inputs.amountinput.md#protected-_typename)
* [importe de la cantidad de dinero](api_evm_inputs.amountinput.md#protected-amount)
* [amountValue](api_evm_inputs.amountinput.md#protected-amountvalue)
* [sigCount](api_evm_inputs.amountinput.md#protected-sigcount)
* [sigIdxs](api_evm_inputs.amountinput.md#protected-sigidxs)

### Métodos de trabajo

* [addSignatureIdx](api_evm_inputs.amountinput.md#addsignatureidx)
* [clon](api_evm_inputs.amountinput.md#abstract-clone)
* [crear un entorno de creación](api_evm_inputs.amountinput.md#abstract-create)
* [deserie](api_evm_inputs.amountinput.md#deserialize)
* [deBuffer](api_evm_inputs.amountinput.md#frombuffer)
* [getAmount](api_evm_inputs.amountinput.md#getamount)
* [getCodecid](api_evm_inputs.amountinput.md#getcodecid)
* [getCredentialID](api_evm_inputs.amountinput.md#abstract-getcredentialid)
* [getInputID](api_evm_inputs.amountinput.md#abstract-getinputid)
* [getSigIdxs](api_evm_inputs.amountinput.md#getsigidxs)
* [getTypeID](api_evm_inputs.amountinput.md#gettypeid)
* [getTypeName](api_evm_inputs.amountinput.md#gettypename)
* [seleccionar](api_evm_inputs.amountinput.md#select)
* [serializar](api_evm_inputs.amountinput.md#serialize)
* [toBuffer](api_evm_inputs.amountinput.md#tobuffer)
* [toString](api_evm_inputs.amountinput.md#tostring)
* [comparador](api_evm_inputs.amountinput.md#static-comparator)

## Constructores

### constructor

\+ **nueva** *[AmountInput](api_evm_inputs.amountinput.md)*(`amount`: BN): Importe de entrada

*Heredado de [StandardAmountInput](common_inputs.standardamountinput.md).[constructor](common_inputs.standardamountinput.md#constructor)*

*Definido en [src/comm/input.ts:311](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/input.ts#L311)*

Una clase [de entrada](api_evm_inputs.amountinput.md) que emite un pago en un activo ID.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `importe de la cantidad de dinero` | BN | no definido. | Un [BN](https://github.com/indutny/bn.js/) que representa el importe en la entrada |

**Retornos:** *[Importe](api_evm_inputs.amountinput.md)*

## Propiedades de las propiedades

### _codecid `protegido`

• **_codecid**: *número* = indefinido.

*Heredada de [SigIdx](common_signature.sigidx.md)[._codecid](common_signature.sigidx.md#protected-_codecid)*

*Definido en [src/utils/serialización.ts:40](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/serialization.ts#L40)*

___

### `Protegido` _typeID

• **_typeID**: *any* = undefined

*Superposición [StandardAmountInput](common_inputs.standardamountinput.md).[_typeID](common_inputs.standardamountinput.md#protected-_typeid)*

*Definido en [src/apis/evm/inputs.ts:75](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/inputs.ts#L75)*

___

### _typeName `protegido`

• **_typeName**: *string* = "AmountInput"

*Superposición [StandardAmountInput](common_inputs.standardamountinput.md).[_typeName](common_inputs.standardamountinput.md#protected-_typename)*

*Definido en [src/apis/evm/inputs.ts:74](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/inputs.ts#L74)*

___

### Cantidad `protegida`

• **cantidad**: *Buffer* = Buffer.aloc(8)

*Heredado de [StandardAmountInput](common_inputs.standardamountinput.md).[amount](common_inputs.standardamountinput.md#protected-amount)*

*Definido en [src/comm/input.ts:285](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/input.ts#L285)*

___

### Cantidad `Protected`

• **amountValue**: *BN* = nuevo BN(0)

*Heredado de [StandardAmountInput](common_inputs.standardamountinput.md).[amountValue](common_inputs.standardamountinput.md#protected-amountvalue)*

*Definido en [src/comm/input.ts:286](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/input.ts#L286)*

___

### sigCount `protegido`

• **sigCount**: *Buffer* = Buffer.aloc(4)

*Heredado de [Input](common_inputs.input.md).[sigCount](common_inputs.input.md#protected-sigcount)*

*Definido en [src/comm/input.ts:38](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/input.ts#L38)*

___

### SigIdxs `protegidos`

• **sigIdxs**: *[SigIdx](common_signature.sigidx.md)[]* =[]

*Heredado de [Input](common_inputs.input.md).[sigIdxs](common_inputs.input.md#protected-sigidxs)*

*Definido en [src/comm/input.ts:39](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/input.ts#L39)*

## Métodos de trabajo

### addSignatureIdx

- **addSignatureIdx**(`addressIdx`: número, `dirección`: Buffer): *void*

*Heredada de [Input](common_inputs.input.md).[addSignatureIdx](common_inputs.input.md#addsignatureidx)*

*Definido en [src/comm/input.ts:70](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/input.ts#L70)*

Crea y agrega un [SigIdx](common_signature.sigidx.md) a la [entrada](common_inputs.input.md).

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `addressIdx` | Número de números | El índice de la dirección a la referencia en las firmas |
| `Dirección de la dirección` | Buffer | La dirección de la fuente de la firma |

**Retornos:** *vacío*

___

### Clon `abstracto`

- **clone**(): *esto*

*Heredado de [Input](common_inputs.input.md).[clone](common_inputs.input.md#abstract-clone)*

*Definido en [src/comm/input.ts:114](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/input.ts#L114)*

**Returns:** *esto*

___

### `Crear, abstracta,`

*-* **create**(...`args`: []cualquiera

*Heredado de [from](common_inputs.input.md)[](common_inputs.input.md#abstract-create)*

*Definido en [src/comm/input.ts:116](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/input.ts#L116)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `..args` | cualquier otra cosa que no sea[] |

**Returns:** *esto*

___

### deserie

- **deserialize**(`fields`: objeto, `codificación`: [SerializedEncoding](../modules/src_utils.md#serializedencoding)): *vacío*

*Heredado de [StandardAmountInput](common_inputs.standardamountinput.md).[deserialize](common_inputs.standardamountinput.md#deserialize)*

*Superar [Input](common_inputs.input.md)[... deserializar](common_inputs.input.md#deserialize)*

*Definido en [src/comm/input.ts:279](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/input.ts#L279)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `campos de cultivo` | objeto de la operación | - |
| `codificación` | [SerializedEncoding](../modules/src_utils.md#serializedencoding) | "hex" |

**Retornos:** *vacío*

___

### deBuffer

- **fromBuffer**(`bytes`: Buffer, `offset`: número): *número*

*Heredado de [StandardAmountInput](common_inputs.standardamountinput.md).[fromBuffer](common_inputs.standardamountinput.md#frombuffer)*

*Supera [Input](common_inputs.input.md).[fromBuffer](common_inputs.input.md#frombuffer)*

*Definido en [src/comm/input.ts:296](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/input.ts#L296)*

Popuates la instancia de un [buffer](https://github.com/feross/buffer) que representa la [entrada de](api_evm_inputs.amountinput.md) Cantidad, y devuelve el tamaño de la entrada.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `bytes` | Buffer | - |
| `offset` | Número de números | 0 |

**Retornos:** *número*

___

### getAmount

- **getAmount**(): *BN*

*Heredado de [StandardAmountInput](common_inputs.standardamountinput.md).[getAmount](common_inputs.standardamountinput.md#getamount)*

*Definido en [src/comm/input.ts:291](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/input.ts#L291)*

Devuelve la cantidad como un [BN](https://github.com/indutny/bn.js/).

**Returns:** *BN*

___

### getCodecid

- **getCodecid():** *número*

*Heredada de [SigIdx](common_signature.sigidx.md)[.getCodecid](common_signature.sigidx.md#getcodecid)*

*Definido en [src/utils/serialización.ts:59](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/serialization.ts#L59)*

Utilizado en serialización. Opcional. TypeID es un número para el tipo de identificación de objeto que se está saliendo.

**Retornos:** *número*

___

### `Resumen` getCredentialID

- **getCredentialID**(): *número*

*Heredada de [Input](common_inputs.input.md).[getCredentialID](common_inputs.input.md#abstract-getcredentialid)*

*Definido en [src/comm/input.ts:62](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/input.ts#L62)*

**Retornos:** *número*

___

### `Resumen` getInputID

- **getInputID**(): *número*

*Heredado de [Input.getInputID](common_inputs.input.md)[](common_inputs.input.md#abstract-getinputid)*

*Definido en [src/comm/input.ts:55](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/input.ts#L55)*

**Retornos:** *número*

___

### getSigIdxs

- **getSigIdxs**(): *[SigIdx](common_signature.sigidx.md)[]*

*Heredada de [Input](common_inputs.input.md).[getSigIdxs](common_inputs.input.md#getsigidxs)*

*Definido en [src/comm/input.ts:60](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/input.ts#L60)*

Devuelve la matriz de [SigIdx](common_signature.sigidx.md) para esta [entrada](common_inputs.input.md)

**Returns:** *[SigIdx](common_signature.sigidx.md)[]*

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

### seleccionar

- **select**(`id`: número, ...`args`: []cualquier): *[Entrada](common_inputs.input.md)*

*Supera [Input](common_inputs.input.md).[select](common_inputs.input.md#abstract-select)*

*Definido en [src/apis/evm/inputs.ts:79](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/inputs.ts#L79)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `I.` | Número de números |
| `..args` | cualquier otra cosa que no sea[] |

**Retornos:** *[Entrada](common_inputs.input.md)*

___

### serializar

- **serialize**(`encoding`: [SerializedEncoding](../modules/src_utils.md#serializedencoding)): *objeto*

*Heredado de [StandardAmountInput](common_inputs.standardamountinput.md).[serialize](common_inputs.standardamountinput.md#serialize)*

*Supera [Input](common_inputs.input.md).[serialize](common_inputs.input.md#serialize)*

*Definido en [src/comm/input.ts:272](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/input.ts#L272)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `codificación` | [SerializedEncoding](../modules/src_utils.md#serializedencoding) | "hex" |

**Return:** *objeto*

___

### toBuffer

- **toBuffer** (): *Buffer*

*Heredado de [StandardAmountInput](common_inputs.standardamountinput.md).[toBuffer](common_inputs.standardamountinput.md#tobuffer)*

*Supera [Input](common_inputs.input.md).[toBuffer](common_inputs.input.md#tobuffer)*

*Definido en [src/comm/input.ts:306](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/input.ts#L306)*

Devuelve el buffer que representa la instancia [de Importe de la](api_evm_inputs.amountinput.md) Cuenta.

**Returns:** *Buffer*

___

### toString

- **toString**(): *string*

*Heredada de [Input](common_inputs.input.md).[toString](common_inputs.input.md#tostring)*

*Definido en [src/comm/input.ts:110](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/input.ts#L110)*

Devuelve una representación de base 58 de la [Entrada](common_inputs.input.md).

**Return:** *string*

___

### Comparador `estático`

- **comparator**(): *función*

*Heredado de [Input](common_inputs.input.md).[comparator](common_inputs.input.md#static-comparator)*

*Definido en [src/comm/input.ts:41](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/input.ts#L41)*

**Retornos:** *función*

- (`a`: [Entrada](common_inputs.input.md), `b`: [Entrada):](common_inputs.input.md) *1 | -1 | 0*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `a a` | [Entrada](common_inputs.input.md) |
| `b b` | [Entrada](common_inputs.input.md) |
