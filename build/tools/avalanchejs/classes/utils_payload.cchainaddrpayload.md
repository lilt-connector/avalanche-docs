[avalanche](../README.md) › [Utils-Payload](../modules/utils_payload.md) › [CCHAINADDRPayload](utils_payload.cchainaddrpayload.md)

# Class: CCHAINADDRPayload

Class for payloads representing C-Chain addresses.

## Hierarchy

  ↳ [ChainAddressPayload](utils_payload.chainaddresspayload.md)

  ↳ **CCHAINADDRPayload**

## Index

### Constructors

* [constructor](utils_payload.cchainaddrpayload.md#constructor)

### Properties

* [chainid](utils_payload.cchainaddrpayload.md#protected-chainid)
* [payload](utils_payload.cchainaddrpayload.md#protected-payload)
* [typeid](utils_payload.cchainaddrpayload.md#protected-typeid)

### Methods

* [fromBuffer](utils_payload.cchainaddrpayload.md#frombuffer)
* [getContent](utils_payload.cchainaddrpayload.md#getcontent)
* [getPayload](utils_payload.cchainaddrpayload.md#getpayload)
* [returnChainID](utils_payload.cchainaddrpayload.md#returnchainid)
* [returnType](utils_payload.cchainaddrpayload.md#returntype)
* [toBuffer](utils_payload.cchainaddrpayload.md#tobuffer)
* [typeID](utils_payload.cchainaddrpayload.md#typeid)
* [typeName](utils_payload.cchainaddrpayload.md#typename)

## Constructors

###  constructor

\+ **new CCHAINADDRPayload**(`payload`: any, `hrp?`: string): *[CCHAINADDRPayload](utils_payload.cchainaddrpayload.md)*

*Inherited from [ChainAddressPayload](utils_payload.chainaddresspayload.md).[constructor](utils_payload.chainaddresspayload.md#constructor)*

*Overrides [PayloadBase](utils_payload.payloadbase.md).[constructor](utils_payload.payloadbase.md#constructor)*

*Defined in [src/utils/payload.ts:414](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/payload.ts#L414)*

**Parameters:**

Name | Type | Default | Description |
------ | ------ | ------ | ------ |
`payload` | any | undefined | Buffer or address string  |
`hrp?` | string | - | - |

**Returns:** *[CCHAINADDRPayload](utils_payload.cchainaddrpayload.md)*

## Properties

### `Protected` chainid

• **chainid**: *string* = "C"

*Overrides [ChainAddressPayload](utils_payload.chainaddresspayload.md).[chainid](utils_payload.chainaddresspayload.md#protected-chainid)*

*Defined in [src/utils/payload.ts:453](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/payload.ts#L453)*

___

### `Protected` payload

• **payload**: *Buffer* = Buffer.alloc(0)

*Inherited from [PayloadBase](utils_payload.payloadbase.md).[payload](utils_payload.payloadbase.md#protected-payload)*

*Defined in [src/utils/payload.ts:168](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/payload.ts#L168)*

___

### `Protected` typeid

• **typeid**: *number* = 8

*Overrides [ChainAddressPayload](utils_payload.chainaddresspayload.md).[typeid](utils_payload.chainaddresspayload.md#protected-typeid)*

*Defined in [src/utils/payload.ts:452](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/payload.ts#L452)*

## Methods

###  fromBuffer

▸ **fromBuffer**(`bytes`: Buffer, `offset`: number): *number*

*Inherited from [PayloadBase](utils_payload.payloadbase.md).[fromBuffer](utils_payload.payloadbase.md#frombuffer)*

*Defined in [src/utils/payload.ts:206](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/payload.ts#L206)*

Decodes the payload as a [Buffer](https://github.com/feross/buffer) including 4 bytes for the length and TypeID.

**Parameters:**

Name | Type | Default |
------ | ------ | ------ |
`bytes` | Buffer | - |
`offset` | number | 0 |

**Returns:** *number*

___

###  getContent

▸ **getContent**(): *Buffer*

*Inherited from [PayloadBase](utils_payload.payloadbase.md).[getContent](utils_payload.payloadbase.md#getcontent)*

*Defined in [src/utils/payload.ts:188](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/payload.ts#L188)*

Returns the payload content (minus typeID).

**Returns:** *Buffer*

___

###  getPayload

▸ **getPayload**(): *Buffer*

*Inherited from [PayloadBase](utils_payload.payloadbase.md).[getPayload](utils_payload.payloadbase.md#getpayload)*

*Defined in [src/utils/payload.ts:196](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/payload.ts#L196)*

Returns the payload (with typeID).

**Returns:** *Buffer*

___

###  returnChainID

▸ **returnChainID**(): *string*

*Inherited from [ChainAddressPayload](utils_payload.chainaddresspayload.md).[returnChainID](utils_payload.chainaddresspayload.md#returnchainid)*

*Defined in [src/utils/payload.ts:404](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/payload.ts#L404)*

Returns the chainid.

**Returns:** *string*

___

###  returnType

▸ **returnType**(`hrp`: string): *string*

*Inherited from [ChainAddressPayload](utils_payload.chainaddresspayload.md).[returnType](utils_payload.chainaddresspayload.md#returntype)*

*Overrides [PayloadBase](utils_payload.payloadbase.md).[returnType](utils_payload.payloadbase.md#abstract-returntype)*

*Defined in [src/utils/payload.ts:411](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/payload.ts#L411)*

Returns an address string for the payload.

**Parameters:**

Name | Type |
------ | ------ |
`hrp` | string |

**Returns:** *string*

___

###  toBuffer

▸ **toBuffer**(): *Buffer*

*Inherited from [PayloadBase](utils_payload.payloadbase.md).[toBuffer](utils_payload.payloadbase.md#tobuffer)*

*Defined in [src/utils/payload.ts:219](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/payload.ts#L219)*

Encodes the payload as a [Buffer](https://github.com/feross/buffer) including 4 bytes for the length and TypeID.

**Returns:** *Buffer*

___

###  typeID

▸ **typeID**(): *number*

*Inherited from [PayloadBase](utils_payload.payloadbase.md).[typeID](utils_payload.payloadbase.md#typeid)*

*Defined in [src/utils/payload.ts:174](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/payload.ts#L174)*

Returns the TypeID for the payload.

**Returns:** *number*

___

###  typeName

▸ **typeName**(): *string*

*Inherited from [PayloadBase](utils_payload.payloadbase.md).[typeName](utils_payload.payloadbase.md#typename)*

*Defined in [src/utils/payload.ts:181](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/payload.ts#L181)*

Returns the string name for the payload's type.

**Returns:** *string*
