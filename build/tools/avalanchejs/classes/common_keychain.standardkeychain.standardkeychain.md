[avalancha](../README.md) › [Common-KeyChain](../modules/common_keychain.md) › [StandardKeyChain](common_keychain.standardkeychain.md)

# Clase: StandardKeyChain ‹**KPClass**›

Clase para representar una cadena de llavero en Avalanche. Todos los puntos finales que necesitan cadenas clave deben extenderse en esta clase.

## Parámetros de tipo

• **KPClass**: *[StandardKeyPair](common_keychain.standardkeypair.md)*

extendiendo [StandardKeyPair](common_keychain.standardkeypair.md) que se utiliza como clave en [StandardKeyChain](common_keychain.standardkeychain.md)

## Jerarquía

* **StandardKeyChain**

   m. [SECP256k1KeyChain](common_secp256k1keychain.secp256k1keychain.md)

## Índice de participación

### Propiedades de las propiedades

* [importKey](common_keychain.standardkeychain.md#importkey)
* [llaves](common_keychain.standardkeychain.md#protected-keys)
* [makKK](common_keychain.standardkeychain.md#makekey)

### Métodos de trabajo

* [addKey](common_keychain.standardkeychain.md#addkey)
* [clon](common_keychain.standardkeychain.md#abstract-clone)
* [crear un entorno de creación](common_keychain.standardkeychain.md#abstract-create)
* [getAddressStrings](common_keychain.standardkeychain.md#getaddressstrings)
* [getAddresses](common_keychain.standardkeychain.md#getaddresses)
* [getKey](common_keychain.standardkeychain.md#getkey)
* [hasKey](common_keychain.standardkeychain.md#haskey)
* [removeKey](common_keychain.standardkeychain.md#removekey)
* [Unión Europea](common_keychain.standardkeychain.md#abstract-union)

## Propiedades de las propiedades

### importKey

• **importKey**: *función*

*Definido en [src/común/llavero.ts:135](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/keychain.ts#L135)*

Dado una clave privada, hace una nueva [StandardKeyPair](common_keychain.standardkeypair.md), devuelve la dirección.

**`param`** A [Buffer](https://github.com/feross/buffer) representando la clave privada

**`devuelve`** Un nuevo [StandardKeyPair](common_keychain.standardkeypair.md)

#### Declaración de tipo:

- (`privado`: Buffer): *KPClass*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `privk` | Buffer |

___

### Clavos `protegidos`

• **llaves**: *objeto*

*Definido en [src/común/llavero.ts:119](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/keychain.ts#L119)*

#### Declaración de tipo:

* \[ **dirección**: *string*\]: KPClass

___

### makKK

• **makeKey**: *función*

*Definido en [src/común/llavero.ts:126](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/keychain.ts#L126)*

Hace un nuevo [StandardKeyPair](common_keychain.standardkeypair.md), devuelve la dirección.

**`devuelve`** Dirección del nuevo [StandardKeyPair](common_keychain.standardkeypair.md)

#### Declaración de tipo:

- (): *KPClass*

## Métodos de trabajo

### addKey

- **addKey**(`newKey`: KPClass): *nul*

*Definido en [src/comm/llavero.ts:158](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/keychain.ts#L158)*

Añade el par de teclas a la lista de las teclas administradas en la Cadena [StandardKeyChain](common_keychain.standardkeychain.md).

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `newKey` | KPClass | Un par de claves de la clase apropiada que se añadirá a la Cadena [StandardKeyChain](common_keychain.standardkeychain.md) |

**Retornos:** *vacío*

___

### Clon `abstracto`

- **clone**(): *esto*

*Definido en [src/comm/llavero.ts:205](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/keychain.ts#L205)*

**Returns:** *esto*

___

### `Crear, abstracta,`

*-* **create**(...`args`: []cualquiera

*Definido en [src/común/llavero.ts:203](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/keychain.ts#L203)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `..args` | cualquier otra cosa que no sea[] |

**Returns:** *esto*

___

### getAddressStrings

- **getAddressStrings**(): *string[]*

*Definido en [src/común/llavero.ts:150](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/keychain.ts#L150)*

Obtiene una serie de direcciones almacenadas en la Cadena [StandardKeyChain](common_keychain.standardkeychain.md).

**Return:** *string[]*

Una serie de representaciones de cadena de las direcciones

___

### getAddresses

- **gets():** *Buffer[]*

*Definido en [src/común/llavero.ts:143](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/keychain.ts#L143)*

Obtiene una serie de direcciones almacenadas en la Cadena [StandardKeyChain](common_keychain.standardkeychain.md).

**Returns:** *Buffer[]*

Una serie de representaciones de [Buffer](https://github.com/feross/buffer) de las direcciones

___

### getKey

- **getKey**(`address`: Buffer): *KPClass*

*Definido en [src/comm/llavero.ts:201](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/keychain.ts#L201)*

Devuelve el [StandardKeyPair](common_keychain.standardkeypair.md) listado bajo la dirección proporcionada

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `Dirección de la dirección` | Buffer | El [Buffer](https://github.com/feross/buffer) de la dirección para recuperar de la base de datos de teclas |

**Returns:** *KPClass*

Una referencia al [StandardKeyPair](common_keychain.standardkeypair.md) en la base de datos de teclas

___

### hasKey

- **hasKey**(`address`: Buffer): *boolean*

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

- **removeKey**(`key`: KPClass | Buffer): *boolean*

*Definido en [src/común/llavero.ts:170](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/keychain.ts#L170)*

Elimina el par de teclas de la lista de las teclas administradas en la Cadena [StandardKeyChain](common_keychain.standardkeychain.md).

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `clave` | KPClass & #124; Buffer | Un [buffer](https://github.com/feross/buffer) para la dirección o KPClass para eliminar |

**Return:** *booleano*

El booleano es cierto si se eliminó una llave.

___

### Unión `abstracta`

- **union**(`kc`: este): *esto*

*Definido en [src/comm/llavero.ts:207](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/keychain.ts#L207)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `kc` | Esto es lo que es un problema |

**Returns:** *esto*
