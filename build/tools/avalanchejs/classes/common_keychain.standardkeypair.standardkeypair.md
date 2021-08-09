[avalancha](../README.md) › [Common-KeyChain](../modules/common_keychain.md) › [StandardKeyPair](common_keychain.standardkeypair.md)

# Clase: StandardKeyPair

Clase para representar un keypair privado y público en Avalanche. Todas las API que necesitan pares clave deben extenderse en esta clase.

## Jerarquía

* **StandardKeyPair**

   [m. SECP256k1Keypar](common_secp256k1keychain.secp256k1keypair.md)

## Índice de participación

### Propiedades de las propiedades

* [generateKey](common_keychain.standardkeypair.md#generatekey)
* [getAddress](common_keychain.standardkeypair.md#getaddress)
* [getAddressString](common_keychain.standardkeypair.md#getaddressstring)
* [getPrivateKeyString](common_keychain.standardkeypair.md#getprivatekeystring)
* [getPublicKeyString](common_keychain.standardkeypair.md#getpublickeystring)
* [importKey](common_keychain.standardkeypair.md#importkey)
* [privk](common_keychain.standardkeypair.md#protected-privk)
* [pubs](common_keychain.standardkeypair.md#protected-pubk)
* [recupere la capacidad de recuperación](common_keychain.standardkeypair.md#recover)
* [señal de que la señal de que la](common_keychain.standardkeypair.md#sign)
* [verificar si se puede verificar si se puede verificar si](common_keychain.standardkeypair.md#verify)

### Métodos de trabajo

* [clon](common_keychain.standardkeypair.md#abstract-clone)
* [crear un entorno de creación](common_keychain.standardkeypair.md#abstract-create)
* [getPrivateKey](common_keychain.standardkeypair.md#getprivatekey)
* [getPublicKey Key](common_keychain.standardkeypair.md#getpublickey)

## Propiedades de las propiedades

### generateKey

• **generateKey**: *función*

*Definido en [src/común/llavero.ts:21](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/keychain.ts#L21)*

Genera un nuevo par de teclas.

**`param`** Parámetro opcional que puede ser necesario para producir teclas seguras

#### Declaración de tipo:

- (`entropía?`: Buffer): *vacío*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `¿entropía?` | Buffer |

___

### getAddress

• **getAddress**: *función*

*Definido en [src/común/llavero.ts:97](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/keychain.ts#L97)*

Devuelve la dirección.

**`devuelve`** Una representación [de buffer](https://github.com/feross/buffer) de la dirección

#### Declaración de tipo:

- (): *Buffer*

___

### getAddressString

• **getAddressString**: *función*

*Definido en [src/común/llavero.ts:104](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/keychain.ts#L104)*

Devuelve la representación de cadena de la dirección.

**`devuelve`** Una representación de cadena de la dirección

#### Declaración de tipo:

- (): *cadena*

___

### getPrivateKeyString

• **getPrivateKeyString**: *función*

*Definido en [src/común/llavero.ts:83](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/keychain.ts#L83)*

Devuelve una representación de cadena de la llave privada.

**`devuelve`** Una representación de cadena de la clave pública

#### Declaración de tipo:

- (): *cadena*

___

### getPublicKeyString

• **getPublicKeyString**: *función*

*Definido en [src/común/llavero.ts:90](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/keychain.ts#L90)*

Devuelve la llave pública.

**`devuelve`** Una representación de cadena de la clave pública

#### Declaración de tipo:

- (): *cadena*

___

### importKey

• **importKey**: *función*

*Definido en [src/común/llavero.ts:30](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/keychain.ts#L30)*

Importa una clave privada y genera la clave pública adecuada.

**`param`** A [Buffer](https://github.com/feross/buffer) representando la clave privada

**`retorna`** verdad sobre el éxito, falso en el fracaso

#### Declaración de tipo:

- (`privk`: Buffer): *booleano*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `privk` | Buffer |

___

### Privk `protegido`

• **privk**: *Buffer*

*Definido en [src/común/llavero.ts:14](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/keychain.ts#L14)*

___

### Pub `protegida`

• **pubk**: *Buffer*

*Definido en [src/común/llavero.ts:13](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/keychain.ts#L13)*

___

### recupere la capacidad de recuperación

• **recuperar**: *función*

*Definido en [src/común/llavero.ts:50](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/keychain.ts#L50)*

Recupera la clave pública de un firmante de mensaje de un mensaje y su firma asociada.

**`param`** El mensaje que ha firmado

**`param`** La firma que se ha firmado en el mensaje

**`devuelve`** Un [buffer](https://github.com/feross/buffer) que contiene el público clave del firmante

#### Declaración de tipo:

- (`msg`: Buffer, `sig`: Buffer): *Buffer*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `ms.` | Buffer |
| `sig` | Buffer |

___

### señal de que la señal de que la

• **señal**: *función*

*Definido en [src/comm/llavero.ts:39](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/keychain.ts#L39)*

Toma un mensaje, firma y devuelve la firma.

**`param`** El mensaje para firmar

**`devuelve`** Un [buffer](https://github.com/feross/buffer) que contiene la firma

#### Declaración de tipo:

- (`msg`: Buffer): *Buffer*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `ms.` | Buffer |

___

### verificar si se puede verificar si se puede verificar si

• **verificar**: *función*

*Definido en [src/común/llavero.ts:62](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/keychain.ts#L62)*

Verifica que la clave privada asociada a la clave pública proporcionada produce la firma asociada con el mensaje dado.

**`param`** El mensaje asociado a la firma

**`param`** La firma del mensaje firmado

**`param`** La clave pública asociada con la firma del mensaje

**`devuelve`** True on éxito, falsedad on fall

#### Declaración de tipo:

- (`msg`: Buffer, `sig`: Buffer, `pubk`: Buffer): *boolean*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `ms.` | Buffer |
| `sig` | Buffer |
| `pubs` | Buffer |

## Métodos de trabajo

### Clon `abstracto`

- **clone**(): *esto*

*Definido en [src/común/llavero.ts:108](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/keychain.ts#L108)*

**Returns:** *esto*

___

### `Crear, abstracta,`

*-* **create**(...`args`: []cualquiera

*Definido en [src/común/llavero.ts:106](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/keychain.ts#L106)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `..args` | cualquier otra cosa que no sea[] |

**Returns:** *esto*

___

### getPrivateKey

- **getPrivateKey**(): *Buffer*

*Definido en [src/común/llavero.ts:69](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/keychain.ts#L69)*

Devuelve una referencia a la llave privada.

**Returns:** *Buffer*

Un [buffer](https://github.com/feross/buffer) que contiene la clave privada

___

### getPublicKey Key

- **getPublicKey**(): *Buffer*

*Definido en [src/común/llavero.ts:76](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/keychain.ts#L76)*

Devuelve una referencia a la clave pública.

**Returns:** *Buffer*

Un [buffer](https://github.com/feross/buffer) que contiene la clave pública
