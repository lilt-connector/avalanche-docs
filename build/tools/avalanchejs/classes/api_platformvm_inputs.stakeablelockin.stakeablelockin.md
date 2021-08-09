[avalanche](../README.md) › Insumos [API-PlatformVM-Inputs](../modules/api_platformvm_inputs.md) › [StakeableLockIn](api_platformvm_inputs.stakeablelockin.md)

# Clase: StakeableLockIn

Una clase [de entrada](common_inputs.input.md) que especifica una entrada que tiene un tiempo de bloqueo que también puede permitir el almacenamiento del valor mantenido, evitando transferencias pero no validación.

## Jerarquía

m [AmountInput](api_platformvm_inputs.amountinput.md)

m **StakeableLockIn**

## Índice de participación

### Constructores

* [constructor](api_platformvm_inputs.stakeablelockin.md#constructor)

### Propiedades de las propiedades

* [_codecid](api_platformvm_inputs.stakeablelockin.md#protected-_codecid)
* [_typeID](api_platformvm_inputs.stakeablelockin.md#protected-_typeid)
* [_typeName](api_platformvm_inputs.stakeablelockin.md#protected-_typename)
* [importe de la cantidad de dinero](api_platformvm_inputs.stakeablelockin.md#protected-amount)
* [amountValue](api_platformvm_inputs.stakeablelockin.md#protected-amountvalue)
* [sigCount](api_platformvm_inputs.stakeablelockin.md#protected-sigcount)
* [sigIdxs](api_platformvm_inputs.stakeablelockin.md#protected-sigidxs)
* [stakeableLocktime](api_platformvm_inputs.stakeablelockin.md#protected-stakeablelocktime)
* [Entrada transferible](api_platformvm_inputs.stakeablelockin.md#protected-transferableinput)

### Métodos de trabajo

* [addSignatureIdx](api_platformvm_inputs.stakeablelockin.md#addsignatureidx)
* [clon](api_platformvm_inputs.stakeablelockin.md#clone)
* [crear un entorno de creación](api_platformvm_inputs.stakeablelockin.md#create)
* [deserie](api_platformvm_inputs.stakeablelockin.md#deserialize)
* [deBuffer](api_platformvm_inputs.stakeablelockin.md#frombuffer)
* [getAmount](api_platformvm_inputs.stakeablelockin.md#getamount)
* [getCodecid](api_platformvm_inputs.stakeablelockin.md#getcodecid)
* [getCredentialID](api_platformvm_inputs.stakeablelockin.md#getcredentialid)
* [getInputID](api_platformvm_inputs.stakeablelockin.md#getinputid)
* [getSigIdxs](api_platformvm_inputs.stakeablelockin.md#getsigidxs)
* [getStakeableLocktime](api_platformvm_inputs.stakeablelockin.md#getstakeablelocktime)
* [getTransferablInput](api_platformvm_inputs.stakeablelockin.md#gettransferablinput)
* [getTypeID](api_platformvm_inputs.stakeablelockin.md#gettypeid)
* [getTypeName](api_platformvm_inputs.stakeablelockin.md#gettypename)
* [seleccionar](api_platformvm_inputs.stakeablelockin.md#select)
* [serializar](api_platformvm_inputs.stakeablelockin.md#serialize)
* [sincronizar](api_platformvm_inputs.stakeablelockin.md#private-synchronize)
* [toBuffer](api_platformvm_inputs.stakeablelockin.md#tobuffer)
* [toString](api_platformvm_inputs.stakeablelockin.md#tostring)
* [comparador](api_platformvm_inputs.stakeablelockin.md#static-comparator)

## Constructores

### constructor

\+ **nuevo** `StakeableLockIn(amount`: `BN,` `stakeableLocktime`: de bloqueo: BN, StakeableLockIn(amount: [ParseableInput](api_platformvm_inputs.parseableinput.md)): *[StakeableLockIn](api_platformvm_inputs.stakeablelockin.md)*

*Supervisión [StandardAmountInput](common_inputs.standardamountinput.md).[constructor](common_inputs.standardamountinput.md#constructor)*

*Definido en [src/apis/platformvm/inputs.ts:222](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/inputs.ts#L222)*

Una clase [de salida](../modules/src_common.md#output) que especifica una [entrada](common_inputs.input.md) que tiene un tiempo de bloqueo que también puede permitir el almacenamiento del valor mantenido, evitando transferencias pero no validación.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `importe de la cantidad de dinero` | BN | no definido. | Un [BN](https://github.com/indutny/bn.js/) que representa el importe en la entrada |
| `stakeableLocktime` | BN | no definido. | Un [BN](https://github.com/indutny/bn.js/) que representa el tiempo de bloqueo de juego |
| `Entrada transferible` | [Entrada ParseableInput](api_platformvm_inputs.parseableinput.md) | no definido. | Una [entrada parseableInput](api_platformvm_inputs.parseableinput.md) que está incrustada en esta entrada. |

**Retornos:** *[StakeableLockIn](api_platformvm_inputs.stakeablelockin.md)*

## Propiedades de las propiedades

### _codecid `protegido`

• **_codecid**: *número* = indefinido.

*Heredada de [SigIdx](common_signature.sigidx.md)[._codecid](common_signature.sigidx.md#protected-_codecid)*

*Definido en [src/utils/serialización.ts:40](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/serialization.ts#L40)*

___

### `Protegido` _typeID

• **_typeID**: *número* = PlatformVMConstants.STAKEABLELOCKINID

*Resources [AmountInput](api_platformvm_inputs.amountinput.md).[_typeID](api_platformvm_inputs.amountinput.md#protected-_typeid)*

*Definido en [src/apis/platformvm/inputs.ts:133](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/inputs.ts#L133)*

___

### _typeName `protegido`

• **_typeName**: *string* = "StakeableLockIn"

*Resources [AmountInput](api_platformvm_inputs.amountinput.md).[_typeName](api_platformvm_inputs.amountinput.md#protected-_typename)*

*Definido en [src/apis/platformvm/inputs.ts:132](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/inputs.ts#L132)*

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

___

### `Protected` stakeableLocktime

• **stakeableLocktime**: de cierre: *Buffer*

*Definido en [src/apis/platformvm/inputs.ts:160](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/inputs.ts#L160)*

___

### Input `transferible protegido`

• **Entrada transferible**: *[Entrada parseableInput](api_platformvm_inputs.parseableinput.md)*

*Definido en [src/apis/platformvm/inputs.ts:161](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/inputs.ts#L161)*

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

### clon

- **clone**(): *esto*

*Supera [Input](common_inputs.input.md).[clone](common_inputs.input.md#abstract-clone)*

*Definido en [src/apis/platformvm/inputs.ts:214](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/inputs.ts#L214)*

**Returns:** *esto*

___

### crear un entorno de creación

*-* **create**(...`args`: []cualquiera

*Supera [Input](common_inputs.input.md).[create](common_inputs.input.md#abstract-create)*

*Definido en [src/apis/platformvm/inputs.ts:210](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/inputs.ts#L210)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `..args` | cualquier otra cosa que no sea[] |

**Returns:** *esto*

___

### deserie

- **deserialize**(`fields`: objeto, `codificación`: [SerializedEncoding](../modules/src_utils.md#serializedencoding)): *vacío*

*Superaciones [StandardAmountInput](common_inputs.standardamountinput.md).[deserialize](common_inputs.standardamountinput.md#deserialize)*

*Definido en [src/apis/platformvm/inputs.ts:149](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/inputs.ts#L149)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `campos de cultivo` | objeto de la operación | - |
| `codificación` | [SerializedEncoding](../modules/src_utils.md#serializedencoding) | "hex" |

**Retornos:** *vacío*

___

### deBuffer

- **fromBuffer**(`bytes`: Buffer, `offset`: número): *número*

*Superposición [StandardAmountInput](common_inputs.standardamountinput.md).[fromBuffer](common_inputs.standardamountinput.md#frombuffer)*

*Definido en [src/apis/platformvm/inputs.ts:191](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/inputs.ts#L191)*

Popuates la instancia de un [Buffer](https://github.com/feross/buffer) que representa al [stakeableLockIn](api_platformvm_inputs.stakeablelockin.md) y devuelve el tamaño de la salida.

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

### getCredentialID

- **getCredentialID**(): *número*

*Superar [Input](common_inputs.input.md).[getCredentialID](common_inputs.input.md#abstract-getcredentialid)*

*Definido en [src/apis/platformvm/inputs.ts:186](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/inputs.ts#L186)*

**Retornos:** *número*

___

### getInputID

- **getInputID**(): *número*

*Superar [Input.getInputID](common_inputs.input.md)[](common_inputs.input.md#abstract-getinputid)*

*Definido en [src/apis/platformvm/inputs.ts:182](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/inputs.ts#L182)*

Devuelve el inputID para esta entrada

**Retornos:** *número*

___

### getSigIdxs

- **getSigIdxs**(): *[SigIdx](common_signature.sigidx.md)[]*

*Heredada de [Input](common_inputs.input.md).[getSigIdxs](common_inputs.input.md#getsigidxs)*

*Definido en [src/comm/input.ts:60](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/input.ts#L60)*

Devuelve la matriz de [SigIdx](common_signature.sigidx.md) para esta [entrada](common_inputs.input.md)

**Returns:** *[SigIdx](common_signature.sigidx.md)[]*

___

### getStakeableLocktime

- **getStakeableLocktime**(): *BN*

*Definido en [src/apis/platformvm/inputs.ts:172](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/inputs.ts#L172)*

**Returns:** *BN*

___

### getTransferablInput

- **getTransferablInput**(): *[ParseableInput](api_platformvm_inputs.parseableinput.md)*

*Definido en [src/apis/platformvm/inputs.ts:176](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/inputs.ts#L176)*

**Retornos:** Entrada *[ParseableInput](api_platformvm_inputs.parseableinput.md)*

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

*Resources [AmountInput](api_platformvm_inputs.amountinput.md).[select](api_platformvm_inputs.amountinput.md#select)*

*Definido en [src/apis/platformvm/inputs.ts:220](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/inputs.ts#L220)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `I.` | Número de números |
| `..args` | cualquier otra cosa que no sea[] |

**Retornos:** *[Entrada](common_inputs.input.md)*

___

### serializar

- **serialize**(`encoding`: [SerializedEncoding](../modules/src_utils.md#serializedencoding)): *objeto*

*Supera [StandardAmountInput](common_inputs.standardamountinput.md).[serialize](common_inputs.standardamountinput.md#serialize)*

*Definido en [src/apis/platformvm/inputs.ts:137](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/inputs.ts#L137)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `codificación` | [SerializedEncoding](../modules/src_utils.md#serializedencoding) | "hex" |

**Return:** *objeto*

___

### Sincronización `privada`

- **sincronize():** *vacío*

*Definido en [src/apis/platformvm/inputs.ts:163](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/inputs.ts#L163)*

**Retornos:** *vacío*

___

### toBuffer

- **toBuffer** (): *Buffer*

*Supera [StandardAmountInput](common_inputs.standardamountinput.md).[toBuffer](common_inputs.standardamountinput.md#tobuffer)*

*Definido en [src/apis/platformvm/inputs.ts:203](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/inputs.ts#L203)*

Devuelve el buffer que representa al [stakeableLockIn](api_platformvm_inputs.stakeablelockin.md) ejemplo.

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
