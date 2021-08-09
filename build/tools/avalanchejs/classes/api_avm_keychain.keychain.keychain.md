[avalancha](../README.md) › [API-AVM-KeyChain](../modules/api_avm_keychain.md) › [KeyChain](api_avm_keychain.keychain.md)

# Clase: KeyChain

Clase para representar una cadena de llavero en Avalanche.

**`typeparam`** Class extendiendo [SECP256k1KeyChain](common_secp256k1keychain.secp256k1keychain.md) que se utiliza como clave en [KeyChain](api_avm_keychain.keychain.md)

## Jerarquía

m. [SECP256k1KeyChain](common_secp256k1keychain.secp256k1keychain.md)‹[KeyPair](api_avm_keychain.keypair.md)›

de **la cadena de teclas**

## Índice de participación

### Constructores

* [constructor](api_avm_keychain.keychain.md#constructor)

### Propiedades de las propiedades

* [chainid](api_avm_keychain.keychain.md#chainid)
* [hrp](api_avm_keychain.keychain.md#hrp)
* [llaves](api_avm_keychain.keychain.md#protected-keys)

### Métodos de trabajo

* [addKey](api_avm_keychain.keychain.md#addkey)
* [clon](api_avm_keychain.keychain.md#clone)
* [crear un entorno de creación](api_avm_keychain.keychain.md#create)
* [getAddressStrings](api_avm_keychain.keychain.md#getaddressstrings)
* [getAddresses](api_avm_keychain.keychain.md#getaddresses)
* [getKey](api_avm_keychain.keychain.md#getkey)
* [hasKey](api_avm_keychain.keychain.md#haskey)
* [importKey](api_avm_keychain.keychain.md#importkey)
* [makKK](api_avm_keychain.keychain.md#makekey)
* [removeKey](api_avm_keychain.keychain.md#removekey)
* [Unión Europea](api_avm_keychain.keychain.md#union)

## Constructores

### constructor

\+ **nuevo KeyChain(hrp:**`` string, `chainid`: string): *[KeyChain](api_avm_keychain.keychain.md)*

*Definido en [src/apis/avm/llavero.ts:156](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/keychain.ts#L156)*

Devuelve la instancia de KeyChain.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `hrp` | cadena de producción |
| `chainid` | cadena de producción |

**Retornos:** *[KeyChain](api_avm_keychain.keychain.md)*

## Propiedades de las propiedades

### chainid

• **chainid**: *cadena* = ""

*Definido en [src/apis/avm/llavero.ts:95](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/keychain.ts#L95)*

___

### hrp

• **hrp**: *cadena* = ""

*Definido en [src/apis/avm/llavero.ts:94](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/keychain.ts#L94)*

___

### Clavos `protegidos`

• **llaves**: *objeto*

*Heredado de [StandardKeyChain](common_keychain.standardkeychain.md).[keys](common_keychain.standardkeychain.md#protected-keys)*

*Definido en [src/común/llavero.ts:119](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/keychain.ts#L119)*

#### Declaración de tipo:

* \[ **dirección**: *string*\]: [KeyPair](api_avm_keychain.keypair.md)

## Métodos de trabajo

### addKey

- **addKey**(`newKey`: [KeyPair](api_avm_keychain.keypair.md)): *vacío*

*Superaciones [SECP256k1KeyChain](common_secp256k1keychain.secp256k1keychain.md).[addKey](common_secp256k1keychain.secp256k1keychain.md#addkey)*

*Definido en [src/apis/avm/llavero.ts:108](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/keychain.ts#L108)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `newKey` | [Key-](api_avm_keychain.keypair.md) |

**Retornos:** *vacío*

___

### clon

- **clone**(): *esto*

*Superar [StandardKeyChain](common_keychain.standardkeychain.md).[clone](common_keychain.standardkeychain.md#abstract-clone)*

*Definido en [src/apis/avm/llavero.ts:142](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/keychain.ts#L142)*

**Returns:** *esto*

___

### crear un entorno de creación

*-* **create**(...`args`: []cualquiera

*Supera [StandardKeyChain](common_keychain.standardkeychain.md).[create](common_keychain.standardkeychain.md#abstract-create)*

*Definido en [src/apis/avm/llavero.ts:135](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/keychain.ts#L135)*

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

- **getKey**(`address`: Buffer): *[KeyPair](api_avm_keychain.keypair.md)*

*Heredado de [StandardKeyChain](common_keychain.standardkeychain.md).[getKey](common_keychain.standardkeychain.md#getkey)*

*Definido en [src/comm/llavero.ts:201](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/keychain.ts#L201)*

Devuelve el [StandardKeyPair](common_keychain.standardkeypair.md) listado bajo la dirección proporcionada

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `Dirección de la dirección` | Buffer | El [Buffer](https://github.com/feross/buffer) de la dirección para recuperar de la base de datos de teclas |

**Returns:** *[KeyPair](api_avm_keychain.keypair.md)*

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

### importKey

- **importKey**(`privk`: Buffer | string): *[KeyPair](api_avm_keychain.keypair.md)*

*Overrides [SECP256k1KeyChain](common_secp256k1keychain.secp256k1keychain.md).[importKey](common_secp256k1keychain.secp256k1keychain.md#importkey)*

*Definido en [src/apis/avm/llavero.ts:120](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/keychain.ts#L120)*

Dado una clave privada, hace un par de teclas nuevo, devuelve la dirección.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `privk` | Buffer &#124; cadena | Una cadena de [buffer](https://github.com/feross/buffer) o cb58 serializada que representa la clave privada |

**Returns:** *[KeyPair](api_avm_keychain.keypair.md)*

El nuevo par de claves

___

### makKK

- **makeKey**(): *[KeyPair](api_avm_keychain.keypair.md)*

*Superaciones [SECP256k1KeyChain](common_secp256k1keychain.secp256k1keychain.md).[makeKey](common_secp256k1keychain.secp256k1keychain.md#makekey)*

*Definido en [src/apis/avm/llavero.ts:102](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/keychain.ts#L102)*

Hace un par de claves nuevo, devuelve la dirección.

**Returns:** *[KeyPair](api_avm_keychain.keypair.md)*

El nuevo par de claves

___

### removeKey

- **removeKey**(`key`: [KeyPair](api_avm_keychain.keypair.md) | Buffer): *boolean*

*Heredado de [StandardKeyChain](common_keychain.standardkeychain.md).[removeKey](common_keychain.standardkeychain.md#removekey)*

*Definido en [src/común/llavero.ts:170](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/keychain.ts#L170)*

Elimina el par de teclas de la lista de las teclas administradas en la Cadena [StandardKeyChain](common_keychain.standardkeychain.md).

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `clave` | [KeyPair](api_avm_keychain.keypair.md) & #124; Buffer | Un [buffer](https://github.com/feross/buffer) para la dirección o KPClass para eliminar |

**Return:** *booleano*

El booleano es cierto si se eliminó una llave.

___

### Unión Europea

- **union**(`kc`: este): *esto*

*Supera [StandardKeyChain](common_keychain.standardkeychain.md).[union](common_keychain.standardkeychain.md#abstract-union)*

*Definido en [src/apis/avm/llavero.ts:150](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/keychain.ts#L150)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `kc` | Esto es lo que es un problema |

**Returns:** *esto*
