[avalanche](../README.md) › Salida [API-EVM-Outputs](api_evm_outputs.md)

# Módulo de entrada: API-EVM-Outputs

## Índice de participación

### Clases de tipo

* [Producto de cantidad](../classes/api_evm_outputs.amountoutput.md)
* [EVMOutput](../classes/api_evm_outputs.evmoutput.md)
* [SECPTransferOutput](../classes/api_evm_outputs.secptransferoutput.md)
* [Producto transferible](../classes/api_evm_outputs.transferableoutput.md)

### Variables

* [bintools](api_evm_outputs.md#const-bintools)

### Funciones de las Naciones Unidas

* [SelectOutputClass](api_evm_outputs.md#const-selectoutputclass)

## Variables

### `Consta` de bintools

• **bintools**: *[BinTools](../classes/utils_bintools.bintools.md)* = BinTools.getInstance()

*Definido en [src/apis/evm/outputs.ts:14](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/outputs.ts#L14)*

## Funciones de las Naciones Unidas

### `Const` SelectOutputClass

- **SelectOutputClass**(`outputID`: número, ..`args`: []cualquiera): *[Salida](../classes/common_output.output.md)*

*Definido en [src/apis/evm/outputs.ts:23](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/outputs.ts#L23)*

Toma un buffer que representa la salida y devuelve la instancia de salida adecuada.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `outputID` | Número de números | Un número que representa el producto analizado antes de los bytes pasados |
| `..args` | cualquier otra cosa que no sea[] | - |

**Retornos:** *[Salida](../classes/common_output.output.md)*

Una instancia de una clase [extendida por la](src_common.md#output) salida.
