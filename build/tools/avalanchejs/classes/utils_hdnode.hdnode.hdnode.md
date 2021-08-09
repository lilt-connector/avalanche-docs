[avalancha](../README.md) › [Utils-HDNode](../modules/utils_hdnode.md) › [HDNode](utils_hdnode.hdnode.md)

# Clase: HDNode

BIP32 teclas deterministas jerárquicos.

## Jerarquía

* **HDNode**

## Índice de participación

### Constructores

* [constructor](utils_hdnode.hdnode.md#constructor)

### Propiedades de las propiedades

* [chainCode de chainCode](utils_hdnode.hdnode.md#chaincode)
* [hdkey](utils_hdnode.hdnode.md#private-hdkey)
* [privateExtendedKey](utils_hdnode.hdnode.md#privateextendedkey)
* [privateKey](utils_hdnode.hdnode.md#privatekey)
* [privadoKeyCB58](utils_hdnode.hdnode.md#privatekeycb58)
* [publicExtendedKey](utils_hdnode.hdnode.md#publicextendedkey)
* [publicKey](utils_hdnode.hdnode.md#publickey)

### Métodos de trabajo

* [deriven de la](utils_hdnode.hdnode.md#derive)
* [señal de que la señal de que la](utils_hdnode.hdnode.md#sign)
* [verificar si se puede verificar si se puede verificar si](utils_hdnode.hdnode.md#verify)
* [wipePrivateData](utils_hdnode.hdnode.md#wipeprivatedata)

## Constructores

### constructor

\+ **nuevo HDNode(from:**`` cadena | Buffer): *[HDNode](utils_hdnode.hdnode.md)*

*Definido en [src/utils/hdnode.ts:70](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/hdnode.ts#L70)*

Crea un HDNode de una semilla maestra o una clave pública / privada extendida

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `de la` | string &#124; Buffer | semillas o clave para crear HDNode desde |

**Retornos:** *[HDNode](utils_hdnode.hdnode.md)*

## Propiedades de las propiedades

### chainCode de chainCode

• **chainCode**: *Buffer*

*Definido en [src/utils/hdnode.ts:20](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/hdnode.ts#L20)*

___

### hdkey `privado`

• **hdkey**: *cualquier*

*Definido en [src/utils/hdnode.ts:16](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/hdnode.ts#L16)*

___

### privateExtendedKey

• **privateExtendedKey**: *cadena*

*Definido en [src/utils/hdnode.ts:21](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/hdnode.ts#L21)*

___

### privateKey

• **privateKey**: *Buffer*

*Definido en [src/utils/hdnode.ts:18](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/hdnode.ts#L18)*

___

### privadoKeyCB58

• **privadoKeyCB58**: *cadena*

*Definido en [src/utils/hdnode.ts:19](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/hdnode.ts#L19)*

___

### publicExtendedKey

• **publicExtendedKey**: *cadena*

*Definido en [src/utils/hdnode.ts:22](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/hdnode.ts#L22)*

___

### publicKey

• **publicKey**: *Buffer*

*Definido en [src/utils/hdnode.ts:17](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/hdnode.ts#L17)*

## Métodos de trabajo

### deriven de la

- **derive**(`path`: string): *[HDNode](utils_hdnode.hdnode.md)*

*Definido en [src/utils/hdnode.ts:29](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/hdnode.ts#L29)*

Deriva el HDNode en la ruta del HDNode actual.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `camino hacia el camino` | cadena de producción |

**Retornos:** *[HDNode](utils_hdnode.hdnode.md)*

nato de HDNode de niño derivado

___

### señal de que la señal de que la

- **señal (hash:**`` Buffer): *Buffer*

*Definido en [src/utils/hdnode.ts:45](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/hdnode.ts#L45)*

Firma el hash buffer con la tecla privada utilizando secp256k1 y devuelve la firma como un buffer.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `hash` | Buffer |

**Returns:** *Buffer*

firma como Buffer

___

### verificar si se puede verificar si se puede verificar si

- **verify**(`hash`: Buffer, `firma`: Buffer): *booleano*

*Definido en [src/utils/hdnode.ts:57](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/hdnode.ts#L57)*

Verifica que la firma es válida para hash y la clave pública del HDNode's utilizando secp256k1.

**`arroja`** si el hash o la firma es la longitud incorrecta.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `hash` | Buffer |
| `firma` | Buffer |

**Return:** *booleano*

es cierto para valido, falso para inválido.

___

### wipePrivateData

- **wipePrivateData**(): *void*

*Definido en [src/utils/hdnode.ts:65](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/hdnode.ts#L65)*

Obtiene todo el registro de la clave privada de la instancia HDNode. Después de llamar a este método, la instancia se comportará como si fuera creado a través de un xpub.

**Retornos:** *vacío*
