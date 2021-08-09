[avalanche](../README.md) › [Utils-Payload](../modules/utils_payload.md) › [XCHAINADDRPayload](utils_payload.xchainaddrpayload.md)

# Clase: XCHAINADDRPayload

Clase para cargas útiles que representan direcciones X-Chin.

## Jerarquía

m. [ChainAddressPayload](utils_payload.chainaddresspayload.md) útil

m. **XCHAINADDRPayload** de pago

## Índice de participación

### Constructores

* [constructor](utils_payload.xchainaddrpayload.md#constructor)

### Propiedades de las propiedades

* [chainid](utils_payload.xchainaddrpayload.md#protected-chainid)
* [carga útil](utils_payload.xchainaddrpayload.md#protected-payload)
* [typeid](utils_payload.xchainaddrpayload.md#protected-typeid)

### Métodos de trabajo

* [deBuffer](utils_payload.xchainaddrpayload.md#frombuffer)
* [getContent](utils_payload.xchainaddrpayload.md#getcontent)
* [getPayload](utils_payload.xchainaddrpayload.md#getpayload)
* [returnChainID](utils_payload.xchainaddrpayload.md#returnchainid)
* [retorno.](utils_payload.xchainaddrpayload.md#returntype)
* [toBuffer](utils_payload.xchainaddrpayload.md#tobuffer)
* [typeID](utils_payload.xchainaddrpayload.md#typeid)
* [typeName](utils_payload.xchainaddrpayload.md#typename)

## Constructores

### constructor

\+ **nuevo XCHAINADDRPayload(payload: útil:**`` cualquiera de ellas, `hrp?`: string): *[XCHAINADDRPayload](utils_payload.xchainaddrpayload.md)*

*Heredado de [ChainAddressPayload](utils_payload.chainaddresspayload.md).[constructor](utils_payload.chainaddresspayload.md#constructor)*

*Desgravaciones [PayloadBase](utils_payload.payloadbase.md).[constructor](utils_payload.payloadbase.md#constructor)*

*Definido en [src/utils/payload.ts:414](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/payload.ts#L414)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `carga útil` | cualquier otra cosa que no sea | no definido. | Cadena de amortiguación o dirección |
| `¿hrp?` | cadena de producción | - | - |

**Returns:** *[XCHAINADDRPayload](utils_payload.xchainaddrpayload.md)*

## Propiedades de las propiedades

### chainid `protegido`

• **chainid**: *cadena* = "X"

*Descubrir [ChainAddressPayload](utils_payload.chainaddresspayload.md).[chainid](utils_payload.chainaddresspayload.md#protected-chainid)*

*Definido en [src/utils/payload.ts:437](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/payload.ts#L437)*

___

### Carga útil `protegida`

• **carga útil**: *Buffer* = Buffer.aloc(0)

*Heredado de [PayloadBase](utils_payload.payloadbase.md).[payload](utils_payload.payloadbase.md#protected-payload)*

*Definido en [src/utils/payload.ts:168](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/payload.ts#L168)*

___

### Tipo `protegido`

• **typeid**: *número* = 6

*Superaciones [ChainAddressPayload](utils_payload.chainaddresspayload.md).[typeid](utils_payload.chainaddresspayload.md#protected-typeid)*

*Definido en [src/utils/payload.ts:436](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/payload.ts#L436)*

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
