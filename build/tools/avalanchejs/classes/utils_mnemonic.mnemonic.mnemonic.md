[avalancha](../README.md) › [Utils-Mnemonic](../modules/utils_mnemonic.md) › [Mnemonic](utils_mnemonic.mnemonic.md)

# Clase: Mnemonic

Código Mnemónico BIP39 para generar teclas deterministas.

## Jerarquía

* **Mnemonic**

## Índice de participación

### Constructores

* [constructor](utils_mnemonic.mnemonic.md#private-constructor)

### Propiedades de las propiedades

* [listas de palabras](utils_mnemonic.mnemonic.md#protected-wordlists)
* [instancia de parte de la](utils_mnemonic.mnemonic.md#static-private-instance)

### Métodos de trabajo

* [entropyToMnemonic](utils_mnemonic.mnemonic.md#entropytomnemonic)
* [generateMnemonic](utils_mnemonic.mnemonic.md#generatemnemonic)
* [getDefaultWordlist lista get](utils_mnemonic.mnemonic.md#getdefaultwordlist)
* [getWordlists](utils_mnemonic.mnemonic.md#getwordlists)
* [mnemonicToEntropy](utils_mnemonic.mnemonic.md#mnemonictoentropy)
* [mnemonicToSeed](utils_mnemonic.mnemonic.md#mnemonictoseed)
* [mnemonicToSeedSync](utils_mnemonic.mnemonic.md#mnemonictoseedsync)
* [setDefaultWordlist lista](utils_mnemonic.mnemonic.md#setdefaultwordlist)
* [validateMnemonic](utils_mnemonic.mnemonic.md#validatemnemonic)
* [getInstance](utils_mnemonic.mnemonic.md#static-getinstance)

## Constructores

### Constructor `privado`

\+ **nuevo Mnemonic():** *[Mnemonic](utils_mnemonic.mnemonic.md)*

*Definido en [src/utils/mnemonic.ts:17](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/mnemonic.ts#L17)*

**Returns:** *[Mnemonic](utils_mnemonic.mnemonic.md)*

## Propiedades de las propiedades

### Listas `de` palabras protegidas

• listas de palabras: *cadena[]* = bip39.**wordlists**

*Definido en [src/utils/mnemonic.ts:19](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/mnemonic.ts#L19)*

___

### Casación `privada` `estática`

• **instancia**: *[Mnemonic](utils_mnemonic.mnemonic.md)*

*Definido en [src/utils/mnemonic.ts:17](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/mnemonic.ts#L17)*

## Métodos de trabajo

### entropyToMnemonic

- **entropyToMnemonic**`(entropy`: Buffer | string, `wordlist?`: []string): *string*

*Definido en [src/utils/mnemonic.ts:92](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/mnemonic.ts#L92)*

Toma mnemonic y wordlist y devuelve buffer

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `entropía` | Buffer &#124; cadena | la entropía como un [Buffer](https://github.com/feross/buffer) o como una cuerda |
| `¿lista de palabras?` | cadena de producción[] | Opcional, la lista de palabras como una serie de cadenas |

**Return:** *string*

Una cuerda

___

### generateMnemonic

- **generateMnemonic**(`strength?`: número, `rng?`: función, `lista de` palabras?: []string): *string*

*Definido en [src/utils/mnemonic.ts:135](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/mnemonic.ts#L135) 135*

Generar un mnemónico aleatorio (utiliza crypto.randomBytes bajo la capucha), predeterminados a 256-bits de entropía

**Parámetros:**

`::` **Fuerza** opcional: *número*

Opcional la fuerza como un número

`::` R**ng:** *función*

Opcional el generador de números aleatorios. Defaults crypto.randomBytes

- (`tamaño`: número): *Buffer*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `tamaño de la talla` | Número de números |

`•` **Lista** de palabras opcionales: *cadena[]*

Opcional

**Return:** *string*

___

### getDefaultWordlist lista get

- **getDefaultWordlist**(): *string*

*Definido en [src/utils/mnemonic.ts:123](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/mnemonic.ts#L123)*

Devuelve el idioma de la lista de palabras predeterminada

**Return:** *string*

Una cuerda

___

### getWordlists

- **getWordlists**(`language?`: string): *string []| Wordlist*

*Definido en [src/utils/mnemonic.ts:38](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/mnemonic.ts#L38)*

Restablecer palabras

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `¿El lenguaje?` | cadena de producción | una cadena que especifica el idioma |

**Returns:** *string[] | Wordlist*

Un objeto [[Wordlist]] o una matriz de cadenas

___

### mnemonicToEntropy

- **mnemonicToEntropy**`(mnemonic`: string, `wordlist?`: []string): *string*

*Definido en [src/utils/mnemonic.ts:80](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/mnemonic.ts#L80)*

Toma mnemonic y wordlist y devuelve buffer

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `mnemonic` | cadena de producción | el mnemonic como una cuerda |
| `¿lista de palabras?` | cadena de producción[] | Opcional la lista de palabras como una variedad de cadenas |

**Return:** *string*

Una cuerda

___

### mnemonicToSeed

- **mnemonicToSeed**`(mnemonic`: string, `contraseña`: string): *Promise‹Buffer›*

*Definido en [src/utils/mnemonic.ts:67](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/mnemonic.ts#L67)*

Asynchronously toma mnemonic y contraseña y devuelve Promise<[Buffer](https://github.com/feross/buffer)>

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `mnemonic` | cadena de producción | - | el mnemonic como una cuerda |
| `contraseña` | cadena de producción | "" | la contraseña como una cadena |

**Returns:** *Promise‹Buffer›* ›

Un [buffer](https://github.com/feross/buffer)

___

### mnemonicToSeedSync

- **mnemonicToSeedSync**`(mnemonic`: string, `contraseña`: string): *Buffer*

*Definido en [src/utils/mnemonic.ts:54](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/mnemonic.ts#L54)*

Synchronously toma mnemonic y contraseña y devuelve [Buffer](https://github.com/feross/buffer)

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `mnemonic` | cadena de producción | - | el mnemonic como una cuerda |
| `contraseña` | cadena de producción | "" | la contraseña como una cadena |

**Returns:** *Buffer*

Un [buffer](https://github.com/feross/buffer)

___

### setDefaultWordlist lista

- **setDefaultWordlist**(`language`: string): *void*

*Definido en [src/utils/mnemonic.ts:114](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/mnemonic.ts#L114)*

Establece la lista de palabras predeterminada

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `lengua` | cadena de producción | el idioma como una cadena |

**Retornos:** *vacío*

___

### validateMnemonic

- **validateMnemonic**(`mnemonic`: string, `wordlist?`: []string): *string*

*Definido en [src/utils/mnemonic.ts:104](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/mnemonic.ts#L104)*

Valida un mnemónico 11*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `mnemonic` | cadena de producción | el mnemonic como una cuerda |
| `¿lista de palabras?` | cadena de producción[] | Opcional la lista de palabras como una variedad de cadenas |

**Return:** *string*

Una cuerda

___

### GetInstance `estática`

- **getInstance**(): *[Mnemonic](utils_mnemonic.mnemonic.md)*

*Definido en [src/utils/mnemonic.ts:24](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/mnemonic.ts#L24)*

Retrieves el singleton Mnemonic.

**Returns:** *[Mnemonic](utils_mnemonic.mnemonic.md)*
