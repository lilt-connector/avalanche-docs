[avalancha](../README.md) › [src/utils](../modules/src_utils.md) › [AvalancheError](src_utils.avalancheerror.md)

# Clase: AvalancheError

## Jerarquía

* [Error](src_utils.avalancheerror.md#static-error)

   **m.**

   m. [AddressError](src_utils.addresserror.md)

   de [GooseEggCheckError](src_utils.gooseeggcheckerror.md)

   de [ChainIdError](src_utils.chainiderror.md)

   n° [NoAtomicUTXOsError](src_utils.noatomicutxoserror.md)

   de [Símbolo Error](src_utils.symbolerror.md)

   de [nombre Error](src_utils.nameerror.md)

   m. [TransactionError](src_utils.transactionerror.md)

   m. [CodecIdError](src_utils.codeciderror.md)

   de [CredIdError](src_utils.crediderror.md)

   [inmutable Error de salida transferible.](src_utils.transferableoutputerror.md)

   [↳ transferible](src_utils.transferableinputerror.md)

   [inputIdError](src_utils.inputiderror.md)

   [m.](src_utils.operationerror.md)

   [↳](src_utils.invalidoperationiderror.md)

   [m.](src_utils.checksumerror.md)

   de [OutputIdError](src_utils.outputiderror.md)

   de [UTXOError](src_utils.utxoerror.md)

   [↳](src_utils.insufficientfundserror.md)

   [m.](src_utils.thresholderror.md)

   inútil de [SECPMintOutputError](src_utils.secpmintoutputerror.md)

   [↳ de](src_utils.evminputerror.md) ↳

   [m.](src_utils.evmoutputerror.md)

   de [FeeAssetError](src_utils.feeasseterror.md) Error

   de [las partes interesadas Error](src_utils.stakeerror.md)

   de [timeError](src_utils.timeerror.md)

   [m.](src_utils.delegationfeeerror.md)

   m. [SubnetOwnerError](src_utils.subnetownererror.md)

   de [BufferSizeError](src_utils.buffersizeerror.md)

   [m.](src_utils.addressindexerror.md)

   [m.](src_utils.publickeyerror.md)

   [m. Error de fusión](src_utils.mergeruleerror.md)

   de [base58Error](src_utils.base58error.md)

   [m.](src_utils.privatekeyerror.md)

   m. [NodeIdError](src_utils.nodeiderror.md)

   [hexError](src_utils.hexerror.md)

   de [tipo Error](src_utils.typeiderror.md)

   de [tipo NameError](src_utils.typenameerror.md)

   [↳](src_utils.unknowntypeerror.md)

   m. [Bech32Error](src_utils.bech32error.md)

   [m.](src_utils.evmfeeerror.md)

   [↳](src_utils.invalidentropy.md)

## Índice de participación

### Constructores

* [constructor](src_utils.avalancheerror.md#constructor)

### Propiedades de las propiedades

* [errorCode](src_utils.avalancheerror.md#errorcode)
* [mensaje](src_utils.avalancheerror.md#message)
* [Nombre del nombre](src_utils.avalancheerror.md#name)
* [pila](src_utils.avalancheerror.md#optional-stack)
* [Error](src_utils.avalancheerror.md#static-error)

### Métodos de trabajo

* [getCode](src_utils.avalancheerror.md#getcode)

## Constructores

### constructor

\+ **nuevo** AvalancheError(`m`: string, `código`: string): *[AvalancheError](src_utils.avalancheerror.md)*

*Definido en [src/utils/errores.ts:44](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/errors.ts#L44)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `m` | cadena de producción |
| `código de conducta` | cadena de producción |

**Return:** *[AvalancheError](src_utils.avalancheerror.md)*

## Propiedades de las propiedades

### errorCode

• **errorCode**: *cadena*

*Definido en [src/utils/errores.ts:44](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/errors.ts#L44)*

___

### mensaje

• **mensaje**: *cadena*

*Heredado de [AvalancheError](src_utils.avalancheerror.md).[message](src_utils.avalancheerror.md#message)*

Definido en node_módulos/typarcript/lib/lib.es5.d.ts:974

___

### Nombre del nombre

• **nombre**: *cadena*

*Heredado de [AvalancheError](src_utils.avalancheerror.md).[name](src_utils.avalancheerror.md#name)*

Definido en node_módulos/typarcript/lib/lib.es5.d.ts:973

___

### Pila `opcional`

• **pila:** *cadena*

*Heredado de [AvalancheError](src_utils.avalancheerror.md).[stack](src_utils.avalancheerror.md#optional-stack)*

*Superar [AvalancheError](src_utils.avalancheerror.md).[stack](src_utils.avalancheerror.md#optional-stack)*

Definido en node_módulos/typarcript/lib/lib.es5.d.ts:975

___

### Error `estático`

• **Error**: *ErrorConstructor*

Definido en node_módulos/typarcript/lib/lib.es5.d.ts:984

## Métodos de trabajo

### getCode

- **getCode**(): *string*

*Definido en [src/utils/errores.ts:51](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/errors.ts#L51)*

**Return:** *string*
