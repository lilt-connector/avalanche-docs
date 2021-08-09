[avalancha](../README.md) › [Importe común](../modules/common_assetamount.md) › [Importe de activos › Importe de activos](common_assetamount.assetamount.md)

# Clase: Importe de activos

Clase para la gestión de los montos de activos en la calcuation de tasas UTXOSet

## Jerarquía

* **Importe de activos**

## Índice de participación

### Constructores

* [constructor](common_assetamount.assetamount.md#constructor)

### Propiedades de las propiedades

* [importe de la cantidad de dinero](common_assetamount.assetamount.md#protected-amount)
* [activos](common_assetamount.assetamount.md#protected-assetid)
* [quemarropa.](common_assetamount.assetamount.md#protected-burn)
* [Cambio de rollos](common_assetamount.assetamount.md#protected-change)
* [Terminado](common_assetamount.assetamount.md#protected-finished)
* [gastado en el gasto.](common_assetamount.assetamount.md#protected-spent)
* [stakeableLockChange](common_assetamount.assetamount.md#protected-stakeablelockchange)
* [Arancel](common_assetamount.assetamount.md#protected-stakeablelockspent)

### Métodos de trabajo

* [getAmount](common_assetamount.assetamount.md#getamount)
* [getAssetID](common_assetamount.assetamount.md#getassetid)
* [getAssetIDString](common_assetamount.assetamount.md#getassetidstring)
* [getBurn](common_assetamount.assetamount.md#getburn)
* [getChange](common_assetamount.assetamount.md#getchange)
* [getSpent](common_assetamount.assetamount.md#getspent)
* [getStakeableLockChange](common_assetamount.assetamount.md#getstakeablelockchange)
* [getStakeableLockSpent](common_assetamount.assetamount.md#getstakeablelockspent)
* [isFinished](common_assetamount.assetamount.md#isfinished)
* [Monto de gasto](common_assetamount.assetamount.md#spendamount)

## Constructores

### constructor

\+ **nuevo Activo AssetAmount(assetID:***[](common_assetamount.assetamount.md)*`` Buffer, `cantidad`: BN, `quemar`: BN): Activo Importe

*Definido en [src/común/activoamount.ts:97](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/assetamount.ts#L97)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `activos` | Buffer |
| `importe de la cantidad de dinero` | BN |
| `quemarropa.` | BN |

**Retorno:** *[Importe de activos](common_assetamount.assetamount.md)*

## Propiedades de las propiedades

### Cantidad `protegida`

• **cantidad**: *BN* = nuevo BN(0)

*Definido en [src/común/activoamount.ts:19](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/assetamount.ts#L19)*

___

### assetID `protegido`

• **assetID**: *Buffer* = Buffer.aloc(32)

*Definido en [src/común/activosumount.ts:17](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/assetamount.ts#L17)*

___

### burn `protegida`

• **quemar**: *BN* = nuevo BN(0)

*Definido en [src/común/activoamount.ts:21](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/assetamount.ts#L21)*

___

### Cambio `protegido`

• **cambio**: *BN* = nuevo BN(0)

*Definido en [src/común/activoamount.ts:31](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/assetamount.ts#L31)*

___

### Acabado `protegido`

• **terminado**: *booleano* = falso

*Definido en [src/común/activoamount.ts:37](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/assetamount.ts#L37)*

___

### `Pasos protegidos`

• **gastado**: *BN* = nuevo BN(0)

*Definido en [src/común/activoamount.ts:24](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/assetamount.ts#L24)*

___

### `Protegido` de la stakeableLockChange

• **stakeableLockChange**: *boolean* = false

*Definido en [src/común/activoamount.ts:34](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/assetamount.ts#L34)*

___

### `Protected` stakeableLockSpent

• **stakeableLockSpent**: *BN* = nuevo BN(0)

*Definido en [src/común/activoamount.ts:27](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/assetamount.ts#L27)*

## Métodos de trabajo

### getAmount

- **getAmount**(): *BN*

*Definido en [src/común/activosumount.ts:47](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/assetamount.ts#L47)*

**Returns:** *BN*

___

### getAssetID

- **getAssetID**(): *Buffer*

*Definido en [src/común/activoamount.ts:39](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/assetamount.ts#L39)*

**Returns:** *Buffer*

___

### getAssetIDString

- **getAssetIDString**(): *string*

*Definido en [src/común/activoamount.ts:43](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/assetamount.ts#L43)*

**Return:** *string*

___

### getBurn

- **getBurn**(): *BN*

*Definido en [src/común/activoamount.ts:55](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/assetamount.ts#L55)*

**Returns:** *BN*

___

### getChange

- **getChange**(): *BN*

*Definido en [src/común/activoamount.ts:59](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/assetamount.ts#L59)*

**Returns:** *BN*

___

### getSpent

- **getSpent**(): *BN*

*Definido en [src/común/activoamount.ts:51](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/assetamount.ts#L51)*

**Returns:** *BN*

___

### getStakeableLockChange

- **getStakeableLockChange**(): *boolean*

*Definido en [src/común/activosumount.ts:67](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/assetamount.ts#L67)*

**Return:** *booleano*

___

### getStakeableLockSpent

- **getStakeableLockSpent**(): *BN*

*Definido en [src/común/activoamount.ts:63](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/assetamount.ts#L63)*

**Returns:** *BN*

___

### isFinished

- **isFinished**(): *booleano*

*Definido en [src/común/activosumount.ts:71](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/assetamount.ts#L71)*

**Return:** *booleano*

___

### Monto de gasto

- **spendAmount(amt:**`` BN, `spendAmount(amt`: booleano): *booleano*

*Definido en [src/común/activosumount.ts:77](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/assetamount.ts#L77)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `amt` | BN | - |
| `Apuesta` | booleano | falso |

**Return:** *booleano*
