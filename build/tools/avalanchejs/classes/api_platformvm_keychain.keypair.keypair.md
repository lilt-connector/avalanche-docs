[avalanche](../README.md) › [API-PlatformVM-KeyChain](../modules/api_platformvm_keychain.md) › [KeyPair](api_platformvm_keychain.keypair.md)

# Clase: KeyPair

Clase para representar un par de teclas privado y público en la cadena de plataforma.

## Jerarquía

[m. SECP256k1Keypar](common_secp256k1keychain.secp256k1keypair.md)

m. **KeyPair**

## Índice de participación

### Constructores

* [constructor](api_platformvm_keychain.keypair.md#constructor)

### Propiedades de las propiedades

* [chainid](api_platformvm_keychain.keypair.md#protected-chainid)
* [hrp](api_platformvm_keychain.keypair.md#protected-hrp)
* [keypair](api_platformvm_keychain.keypair.md#protected-keypair)
* [privk](api_platformvm_keychain.keypair.md#protected-privk)
* [pubs](api_platformvm_keychain.keypair.md#protected-pubk)

### Métodos de trabajo

* [addressFromPublicKey](api_platformvm_keychain.keypair.md#addressfrompublickey)
* [clon](api_platformvm_keychain.keypair.md#clone)
* [crear un entorno de creación](api_platformvm_keychain.keypair.md#create)
* [generateKey](api_platformvm_keychain.keypair.md#generatekey)
* [getAddress](api_platformvm_keychain.keypair.md#getaddress)
* [getAddressString](api_platformvm_keychain.keypair.md#getaddressstring)
* [getChainID](api_platformvm_keychain.keypair.md#getchainid)
* [getHRP](api_platformvm_keychain.keypair.md#gethrp)
* [getPrivateKey](api_platformvm_keychain.keypair.md#getprivatekey)
* [getPrivateKeyString](api_platformvm_keychain.keypair.md#getprivatekeystring)
* [getPublicKey Key](api_platformvm_keychain.keypair.md#getpublickey)
* [getPublicKeyString](api_platformvm_keychain.keypair.md#getpublickeystring)
* [importKey](api_platformvm_keychain.keypair.md#importkey)
* [recupere la capacidad de recuperación](api_platformvm_keychain.keypair.md#recover)
* [setChainID](api_platformvm_keychain.keypair.md#setchainid)
* [setHRP](api_platformvm_keychain.keypair.md#sethrp)
* [señal de que la señal de que la](api_platformvm_keychain.keypair.md#sign)
* [verificar si se puede verificar si se puede verificar si](api_platformvm_keychain.keypair.md#verify)

## Constructores

### constructor

\+ **new KeyPair**(`hrp`: string, `chainid`: string): *[KeyPair](api_platformvm_keychain.keypair.md)*

*Overrides [SECP256k1KeyPair](common_secp256k1keychain.secp256k1keypair.md).[constructor](common_secp256k1keychain.secp256k1keypair.md#constructor)*

*Definido en [src/apis/platformvm/llavero.ts:79](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/keychain.ts#L79)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `hrp` | cadena de producción |
| `chainid` | cadena de producción |

**Returns:** *[KeyPair](api_platformvm_keychain.keypair.md)*

## Propiedades de las propiedades

### chainid `protegido`

• **chainid**: *cadena* = ""

*Definido en [src/apis/platformvm/llavero.ts:21](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/keychain.ts#L21)*

___

### hrp `protegido`

• **hrp**: *cadena* = ""

*Definido en [src/apis/platformvm/llavero.ts:22](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/keychain.ts#L22)*

___

### Keywords `protegidos`

• **keypair**: *elliptic.ec.KeyPair*

*Heredado de [SECP256k1KeyPair](common_secp256k1keychain.secp256k1keypair.md)[.keypair.keypair](common_secp256k1keychain.secp256k1keypair.md#protected-keypair)*

*Definido en [src/comm/secp256k1.ts:42](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/secp256k1.ts#L42)*

___

### Privk `protegido`

• **privk**: *Buffer*

*Heredado de [StandardKeyPair](common_keychain.standardkeypair.md).[privk](common_keychain.standardkeypair.md#protected-privk)*

*Definido en [src/común/llavero.ts:14](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/keychain.ts#L14)*

___

### Pub `protegida`

• **pubk**: *Buffer*

*Heredado de [StandardKeyPair](common_keychain.standardkeypair.md).[pubk](common_keychain.standardkeypair.md#protected-pubk)*

*Definido en [src/común/llavero.ts:13](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/keychain.ts#L13)*

## Métodos de trabajo

### addressFromPublicKey

- **addressFromPublicKey**(`pubk`: Buffer): *Buffer*

*Heredado de [SECP256k1KeyPair](common_secp256k1keychain.secp256k1keypair.md)[.addressFromPublicoKey](common_secp256k1keychain.secp256k1keypair.md#addressfrompublickey)*

*Definido en [src/comm/secp256k1.ts:108](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/secp256k1.ts#L108)*

Devuelve una dirección dada una clave pública.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `pubs` | Buffer | Un [buffer](https://github.com/feross/buffer) que representa la clave pública |

**Returns:** *Buffer*

Un [buffer](https://github.com/feross/buffer) para la dirección de la llave pública.

___

### clon

- **clone**(): *esto*

*Superaciones [StandardKeyPair](common_keychain.standardkeypair.md).[clone](common_keychain.standardkeypair.md#abstract-clone)*

*Definido en [src/apis/platformvm/llavero.ts:68](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/keychain.ts#L68)*

**Returns:** *esto*

___

### crear un entorno de creación

*-* **create**(...`args`: []cualquiera

*Overrides [StandardKeyPair](common_keychain.standardkeypair.md).[create](common_keychain.standardkeypair.md#abstract-create)*

*Definido en [src/apis/platformvm/llavero.ts:74](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/keychain.ts#L74)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `..args` | cualquier otra cosa que no sea[] |

**Returns:** *esto*

___

### generateKey

- **generateKey**(): *vacío*

*Heredado de [SECP256k1KeyPair](common_secp256k1keychain.secp256k1keypair.md).[generateKey](common_secp256k1keychain.secp256k1keypair.md#generatekey)*

*Overrides [StandardKeyPair.generateKey StandardKeyPair.generateKey](common_keychain.standardkeypair.md)[](common_keychain.standardkeypair.md#generatekey)*

*Definido en [src/comm/secp256k1.ts:62](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/secp256k1.ts#L62)*

Genera un nuevo par de teclas.

**Retornos:** *vacío*

___

### getAddress

- **getAddress**(): *Buffer*

*Heredada de [SECP256k1KeyPair](common_secp256k1keychain.secp256k1keypair.md).[getAddress](common_secp256k1keychain.secp256k1keypair.md#getaddress)*

*Overrides [StandardKeyPair](common_keychain.standardkeypair.md).[getAddress](common_keychain.standardkeypair.md#getaddress)*

*Definido en [src/comm/secp256k1.ts:90](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/secp256k1.ts#L90)*

Devuelve la dirección como [Buffer](https://github.com/feross/buffer).

**Returns:** *Buffer*

Una representación [de buffer](https://github.com/feross/buffer) de la dirección

___

### getAddressString

- **getAddressString**(): *string*

*Overrides [SECP256k1KeyPair](common_secp256k1keychain.secp256k1keypair.md)[.getDirecciónString](common_secp256k1keychain.secp256k1keypair.md#getaddressstring)*

*Definido en [src/apis/platformvm/llavero.ts:29](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/keychain.ts#L29)*

Devuelve la representación de cadena de la dirección.

**Return:** *string*

Una representación de cadena de la dirección

___

### getChainID

- **getChainID**(): *string*

*Definido en [src/apis/platformvm/llavero.ts:40](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/keychain.ts#L40)*

Devuelve la chainID asociada a esta clave.

**Return:** *string*

La cadena de identificación del [KeyPair](api_platformvm_keychain.keypair.md)

___

### getHRP

- **getHRP**(): *string*

*Definido en [src/apis/platformvm/llavero.ts:57](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/keychain.ts#L57)*

Devuelve la parte de la red de lectura humana asociada a esta clave.

**Return:** *string*

Parte de la línea de direccionamiento Bech32 de la red [KeyPair](api_platformvm_keychain.keypair.md)

___

### getPrivateKey

- **getPrivateKey**(): *Buffer*

*Heredado de [StandardKeyPair](common_keychain.standardkeypair.md).[getPrivateKey](common_keychain.standardkeypair.md#getprivatekey)*

*Definido en [src/común/llavero.ts:69](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/keychain.ts#L69)*

Devuelve una referencia a la llave privada.

**Returns:** *Buffer*

Un [buffer](https://github.com/feross/buffer) que contiene la clave privada

___

### getPrivateKeyString

- **getPrivateKeyString**(): *string*

*Heredado de [SECP256k1KeyPair](common_secp256k1keychain.secp256k1keypair.md).[getPrivateKeyString](common_secp256k1keychain.secp256k1keypair.md#getprivatekeystring)*

*Overrides [StandardKeyPair](common_keychain.standardkeypair.md).[getPrivateKeyString](common_keychain.standardkeypair.md#getprivatekeystring)*

*Definido en [src/comm/secp256k1.ts:127](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/secp256k1.ts#L127)*

Devuelve una representación de cadena de la llave privada.

**Return:** *string*

Una representación de cadena serializada cb58 de la clave privada

___

### getPublicKey Key

- **getPublicKey**(): *Buffer*

*Heredada de [StandardKeyPair](common_keychain.standardkeypair.md).[getPublicKey](common_keychain.standardkeypair.md#getpublickey)*

*Definido en [src/común/llavero.ts:76](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/keychain.ts#L76)*

Devuelve una referencia a la clave pública.

**Returns:** *Buffer*

Un [buffer](https://github.com/feross/buffer) que contiene la clave pública

___

### getPublicKeyString

- **getPublicKeyString**(): *string*

*Heredado de [SECP256k1KeyPair](common_secp256k1keychain.secp256k1keypair.md)[.getPublic KeyString](common_secp256k1keychain.secp256k1keypair.md#getpublickeystring)*

*Overrides [StandardKeyPair](common_keychain.standardkeypair.md).[getPublicKeyString](common_keychain.standardkeypair.md#getpublickeystring) KeyString*

*Definido en [src/comm/secp256k1.ts:136](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/secp256k1.ts#L136)*

Devuelve la llave pública.

**Return:** *string*

Una representación de cadena serializada cb58 de la clave pública

___

### importKey

- **importKey**(`privk`: Buffer): *boolean*

*Heredado de [SECP256k1KeyPair](common_secp256k1keychain.secp256k1keypair.md).[importKey](common_secp256k1keychain.secp256k1keypair.md#importkey)*

*Overrides [StandardKeyPair](common_keychain.standardkeypair.md).[importKey](common_keychain.standardkeypair.md#importkey)*

*Definido en [src/comm/secp256k1.ts:77](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/secp256k1.ts#L77)*

Importa una clave privada y genera la clave pública adecuada.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `privk` | Buffer | Un [buffer](https://github.com/feross/buffer) que representa la clave privada |

**Return:** *booleano*

verdad sobre el éxito, falso en el fracaso

___

### recupere la capacidad de recuperación

- **recover**(`msg`: Buffer, `sig`: Buffer): *Buffer*

*Heredada de [SECP256k1KeyPair](common_secp256k1keychain.secp256k1keypair.md)[.recove](common_secp256k1keychain.secp256k1keypair.md#recover)*

*Overrides [StandardKeyPair](common_keychain.standardkeypair.md).[recover](common_keychain.standardkeypair.md#recover)*

*Definido en [src/comm/secp256k1.ts:179](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/secp256k1.ts#L179)*

Recupera la clave pública de un firmante de mensaje de un mensaje y su firma asociada.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `ms.` | Buffer | El mensaje que ha firmado |
| `sig` | Buffer | La firma que ha firmado en el mensaje |

**Returns:** *Buffer*

Un [buffer](https://github.com/feross/buffer) que contiene la clave pública del firmante

___

### setChainID

- **setChainID**(`chainid`: string): *void*

*Definido en [src/apis/platformvm/llavero.ts:47](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/keychain.ts#L47)*

Establece la chainID asociada a esta llave.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `chainid` | cadena de producción | Cadena para la chainID |

**Retornos:** *vacío*

___

### setHRP

- **setHRP**(`hrp`: string): *void*

*Definido en [src/apis/platformvm/llavero.ts:64](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/keychain.ts#L64)*

Establece la parte de la red de lectura humana asociada a esta clave.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `hrp` | cadena de producción | Cadena para las direcciones de Bech32 legibles de lectura humana. |

**Retornos:** *vacío*

___

### señal de que la señal de que la

- **sign**(`msg`: Buffer): *Buffer*

*Heredado de [SECP256k1KeyPair](common_secp256k1keychain.secp256k1keypair.md).[sign](common_secp256k1keychain.secp256k1keypair.md#sign).*

*Superar [StandardKeyPair](common_keychain.standardkeypair.md).[sign](common_keychain.standardkeypair.md#sign).*

*Definido en [src/comm/secp256k1.ts:148](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/secp256k1.ts#L148)*

Toma un mensaje, firma y devuelve la firma.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `ms.` | Buffer | El mensaje a firmar, asegúrese de hash primero si se espera |

**Returns:** *Buffer*

Un [buffer](https://github.com/feross/buffer) que contiene la firma

___

### verificar si se puede verificar si se puede verificar si

- **verify**(`msg`: Buffer, `sig`: Buffer): *booleano*

*Heredado de [SECP256k1KeyPair](common_secp256k1keychain.secp256k1keypair.md)[.ver..](common_secp256k1keychain.secp256k1keypair.md#verify)*

*Overrides [StandardKeyPair](common_keychain.standardkeypair.md).[verify](common_keychain.standardkeypair.md#verify)*

*Definido en [src/comm/secp256k1.ts:166](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/secp256k1.ts#L166)*

Verifica que la clave privada asociada a la clave pública proporcionada produce la firma asociada al mensaje dado.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `ms.` | Buffer | El mensaje asociado a la firma |
| `sig` | Buffer | La firma del mensaje firmado |

**Return:** *booleano*

Verdadero sobre el éxito, falso en el fracaso
