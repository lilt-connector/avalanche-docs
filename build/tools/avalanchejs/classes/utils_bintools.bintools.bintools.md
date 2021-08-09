[avalancha](../README.md) › [Utils-BinTools](../modules/utils_bintools.md) › [BinTools](utils_bintools.bintools.md)

# Clase: BinTools

Una clase que contiene herramientas útiles para interactuar con la plataforma cruzada de datos binarios utilizando nodejs & javascript.

Esta clase nunca debe ser instantiated directamente. En lugar de eso, invocar la función estática "BinTools.getInstance()" * para agarrar el singleton instancia de las herramientas.

Todo lo que usa en esta biblioteca [la clase de Buffer de la feross's](https://github.com/feross/buffer)

```js
const bintools = BinTools.getInstance();
let b58str = bintools.bufferToB58(Buffer.from("Wubalubadubdub!"));
```

## Jerarquía

* **BinTools**

## Índice de participación

### Constructores

* [constructor](utils_bintools.bintools.md#private-constructor)

### Propiedades de las propiedades

* [b58](utils_bintools.bintools.md#private-b58)
* [instancia de parte de la](utils_bintools.bintools.md#static-private-instance)

### Métodos de trabajo

* [addChecksum](utils_bintools.bintools.md#addchecksum)
* [addressToString](utils_bintools.bintools.md#addresstostring)
* [b58ToBuffer](utils_bintools.bintools.md#b58tobuffer)
* [búferToB58](utils_bintools.bintools.md#buffertob58)
* [bufferToString](utils_bintools.bintools.md#buffertostring)
* [cb58Decodeco.](utils_bintools.bintools.md#cb58decode)
* [cb58Encook](utils_bintools.bintools.md#cb58encode)
* [copia.](utils_bintools.bintools.md#copyfrom)
* [fromArrayBufferToBuffer](utils_bintools.bintools.md#fromarraybuffertobuffer)
* [fromBNToBuffer](utils_bintools.bintools.md#frombntobuffer)
* [fromBufferToArrayBuffer](utils_bintools.bintools.md#frombuffertoarraybuffer)
* [fromBufferToBN](utils_bintools.bintools.md#frombuffertobn)
* [isBase58](utils_bintools.bintools.md#isbase58)
* [isBase64](utils_bintools.bintools.md#isbase64)
* [isCB58](utils_bintools.bintools.md#iscb58)
* [isDecimal](utils_bintools.bintools.md#isdecimal)
* [isHex](utils_bintools.bintools.md#ishex)
* [isPrimaryBechAddress](utils_bintools.bintools.md#isprimarybechaddress)
* [parseAddress](utils_bintools.bintools.md#parseaddress)
* [stringToAddress](utils_bintools.bintools.md#stringtoaddress)
* [stringToBuffer](utils_bintools.bintools.md#stringtobuffer)
* [validar Checksum](utils_bintools.bintools.md#validatechecksum)
* [getInstance](utils_bintools.bintools.md#static-getinstance)

## Constructores

### Constructor `privado`

\+ **nuevo BinTools():** *[BinTools](utils_bintools.bintools.md)*

*Definido en [src/utils/bintools.ts:31](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/bintools.ts#L31)*

**Retornos:** *[BinTools](utils_bintools.bintools.md)*

## Propiedades de las propiedades

### `Privada` b58

• **b58**: *[Base58](utils_base58.base58.md)*

*Definido en [src/utils/bintools.ts:37](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/bintools.ts#L37)*

___

### Casación `privada` `estática`

• **instancia**: *[BinTools](utils_bintools.bintools.md)*

*Definido en [src/utils/bintools.ts:31](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/bintools.ts#L31)*

## Métodos de trabajo

### addChecksum

- **addChecksum**(`buff`: Buffer): *Buffer*

*Definido en [src/utils/bintools.ts:251](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/bintools.ts#L251)*

Toma un [buffer](https://github.com/feross/buffer) y agrega una suma de comprobación, regresando a [Buffer](https://github.com/feross/buffer) con la suma de verificación de 4 bytes adjunta.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `buffet` | Buffer | El [buffer](https://github.com/feross/buffer) adjuntar una suma de verificación |

**Returns:** *Buffer*

___

### addressToString

- **addressToString**(`hrp`: string, `chainid`: string, `bytes`: Buffer): *string*

*Definido en [src/utils/bintools.ts:297](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/bintools.ts#L297)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `hrp` | cadena de producción |
| `chainid` | cadena de producción |
| `bytes` | Buffer |

**Return:** *string*

___

### b58ToBuffer

- **b58ToBuffer** (`b58str`: string): *Buffer*

*Definido en [src/utils/bintools.ts:177](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/bintools.ts#L177)*

Toma una cadena base-58 y devuelve un [Buffer](https://github.com/feross/buffer).

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `b58str` | cadena de producción | La cadena base-58 para convertir a un [Buffer](https://github.com/feross/buffer) |

**Returns:** *Buffer*

___

### búferToB58

- **bufferToB58**`(buff`: Buffer): *string*

*Definido en [src/utils/bintools.ts:169](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/bintools.ts#L169)*

Toma un [buffer](https://github.com/feross/buffer) y devuelve una cadena base-58 de el [Buffer](https://github.com/feross/buffer).

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `buffet` | Buffer | El [buffer](https://github.com/feross/buffer) para convertir a base-58 |

**Return:** *string*

___

### bufferToString

- **bufferToString**`(buff`: Buffer): *string*

*Definido en [src/utils/bintools.ts:134](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/bintools.ts#L134)*

Produce una cadena de un [Buffer](https://github.com/feross/buffer) representando una cuerda. SOLO SE UTILIZA EN EL FORMATO DE TRANSACCIÓN, SE PREVÉ LA LONGITUD ASUMIDA.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `buffet` | Buffer | El [buffer](https://github.com/feross/buffer) para convertir a una cadena |

**Return:** *string*

___

### cb58Decodeco.

- **cb58Decode**(`bytes`: Buffer | string): *Buffer*

*Definido en [src/utils/bintools.ts:287](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/bintools.ts#L287)*

Toma una cadena [de buffer](https://github.com/feross/buffer) o base 58 serializado cb58 y devuelve un [Buffer](https://github.com/feross/buffer) de los datos originales. Se lanza en el error.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `bytes` | Buffer &#124; cadena | Una cadena de [buffer](https://github.com/feross/buffer) o base 58 serializado cb58 |

**Returns:** *Buffer*

___

### cb58Encook

- **cb58Encode**(`bytes`: Buffer): *string*

*Definido en [src/utils/bintools.ts:276](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/bintools.ts#L276)*

Toma un [buffer](https://github.com/feross/buffer) y devuelve una cadena base-58 con suma de control según el estándar cb58.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `bytes` | Buffer | Un [buffer](https://github.com/feross/buffer) para serializar |

**Return:** *string*

Una cadena de base serializada 58 del Buffer.

___

### copia.

- **copyFrom**(`buff`: Buffer: `start`: number, `fin`: number): *Buffer*

*Definido en [src/utils/bintools.ts:156](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/bintools.ts#L156)*

Hace una copia (sin referencia) de un [Buffer](https://github.com/feross/buffer) sobre los indecies. proporcionados.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `buffet` | Buffer | - | El [buffer](https://github.com/feross/buffer) para copiar |
| `inicio de la sesión` | Número de números | 0 | El índice para iniciar la copia |
| `Final,` | Número de números | no definido. | El índice para poner fin a la copia |

**Returns:** *Buffer*

___

### fromArrayBufferToBuffer

- **fromArrayBufferToBuffer**(`ab`: ArrayBuffer): *Buffer*

*Definido en [src/utils/bintools.ts:199](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/bintools.ts#L199)*

Toma un ArrayBuffer y lo convierte en un [Buffer](https://github.com/feross/buffer).

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `ab` | ArrayBuffer | El ArrayBuffer se convierte en un [Buffer](https://github.com/feross/buffer) |

**Returns:** *Buffer*

___

### fromBNToBuffer

- **fromBNToBuffer**(`bn`: BN, `longitud?`: número): *Buffer*

*Definido en [src/utils/bintools.ts:228](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/bintools.ts#L228)*

Toma un [BN](https://github.com/indutny/bn.js/) y lo convierte a un [buffer](https://github.com/feross/buffer).

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `b)` | BN | El [BN](https://github.com/indutny/bn.js/) se convierte en un [Buffer](https://github.com/feross/buffer) |
| `¿longitud?` | Número de números | La longitud cero acolchada del [buffer](https://github.com/feross/buffer) |

**Returns:** *Buffer*

___

### fromBufferToArrayBuffer

- **fromBufferToArrayBuffer**`(buff`: (buffer: Buffer): *ArrayBuffer*

*Definido en [src/utils/bintools.ts:185](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/bintools.ts#L185)*

Toma un [buffer](https://github.com/feross/buffer) y devuelve un ArrayBuffer.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `buffet` | Buffer | El [buffer](https://github.com/feross/buffer) para convertir a un ArrayBuffer |

**Returns:** *ArrayBuffer*

___

### fromBufferToBN

- **fromBufferToBN**(`buff`: Buffer): *BN*

*Definido en [src/utils/bintools.ts:214](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/bintools.ts#L214)*

Toma un [buffer](https://github.com/feross/buffer) y lo convierte a un [BN](https://github.com/indutny/bn.js/).

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `buffet` | Buffer | El [buffer](https://github.com/feross/buffer) para convertir a un [BN](https://github.com/indutny/bn.js/) |

**Returns:** *BN*

___

### isBase58

- **isBase58**(`base58`: string): *boolean*

*Definido en [src/utils/bintools.ts:75](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/bintools.ts#L75)*

Devuelve cierto si base58, de lo contrario falso

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `base58` | cadena de producción | la cadena para verificar es base58 |

**Return:** *booleano*

___

### isBase64

- **isBase64**`(str`: str: string): *boolean*

*Definido en [src/utils/bintools.ts:53](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/bintools.ts#L53)*

Devuelve cierto si base64, de lo contrario falso

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `str` | cadena de producción | la cadena para verificar es Base64 |

**Return:** *booleano*

___

### isCB58

- **isCB58**(`cb58`: string): *boolean*

*Definido en [src/utils/bintools.ts:67](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/bintools.ts#L67)*

Devuelve cierto si cb58, de lo contrario falso

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `cb58` | cadena de producción | la cadena para verificar es cb58 |

**Return:** *booleano*

___

### isDecimal

- **isDecimal**`(str`: str: string): *booleano*

*Definido en [src/utils/bintools.ts:101](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/bintools.ts#L101)*

Devuelve verdad si decimal, de otra manera falsa

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `str` | cadena de producción | la cadena para verificar es hexidecimal |

**Return:** *booleano*

___

### isHex

- **isHex**(`hex`: string): *booleano*

*Definido en [src/utils/bintools.ts:88](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/bintools.ts#L88)*

Devuelve verdad si hexidecimal, de otra manera falsa

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `hex` | cadena de producción | la cadena para verificar es hexidecimal |

**Return:** *booleano*

___

### isPrimaryBechAddress

- **isPrimaryBechAddress**(`address`: string): *boolean*

*Definido en [src/utils/bintools.ts:114](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/bintools.ts#L114)*

Devuelve cierto si cumple los requisitos para analizar como dirección como Bech32 en cadena X o cadena P-Chain, de lo contrario falso

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `Dirección de la dirección` | cadena de producción | la cadena para verificar es dirección |

**Return:** *booleano*

___

### parseAddress

- **parseAddress**`(addr`: string, `blockchainID`: string, `alias`: string, `addrlen`: number): *Buffer*

*Definido en [src/utils/bintools.ts:348](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/bintools.ts#L348)*

Toma una dirección y devuelve su [Buffer](https://github.com/feross/buffer) representación si es válida. Una versión más estricta de stringToAddress.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `addr` | cadena de producción | - | Una representación de cadena de la dirección |
| `blockchainID` | cadena de producción | - | Una representación de cadena codificada cb58 del blockchainID |
| `alias` | cadena de producción | no definido. | Un alias de chainID de que la dirección también puede analizar. |
| `addrlen` | Número de números | 20 | Las VMs pueden utilizar cualquier esquema de dirección que desee, por lo que este es el número adecuado de bytes de dirección. Predeterminado 20. |

**Returns:** *Buffer*

Un [buffer](https://github.com/feross/buffer) para la dirección si es válido, no definido, si no es válido.

___

### stringToAddress

- **stringToAddress**(`address`: string, `hrp?`: string): *Buffer*

*Definido en [src/utils/bintools.ts:299](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/bintools.ts#L299)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `Dirección de la dirección` | cadena de producción |
| `¿hrp?` | cadena de producción |

**Returns:** *Buffer*

___

### stringToBuffer

- **stringToBuffer**`(str`: str: string): *Buffer*

*Definido en [src/utils/bintools.ts:141](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/bintools.ts#L141)*

Produce un [Buffer](https://github.com/feross/buffer) de una cuerda. SOLO SE UTILIZA EN EL FORMATO DE TRANSACCIÓN, LA LONGITUD SE PREPENDED.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `str` | cadena de producción | La cadena para convertir a un [Buffer](https://github.com/feross/buffer) |

**Returns:** *Buffer*

___

### validar Checksum

- **validateChecksum**(`buff`: Buffer): *boolean*

*Definido en [src/utils/bintools.ts:262](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/bintools.ts#L262)*

Toma un [buffer](https://github.com/feross/buffer) con una suma de verificación de 4 bytes adjunta y devuelve cierto si la suma de verificación es válida, de lo contrario falsa.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `buffet` | Buffer |

**Return:** *booleano*

___

### GetInstance `estática`

- **getInstance**(): *[BinTools](utils_bintools.bintools.md)*

*Definido en [src/utils/bintools.ts:42](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/bintools.ts#L42)*

Recupera el singleton de BinTools

**Retornos:** *[BinTools](utils_bintools.bintools.md)*
