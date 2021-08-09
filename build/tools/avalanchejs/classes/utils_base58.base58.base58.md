[avalanche](../README.md) › [Utiles-Base58](../modules/utils_base58.md)[](utils_base58.base58.md) › Base58

# Clase: Base58

Una clase Base58 que utiliza el módulo de Buffer multiplataforma. Construida para que el tipo aceptará el código.

```js
let b58:Base58 = new Base58();
let str:string = b58.encode(somebuffer);
let buff:Buffer = b58.decode(somestring);
```

## Jerarquía

* **Base58**

## Índice de participación

### Constructores

* [constructor](utils_base58.base58.md#private-constructor)

### Propiedades de las propiedades

* [alhabetIdx0](utils_base58.base58.md#protected-alphabetidx0)
* [b58](utils_base58.base58.md#protected-b58)
* [b58alfabeto](utils_base58.base58.md#protected-b58alphabet)
* [big58Radix](utils_base58.base58.md#protected-big58radix)
* [bigZero](utils_base58.base58.md#protected-bigzero)
* [instancia de parte de la](utils_base58.base58.md#static-private-instance)

### Métodos de trabajo

* [decodificación:](utils_base58.base58.md#decode)
* [codificador](utils_base58.base58.md#encode)
* [getInstance](utils_base58.base58.md#static-getinstance)

## Constructores

### Constructor `privado`

\+ **nuevo Base58():** *[Base58](utils_base58.base58.md)*

*Definido en [src/utils/base58.ts:21](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/base58.ts#L21)*

**Returns:** *[Base58](utils_base58.base58.md)*

## Propiedades de las propiedades

### AlfabetoIdx0 `protegido`

• **alfabetIdx0**: *cadena* = "1"

*Definido en [src/utils/base58.ts:37](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/base58.ts#L37)*

___

### b58 `protegido`

• **b58**: *número[]* =[ 255, 255, 25, 25, 2555, 25, 2, 25, 255, 2555, 25, 2555, 25, 255, 25, 255, 255, 2555, 25, 25, 255, 25, 255, 2555, 25, 255, 25, 255, 25, 255, 25555, 25, 255, 255, 25, 2, 25, 25, 2, 25, 25, 2555, 25, 2555, 2555, 25, 25555, 25, 255, 255, 2, 25, 25, 25, 2, 25, 25, 25, 2, 25, 255, 2, 255, 25, 2, 25, 2555, 25, 2, 25, 25, 255, 9, 10, 11, 12, 13, 14, 15, 16, 255, 17, 18, 19, 20, 21, 255, 22, 23, 24, 25, 26, 27, 28, 29, 30, 31, 32, 255, 255, 33, 34, 35, 36, 37, 39, 40, 41, 42, 43, 255, 45, 46, 47, 48, 49, 50, 51, 52, 54, 55, 255, 25, 25, 255, 255, 25, 9, 9, 2, 255, 1, 9, 1, 9, 25, 9, 4, 4, 1, 9, 255, 255, 4, 4447, 47, 25, 47, 25, 2555, 9, 9, 2555, 25, 255, 25, 255, 25, 9, 9, 255, 255, 255, 25, 2, 25, 9, 2, 9, 9, 25, 25, 9, 25, 9, 2, 2555, 9, 25, 255, 25555, 25, 255, 25, 2, 2555, 2, 255, 9, 9, 2, 4, 4, 9, 4, 4, 2555, 9, 25, 9, 9, 255, 44, 44, 9, 4, 24, 9, 9, 255, 2555, 4, 4, 1, 1, 1, 9, 1, 4, 4, 4, 2, 4, 44, 25, 1, 1, 9, 9, 25, 44, 4, 4, 44, 4, 2, 2, 9, 255, 255, 4, 44, 4, 9, 9, 9, 1, 9, 9, 1, 1, 1, 9, 9, 9, 444, 9, 9, 1, 1, 9, 9, 1, 1, 2551, 9, 1, 1, 9, 1, 1, 25, 25, 1, 1, 255, 1, 1, 9, 9, 9, 255, 255, 25, 255, 2555, 25, 255, 255, 25, 255, 255, 255, 255, 25, 2555, 25, 255, 255, 255, 255, 255, 25555, 25, 255, 2555, 25, 255, 255, 255, 25, 2555, 25, 255, 255, 255, 255, 255, 255, 25, 2555, 25, 255, 255, 255, 25, 255, 25555, 25, 25555, 25, 255, 255, 2555, 25, 2555, 25, 255, 2555, 25, 2555, 25, 255, 255, 255, 255, 255, 255, 255, 255, 25, 2555, 25, 25555, 25, 255, 255, 25, 25, 2, 25, 255, 255, 25 255, 255, 255, 2555, 25, 255, 2555, 25, 255, 255, 255, 255, 25, 255, 25, 255, 25, 255, 255, 255, 255, 25555, 25, 2555, 25, 255, 25, 2555, 25, 25, 255, 255, 2555, 25, 2555, 25, 255, 25, 255, 255, 255, 25, 2555, 255, 2555, 25, 2555, 2555, 255, 2555, 25, 25, 25555, 25, 2555, 25, 255, 25555, 25, 255, 2555, 25, 2555, 25, 255, 25, 2555, 25, 255, 25555, 25, 255, 255, 25555, 25, 255, 25, 2555, 2555, 25, 255, 25, 25555, 25, 2555, 255, 255, 25, 25, 2555, 2555, 25, 255, 2]

*Definido en [src/utils/base58.ts:39](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/base58.ts#L39)*

___

### b58alfabeto `protegido`

• **b58alfabeto**: *cadena* = "123456789ABCDEFGHJKLMNPQRSTUVWXYZabcdefghijkmnopqrstuvwxyz"

*Definido en [src/utils/base58.ts:35](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/base58.ts#L35)*

___

### `Protected` big58Radix

• **big58Radix**: *BN* = nuevo BN(58)

*Definido en [src/utils/base58.ts:74](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/base58.ts#L74)*

___

### `Protected`

• **bigZero**: *BN* = nuevo BN(0)

*Definido en [src/utils/base58.ts:76](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/base58.ts#L76)*

___

### Casación `privada` `estática`

• **instancia de la** *[base58](utils_base58.base58.md)*

*Definido en [src/utils/base58.ts:21](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/base58.ts#L21)*

## Métodos de trabajo

### decodificación:

- **decode**(`b`: string): *Buffer*

*Definido en [src/utils/base58.ts:110](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/base58.ts#L110)*

Decodifica una base-58 en un [buffet](https://github.com/feross/buffer)

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `b b` | cadena de producción | Una cadena base-58 para decodificar |

**Returns:** *Buffer*

Un [buffer](https://github.com/feross/buffer) de la cuerda decodificada.

___

### codificador

- **encode**(`buff`: Buffer): *string*

*Definido en [src/utils/base58.ts:85](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/base58.ts#L85)*

Encodes un [Buffer](https://github.com/feross/buffer) como una cadena base-58

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `buffet` | Buffer | Un [buffer](https://github.com/feross/buffer) para codificar |

**Return:** *string*

Una cuerda de base-58.

___

### GetInstance `estática`

- **getInstance**(): *[Base58](utils_base58.base58.md)*

*Definido en [src/utils/base58.ts:28](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/base58.ts#L28)*

Recupera el singleton Base58.

**Returns:** *[Base58](utils_base58.base58.md)*
