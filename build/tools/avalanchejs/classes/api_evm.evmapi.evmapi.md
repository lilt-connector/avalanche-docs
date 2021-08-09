[avalancha](../README.md) › [API-EVM](../modules/api_evm.md) › [EVMAPI](api_evm.evmapi.md)

# Clase: EVMAPI

Clase para interactuar con EVMAPI de un nodo

**`comentarios`** Esto extiende la clase [JRPCAPI](common_jrpcapi.jrpcapi.md). Esta clase no debe ser llamada directamente. En cambio, utilice la función [Avalanche.addAPI](avalanche.avalanche-1.md#addapi) para registrar esta interfaz con Avalanche.

## Jerarquía

m. [JRPCAPI](common_jrpcapi.jrpcapi.md)

-**EVMAPI**

## Índice de participación

### Constructores

* [constructor](api_evm.evmapi.md#constructor)

### Propiedades de las propiedades

* [AVAXAssetID](api_evm.evmapi.md#protected-avaxassetid)
* [baseurl](api_evm.evmapi.md#protected-baseurl)
* [blockchainAlias](api_evm.evmapi.md#protected-blockchainalias)
* [blockchainID](api_evm.evmapi.md#protected-blockchainid)
* [núcleo de la](api_evm.evmapi.md#protected-core)
* [db](api_evm.evmapi.md#protected-db)
* [jrpcVersion](api_evm.evmapi.md#protected-jrpcversion)
* [rpcid](api_evm.evmapi.md#protected-rpcid)
* [txFee](api_evm.evmapi.md#protected-txfee)

### Métodos de trabajo

* [addressFromBuffer](api_evm.evmapi.md#addressfrombuffer)
* [buildExportTx](api_evm.evmapi.md#buildexporttx)
* [buildImportTx](api_evm.evmapi.md#buildimporttx)
* [callMethod](api_evm.evmapi.md#callmethod)
* [exportación de productos](api_evm.evmapi.md#export)
* [exportAVAX](api_evm.evmapi.md#exportavax)
* [exportKey](api_evm.evmapi.md#exportkey)
* [getAVAXAssetID](api_evm.evmapi.md#getavaxassetid)
* [getAssetBalance](api_evm.evmapi.md#getassetbalance)
* [getAssetDescription](api_evm.evmapi.md#getassetdescription)
* [getAtomicTxStatus](api_evm.evmapi.md#getatomictxstatus)
* [getBaseURL](api_evm.evmapi.md#getbaseurl)
* [getBlockchainAlias](api_evm.evmapi.md#getblockchainalias)
* [getBlockchainID](api_evm.evmapi.md#getblockchainid)
* [getDB](api_evm.evmapi.md#getdb)
* [getDefaultTxFee](api_evm.evmapi.md#getdefaulttxfee)
* [getRPCID](api_evm.evmapi.md#getrpcid)
* [getTxFee](api_evm.evmapi.md#gettxfee)
* [getUTXOs](api_evm.evmapi.md#getutxos)
* [importación de productos](api_evm.evmapi.md#import)
* [importAVAX](api_evm.evmapi.md#importavax)
* [importKey](api_evm.evmapi.md#importkey)
* [issueTx](api_evm.evmapi.md#issuetx)
* [keyChain](api_evm.evmapi.md#keychain)
* [parseAddress](api_evm.evmapi.md#parseaddress)
* [refreshBlockchainID](api_evm.evmapi.md#refreshblockchainid)
* [setAVAXAssetID](api_evm.evmapi.md#setavaxassetid)
* [setBaseURL](api_evm.evmapi.md#setbaseurl)
* [setBlockchainAlias](api_evm.evmapi.md#setblockchainalias)

## Constructores

### constructor

\+ **new EVMAPI**`(core`: [AvalancheCore](avalanchecore.avalanchecore-1.md), `EVMAPI(core`: string, `blockchainID`: string): *[EVMAPI](api_evm.evmapi.md)*

*Superación [JRPCAPI](common_jrpcapi.jrpcapi.md).[constructor](common_jrpcapi.jrpcapi.md#constructor)*

*Definido en [src/apis/evm/api.ts:718](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/api.ts#L718)*

Esta clase no debe ser instantiated directamente. En lugar de ello, utilice el método [Avalanche.addAPI](avalanche.avalanche-1.md#addapi).

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `núcleo de la` | [AvalancheCore](avalanchecore.avalanchecore-1.md) | - | Una referencia a la clase Avalanche |
| `baseurl` | cadena de producción | "/ext/bc/C/avax" | Default a la cadena "/ext/bc/C/avax" como el camino hacia el baseurl de blockchain |
| `blockchainID` | cadena de producción | "" | La identificación del Bloqueo. Default a una cadena vacía: "" |

**Returns:** *[EVMAPI](api_evm.evmapi.md)*

## Propiedades de las propiedades

### AVAXAssetID `protegido`

• **AVAXAssetID**: *Buffer* = indefinido.

*Definido en [src/apis/evm/api.ts:63](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/api.ts#L63)*

___

### Base `protegida`

• **baseurl**: *cadena*

*Heredada de [APIBase](common_apibase.apibase.md).[baseurl](common_apibase.apibase.md#protected-baseurl)*

*Definido en [src/comm/apibase.ts:28](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/apibase.ts#L28)*

___

### blockchainAlias `protegidas`

• **blockchainAlias**: *string* = undefined

*Definido en [src/apis/evm/api.ts:62](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/api.ts#L62)*

___

### blockchainID `protegido`

• **blockchainID**: *string* = ""

*Definido en [src/apis/evm/api.ts:61](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/api.ts#L61)*

___

### Correa `protegida`

• **núcleo**: *[AvalancheCore](avalanchecore.avalanchecore-1.md)*

*Heredada de [APIbase.core](common_apibase.apibase.md)[](common_apibase.apibase.md#protected-core)*

*Definido en [src/comm/apibase.ts:26](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/apibase.ts#L26)*

___

### db `protegido`

• **db**: *StoreAPI*

*Heredada de [APIbase.db](common_apibase.apibase.md)[](common_apibase.apibase.md#protected-db)*

*Definido en [src/comm/apibase.ts:30](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/apibase.ts#L30)*

___

### jrpcVersion `protegida`

• **jrpcVersion**: *cadena* = "2.0"

*Heredado de [JRPCAPI](common_jrpcapi.jrpcapi.md).[jrpcVersion](common_jrpcapi.jrpcapi.md#protected-jrpcversion)*

*Definido en [src/comm/jrpcapi.ts:11](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/jrpcapi.ts#L11)*

___

### rpcid `protegido`

• **rpcid**: *número* = 1

*Heredada de [JRPCAPI](common_jrpcapi.jrpcapi.md).[rpcid](common_jrpcapi.jrpcapi.md#protected-rpcid)*

*Definido en [src/comm/jrpcapi.ts:12](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/jrpcapi.ts#L12)*

___

### TxFee `protegido`

• **txFee**: *BN* = indefinido.

*Definido en [src/apis/evm/api.ts:64](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/api.ts#L64)*

## Métodos de trabajo

### addressFromBuffer

- **addressFromBuffer**`(address: (dirección`: Buffer): *string*

*Definido en [src/apis/evm/api.ts:138](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/api.ts#L138)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `Dirección de la dirección` | Buffer |

**Return:** *string*

___

### buildExportTx

- **buildExportTx(amount:**`` BN, `assetID`: Buffer | string, `buildExportTx(amount`: Buffer | string, `buildExportTx(amount`: string, `buildExportTx(amount`: string, `toAddresses`: []string, `nonce`: number, `locktime`: BN, `umbral`: number): *Promise‹[UnsignedTx](api_evm_transactions.unsignedtx.md)›*

*Definido en [src/apis/evm/api.ts:614](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/api.ts#L614)*

Función de ayuda que crea una Export Tx sin firmar. Para un control más granular, usted puede crear su propio [Sin firmar Tx](api_platformvm_transactions.unsignedtx.md) manualmente (con sus correspondientes [Entradas,](api_platformvm_inputs.transferableinput.md) [Productos Transferibles).](api_platformvm_outputs.transferableoutput.md)

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `importe de la cantidad de dinero` | BN | - | La cantidad que se exportará como [BN](https://github.com/indutny/bn.js/) |
| `activos` | Buffer &#124; cadena | - | El id de activos que se envía |
| `destinationChain de destino` | Buffer &#124; cadena | - | El chainid para donde se enviarán los activos. |
| `fromAddressHex` | cadena de producción | - | - |
| `fromAddressBech` | cadena de producción | - | - |
| `toAddresses` | cadena de producción[] | - | Las direcciones para enviar los fondos |
| `Nocy` | Número de números | 0 | - |
| `Tiempo de bloqueo` | BN | nuevo BN(0) | Opcional. El campo de bloqueo creado en las salidas resultantes |
| `umbral` | Número de números | 1 1 | Opcional. El número de firmas necesarias para gastar los fondos en la UTXO resultante |

**Returns:** *Promise‹[UnsignedTx](api_evm_transactions.unsignedtx.md)›*

Una transacción no firmada ([UnsignedTx](api_platformvm_transactions.unsignedtx.md)) que contiene una [ExportTx](api_platformvm_exporttx.exporttx.md).

___

### buildImportTx

[]- **buildImportTx(utxoset:**`` [UTXOSet](api_evm_utxos.utxoset.md), `buildImportTx(utxoset`: string, `buildImportTx(utxoset```: string, `sourceChain`: Buffer | string, buildImportTx(utxoset: []string): *Promise‹[UnsignedTx](api_evm_transactions.unsignedtx.md)›*

*Definido en [src/apis/evm/api.ts:554](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/api.ts#L554)*

Función de ayuda que crea un Tx de importación sin firmar. Para un control más granular, usted puede crear su propio [Sin firmar Tx](api_platformvm_transactions.unsignedtx.md) manualmente (con sus correspondientes [Entradas,](api_platformvm_inputs.transferableinput.md) [Productos Transferibles).](api_platformvm_outputs.transferableoutput.md)

**`observaciones sobre las observaciones formuladas`** Este ayudante existe porque la API de endpoint debe ser el punto principal de entrada para la mayoría de la funcionalidad.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `utxoset` | [UTXOSet](api_evm_utxos.utxoset.md) | Un conjunto de UTXOS en el que se basa la transacción |
| `aDirección` | cadena de producción | La dirección para enviar los fondos |
| `ownerAddresses` | cadena de producción[] | Las direcciones que se utilizan para importar |
| `sourceChain` | Buffer &#124; cadena | El chainid para donde viene la importación |
| `fromAddresses` | cadena de producción[] | Las direcciones que se utilizan para enviar los fondos de UTXOs proporcionadas |

**Returns:** *Promise‹[UnsignedTx](api_evm_transactions.unsignedtx.md)›*

Una transacción no firmada ([UnsignedTx](api_platformvm_transactions.unsignedtx.md)) que contiene una [ImportTx](api_platformvm_importtx.importtx.md).

___

### callMethod

- **callMethod**(`method`: string, `params?`: objeto []| objeto, `baseurl?`: string, `headers?`: objeto): *Promise‹[RequestResponseData](common_apibase.requestresponsedata.md)›*

*Heredado de [JRPCAPI](common_jrpcapi.jrpcapi.md).[callMethod](common_jrpcapi.jrpcapi.md#callmethod) Method*

*Definido en [src/comm/jrpcapi.ts:14](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/jrpcapi.ts#L14)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `método` | cadena de producción |
| `¿params?` | objeto []&#124; objeto |
| `baseurl?` | cadena de producción |
| `¿Los encabezados?` | objeto de la operación |

**Return:** *Promise‹[RequestResponseData](common_apibase.requestresponsedata.md)›*

___

### exportación de productos

- **export**(`username`: de usuario: string, `contraseña`: string, string, `suma`: BN, `assetID`: `string)`: *Promise‹string›*

*Definido en [src/apis/evm/api.ts:283](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/api.ts#L283)*

Enviar activos ANT (Avalanche Native Token) incluyendo AVAX desde la C-Chain a una cuenta en la X-Chain.

Después de llamar a este método, debe llamar al método de importación de la cadena X-X para completar la transferencia.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `Nombre de usuario` | cadena de producción | El usuario de `Keystore` que controla la cuenta de X-Chain especificada en |
| `contraseña` | cadena de producción | La contraseña del usuario de Keystore |
| `a la hora de que se le dé a la` | cadena de producción | La cuenta de la cadena X para enviar el AVAX a. |
| `importe de la cantidad de dinero` | BN | Importe de activos a exportar como [BN](https://github.com/indutny/bn.js/) |
| `activos` | cadena de producción | El id de activos que se envía |

**Returns:** *Promise‹string›*

Corriente que representa el id de la transacción

___

### exportAVAX

- **exportAVAX**(`username`: de usuario: string, `contraseña`: string, `a`: string, `sumite`: BN): *Promise‹string›*

*Definido en [src/apis/evm/api.ts:319](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/api.ts#L319)*

Enviar AVAX desde la cadena C a una cuenta en la cadena X.

Después de llamar a este método, debe llamar al método importAVAX de la cadena X-X, para completar la transferencia.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `Nombre de usuario` | cadena de producción | El usuario de `Keystore` que controla la cuenta de X-Chain especificada en |
| `contraseña` | cadena de producción | La contraseña del usuario de Keystore |
| `a la hora de que se le dé a la` | cadena de producción | La cuenta de la cadena X para enviar el AVAX a. |
| `importe de la cantidad de dinero` | BN | Cantidad de AVAX para exportar como [BN](https://github.com/indutny/bn.js/) |

**Returns:** *Promise‹string›*

Corriente que representa el id de la transacción

___

### exportKey

- **exportKey**(`username`: de usuario: string, `contraseña`: string, `dirección`: string): *Promise‹string›*

*Definido en [src/apis/evm/api.ts:521](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/api.ts#L521)*

Exportar la clave privada para una dirección.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `Nombre de usuario` | cadena de producción | El nombre del usuario con la clave privada |
| `contraseña` | cadena de producción | La contraseña utilizada para descifrar la clave privada |
| `Dirección de la dirección` | cadena de producción | La dirección cuya clave privada debe exportarse |

**Returns:** *Promise‹string›*

Promete con la clave privada descifrada como tienda en la base de datos

___

### getAVAXAssetID

- **getAVAXAssetID**(`refresh`: booleano): *Promise‹Buffer›*

*Definido en [src/apis/evm/api.ts:188](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/api.ts#L188)*

Toma el AVAX AssetID y lo devuelve en una Promesa.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `refrescarse` | booleano | falso | Esta función encauza la respuesta. Refresh = true will el caché. |

**Returns:** *Promise‹Buffer›* ›

La cadena proporcionada que representa el AVAX AssetID

___

### getAssetBalance

- **getAssetBalance**(`hexAddress`: string, `blockHeight`: string, `assetID`: string): *Promise‹string›*

*Definido en [src/apis/evm/api.ts:229](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/api.ts#L229)*

devuelve la cantidad de [la identificación] de activos para la dirección dada en el estado del número de bloque dado. También se permiten números de bloque de "latest", "más recientes", "pendientes" y "aceptados".

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `hexAddress` | cadena de producción | La representación hex de la dirección |
| `blockHeight` | cadena de producción | La altura del bloque |
| `activos` | cadena de producción | El ID de activos |

**Returns:** *Promise‹string›*

Devuelve una promesa<string>que contiene el saldo

___

### getAssetDescription

- **getAssetDescription**(`assetID`: Buffer | string): *Promise‹any›*

*Definido en [src/apis/evm/api.ts:151](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/api.ts#L151)*

Recupera un nombre y símbolo de activos.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `activos` | Buffer &#124; cadena | O bien un [Buffer](https://github.com/feross/buffer) o una cadena serializada b58 para el AssetID o su alias. |

**Returns:** *Promise‹any›*

Devuelve una promesa<Asset>con las teclas "nombre", "símbolo", "assetID" y "denominación".

___

### getAtomicTxStatus

- **getAtomicTxStatus**(`txID`: string): *Promise‹string›*

*Definido en [src/apis/evm/api.ts:249](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/api.ts#L249)*

Devuelve el estado de un ID de transacción atómica proporcionado llamando al método `getAtomicTxStatus` del nodo.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `txID` | cadena de producción | La representación de cadena del ID de transacción |

**Returns:** *Promise‹string›*

Devuelve una promesa<string>que contiene el estado recuperado del nodo

___

### getBaseURL

- **getBaseURL**(): *string*

*Heredada de [APIbase.getBaseURL](common_apibase.apibase.md)[](common_apibase.apibase.md#getbaseurl)*

*Definido en [src/comm/apibase.ts:53](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/apibase.ts#L53)*

Devuelve el camino del baseurl's

**Return:** *string*

___

### getBlockchainAlias

- **getBlockchainAlias**(): *string*

*Definido en [src/apis/evm/api.ts:71](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/api.ts#L71)*

Obtiene el alias para el blockchainID si existe, de lo contrario devuelve `indefinido`.

**Return:** *string*

El alias para el blockchainID

___

### getBlockchainID

- **getBlockchainID**(): *string*

*Definido en [src/apis/evm/api.ts:103](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/api.ts#L103)*

Obtiene el blockchainID y lo devuelve

**Return:** *string*

El blockchainID

___

### getDB

- **getDB**(): *StoreAPI*

*Heredada de [APIbase.getDB](common_apibase.apibase.md)[](common_apibase.apibase.md#getdb)*

*Definido en [src/comm/apibase.ts:58](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/apibase.ts#L58)*

Devuelve la base de datos del baseurl's

**Retornos:** *StoreAPI*

___

### getDefaultTxFee

- **getDefaultTxFee**(): *BN*

*Definido en [src/apis/evm/api.ts:215](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/api.ts#L215)*

Obtiene la cuota tx predeterminada para esta cadena.

**Returns:** *BN*

La tasa tx predeterminada como [BN](https://github.com/indutny/bn.js/)

___

### getRPCID

- **getRPCID**(): *número*

*Heredada de [JRPCAPI](common_jrpcapi.jrpcapi.md).[getRPCID](common_jrpcapi.jrpcapi.md#getrpcid)*

*Definido en [src/comm/jrpcapi.ts:69](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/jrpcapi.ts#L69)*

Devuelve el rpcid, un número de aumento estricto, a partir de 1, indicando el siguiente solicitar identificación que se enviará.

**Retornos:** *número*

___

### getTxFee

- **getTxFee**(): *BN*

*Definido en [src/apis/evm/api.ts:263](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/api.ts#L263)*

Obtiene la cuota de tx por esta cadena.

**Returns:** *BN*

La tasa tx como [BN](https://github.com/indutny/bn.js/)

___

### getUTXOs

- **getUTXOs**(`addresses`: string []| string, `sourceChain`: string, `limit`: number, `startIndex`: [Index):](../interfaces/common_interfaces.index.md) *Promise‹object›*

*Definido en [src/apis/evm/api.ts:351](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/api.ts#L351)*

Recupera las UTXOs relacionadas con las direcciones proporcionadas del método `getUTXOS` del nodo.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `direcciones` | string[] &#124; string | - | Una serie de direcciones como cadenas o direcciones cb58 como [Buffer](https://github.com/feross/buffer)s |
| `sourceChain` | cadena de producción | no definido. | Una cadena para que la cadena busque la UTXO's. El predeterminado es utilizar esta cadena, pero si existen UTXOs exportados de otras cadenas, esto puede utilizarse para tirarlos en su lugar. |
| `límite de la duración de la duración de la duración` | Número de números | 0 | Opcional. Devuelve en la mayoría [de] las direcciones limitadas. Si [límite] == 0 o > [maxUTXOsToFetch], llega hasta [maxUTXOsToFetch]. |
| `startIndex` | [Índice de participación](../interfaces/common_interfaces.index.md) | no definido. | Opcional. [StartIndex] define dónde empezar a buscar UTXOS (para la paginación.) Las UTXOs obtenidas son de direcciones iguales o mayores que [StartIndex.Address][] Para dirección StartIndex.Address solo UTXOs con ID mayores que [StartIndex.Utxo] será devuelta. |

**Returns:** *Promise‹object›*

___

### importación de productos

- **import**(`username`: de usuario: string, `contraseña`: string, `sourceChain```: string): *Promise‹string›*

*Definido en [src/apis/evm/api.ts:398](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/api.ts#L398)*

Enviar activos ANT (Avalanche Native Token) incluyendo AVAX desde una cuenta en la X-Chain a una dirección en la C-Chain. Esta transacción deberá firmar con la clave de la cuenta de la que se envía el activo y que paga la cuota de transacción.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `Nombre de usuario` | cadena de producción | El usuario de `Keystore` que controla la cuenta especificada en |
| `contraseña` | cadena de producción | La contraseña del usuario de Keystore |
| `a la hora de que se le dé a la` | cadena de producción | La dirección de la cuenta a la que se envía el activo. |
| `sourceChain` | cadena de producción | El chainID de donde vienen los fondos. Ex: "X" |

**Returns:** *Promise‹string›*

Promesa para una cadena de transacción, que debe enviarse a la red llamando a issueTx.

___

### importAVAX

- **importAVAX**(`username`: de `usuario`: string, `contraseña`: string, `sourceChain`: string): *Promise‹string›*

*Definido en [src/apis/evm/api.ts:434](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/api.ts#L434)*

Enviar AVAX desde una cuenta en la cadena X a una dirección en la cadena C-Chain. Esta transacción deberá firmar con la clave de la cuenta de la que se envía el AVAX y que paga la cuota de transacción.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `Nombre de usuario` | cadena de producción | El usuario de `Keystore` que controla la cuenta especificada en |
| `contraseña` | cadena de producción | La contraseña del usuario de Keystore |
| `a la hora de que se le dé a la` | cadena de producción | La dirección de la cuenta a la que se envía AVAX. Esto debe ser lo mismo que el argumento de la llamada correspondiente a la exportación exportAVAX de la cadena X. |
| `sourceChain` | cadena de producción | El chainID de donde vienen los fondos. |

**Returns:** *Promise‹string›*

Promesa para una cadena de transacción, que debe enviarse a la red llamando a issueTx.

___

### importKey

- **importKey**(`username`: de usuario: string, `contraseña`: string, `privateKey`: string): *Promise‹string›*

*Definido en [src/apis/evm/api.ts:464](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/api.ts#L464)*

Dé un control de usuario sobre una dirección proporcionando la clave privada que controla la dirección.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `Nombre de usuario` | cadena de producción | El nombre del usuario para almacenar la clave privada |
| `contraseña` | cadena de producción | La contraseña que desbloquea el usuario |
| `privateKey` | cadena de producción | Una cadena que representa la clave privada en el formato vm |

**Returns:** *Promise‹string›*

La dirección para la llave privada importada.

___

### issueTx

- **issueTx**(`tx`: string | Buffer | [Tx):](api_evm_transactions.tx.md) *Promise‹string›*

*Definido en [src/apis/evm/api.ts:489](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/api.ts#L489)*

Llama el método issueTx del nodo desde la API y devuelve el ID de transacción resultante como una cadena.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `txx` | string &#124; Buffer &#124; [Tx](api_evm_transactions.tx.md) | Una cadena, [Buffer](https://github.com/feross/buffer) o [Tx](api_platformvm_transactions.tx.md) que representa una transacción |

**Returns:** *Promise‹string›*

Una promesa<string>representando el ID de transacción de la transacción publicada.

___

### keyChain

- **keyChain**(): *[KeyChain](api_evm_keychain.keychain.md)*

*Definido en [src/apis/evm/api.ts:695](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/api.ts#L695)*

Obtiene una referencia al llavero para esta clase.

**Retornos:** *[KeyChain](api_evm_keychain.keychain.md)*

La instancia de [KeyChain](api_platformvm_keychain.keychain.md) para esta clase

___

### parseAddress

- **parseAddress**(`addr`: string): *Buffer*

*Definido en [src/apis/evm/api.ts:132](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/api.ts#L132)*

Toma una cadena de dirección y devuelve su representación de [Buffer](https://github.com/feross/buffer) si es válida.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `addr` | cadena de producción |

**Returns:** *Buffer*

Un [buffer](https://github.com/feross/buffer) para la dirección si es válido, sin definir si no es válido.

___

### refreshBlockchainID

- **refreshBlockchainID**(`blockchainID`: string): *boolean*

*Definido en [src/apis/evm/api.ts:112](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/api.ts#L112)*

Refrescar blockchainID, y si se pasa un blockchainID dentro, utilice eso.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `blockchainID` | cadena de producción | no definido. |

**Return:** *booleano*

Un booleano si el blockchainID fue reactualizado con éxito.

___

### setAVAXAssetID

- **setAVAXAssetID**(`avaxAssetID`: string | Buffer): *nul*

*Definido en [src/apis/evm/api.ts:203](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/api.ts#L203)*

Supera los valores predeterminados y establece la caché en un AssetID específico de AVAX

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `avaxAssetID` | string &#124; Buffer | Una cadena cb58 o Buffer que representa el AVAX AssetID |

**Retornos:** *vacío*

La cadena proporcionada que representa el AVAX AssetID

___

### setBaseURL

- **setBaseURL**(`baseurl`: string): *void*

*Heredado de [APIbase.setBaseURL](common_apibase.apibase.md)[](common_apibase.apibase.md#setbaseurl)*

*Definido en [src/comm/apibase.ts:37](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/apibase.ts#L37)*

Establece el camino de las API baseurl.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `baseurl` | cadena de producción | Camino de las API baseurl - ex: "/ext/bc/X" |

**Retornos:** *vacío*

___

### setBlockchainAlias

- **setBlockchainAlias**(`alias`: string): *string*

*Definido en [src/apis/evm/api.ts:91](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/evm/api.ts#L91)*

Establece el alias para el blockchainID.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `alias` | cadena de producción | Los alias para el blockchainID. |

**Return:** *string*
