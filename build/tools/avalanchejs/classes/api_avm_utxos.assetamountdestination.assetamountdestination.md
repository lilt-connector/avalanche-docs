[avalanche](../README.md) › [API-AVM-UTXOS](../modules/api_avm_utxos.md) › [AssetAmountDestination](api_avm_utxos.assetamountdestination.md)

# Clase: AssetAmountDestination

## Jerarquía

* [StandardAssetAmountDestination](common_assetamount.standardassetamountdestination.md)[‹TransferableOutput,](api_avm_inputs.transferableinput.md)[](api_avm_outputs.transferableoutput.md)

   m **AssetAmountDestination**

## Índice de participación

### Constructores

* [constructor](api_avm_utxos.assetamountdestination.md#constructor)

### Propiedades de las propiedades

* [amountkey](api_avm_utxos.assetamountdestination.md#protected-amountkey)
* [Monto](api_avm_utxos.assetamountdestination.md#protected-amounts)
* [Cambio de rollos](api_avm_utxos.assetamountdestination.md#protected-change)
* [changeAddresses](api_avm_utxos.assetamountdestination.md#protected-changeaddresses)
* [destinos de destino](api_avm_utxos.assetamountdestination.md#protected-destinations)
* [entradas](api_avm_utxos.assetamountdestination.md#protected-inputs)
* [Productos de la partida](api_avm_utxos.assetamountdestination.md#protected-outputs)
* [remitentes](api_avm_utxos.assetamountdestination.md#protected-senders)

### Métodos de trabajo

* [addAssetAmount](api_avm_utxos.assetamountdestination.md#addassetamount)
* [addChange](api_avm_utxos.assetamountdestination.md#addchange)
* [addInput](api_avm_utxos.assetamountdestination.md#addinput)
* [addOutput](api_avm_utxos.assetamountdestination.md#addoutput)
* [activos Existidos](api_avm_utxos.assetamountdestination.md#assetexists)
* [canComplete](api_avm_utxos.assetamountdestination.md#cancomplete)
* [getAllOutputs](api_avm_utxos.assetamountdestination.md#getalloutputs)
* [obtener cantidades](api_avm_utxos.assetamountdestination.md#getamounts)
* [getAssetAmount](api_avm_utxos.assetamountdestination.md#getassetamount)
* [getChangeAddresses](api_avm_utxos.assetamountdestination.md#getchangeaddresses)
* [getChangeOutputs](api_avm_utxos.assetamountdestination.md#getchangeoutputs)
* [getDestinations](api_avm_utxos.assetamountdestination.md#getdestinations)
* [getInputs](api_avm_utxos.assetamountdestination.md#getinputs)
* [getOutputs](api_avm_utxos.assetamountdestination.md#getoutputs)
* [getSenders](api_avm_utxos.assetamountdestination.md#getsenders)

## Constructores

### constructor

\+ **nuevo** `AssetAmountDestination(destinations`: Buffer, `remitentes`: []Buffer, `AssetAmountDestination(destinations`: [][]Buffer): *[AssetAmountDestination](api_avm_utxos.assetamountdestination.md)*

*Heredado de [StandardAssetAmountDestination](common_assetamount.standardassetamountdestination.md).[constructor](common_assetamount.standardassetamountdestination.md#constructor)*

*Definido en [src/común/activosumount.ts:187](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/assetamount.ts#L187)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `destinos de destino` | Buffer[] |
| `remitentes` | Buffer[] |
| `changeAddresses` | Buffer[] |

**Returns:** *[AssetAmountDestination](api_avm_utxos.assetamountdestination.md)*

## Propiedades de las propiedades

### amountkey `protegido`

• **amountkey**: *objeto*

*Heredado de [StandardAssetAmountDestination.amountkey StandardAssetAmountDestination.amountkey](common_assetamount.standardassetamountdestination.md)[](common_assetamount.standardassetamountdestination.md#protected-amountkey)*

*Definido en [src/común/activosumount.ts:114](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/assetamount.ts#L114)*

___

### Monto `protegido`

• **Cantidad**: *[Importe de activos](common_assetamount.assetamount.md)[]* =[]

*Heredado de [StandardAssetAmountDestination](common_assetamount.standardassetamountdestination.md).[amounts](common_assetamount.standardassetamountdestination.md#protected-amounts)*

*Definido en [src/común/activoamount.ts:110](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/assetamount.ts#L110)*

___

### Cambio `protegido`

• **cambio**: *[TransferableOutput](api_avm_outputs.transferableoutput.md)[]* =[]

*Heredado de [StandardAssetAmountDestination](common_assetamount.standardassetamountdestination.md).[change](common_assetamount.standardassetamountdestination.md#protected-change)*

*Definido en [src/común/activosumount.ts:117](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/assetamount.ts#L117)*

___

### Cambios `protegidos` Direcciones

• **changeAddresses**: *Buffer[]* =[]

*Heredado de [StandardAssetAmountDestination](common_assetamount.standardassetamountdestination.md).[changeAddresses](common_assetamount.standardassetamountdestination.md#protected-changeaddresses)*

*Definido en [src/común/activoamount.ts:113](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/assetamount.ts#L113)*

___

### Destinos `protegidos`

• **destinos**: *Buffer[]* =[]

*Heredado de [StandardAssetAmountDestination](common_assetamount.standardassetamountdestination.md).[destinations](common_assetamount.standardassetamountdestination.md#protected-destinations)*

*Definido en [src/común/activosumount.ts:111](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/assetamount.ts#L111)*

___

### Instancias `protegidas`

• **entradas**: *[TransferableInput](api_avm_inputs.transferableinput.md)[]* =[]

*Heredado de [StandardAssetAmountDestination](common_assetamount.standardassetamountdestination.md).[inputs](common_assetamount.standardassetamountdestination.md#protected-inputs)*

*Definido en [src/común/activoamount.ts:115](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/assetamount.ts#L115)*

___

### Productos `protegidos`

• **salida**: *[TransferableOutput](api_avm_outputs.transferableoutput.md)[]* =[]

*Heredado de [StandardAssetAmountDestination](common_assetamount.standardassetamountdestination.md).[outputs](common_assetamount.standardassetamountdestination.md#protected-outputs)*

*Definido en [src/común/activosumount.ts:116](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/assetamount.ts#L116)*

___

### Remitentes `protegidos`

• **remitentes**: *Buffer[]* =[]

*Heredado de [StandardAssetAmountDestination](common_assetamount.standardassetamountdestination.md).[senders](common_assetamount.standardassetamountdestination.md#protected-senders)*

*Definido en [src/común/activosumount.ts:112](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/assetamount.ts#L112)*

## Métodos de trabajo

### addAssetAmount

- **addAssetAmount**(`assetID`: Buffer, `cantidad`: BN, `quemar`: BN): *nulo*

*Heredado de [StandardAssetAmountDestination](common_assetamount.standardassetamountdestination.md).[addAssetAmount](common_assetamount.standardassetamountdestination.md#addassetamount)*

*Definido en [src/común/activosumount.ts:121](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/assetamount.ts#L121)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `activos` | Buffer |
| `importe de la cantidad de dinero` | BN |
| `quemarropa.` | BN |

**Retornos:** *vacío*

___

### addChange

- **addChange**(`output`: [TransferableOutput](api_avm_outputs.transferableoutput.md)): *vacío*

*Heredado de [StandardAssetAmountDestination](common_assetamount.standardassetamountdestination.md).[addChange](common_assetamount.standardassetamountdestination.md#addchange)*

*Definido en [src/común/activoamount.ts:135](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/assetamount.ts#L135)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `salida de la salida de la salida` | [Producto transferible](api_avm_outputs.transferableoutput.md) |

**Retornos:** *vacío*

___

### addInput

- **addInput**(`input`: [TransferableInput](api_avm_inputs.transferableinput.md)): *vacío*

*Heredado de [StandardAssetAmountDestination](common_assetamount.standardassetamountdestination.md).[addInput](common_assetamount.standardassetamountdestination.md#addinput)*

*Definido en [src/común/activosumount.ts:127](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/assetamount.ts#L127)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `entrada en vigor de la entrada` | [Entrada transferible](api_avm_inputs.transferableinput.md) |

**Retornos:** *vacío*

___

### addOutput

- **addOutput(output:**`` [addOutput(output:](api_avm_outputs.transferableoutput.md) *vacío*

*Heredado de [StandardAssetAmountDestination](common_assetamount.standardassetamountdestination.md).[addOutput](common_assetamount.standardassetamountdestination.md#addoutput)*

*Definido en [src/común/activosumount.ts:131](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/assetamount.ts#L131)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `salida de la salida de la salida` | [Producto transferible](api_avm_outputs.transferableoutput.md) |

**Retornos:** *vacío*

___

### activos Existidos

- **assetExists**(`assetHexStr`: string): *boolean*

*Heredado de [StandardAssetAmountDestination](common_assetamount.standardassetamountdestination.md).[assetExists](common_assetamount.standardassetamountdestination.md#assetexists)*

*Definido en [src/común/activoamount.ts:159](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/assetamount.ts#L159)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `assetHexStr` | cadena de producción |

**Return:** *booleano*

___

### canComplete

- **canComplete**(): *booleano*

*Heredado de [StandardAssetAmountDestination](common_assetamount.standardassetamountdestination.md).[canComplete](common_assetamount.standardassetamountdestination.md#cancomplete)*

*Definido en [src/común/activosumount.ts:179](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/assetamount.ts#L179)*

**Return:** *booleano*

___

### getAllOutputs

- **getAllOutputs**(): *[TransferableOutput](api_avm_outputs.transferableoutput.md)[]*

*Heredado de [StandardAssetAmountDestination](common_assetamount.standardassetamountdestination.md).[getAllOutputs](common_assetamount.standardassetamountdestination.md#getalloutputs)*

*Definido en [src/común/activoamount.ts:175](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/assetamount.ts#L175)*

**Retornos:** *[Producto transferible](api_avm_outputs.transferableoutput.md)[]*

___

### obtener cantidades

- **getAmounts**(): *[Activo Importe](common_assetamount.assetamount.md)[]*

*Heredado de [StandardAssetAmountDestination](common_assetamount.standardassetamountdestination.md).[getAmounts](common_assetamount.standardassetamountdestination.md#getamounts)*

*Definido en [src/común/activosumount.ts:139](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/assetamount.ts#L139)*

**Retorno:** *[Importe de activos](common_assetamount.assetamount.md)[]*

___

### getAssetAmount

- **getAssetAmount**(`assetHexStr`: string): *[AssetAmount](common_assetamount.assetamount.md)*

*Heredado de [StandardAssetAmountDestination](common_assetamount.standardassetamountdestination.md).[getAssetAmount](common_assetamount.standardassetamountdestination.md#getassetamount)*

*Definido en [src/común/activoamount.ts:155](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/assetamount.ts#L155)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `assetHexStr` | cadena de producción |

**Retorno:** *[Importe de activos](common_assetamount.assetamount.md)*

___

### getChangeAddresses

- **getChangeAddresses**(): *Buffer[]*

*Heredado de [StandardAssetAmountDestination](common_assetamount.standardassetamountdestination.md).[getChangeAddresses](common_assetamount.standardassetamountdestination.md#getchangeaddresses)*

*Definido en [src/común/activoamount.ts:151](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/assetamount.ts#L151)*

**Returns:** *Buffer[]*

___

### getChangeOutputs

- **getChangeOutputs**(): *[TransferableOutput](api_avm_outputs.transferableoutput.md)[]*

*Heredado de [StandardAssetAmountDestination](common_assetamount.standardassetamountdestination.md).[getChangeOutputs](common_assetamount.standardassetamountdestination.md#getchangeoutputs)*

*Definido en [src/común/activosumount.ts:171](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/assetamount.ts#L171)*

**Retornos:** *[Producto transferible](api_avm_outputs.transferableoutput.md)[]*

___

### getDestinations

- **getDestinations**(): *Buffer[]*

*Heredado de [StandardAssetAmountDestination](common_assetamount.standardassetamountdestination.md).[getDestinations](common_assetamount.standardassetamountdestination.md#getdestinations)*

*Definido en [src/común/activoamount.ts:143](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/assetamount.ts#L143)*

**Returns:** *Buffer[]*

___

### getInputs

- **getInputs():** *[getInputs():](api_avm_inputs.transferableinput.md)[]*

*Heredado de [StandardAssetAmountDestination](common_assetamount.standardassetamountdestination.md).[getInputs](common_assetamount.standardassetamountdestination.md#getinputs)*

*Definido en [src/común/activosumount.ts:163](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/assetamount.ts#L163)*

**Retornos:** *[Input transferible](api_avm_inputs.transferableinput.md)[]*

___

### getOutputs

- **getOutputs**(): *[TransferableOutput](api_avm_outputs.transferableoutput.md)[]*

*Heredado de [StandardAssetAmountDestination](common_assetamount.standardassetamountdestination.md).[getOutputs](common_assetamount.standardassetamountdestination.md#getoutputs)*

*Definido en [src/común/activosumount.ts:167](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/assetamount.ts#L167)*

**Retornos:** *[Producto transferible](api_avm_outputs.transferableoutput.md)[]*

___

### getSenders

- **getSenders**(): *Buffer[]*

*Heredado de [StandardAssetAmountDestination](common_assetamount.standardassetamountdestination.md).[getSenders](common_assetamount.standardassetamountdestination.md#getsenders)*

*Definido en [src/común/activosumount.ts:147](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/assetamount.ts#L147)*

**Returns:** *Buffer[]*
