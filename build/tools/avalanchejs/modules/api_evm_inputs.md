[avalancha](../README.md) › [API-EVM-Inputs](api_evm_inputs.md)

# Módulo de entrada: API-EVM-Inputs

## Índice de participación

### Clases de tipo

* [AmountInput](../classes/api_evm_inputs.amountinput.md)
* [EVMInput](../classes/api_evm_inputs.evminput.md)
* [SECPTransferInput](../classes/api_evm_inputs.secptransferinput.md)
* [Entrada transferible](../classes/api_evm_inputs.transferableinput.md)

### Funciones de las Naciones Unidas

* [SelectInputClass](api_evm_inputs.md#const-selectinputclass)

## Funciones de las Naciones Unidas

### `Const` SelectInputClass

- **SelectInputClass**(`inputID`: número, ..`args`: []any): *[Entrada](../classes/common_inputs.input.md)*

*Definido en [src/apis/evm/inputs.ts:31](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/inputs.ts#L31)*

Toma un buffer que representa la salida y devuelve la instancia [de entrada](../classes/common_inputs.input.md) adecuada.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `inputID` | Número de números | Un número que representa el inputID analizado antes de los bytes pasados |
| `..args` | cualquier otra cosa que no sea[] | - |

**Retornos:** *[Entrada](../classes/common_inputs.input.md)*

Una instancia de una clase [extendida por](../classes/common_inputs.input.md) entrada.
