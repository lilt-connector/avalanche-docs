[avalancha](../README.md) › Salida [común](../modules/common_output.md) › [Salida estándar](common_output.standardamountoutput.md)

# Clase: Salida estándar

Una clase [de salida](common_output.output.md) que especifica una cantidad de tokken.

## Jerarquía

de [salida](common_output.output.md)

m **StandardAmountOutput**

de [la cantidad de salida](api_platformvm_outputs.amountoutput.md)

de [la cantidad de salida](api_avm_outputs.amountoutput.md)

de [la cantidad de salida](api_evm_outputs.amountoutput.md)

## Índice de participación

### Constructores

* [constructor](common_output.standardamountoutput.md#constructor)

### Propiedades de las propiedades

* [_codecid](common_output.standardamountoutput.md#protected-_codecid)
* [_typeID](common_output.standardamountoutput.md#protected-_typeid)
* [_typeName](common_output.standardamountoutput.md#protected-_typename)
* [direcciones](common_output.standardamountoutput.md#protected-addresses)
* [importe de la cantidad de dinero](common_output.standardamountoutput.md#protected-amount)
* [amountValue](common_output.standardamountoutput.md#protected-amountvalue)
* [Tiempo de bloqueo](common_output.standardamountoutput.md#protected-locktime)
* [numaddrs](common_output.standardamountoutput.md#protected-numaddrs)
* [umbral](common_output.standardamountoutput.md#protected-threshold)

### Métodos de trabajo

* [clon](common_output.standardamountoutput.md#abstract-clone)
* [crear un entorno de creación](common_output.standardamountoutput.md#abstract-create)
* [deserie](common_output.standardamountoutput.md#deserialize)
* [deBuffer](common_output.standardamountoutput.md#frombuffer)
* [getAddress](common_output.standardamountoutput.md#getaddress)
* [getAddressIdx](common_output.standardamountoutput.md#getaddressidx)
* [getAddresses](common_output.standardamountoutput.md#getaddresses)
* [getAmount](common_output.standardamountoutput.md#getamount)
* [getCodecid](common_output.standardamountoutput.md#getcodecid)
* [getLocktime](common_output.standardamountoutput.md#getlocktime)
* [getOutputID](common_output.standardamountoutput.md#abstract-getoutputid)
* [getSpenders](common_output.standardamountoutput.md#getspenders)
* [getThreshold](common_output.standardamountoutput.md#getthreshold)
* [getTypeID](common_output.standardamountoutput.md#gettypeid)
* [getTypeName](common_output.standardamountoutput.md#gettypename)
* [Transferible](common_output.standardamountoutput.md#abstract-maketransferable)
* [MeetsThreshold](common_output.standardamountoutput.md#meetsthreshold)
* [seleccionar](common_output.standardamountoutput.md#abstract-select)
* [serializar](common_output.standardamountoutput.md#serialize)
* [toBuffer](common_output.standardamountoutput.md#tobuffer)
* [toString](common_output.standardamountoutput.md#tostring)
* [comparador](common_output.standardamountoutput.md#static-comparator)

## Constructores

### constructor

\+ **nuevo StandardAmountOutput(amount:**`` BN, `direcciones`: []Buffer, `tiempo de` bloqueo: BN, `umbral`: número): *[StandardAmountOutput](common_output.standardamountoutput.md)*

*Superpone [SECPOwnerOutput](api_platformvm_outputs.secpowneroutput.md).[constructor](api_platformvm_outputs.secpowneroutput.md#constructor)*

*Definido en [src/comm/output.ts:473](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/output.ts#L473)*

Una clase de salida [StandardAmountOutput](common_output.standardamountoutput.md) que emite un pago en un activo ID.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `importe de la cantidad de dinero` | BN | no definido. | Un [BN](https://github.com/indutny/bn.js/) que representa el importe en la salida |
| `direcciones` | Buffer[] | no definido. | Una serie de [buffers](https://github.com/feross/buffer) que representan direcciones |
| `Tiempo de bloqueo` | BN | no definido. | Un [BN](https://github.com/indutny/bn.js/) que representa el tiempo de bloqueo |
| `umbral` | Número de números | no definido. | Número que representa el número de firmantes necesarios para firmar la transacción |

**Retornos:** Producto *[StandardAmountOutput](common_output.standardamountoutput.md)*

## Propiedades de las propiedades

### _codecid `protegido`

• **_codecid**: *número* = indefinido.

*Heredada de [SigIdx](common_signature.sigidx.md)[._codecid](common_signature.sigidx.md#protected-_codecid)*

*Definido en [src/utils/serialización.ts:40](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/serialization.ts#L40)*

___

### `Protegido` _typeID

• **_typeID**: *any* = undefined

*Supera la [Output](common_output.output.md).[_typeID](common_output.output.md#protected-_typeid)*

*Definido en [src/comm/output.ts:431](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/output.ts#L431)*

___

### _typeName `protegido`

• **_typeName**: *string* = "StandardAmountOutput"

*Supera la [Output](common_output.output.md).[_typeName](common_output.output.md#protected-_typename)*

*Definido en [src/comm/output.ts:430](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/output.ts#L430)*

___

### Direcciones `protegidas`

• **direcciones**: *[Dirección](common_output.address.md)[]* =[]

*Heredado de la salida de [AmountOutput](api_platformvm_outputs.amountoutput.md).[addresses](api_platformvm_outputs.amountoutput.md#protected-addresses)*

*Definido en [src/comm/output.ts:121](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/output.ts#L121)*

___

### Cantidad `protegida`

• **cantidad**: *Buffer* = Buffer.aloc(8)

*Definido en [src/comm/output.ts:446](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/output.ts#L446)*

___

### Cantidad `Protected`

• **amountValue**: *BN* = nuevo BN(0)

*Definido en [src/comm/output.ts:447](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/output.ts#L447)*

___

### Tiempo `de` bloqueo protegido

• **tiempo de bloqueo**: *Buffer* = Buffer.aloc(8)

*Heredado de la cantidad [AmountOutput](api_platformvm_outputs.amountoutput.md).[locktime](api_platformvm_outputs.amountoutput.md#protected-locktime)*

*Definido en [src/comm/output.ts:118](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/output.ts#L118)*

___

### Numaddrs `protegidos`

• **numaddrs**: *Buffer* = Buffer.aloc(4)

*Heredada de la [AmountOutput](api_platformvm_outputs.amountoutput.md).[numaddrs](api_platformvm_outputs.amountoutput.md#protected-numaddrs)*

*Definido en [src/comm/output.ts:120](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/output.ts#L120)*

___

### Umbral `protegido`

• **umbral**: *Buffer* = Buffer.aloc(4)

*Heredada de la salida de [AmountOutput](api_platformvm_outputs.amountoutput.md).[threshold](api_platformvm_outputs.amountoutput.md#protected-threshold)*

*Definido en [src/comm/output.ts:119](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/output.ts#L119)*

## Métodos de trabajo

### Clon `abstracto`

- **clone**(): *esto*

*Heredada de la [AmountOutput](api_platformvm_outputs.amountoutput.md).[clone](api_platformvm_outputs.amountoutput.md#abstract-clone)*

*Definido en [src/comm/output.ts:319](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/output.ts#L319)*

**Returns:** *esto*

___

### `Crear, abstracta,`

*-* **create**(...`args`: []cualquiera

*Heredado de la [AmountOutput](api_platformvm_outputs.amountoutput.md).[create](api_platformvm_outputs.amountoutput.md#abstract-create)*

*Definido en [src/comm/output.ts:321](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/output.ts#L321)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `..args` | cualquier otra cosa que no sea[] |

**Returns:** *esto*

___

### deserie

- **deserialize**(`fields`: objeto, `codificación`: [SerializedEncoding](../modules/src_utils.md#serializedencoding)): *vacío*

*Superaciones [SECPOwnerOutput](api_platformvm_outputs.secpowneroutput.md).[deserialize](api_platformvm_outputs.secpowneroutput.md#deserialize)*

*Definido en [src/comm/output.ts:440](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/output.ts#L440)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `campos de cultivo` | objeto de la operación | - |
| `codificación` | [SerializedEncoding](../modules/src_utils.md#serializedencoding) | "hex" |

**Retornos:** *vacío*

___

### deBuffer

- **fromBuffer**(`outbuff`: Buffer, `offset`: número): *número*

*Superpone [SECPOwnerOutput](api_platformvm_outputs.secpowneroutput.md).[fromBuffer](api_platformvm_outputs.secpowneroutput.md#frombuffer)*

*Definido en [src/comm/output.ts:457](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/output.ts#L457)*

Popuates la instancia de un [Buffer](https://github.com/feross/buffer) que representa la [salida estándar](common_output.standardamountoutput.md) y devuelve el tamaño de la salida.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `outbuff` | Buffer | - |
| `offset` | Número de números | 0 |

**Retornos:** *número*

___

### getAddress

- **getAddress**(`idx`: número): *Buffer*

*Heredado de [AmountOutput](api_platformvm_outputs.amountoutput.md).[getAddress](api_platformvm_outputs.amountoutput.md#getaddress)*

*Definido en [src/comm/output.ts:168](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/output.ts#L168)*

Devuelve la dirección del índice proporcionado.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `idx` | Número de números | El índice de la dirección. |

**Returns:** *Buffer*

Devuelve la cadena que representa la dirección.

___

### getAddressIdx

- **getAddressIdx**(`address`: Buffer): *número*

*Heredado de [AmountOutput](api_platformvm_outputs.amountoutput.md).[getAddressIdx](api_platformvm_outputs.amountoutput.md#getaddressidx)*

*Definido en [src/comm/output.ts:151](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/output.ts#L151)*

Devuelve el índice de la dirección.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `Dirección de la dirección` | Buffer | Un [buffer](https://github.com/feross/buffer) de la dirección para buscar para devolver su índice. |

**Retornos:** *número*

El índice de la dirección.

___

### getAddresses

- **gets():** *Buffer[]*

*Heredado de [AmountOutput](api_platformvm_outputs.amountoutput.md).[getAddresses](api_platformvm_outputs.amountoutput.md#getaddresses)*

*Definido en [src/comm/output.ts:136](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/output.ts#L136)*

Devuelve una variedad de [Buffer](https://github.com/feross/buffer)s para las direcciones.

**Returns:** *Buffer[]*

___

### getAmount

- **getAmount**(): *BN*

*Definido en [src/comm/output.ts:452](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/output.ts#L452)*

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

### getLocktime

- **getLocktime**(): *BN*

*Heredado de [AmountOutput](api_platformvm_outputs.amountoutput.md).[getLocktime](api_platformvm_outputs.amountoutput.md#getlocktime)*

*Definido en [src/comm/output.ts:131](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/output.ts#L131)*

Devuelve la [marca de](https://github.com/indutny/bn.js/) tiempo UNIX cuando se pone a disposición el bloqueo.

**Returns:** *BN*

___

### `Resumen` getOutputID

- **getOutputID**(): *número*

*Heredada de la [AmountOutput](api_platformvm_outputs.amountoutput.md).[getOutputID](api_platformvm_outputs.amountoutput.md#abstract-getoutputid)*

*Definido en [src/comm/output.ts:317](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/output.ts#L317)*

Devuelve el outputID para la salida que le dice a los parsers qué tipo es

**Retornos:** *número*

___

### getSpenders

- **getSpenders**(`addresses`: []Buffer, `comode`: BN): *Buffer[]*

*Heredado de [AmountOutput](api_platformvm_outputs.amountoutput.md).[getSpenders](api_platformvm_outputs.amountoutput.md#getspenders)*

*Definido en [src/comm/output.ts:197](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/output.ts#L197)*

Dado una serie de direcciones y una marca de tiempo opcional, seleccione una variedad de direcciones [Buffer](https://github.com/feross/buffer)s de los proveedores cualificados para la salida.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `direcciones` | Buffer[] | - |
| `as.` | BN | no definido. |

**Returns:** *Buffer[]*

___

### getThreshold

- **getThreshold**(): *número*

*Heredado de la [AmountOutput](api_platformvm_outputs.amountoutput.md).[getThreshold](api_platformvm_outputs.amountoutput.md#getthreshold)*

*Definido en [src/comm/output.ts:126](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/output.ts#L126)*

Devuelve el umbral de los firmantes necesarios para gastar esta salida.

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

### Transferible hecho `abstracto`

- Transferible **makeTransferable**(`assetID`: Buffer): *[Producto estándar transferible](common_output.standardtransferableoutput.md)*

*Heredado de [Output](common_output.output.md).[makeTransferable](common_output.output.md#abstract-maketransferable)*

*Definido en [src/comm/output.ts:331](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/output.ts#L331)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `activos` | Buffer | Debe implementarse un activo que se envuelve alrededor del Buffer de la salida para utilizar el producto transferible apropiado para el VM. |

**Retornos:** *[Producto estándar transferible](common_output.standardtransferableoutput.md)*

___

### MeetsThreshold

- **meetsThreshold**(`addresses`: []Buffer, `comode`: BN): *booleano*

*Heredado de la [AmountOutput](api_platformvm_outputs.amountoutput.md).[meetsThreshold](api_platformvm_outputs.amountoutput.md#meetsthreshold)*

*Definido en [src/comm/output.ts:178](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/output.ts#L178)*

Dado una variedad de direcciones [Buffer](https://github.com/feross/buffer)s y una marca de tiempo opcional, devuelve cierto si las direcciones cumplen el umbral necesario para gastar la salida.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `direcciones` | Buffer[] | - |
| `as.` | BN | no definido. |

**Return:** *booleano*

___

### `Seleccione abstracto`

- **select**`(id`: número, ...`args`: []cualquier): *[Salida](common_output.output.md)*

*Heredado de [Output](common_output.output.md).[select](common_output.output.md#abstract-select)*

*Definido en [src/comm/output.ts:323](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/output.ts#L323)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `I.` | Número de números |
| `..args` | cualquier otra cosa que no sea[] |

**Retornos:** *[Salida](common_output.output.md)*

___

### serializar

- **serialize**(`encoding`: [SerializedEncoding](../modules/src_utils.md#serializedencoding)): *objeto*

*Supera [SECPOwnerOutput](api_platformvm_outputs.secpowneroutput.md).[serialize](api_platformvm_outputs.secpowneroutput.md#serialize)*

*Definido en [src/comm/output.ts:433](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/output.ts#L433)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `codificación` | [SerializedEncoding](../modules/src_utils.md#serializedencoding) | "hex" |

**Return:** *objeto*

___

### toBuffer

- **toBuffer** (): *Buffer*

*Superpone [SECPOwnerOutput](api_platformvm_outputs.secpowneroutput.md).[toBuffer](api_platformvm_outputs.secpowneroutput.md#tobuffer)*

*Definido en [src/comm/output.ts:467](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/output.ts#L467)*

Devuelve el buffer que representa la instancia [de salida estándar.](common_output.standardamountoutput.md)

**Returns:** *Buffer*

___

### toString

- **toString**(): *string*

*Heredado de la [AmountOutput](api_platformvm_outputs.amountoutput.md).[toString](api_platformvm_outputs.amountoutput.md#tostring)*

*Definido en [src/comm/output.ts:262](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/output.ts#L262)*

Devuelve una cadena base-58 que representa el [Salida](common_output.output.md).

**Return:** *string*

___

### Comparador `estático`

- **comparator**(): *función*

*Heredada de [AmountOutput](api_platformvm_outputs.amountoutput.md).[comparator](api_platformvm_outputs.amountoutput.md#static-comparator)*

*Definido en [src/comm/output.ts:266](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/output.ts#L266)*

**Retornos:** *función*

- (`a`: [Salida](common_output.output.md), `b`: [Salida):](common_output.output.md) *1 | -1 | 0*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `a a` | [Producción de productos](common_output.output.md) |
| `b b` | [Producción de productos](common_output.output.md) |
