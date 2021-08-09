[avalancha](../README.md) › [Comunes-SECP256k1KeyChain](../modules/common_secp256k1keychain.md)[](common_secp256k1keychain.secp256k1keychain.md) › SECP256k1KeyChain

# Clase: SECP256k1KeyChain ‹**SECPKPClass**›

Clase para representar una cadena de llavero en Avalanche.

**`typeparam`** Class extendiendo [StandardKeyPair](common_keychain.standardkeypair.md) que se utiliza como clave en [SECP256k1KeyChain](common_secp256k1keychain.secp256k1keychain.md)

## Parámetros de tipo

• **SECPKPClass**: *[SECP256k1Keypar](common_secp256k1keychain.secp256k1keypair.md)*

## Jerarquía

* [StandardKeyChain](common_keychain.standardkeychain.md)‹SECPKPClass›

   m. **SECP256k1KeyChain**

   de [la cadena de teclas](api_platformvm_keychain.keychain.md)

   de [la cadena de teclas](api_avm_keychain.keychain.md)

   de [la cadena de teclas](api_evm_keychain.keychain.md)

## Índice de participación

### Propiedades de las propiedades

* [importKey](common_secp256k1keychain.secp256k1keychain.md#importkey)
* [llaves](common_secp256k1keychain.secp256k1keychain.md#protected-keys)
* [makKK](common_secp256k1keychain.secp256k1keychain.md#makekey)

### Métodos de trabajo

* [addKey](common_secp256k1keychain.secp256k1keychain.md#addkey)
* [clon](common_secp256k1keychain.secp256k1keychain.md#abstract-clone)
* [crear un entorno de creación](common_secp256k1keychain.secp256k1keychain.md#abstract-create)
* [getAddressStrings](common_secp256k1keychain.secp256k1keychain.md#getaddressstrings)
* [getAddresses](common_secp256k1keychain.secp256k1keychain.md#getaddresses)
* [getKey](common_secp256k1keychain.secp256k1keychain.md#getkey)
* [hasKey](common_secp256k1keychain.secp256k1keychain.md#haskey)
* [removeKey](common_secp256k1keychain.secp256k1keychain.md#removekey)
* [Unión Europea](common_secp256k1keychain.secp256k1keychain.md#abstract-union)

## Propiedades de las propiedades

### importKey

• **importKey**: *función*

*Overrides [StandardKeyChain](common_keychain.standardkeychain.md).[importKey](common_keychain.standardkeychain.md#importkey)*

*Definido en [src/comm/secp256k1.ts:219](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/secp256k1.ts#L219)*

Dado una clave privada, hace un par de teclas nuevo, devuelve la dirección.

**`param`** A [Buffer](https://github.com/feross/buffer) o cb58 cadena serializada que representa la clave privada

**`devuelve`** Dirección del nuevo par de teclas

#### Declaración de tipo:

- (`privk`: Buffer | string): *SECPKPClass*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `privk` | Buffer &#124; cadena |

___

### Clavos `protegidos`

• **llaves**: *objeto*

*Heredado de [StandardKeyChain](common_keychain.standardkeychain.md).[keys](common_keychain.standardkeychain.md#protected-keys)*

*Definido en [src/común/llavero.ts:119](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/keychain.ts#L119)*

#### Declaración de tipo:

* \[ **dirección**: *string*\]: SECPKPClass

___

### makKK

• **makeKey**: *función*

*Superaciones [StandardKeyChain](common_keychain.standardkeychain.md).[makeKey](common_keychain.standardkeychain.md#makekey)*

*Definido en [src/comm/secp256k1.ts:206](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/secp256k1.ts#L206)*

Hace un par de claves nuevo, devuelve la dirección.

**`devuelve`** Dirección del nuevo par de teclas

#### Declaración de tipo:

- (): *SECPKPClass*

## Métodos de trabajo

### addKey

- **addKey**(`newKey`: SECPKPClass): *void*

*Supera [StandardKeyChain](common_keychain.standardkeychain.md).[addKey](common_keychain.standardkeychain.md#addkey)*

*Definido en [src/comm/secp256k1.ts:208](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/secp256k1.ts#L208)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `newKey` | SECPKPClass |

**Retornos:** *vacío*

___

### Clon `abstracto`

- **clone**(): *esto*

*Heredado de [StandardKeyChain](common_keychain.standardkeychain.md).[clone](common_keychain.standardkeychain.md#abstract-clone)*

*Definido en [src/comm/llavero.ts:205](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/keychain.ts#L205)*

**Returns:** *esto*

___

### `Crear, abstracta,`

*-* **create**(...`args`: []cualquiera

*Heredado de [StandardKeyChain](common_keychain.standardkeychain.md).[create](common_keychain.standardkeychain.md#abstract-create)*

*Definido en [src/común/llavero.ts:203](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/keychain.ts#L203)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `..args` | cualquier otra cosa que no sea[] |

**Returns:** *esto*

___

### getAddressStrings

- **getAddressStrings**(): *string[]*

*Heredado de [StandardKeyChain](common_keychain.standardkeychain.md).[getAddressStrings](common_keychain.standardkeychain.md#getaddressstrings)*

*Definido en [src/común/llavero.ts:150](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/keychain.ts#L150)*

Obtiene una serie de direcciones almacenadas en la Cadena [StandardKeyChain](common_keychain.standardkeychain.md).

**Return:** *string[]*

Una serie de representaciones de cadena de las direcciones

___

### getAddresses

- **gets():** *Buffer[]*

*Heredado de [StandardKeyChain](common_keychain.standardkeychain.md).[getAddresses](common_keychain.standardkeychain.md#getaddresses)*

*Definido en [src/común/llavero.ts:143](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/keychain.ts#L143)*

Obtiene una serie de direcciones almacenadas en la Cadena [StandardKeyChain](common_keychain.standardkeychain.md).

**Returns:** *Buffer[]*

Una serie de representaciones de [Buffer](https://github.com/feross/buffer) de las direcciones

___

### getKey

- **getKey**(`address`: Buffer): *SECPKPClass*

*Heredado de [StandardKeyChain](common_keychain.standardkeychain.md).[getKey](common_keychain.standardkeychain.md#getkey)*

*Definido en [src/comm/llavero.ts:201](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/keychain.ts#L201)*

Devuelve el [StandardKeyPair](common_keychain.standardkeypair.md) listado bajo la dirección proporcionada

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `Dirección de la dirección` | Buffer | El [Buffer](https://github.com/feross/buffer) de la dirección para recuperar de la base de datos de teclas |

**Returns:** *SECPKPClass*

Una referencia al [StandardKeyPair](common_keychain.standardkeypair.md) en la base de datos de teclas

___

### hasKey

- **hasKey**(`address`: Buffer): *boolean*

*Heredado de [StandardKeyChain](common_keychain.standardkeychain.md).[hasKey](common_keychain.standardkeychain.md#haskey)*

*Definido en [src/común/llavero.ts:191](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/keychain.ts#L191)*

Comprobaciones si hay una clave asociada a la dirección proporcionada.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `Dirección de la dirección` | Buffer | La dirección para verificar la existencia en la base de datos de teclas |

**Return:** *booleano*

Verdadero sobre el éxito, falso si no se encuentra

___

### removeKey

- **removeKey**(`key`: SECPKPClass | Buffer): *boolean*

*Heredado de [StandardKeyChain](common_keychain.standardkeychain.md).[removeKey](common_keychain.standardkeychain.md#removekey)*

*Definido en [src/común/llavero.ts:170](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/keychain.ts#L170)*

Elimina el par de teclas de la lista de las teclas administradas en la Cadena [StandardKeyChain](common_keychain.standardkeychain.md).

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `clave` | SECPKPClass &#124; Buffer | Un [buffer](https://github.com/feross/buffer) para la dirección o KPClass para eliminar |

**Return:** *booleano*

El booleano es cierto si se eliminó una llave.

___

### Unión `abstracta`

- **union**(`kc`: este): *esto*

*Heredado de [StandardKeyChain](common_keychain.standardkeychain.md).[union](common_keychain.standardkeychain.md#abstract-union)*

*Definido en [src/comm/llavero.ts:207](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/keychain.ts#L207)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `kc` | Esto es lo que es un problema |

**Returns:** *esto*
