[avalanche](../README.md) › [Utils-Payload](../modules/utils_payload.md) › [PCHAINADDRPayload](utils_payload.pchainaddrpayload.md)

# Clase: PCHAINADDRPayload

Clase para cargas útiles que representan direcciones de cadena P.

## Jerarquía

m. [ChainAddressPayload](utils_payload.chainaddresspayload.md) útil

m. **PCHAINADDRPayload** de pago

## Índice de participación

### Constructores

* [constructor](utils_payload.pchainaddrpayload.md#constructor)

### Propiedades de las propiedades

* [chainid](utils_payload.pchainaddrpayload.md#protected-chainid)
* [carga útil](utils_payload.pchainaddrpayload.md#protected-payload)
* [typeid](utils_payload.pchainaddrpayload.md#protected-typeid)

### Métodos de trabajo

* [deBuffer](utils_payload.pchainaddrpayload.md#frombuffer)
* [getContent](utils_payload.pchainaddrpayload.md#getcontent)
* [getPayload](utils_payload.pchainaddrpayload.md#getpayload)
* [returnChainID](utils_payload.pchainaddrpayload.md#returnchainid)
* [retorno.](utils_payload.pchainaddrpayload.md#returntype)
* [toBuffer](utils_payload.pchainaddrpayload.md#tobuffer)
* [typeID](utils_payload.pchainaddrpayload.md#typeid)
* [typeName](utils_payload.pchainaddrpayload.md#typename)

## Constructores

### constructor

\+ **nuevo PCHAINADDRPayload(payload: útil:***[](utils_payload.pchainaddrpayload.md)*`` cualquiera de ellas, `hrp?`: string): PCHAINADDRPayload

*Heredado de [ChainAddressPayload](utils_payload.chainaddresspayload.md).[constructor](utils_payload.chainaddresspayload.md#constructor)*

*Desgravaciones [PayloadBase](utils_payload.payloadbase.md).[constructor](utils_payload.payloadbase.md#constructor)*

*Definido en [src/utils/payload.ts:414](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/payload.ts#L414)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `carga útil` | cualquier otra cosa que no sea | no definido. | Cadena de amortiguación o dirección |
| `¿hrp?` | cadena de producción | - | - |

**Retornos:** *[PCHAINADDRPayload](utils_payload.pchainaddrpayload.md)*

## Propiedades de las propiedades

### chainid `protegido`

• **chainid**: *cadena* = "P"

*Descubrir [ChainAddressPayload](utils_payload.chainaddresspayload.md).[chainid](utils_payload.chainaddresspayload.md#protected-chainid)*

*Definido en [src/utils/payload.ts:445](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/payload.ts#L445)*

___

### Carga útil `protegida`

• **carga útil**: *Buffer* = Buffer.aloc(0)

*Heredado de [PayloadBase](utils_payload.payloadbase.md).[payload](utils_payload.payloadbase.md#protected-payload)*

*Definido en [src/utils/payload.ts:168](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/payload.ts#L168)*

___

### Tipo `protegido`

• **typeid**: *número* = 7

*Superaciones [ChainAddressPayload](utils_payload.chainaddresspayload.md).[typeid](utils_payload.chainaddresspayload.md#protected-typeid)*

*Definido en [src/utils/payload.ts:444](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/payload.ts#L444)*

## Métodos de trabajo

### deBuffer

- **fromBuffer**(`bytes`: Buffer, `offset`: número): *número*

*Heredada de [PayloadBase](utils_payload.payloadbase.md).[fromBuffer](utils_payload.payloadbase.md#frombuffer)*

*Definido en [src/utils/payload.ts:206](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/payload.ts#L206)*

Decodifica la carga útil como un [Buffer](https://github.com/feross/buffer) incluyendo 4 bytes para la longitud y TypeID.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `bytes` | Buffer | - |
| `offset` | Número de números | 0 |

**Retornos:** *número*

___

### getContent

- **getContent**(): *Buffer*

*Heredado de [PayloadBase](utils_payload.payloadbase.md).[getContent](utils_payload.payloadbase.md#getcontent)*

*Definido en [src/utils/payload.ts:188](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/payload.ts#L188)*

Devuelve el contenido de carga útil (menos typeID).

**Returns:** *Buffer*

___

### getPayload

- **getPayload**(): *Buffer*

*Heredado de [PayloadBase](utils_payload.payloadbase.md).[getPayload](utils_payload.payloadbase.md#getpayload)*

*Definido en [src/utils/payload.ts:196](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/payload.ts#L196)*

Devuelve la carga útil (con typeID).

**Returns:** *Buffer*

___

### returnChainID

- **returnChainID**(): *cadena*

*Heredado de [ChainAddressPayload](utils_payload.chainaddresspayload.md).[returnChainID](utils_payload.chainaddresspayload.md#returnchainid)*

*Definido en [src/utils/payload.ts:404](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/payload.ts#L404)*

Devuelve el chainid.

**Return:** *string*

___

### retorno.

- **returnType**(`hrp`: string): *string*

*Heredado de [ChainAddressPayload](utils_payload.chainaddresspayload.md).[returnType](utils_payload.chainaddresspayload.md#returntype)*

*Desgravaciones [PayloadBase](utils_payload.payloadbase.md).[returnType](utils_payload.payloadbase.md#abstract-returntype)*

*Definido en [src/utils/payload.ts:411](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/payload.ts#L411)*

Devuelve una cadena de dirección para la carga útil.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `hrp` | cadena de producción |

**Return:** *string*

___

### toBuffer

- **toBuffer** (): *Buffer*

*Heredada de [PayloadBase](utils_payload.payloadbase.md).[toBuffer](utils_payload.payloadbase.md#tobuffer)*

*Definido en [src/utils/payload.ts:219](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/payload.ts#L219)*

Encodes la carga útil como [Buffer](https://github.com/feross/buffer) incluyendo 4 bytes para la longitud y TypeID.

**Returns:** *Buffer*

___

### typeID

- **typeID**(): *número*

*Heredado de [PayloadBase](utils_payload.payloadbase.md).[typeID](utils_payload.payloadbase.md#typeid)*

*Definido en [src/utils/payload.ts:174](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/payload.ts#L174)*

Devuelve el TypeID para la carga útil.

**Retornos:** *número*

___

### typeName

- **typeName**(): *string*

*Heredado de [PayloadBase](utils_payload.payloadbase.md).[typeName](utils_payload.payloadbase.md#typename)*

*Definido en [src/utils/payload.ts:181](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/payload.ts#L181)*

Devuelve el nombre de cadena para el tipo de carga útil.

**Return:** *string*
