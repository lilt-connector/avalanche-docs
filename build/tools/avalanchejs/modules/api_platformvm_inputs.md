[avalanche](../README.md) › [API-PlatformVM-Inputs](api_platformvm_inputs.md)

# Módulo de entrada: API-PlatformVM-Inputs

## Índice de participación

### Clases de tipo

* [AmountInput](../classes/api_platformvm_inputs.amountinput.md)
* [Entrada ParseableInput](../classes/api_platformvm_inputs.parseableinput.md)
* [SECPTransferInput](../classes/api_platformvm_inputs.secptransferinput.md)
* [StakeableLockIn](../classes/api_platformvm_inputs.stakeablelockin.md)
* [Entrada transferible](../classes/api_platformvm_inputs.transferableinput.md)

### Variables

* [serialización](api_platformvm_inputs.md#const-serialization)

### Funciones de las Naciones Unidas

* [SelectInputClass](api_platformvm_inputs.md#const-selectinputclass)

## Variables

### `Consta` serialización

• **Serialización**: Serialización = *[Serialization](../classes/utils_serialization.serialization.md)*.getInstance()

*Definido en [src/apis/platformvm/inputs.ts:17](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/inputs.ts#L17)*

## Funciones de las Naciones Unidas

### `Const` SelectInputClass

- **SelectInputClass(inputid:**`` número, ..`args`: []SelectInputClass(inputid: *[Entrada](../classes/common_inputs.input.md)*

*Definido en [src/apis/platformvm/inputs.ts:26](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/inputs.ts#L26)*

Toma un buffer que representa la salida y devuelve la instancia [de entrada](../classes/common_inputs.input.md) adecuada.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `inputid` | Número de números | Un número que representa el inputID analizado antes de los bytes pasados |
| `..args` | cualquier otra cosa que no sea[] | - |

**Retornos:** *[Entrada](../classes/common_inputs.input.md)*

Una instancia de una clase [extendida por](../classes/common_inputs.input.md) entrada.
