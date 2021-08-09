[avalanche](../README.md) › Transacciones [API-AVM-Transactions](api_avm_transactions.md)

# Módulo de transacciones: API-AVM-Transactions

## Índice de participación

### Clases de tipo

* [Txx](../classes/api_avm_transactions.tx.md)
* [Sin UnsignedTx](../classes/api_avm_transactions.unsignedtx.md)

### Funciones de las Naciones Unidas

* [SelectTxClass](api_avm_transactions.md#const-selecttxclass)

## Funciones de las Naciones Unidas

### `Consta` SelectTxClass

- **SelectTxClass**(`txtype`: número, ...`args`: []any): *[BaseTx](../classes/api_avm_basetx.basetx.md)*

*Definido en [src/apis/avm/tx.ts:33](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/tx.ts#L33)*

Toma un buffer que representa la salida y devuelve la instancia de [BaseTx](../classes/api_platformvm_basetx.basetx.md) adecuada.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `txtype` | Número de números | El id del tipo de transacción |
| `..args` | cualquier otra cosa que no sea[] | - |

**Returns:** *[BaseTx](../classes/api_avm_basetx.basetx.md)*

Una instancia de una clase extendida por [BaseTx](../classes/api_platformvm_basetx.basetx.md)-extended
