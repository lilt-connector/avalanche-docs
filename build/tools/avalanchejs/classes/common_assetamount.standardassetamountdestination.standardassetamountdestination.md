[avalancha](../README.md) › [Importe común](../modules/common_assetamount.md) › Importe de activos › [StandardAssetAmountDestination](common_assetamount.standardassetamountdestination.md)

# Clase: StandardAssetAmountDestination ‹**TO, TI**›

## Parámetros de tipo

• **A**: *[Producto estándar transferible](common_output.standardtransferableoutput.md)*

• **TI**: *[Entrada estándar](common_inputs.standardtransferableinput.md)* transferible.

## Jerarquía

* **StandardAssetAmountDestination**

   m [AssetAmountDestination](api_platformvm_utxos.assetamountdestination.md)

   m [AssetAmountDestination](api_avm_utxos.assetamountdestination.md)

   m [AssetAmountDestination](api_evm_utxos.assetamountdestination.md)

## Índice de participación

### Constructores

* [constructor](common_assetamount.standardassetamountdestination.md#constructor)

### Propiedades de las propiedades

* [amountkey](common_assetamount.standardassetamountdestination.md#protected-amountkey)
* [Monto](common_assetamount.standardassetamountdestination.md#protected-amounts)
* [Cambio de rollos](common_assetamount.standardassetamountdestination.md#protected-change)
* [changeAddresses](common_assetamount.standardassetamountdestination.md#protected-changeaddresses)
* [destinos de destino](common_assetamount.standardassetamountdestination.md#protected-destinations)
* [entradas](common_assetamount.standardassetamountdestination.md#protected-inputs)
* [Productos de la partida](common_assetamount.standardassetamountdestination.md#protected-outputs)
* [remitentes](common_assetamount.standardassetamountdestination.md#protected-senders)

### Métodos de trabajo

* [addAssetAmount](common_assetamount.standardassetamountdestination.md#addassetamount)
* [addChange](common_assetamount.standardassetamountdestination.md#addchange)
* [addInput](common_assetamount.standardassetamountdestination.md#addinput)
* [addOutput](common_assetamount.standardassetamountdestination.md#addoutput)
* [activos Existidos](common_assetamount.standardassetamountdestination.md#assetexists)
* [canComplete](common_assetamount.standardassetamountdestination.md#cancomplete)
* [getAllOutputs](common_assetamount.standardassetamountdestination.md#getalloutputs)
* [obtener cantidades](common_assetamount.standardassetamountdestination.md#getamounts)
* [getAssetAmount](common_assetamount.standardassetamountdestination.md#getassetamount)
* [getChangeAddresses](common_assetamount.standardassetamountdestination.md#getchangeaddresses)
* [getChangeOutputs](common_assetamount.standardassetamountdestination.md#getchangeoutputs)
* [getDestinations](common_assetamount.standardassetamountdestination.md#getdestinations)
* [getInputs](common_assetamount.standardassetamountdestination.md#getinputs)
* [getOutputs](common_assetamount.standardassetamountdestination.md#getoutputs)
* [getSenders](common_assetamount.standardassetamountdestination.md#getsenders)

## Constructores

### constructor

\+ **nuevo StandardAssetAmountDestination(destinations:**`` Buffer, `remitentes`: []Buffer, `StandardAssetAmountDestination(destinations`: [][]Buffer): *[StandardAssetAmountDestination(destinations:](common_assetamount.standardassetamountdestination.md)*

*Definido en [src/común/activosumount.ts:187](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/assetamount.ts#L187)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `destinos de destino` | Buffer[] |
| `remitentes` | Buffer[] |
| `changeAddresses` | Buffer[] |

**Returns:** *[StandardAssetAmountDestination](common_assetamount.standardassetamountdestination.md)*

## Propiedades de las propiedades

### amountkey `protegido`

• **amountkey**: *objeto*

*Definido en [src/común/activosumount.ts:114](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/assetamount.ts#L114)*

___

### Monto `protegido`

• **Cantidad**: *[Importe de activos](common_assetamount.assetamount.md)[]* =[]

*Definido en [src/común/activoamount.ts:110](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/assetamount.ts#L110)*

___

### Cambio `protegido`

• **cambio**: *A[]* =[]

*Definido en [src/común/activosumount.ts:117](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/assetamount.ts#L117)*

___

### Cambios `protegidos` Direcciones

• **changeAddresses**: *Buffer[]* =[]

*Definido en [src/común/activoamount.ts:113](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/assetamount.ts#L113)*

___

### Destinos `protegidos`

• **destinos**: *Buffer[]* =[]

*Definido en [src/común/activosumount.ts:111](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/assetamount.ts#L111)*

___

### Instancias `protegidas`

• **entrada**: *TI[]* =[]

*Definido en [src/común/activoamount.ts:115](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/assetamount.ts#L115)*

___

### Productos `protegidos`

• **salidas**: *A[]* =[]

*Definido en [src/común/activosumount.ts:116](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/assetamount.ts#L116)*

___

### Remitentes `protegidos`

• **remitentes**: *Buffer[]* =[]

*Definido en [src/común/activosumount.ts:112](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/assetamount.ts#L112)*

## Métodos de trabajo

### addAssetAmount

- **addAssetAmount**(`assetID`: Buffer, `cantidad`: BN, `quemar`: BN): *nulo*

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

- **addChange**(`output`: TO): *vacío*

*Definido en [src/común/activoamount.ts:135](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/assetamount.ts#L135)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `salida de la salida de la salida` | A LA HORA DE QUE |

**Retornos:** *vacío*

___

### addInput

- **addInput**(`input`: TI): *vacío*

*Definido en [src/común/activosumount.ts:127](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/assetamount.ts#L127)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `entrada en vigor de la entrada` | TI |

**Retornos:** *vacío*

___

### addOutput

- **addOutput**(`output`: TO): *vacío*

*Definido en [src/común/activosumount.ts:131](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/assetamount.ts#L131)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `salida de la salida de la salida` | A LA HORA DE QUE |

**Retornos:** *vacío*

___

### activos Existidos

- **assetExists**(`assetHexStr`: string): *boolean*

*Definido en [src/común/activoamount.ts:159](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/assetamount.ts#L159)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `assetHexStr` | cadena de producción |

**Return:** *booleano*

___

### canComplete

- **canComplete**(): *booleano*

*Definido en [src/común/activosumount.ts:179](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/assetamount.ts#L179)*

**Return:** *booleano*

___

### getAllOutputs

- **getAllOutputs**(): *A[]*

*Definido en [src/común/activoamount.ts:175](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/assetamount.ts#L175)*

**Return:** *A[]*

___

### obtener cantidades

- **getAmounts**(): *[Activo Importe](common_assetamount.assetamount.md)[]*

*Definido en [src/común/activosumount.ts:139](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/assetamount.ts#L139)*

**Retorno:** *[Importe de activos](common_assetamount.assetamount.md)[]*

___

### getAssetAmount

- **getAssetAmount**(`assetHexStr`: string): *[AssetAmount](common_assetamount.assetamount.md)*

*Definido en [src/común/activoamount.ts:155](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/assetamount.ts#L155)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `assetHexStr` | cadena de producción |

**Retorno:** *[Importe de activos](common_assetamount.assetamount.md)*

___

### getChangeAddresses

- **getChangeAddresses**(): *Buffer[]*

*Definido en [src/común/activoamount.ts:151](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/assetamount.ts#L151)*

**Returns:** *Buffer[]*

___

### getChangeOutputs

- **getChangeOutputs**(): *A[]*

*Definido en [src/común/activosumount.ts:171](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/assetamount.ts#L171)*

**Return:** *A[]*

___

### getDestinations

- **getDestinations**(): *Buffer[]*

*Definido en [src/común/activoamount.ts:143](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/assetamount.ts#L143)*

**Returns:** *Buffer[]*

___

### getInputs

- **getInputs**(): *TI[]*

*Definido en [src/común/activosumount.ts:163](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/assetamount.ts#L163)*

**Returns:** *TI[]*

___

### getOutputs

- **getOutputs**(): *A[]*

*Definido en [src/común/activosumount.ts:167](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/assetamount.ts#L167)*

**Return:** *A[]*

___

### getSenders

- **getSenders**(): *Buffer[]*

*Definido en [src/común/activosumount.ts:147](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/assetamount.ts#L147)*

**Returns:** *Buffer[]*
