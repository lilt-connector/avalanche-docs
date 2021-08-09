[avalancha](../README.md) › [API-AVM](../modules/api_avm.md) › [AVMAPI](api_avm.avmapi.md)

# Clase: AVMAPI

Clase para interactuar con un punto de extremo de nodo que está utilizando el AVM.

**`comentarios`** Esto extiende la clase [JRPCAPI](common_jrpcapi.jrpcapi.md). Esta clase no debe ser llamada directamente. En cambio, utilice la función [Avalanche.addAPI](avalanche.avalanche-1.md#addapi) para registrar esta interfaz con Avalanche.

## Jerarquía

m. [JRPCAPI](common_jrpcapi.jrpcapi.md)

m. **AVMAPI**

## Índice de participación

### Constructores

* [constructor](api_avm.avmapi.md#constructor)

### Propiedades de las propiedades

* [AVAXAssetID](api_avm.avmapi.md#protected-avaxassetid)
* [baseurl](api_avm.avmapi.md#protected-baseurl)
* [blockchainAlias](api_avm.avmapi.md#protected-blockchainalias)
* [blockchainID](api_avm.avmapi.md#protected-blockchainid)
* [núcleo de la](api_avm.avmapi.md#protected-core)
* [creationTxFee](api_avm.avmapi.md#protected-creationtxfee)
* [db](api_avm.avmapi.md#protected-db)
* [jrpcVersion](api_avm.avmapi.md#protected-jrpcversion)
* [rpcid](api_avm.avmapi.md#protected-rpcid)
* [txFee](api_avm.avmapi.md#protected-txfee)

### Métodos de trabajo

* [addressFromBuffer](api_avm.avmapi.md#addressfrombuffer)
* [buildBaseTx](api_avm.avmapi.md#buildbasetx)
* [buildCreateAssetTx](api_avm.avmapi.md#buildcreateassettx)
* [buildCreateNFTAssetTx](api_avm.avmapi.md#buildcreatenftassettx)
* [buildCreateNFTMintTx](api_avm.avmapi.md#buildcreatenftminttx)
* [buildExportTx](api_avm.avmapi.md#buildexporttx)
* [building.](api_avm.avmapi.md#buildgenesis)
* [buildImportTx](api_avm.avmapi.md#buildimporttx)
* [buildNFTTransferTx](api_avm.avmapi.md#buildnfttransfertx)
* [buildSECPMintTx](api_avm.avmapi.md#buildsecpminttx)
* [callMethod](api_avm.avmapi.md#callmethod)
* [checkGooseEgg](api_avm.avmapi.md#checkgooseegg)
* [createAddress](api_avm.avmapi.md#createaddress)
* [createFixedCapAsset createFixedCapAsset](api_avm.avmapi.md#createfixedcapasset)
* [createVariableCapAsset](api_avm.avmapi.md#createvariablecapasset)
* [exportación de productos](api_avm.avmapi.md#export)
* [exportAVAX](api_avm.avmapi.md#exportavax)
* [exportKey](api_avm.avmapi.md#exportkey)
* [getAVAXAssetID](api_avm.avmapi.md#getavaxassetid)
* [getAllBalances](api_avm.avmapi.md#getallbalances)
* [getAssetDescription](api_avm.avmapi.md#getassetdescription)
* [getBalance](api_avm.avmapi.md#getbalance)
* [getBaseURL](api_avm.avmapi.md#getbaseurl)
* [getBlockchainAlias](api_avm.avmapi.md#getblockchainalias)
* [getBlockchainID](api_avm.avmapi.md#getblockchainid)
* [getCreationTxFee](api_avm.avmapi.md#getcreationtxfee)
* [getDB](api_avm.avmapi.md#getdb)
* [getDefaultCreationTxFee](api_avm.avmapi.md#getdefaultcreationtxfee)
* [getDefaultTxFee](api_avm.avmapi.md#getdefaulttxfee)
* [getRPCID](api_avm.avmapi.md#getrpcid)
* [getTx](api_avm.avmapi.md#gettx)
* [getTxFee](api_avm.avmapi.md#gettxfee)
* [getTxStatus](api_avm.avmapi.md#gettxstatus)
* [getUTXOs](api_avm.avmapi.md#getutxos)
* [importación de productos](api_avm.avmapi.md#import)
* [importAVAX](api_avm.avmapi.md#importavax)
* [importKey](api_avm.avmapi.md#importkey)
* [issueTx](api_avm.avmapi.md#issuetx)
* [keyChain](api_avm.avmapi.md#keychain)
* [listAddresses](api_avm.avmapi.md#listaddresses)
* [menta](api_avm.avmapi.md#mint)
* [parseAddress](api_avm.avmapi.md#parseaddress)
* [refreshBlockchainID](api_avm.avmapi.md#refreshblockchainid)
* [enviar a un correo electrónico](api_avm.avmapi.md#send)
* [sendMultiple](api_avm.avmapi.md#sendmultiple)
* [setAVAXAssetID](api_avm.avmapi.md#setavaxassetid)
* [setBaseURL](api_avm.avmapi.md#setbaseurl)
* [setBlockchainAlias](api_avm.avmapi.md#setblockchainalias)
* [setCreationTxFee](api_avm.avmapi.md#setcreationtxfee)
* [setTxFee](api_avm.avmapi.md#settxfee)
* [signTx](api_avm.avmapi.md#signtx)

## Constructores

### constructor

\+ **nuevo** `AVMAPI(core`: [AvalancheCore](avalanchecore.avalanchecore-1.md), `AVMAPI(core`: string, `blockchainID`: string): *[AVMAPI](api_avm.avmapi.md)*

*Superación [JRPCAPI](common_jrpcapi.jrpcapi.md).[constructor](common_jrpcapi.jrpcapi.md#constructor)*

*Definido en [src/apis/avm/api.ts:1493](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/api.ts#L1493)*

Esta clase no debe ser instantiated directamente. En lugar de ello, utilice el método [Avalanche.addAPI](avalanche.avalanche-1.md#addapi).

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `núcleo de la` | [AvalancheCore](avalanchecore.avalanchecore-1.md) | - | Una referencia a la clase Avalanche |
| `baseurl` | cadena de producción | "/ext/bc/X" | Default a la cadena "/ext/bc/X" como la ruta hacia el baseurl de blockchain" |
| `blockchainID` | cadena de producción | "" | El ID de Blockchain. Default a una cadena vacía: "" |

**Returns:** *[AVMAPI](api_avm.avmapi.md)*

## Propiedades de las propiedades

### AVAXAssetID `protegido`

• **AVAXAssetID**: *Buffer* = indefinido.

*Definido en [src/apis/avm/api.ts:54](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/api.ts#L54)*

___

### Base `protegida`

• **baseurl**: *cadena*

*Heredada de [APIBase](common_apibase.apibase.md).[baseurl](common_apibase.apibase.md#protected-baseurl)*

*Definido en [src/comm/apibase.ts:28](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/apibase.ts#L28)*

___

### blockchainAlias `protegidas`

• **blockchainAlias**: *string* = undefined

*Definido en [src/apis/avm/api.ts:53](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/api.ts#L53)*

___

### blockchainID `protegido`

• **blockchainID**: *string* = ""

*Definido en [src/apis/avm/api.ts:52](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/api.ts#L52)*

___

### Correa `protegida`

• **núcleo**: *[AvalancheCore](avalanchecore.avalanchecore-1.md)*

*Heredada de [APIbase.core](common_apibase.apibase.md)[](common_apibase.apibase.md#protected-core)*

*Definido en [src/comm/apibase.ts:26](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/apibase.ts#L26)*

___

### Creación `Protected`

• **creationTxFee**: *BN* = indefinido.

*Definido en [src/apis/avm/api.ts:56](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/api.ts#L56)*

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

*Definido en [src/apis/avm/api.ts:55](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/api.ts#L55)*

## Métodos de trabajo

### addressFromBuffer

- **addressFromBuffer**`(address: (dirección`: Buffer): *string*

*Definido en [src/apis/avm/api.ts:126](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/api.ts#L126)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `Dirección de la dirección` | Buffer |

**Return:** *string*

___

### buildBaseTx

- **buildBaseTx(utxoset:**`` [UTXOSet](api_avm_utxos.utxoset.md), `sumo`: BN, `assetID`: Buffer | string, `buildBaseTx(utxoset`: []string, `deDirecciones`: []string, `buildBaseTx(utxoset`: []string, `memo`: [PayloadBase](utils_payload.payloadbase.md) | Buffer, `comode`: BN, `locktime`: BN, `umbral`: número): *Promise‹[UnsignedTx](api_avm_transactions.unsignedtx.md)›*

*Definido en [src/apis/avm/api.ts:739](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/api.ts#L739)*

Función de ayuda que crea una transacción sin firmar. Para un control más granular, usted puede crear su propio [Sin firmar Tx](api_platformvm_transactions.unsignedtx.md) manualmente (con sus correspondientes [Entradas,](api_platformvm_inputs.transferableinput.md) [Productos Transferibles](api_platformvm_outputs.transferableoutput.md) y [[TransferOperation]]s).

**`observaciones sobre las observaciones formuladas`** Este ayudante existe porque la API de endpoint debe ser el punto principal de entrada para la mayoría de la funcionalidad.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `utxoset` | [UTXOSet](api_avm_utxos.utxoset.md) | - | Un conjunto de UTXOS en el que se basa la transacción |
| `importe de la cantidad de dinero` | BN | - | La cantidad de activos que se gastará en su denominación más pequeña, representada como [BN](https://github.com/indutny/bn.js/). |
| `activos` | Buffer &#124; cadena | no definido. | El valor de la identificación |
| `toAddresses` | cadena de producción[] | - | Las direcciones para enviar los fondos |
| `fromAddresses` | cadena de producción[] | - | Las direcciones que se utilizan para enviar los fondos de UTXOs proporcionadas |
| `changeAddresses` | cadena de producción[] | - | Las direcciones que pueden gastar el cambio restante de UTXOs gastado |
| `meme` | [PayloadBase](utils_payload.payloadbase.md) &#124; Buffer | no definido. | Opcional CB58 Buffer o String que contiene bytes arbitrarios, hasta 256 bytes |
| `as.` | BN | UnixNow() | Opcional. La marca de tiempo para verificar la transacción contra un [BN](https://github.com/indutny/bn.js/) |
| `Tiempo de bloqueo` | BN | nuevo BN(0) | Opcional. El campo de bloqueo creado en las salidas resultantes |
| `umbral` | Número de números | 1 1 | Opcional. El número de firmas necesarias para gastar los fondos en la UTXO resultante |

**Returns:** *Promise‹[UnsignedTx](api_avm_transactions.unsignedtx.md)›*

Una transacción no firmada ([UnsignedTx](api_platformvm_transactions.unsignedtx.md)) que contiene una [BaseTx](api_platformvm_basetx.basetx.md).

___

### buildCreateAssetTx

- **buildCreateAssetTx(utxoset:**`` [UTXOSet](api_avm_utxos.utxoset.md), `buildCreateAssetTx(utxoset```: string, buildCreateAssetTx(utxoset: string, `buildCreateAssetTx(utxoset`[:](api_avm_initialstates.initialstates.md) string, `nombre`: []string, `símbolo`: string, `denomination`: number, `buildCreateAssetTx(utxoset`: [SECPMintOutput](api_avm_outputs.secpmintoutput.md)[], `memo`: [PayloadBase](utils_payload.payloadbase.md) | []Buffer, `asOf`: BN): *Promise‹[UnsignedTx](api_avm_transactions.unsignedtx.md)›*

*Definido en [src/apis/avm/api.ts:1040](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/api.ts#L1040) 1040*

Crea una transacción sin firmar. Para un control más granular, usted puede crear su propio [Sin firmar Tx](api_platformvm_transactions.unsignedtx.md) manualmente (con sus correspondientes [Entradas,](api_platformvm_inputs.transferableinput.md) [Productos Transferibles](api_platformvm_outputs.transferableoutput.md) y [[TransferOperation]]s).

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `utxoset` | [UTXOSet](api_avm_utxos.utxoset.md) | - | Un conjunto de UTXOS en el que se basa la transacción |
| `fromAddresses` | cadena de producción[] | - | Las direcciones que se utilizan para enviar los fondos del [Buffer](https://github.com/feross/buffer) UTXOS |
| `changeAddresses` | cadena de producción[] | - | Las direcciones que pueden gastar el cambio restante de UTXOs gastado |
| `Estados iniciales` | [Estados iniciales.](api_avm_initialstates.initialstates.md) | - | - |
| `Nombre del nombre` | cadena de producción | - | Correa para el nombre descriptivo del activo |
| `Sí, sí.` | cadena de producción | - | Cadena para el símbolo de cosquillas del activo |
| `denominación` | Número de números | - | Número de denominación que es 10^D. D debe ser >= 0 y <= 32: $1 AVAX = 10^9 $nAVAX |
| `mintOutputs` | [SECPMintOutput](api_avm_outputs.secpmintoutput.md)[] | no definido. | Opcional. Conjunto de productos [SECPMintOutput](api_avm_outputs.secpmintoutput.md)s que se incluirán en la transacción. Estos productos pueden gastarse para mentar más tokens. |
| `meme` | [PayloadBase](utils_payload.payloadbase.md) &#124; Buffer | no definido. | Opcional CB58 Buffer o String que contiene bytes arbitrarios, hasta 256 bytes |
| `as.` | BN | UnixNow() | Opcional. La marca de tiempo para verificar la transacción contra un [BN](https://github.com/indutny/bn.js/) |

**Returns:** *Promise‹[UnsignedTx](api_avm_transactions.unsignedtx.md)›*

Una transacción no firmada ([UnsignedTx](api_platformvm_transactions.unsignedtx.md)) que contiene un [CreateAssetTx](api_avm_createassettx.createassettx.md).

___

### buildCreateNFTAssetTx

- **buildCreateNFTAssetTx(utxoset:**`` [UTXOSet](api_avm_utxos.utxoset.md), `buildCreateNFTAssetTx(utxoset```: string, buildCreateNFTAssetTx(utxoset: []string, `minterSets`: [MinterSet](api_avm_minterset.minterset.md)[], `nombre`: string, `símbolo`: string, `memo`: [PayloadBase](utils_payload.payloadbase.md) | Buffer, `comode`: []BN, `locktime`: BN): *Promise‹[UnsignedTx](api_avm_transactions.unsignedtx.md)›*

*Definido en [src/apis/avm/api.ts:1168](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/api.ts#L1168)*

Crea una transacción sin firmar. Para un control más granular, usted puede crear su propio [Sin firmar Tx](api_platformvm_transactions.unsignedtx.md) manualmente (con sus correspondientes [Entradas,](api_platformvm_inputs.transferableinput.md) [Productos Transferibles](api_platformvm_outputs.transferableoutput.md) y [[TransferOperation]]s).

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `utxoset` | [UTXOSet](api_avm_utxos.utxoset.md) | - | Un conjunto de UTXOS en el que se basa la transacción |
| `fromAddresses` | cadena de producción[] | - | Las direcciones que se utilizan para enviar los fondos del [Buffer](https://github.com/feross/buffer) UTXOS |
| `changeAddresses` | cadena de producción[] | - | Las direcciones que pueden gastar el cambio restante de UTXOs gastado |
| `minterSets` | [MinterSet](api_avm_minterset.minterset.md)[] | - | es una lista en la que cada elemento especifica que el umbral de las direcciones en mineros puede mintar más del activo mediante la firma de una transacción de menta |
| `Nombre del nombre` | cadena de producción | - | Correa para el nombre descriptivo del activo |
| `Sí, sí.` | cadena de producción | - | Cadena para el símbolo de cosquillas del activo |
| `meme` | [PayloadBase](utils_payload.payloadbase.md) &#124; Buffer | no definido. | Opcional CB58 Buffer o String que contiene bytes arbitrarios, hasta 256 bytes |
| `as.` | BN | UnixNow() | Opcional. La marca de tiempo para verificar la transacción contra un [BN](https://github.com/indutny/bn.js/) |
| `Tiempo de bloqueo` | BN | nuevo BN(0) | Opcional. El campo de bloqueo creado en la salida de menta resultante ```js Ejemplo minterSets: [ "minters":[ "X-avax1ghstjkrtw8935lryqtnh643xe9a94u3t75c7"], "umbral": 1 }, ${ "minters": [ "X-avax1yell3e4nln0m39cfpdhgqprsd87jkh4qnakkklx", "X-avax1k4nr26c80jaquzm9369j5a4shmwcjn0vmemcjz", "X-avax1ztkzsrjn0cek5rhqdtcg23nhge3nnnr5nr5nr.2 23nr5.2``` |

**Returns:** *Promise‹[UnsignedTx](api_avm_transactions.unsignedtx.md)›*

Una transacción no firmada ([UnsignedTx](api_platformvm_transactions.unsignedtx.md)) que contiene un [CreateAssetTx](api_avm_createassettx.createassettx.md).

___

### buildCreateNFTMintTx

- **buildCreateNFTMintTx(utxoset:**`` [UTXOSet](api_avm_utxos.utxoset.md), `dueños`: [OutputOwners](common_output.outputowners.md) []| [OutputOwners](common_output.outputowners.md), `buildCreateNFTMintTx(utxoset`: []string, `buildCreateNFTMintTx(utxoset`: []string, `utxoid`: []string, `groupID`: number, `payloadBase` | Buffer, `memo`: [PayloadBase](utils_payload.payloadbase.md)[](utils_payload.payloadbase.md) | Buffer, `asOf`: BN): *Promise‹any›*

*Definido en [src/apis/avm/api.ts:1229](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/api.ts#L1229)*

Crea una transacción sin firmar. Para un control más granular, usted puede crear su propio [Sin firmar Tx](api_platformvm_transactions.unsignedtx.md) manualmente (con sus correspondientes [Entradas,](api_platformvm_inputs.transferableinput.md) [Productos Transferibles](api_platformvm_outputs.transferableoutput.md) y [[TransferOperation]]s).

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `utxoset` | [UTXOSet](api_avm_utxos.utxoset.md) | - | Un conjunto de UTXOS en el que se basa la transacción |
| `propietarios de los propietarios` | [OutputOwners](common_output.outputowners.md)[] &#124; [OutputOwners](common_output.outputowners.md) | - | O bien un solo o una matriz de [OutputOwners](../modules/src_common.md#outputowners) para enviar la salida nft |
| `fromAddresses` | cadena de producción[] | - | Las direcciones que se utilizan para enviar la NFT desde el utxoID proporcionado. |
| `changeAddresses` | cadena de producción[] | - | Las direcciones que pueden gastar el cambio restante de UTXOs gastado |
| `utxoid` | string &#124; string[] | - | Una utxoID base58 o una matriz de utxoID base58 para la salida de menta nft esta transacción está enviando |
| `groupID` | Número de números | 0 | Opcional. El grupo al que se emite la NFT. |
| `carga útil` | [PayloadBase](utils_payload.payloadbase.md) &#124; Buffer | no definido. | Opcional. Datos sobre carga útil NFT como [PayloadBase](utils_payload.payloadbase.md) o [Buffer](https://github.com/feross/buffer) |
| `meme` | [PayloadBase](utils_payload.payloadbase.md) &#124; Buffer | no definido. | Opcional CB58 Buffer o String que contiene bytes arbitrarios, hasta 256 bytes |
| `as.` | BN | UnixNow() | Opcional. La marca de tiempo para verificar la transacción contra un [BN](https://github.com/indutny/bn.js/) |

**Returns:** *Promise‹any›*

Una transacción no firmada ([UnsignedTx](api_platformvm_transactions.unsignedtx.md)) que contiene una [OperationTx](api_avm_operationtx.operationtx.md).

___

### buildExportTx

[]- **buildExportTx(utxoset:**`` [UTXOSet](api_avm_utxos.utxoset.md), `sumo`: BN, `buildExportTx(utxoset`: Buffer | string, `buildExportTx(utxoset`: string, `deDirecciones`: string, `buildExportTx(utxoset`: []string, `memorando`: [PayloadBase](utils_payload.payloadbase.md) | Buffer, `comode`: BN, `locktime`: BN, `umbral`: número, `assetID`: []string): *Promise‹[UnsignedTx](api_avm_transactions.unsignedtx.md)›*

*Definido en [src/apis/avm/api.ts:950](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/api.ts#L950)*

Función de ayuda que crea una Export Tx sin firmar. Para un control más granular, usted puede crear su propio [Sin firmar Tx](api_platformvm_transactions.unsignedtx.md) manualmente (con sus correspondientes [Entradas,](api_platformvm_inputs.transferableinput.md) [Productos Transferibles](api_platformvm_outputs.transferableoutput.md) y [[TransferOperation]]s).

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `utxoset` | [UTXOSet](api_avm_utxos.utxoset.md) | - | Un conjunto de UTXOS en el que se basa la transacción |
| `importe de la cantidad de dinero` | BN | - | La cantidad que se exportará como [BN](https://github.com/indutny/bn.js/) |
| `destinationChain de destino` | Buffer &#124; cadena | - | El chainid para donde se enviarán los activos. |
| `toAddresses` | cadena de producción[] | - | Las direcciones para enviar los fondos |
| `fromAddresses` | cadena de producción[] | - | Las direcciones que se utilizan para enviar los fondos de UTXOs proporcionadas |
| `changeAddresses` | cadena de producción[] | no definido. | Las direcciones que pueden gastar el cambio restante de UTXOs gastado |
| `meme` | [PayloadBase](utils_payload.payloadbase.md) &#124; Buffer | no definido. | Opcional CB58 Buffer o String que contiene bytes arbitrarios, hasta 256 bytes |
| `as.` | BN | UnixNow() | Opcional. La marca de tiempo para verificar la transacción contra un [BN](https://github.com/indutny/bn.js/) |
| `Tiempo de bloqueo` | BN | nuevo BN(0) | Opcional. El campo de bloqueo creado en las salidas resultantes |
| `umbral` | Número de números | 1 1 | Opcional. El número de firmas necesarias para gastar los fondos en la UTXO resultante |
| `activos` | cadena de producción | no definido. | Opcional. El activo de la entidad a enviar. Default to AVAX asset Independientemente del activo que esté exportando, todos los honorarios se pagan en AVAX. |

**Returns:** *Promise‹[UnsignedTx](api_avm_transactions.unsignedtx.md)›*

Una transacción no firmada ([UnsignedTx](api_platformvm_transactions.unsignedtx.md)) que contiene una [ExportTx](api_platformvm_exporttx.exporttx.md).

___

### building.

- **buildGenesis**(`genesisData`: objeto): *Promise‹string›*

*Definido en [src/apis/avm/api.ts:1464](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/api.ts#L1464)*

Dado una representación JSON del estado de génesis de esta Máquina Virtual, crea la representación byte de ese estado.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `genesisData` | objeto de la operación | El objeto de datos de génesis de blockchain |

**Returns:** *Promise‹string›*

Promesa de una cadena de bytes

___

### buildImportTx

[][]- **buildImportTx**(`utxoset`: [UTXOSet](api_avm_utxos.utxoset.md), `ownerAddresses```: string, `sourceChain`: Buffer | string, `ownerAddresses`: string, `deDirecciones`: string, ownerAddresses: []string, `memo`: [PayloadBase](utils_payload.payloadbase.md) | Buffer, `comoDe`: BN, `locktime`: []BN, `umbral`: número): *Promise‹[UnsignedTx](api_avm_transactions.unsignedtx.md)›*

*Definido en [src/apis/avm/api.ts:870](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/api.ts#L870)*

Función de ayuda que crea un Tx de importación sin firmar. Para un control más granular, usted puede crear su propio [Sin firmar Tx](api_platformvm_transactions.unsignedtx.md) manualmente (con sus correspondientes [Entradas,](api_platformvm_inputs.transferableinput.md) [Productos Transferibles](api_platformvm_outputs.transferableoutput.md) y [[TransferOperation]]s).

**`observaciones sobre las observaciones formuladas`** Este ayudante existe porque la API de endpoint debe ser el punto principal de entrada para la mayoría de la funcionalidad.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `utxoset` | [UTXOSet](api_avm_utxos.utxoset.md) | - | Un conjunto de UTXOS en el que se basa la transacción |
| `ownerAddresses` | cadena de producción[] | - | Las direcciones que se utilizan para importar |
| `sourceChain` | Buffer &#124; cadena | - | El chainid para donde viene la importación |
| `toAddresses` | cadena de producción[] | - | Las direcciones para enviar los fondos |
| `fromAddresses` | cadena de producción[] | - | Las direcciones que se utilizan para enviar los fondos de UTXOs proporcionadas |
| `changeAddresses` | cadena de producción[] | no definido. | Las direcciones que pueden gastar el cambio restante de UTXOs gastado |
| `meme` | [PayloadBase](utils_payload.payloadbase.md) &#124; Buffer | no definido. | Opcional CB58 Buffer o String que contiene bytes arbitrarios, hasta 256 bytes |
| `as.` | BN | UnixNow() | Opcional. La marca de tiempo para verificar la transacción contra un [BN](https://github.com/indutny/bn.js/) |
| `Tiempo de bloqueo` | BN | nuevo BN(0) | Opcional. El campo de bloqueo creado en las salidas resultantes |
| `umbral` | Número de números | 1 1 | Opcional. El número de firmas necesarias para gastar los fondos en la UTXO resultante |

**Returns:** *Promise‹[UnsignedTx](api_avm_transactions.unsignedtx.md)›*

Una transacción no firmada ([UnsignedTx](api_platformvm_transactions.unsignedtx.md)) que contiene una [ImportTx](api_platformvm_importtx.importtx.md).

___

### buildNFTTransferTx

- **buildNFTTransferTx(utxoset:**`` [UTXOSet](api_avm_utxos.utxoset.md): `buildNFTTransferTx(utxoset```: []string, `deDirecciones`: string, buildNFTTransferTx(utxoset: []string, `utxoid`: []string, `memorando`: [PayloadBase](utils_payload.payloadbase.md) | Buffer, `comode`: BN, `locktime`: []BN, `umbral`: número): *Promise‹[UnsignedTx](api_avm_transactions.unsignedtx.md)›*

*Definido en [src/apis/avm/api.ts:803](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/api.ts#L803)*

Función de ayuda que crea una transferencia NFT sin firmar. Para un control más granular, usted puede crear su propio [Sin firmar Tx](api_platformvm_transactions.unsignedtx.md) manualmente (con sus correspondientes [Entradas,](api_platformvm_inputs.transferableinput.md) [Productos Transferibles](api_platformvm_outputs.transferableoutput.md) y [[TransferOperation]]s).

**`observaciones sobre las observaciones formuladas`** Este ayudante existe porque la API de endpoint debe ser el punto principal de entrada para la mayoría de la funcionalidad.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `utxoset` | [UTXOSet](api_avm_utxos.utxoset.md) | - | Un conjunto de UTXOS en el que se basa la transacción |
| `toAddresses` | cadena de producción[] | - | Las direcciones para enviar la NFT |
| `fromAddresses` | cadena de producción[] | - | Las direcciones que se utilizan para enviar la NFT desde el utxoID proporcionado. |
| `changeAddresses` | cadena de producción[] | - | Las direcciones que pueden gastar el cambio restante de UTXOs gastado |
| `utxoid` | string &#124; string[] | - | Una utxoID base58 o una variedad de utxoIDs base58 para las nociones de la operación esta enviando |
| `meme` | [PayloadBase](utils_payload.payloadbase.md) &#124; Buffer | no definido. | Opcional CB58 Buffer o String que contiene bytes arbitrarios, hasta 256 bytes |
| `as.` | BN | UnixNow() | Opcional. La marca de tiempo para verificar la transacción contra un [BN](https://github.com/indutny/bn.js/) |
| `Tiempo de bloqueo` | BN | nuevo BN(0) | Opcional. El campo de bloqueo creado en las salidas resultantes |
| `umbral` | Número de números | 1 1 | Opcional. El número de firmas necesarias para gastar los fondos en la UTXO resultante |

**Returns:** *Promise‹[UnsignedTx](api_avm_transactions.unsignedtx.md)›*

Una transacción no firmada ([UnsignedTx](api_platformvm_transactions.unsignedtx.md)) que contiene una [[NFTTransferTx]].

___

### buildSECPMintTx

- **buildSECPMintTx(utxoset:**`` [UTXOSet](api_avm_utxos.utxoset.md), `buildSECPMintTx(utxoset```: [SECPMintOutput](api_avm_outputs.secpmintoutput.md), buildSECPMintTx(utxoset: [SECPTransferOutput](api_avm_outputs.secptransferoutput.md), `buildSECPMintTx(utxoset`: string, `buildSECPMintTx(utxoset`: [][]string, `mintUTXOID`: string, `memo`: [PayloadBase](utils_payload.payloadbase.md) | Buffer, `buildSECPMintTx(utxoset`: BN): *Promise‹any›*

*Definido en [src/apis/avm/api.ts:1094](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/api.ts#L1094)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `utxoset` | [UTXOSet](api_avm_utxos.utxoset.md) | - |
| `mintOwner,` | [SECPMintOutput](api_avm_outputs.secpmintoutput.md) | - |
| `transferOwner` | [SECPTransferOutput](api_avm_outputs.secptransferoutput.md) | - |
| `fromAddresses` | cadena de producción[] | - |
| `changeAddresses` | cadena de producción[] | - |
| `mintutXOID` | cadena de producción | - |
| `meme` | [PayloadBase](utils_payload.payloadbase.md) &#124; Buffer | no definido. |
| `as.` | BN | UnixNow() |

**Returns:** *Promise‹any›*

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

### checkGooseEgg

- **checkGooseEgg**(`utx`: [UnsignedTx](api_avm_transactions.unsignedtx.md), `outTotal`: BN): *Promise‹boolean›*

*Definido en [src/apis/avm/api.ts:258](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/api.ts#L258)*

Función de ayuda que determina si una tx es una transacción de huevo de ganso.

**`observaciones sobre las observaciones formuladas`** Una "Transacción de huevo de ganso" es cuando la cuota supera con creces una cantidad razonable

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `utt` | [Sin UnsignedTx](api_avm_transactions.unsignedtx.md) | - | Un Tx Sin Firmar. |
| `outTotal` | BN | nuevo BN(0) | - |

**Returns:** *Promise‹boolean›*

booleano verdadero si pasa la prueba de huevo de ganso y falso si falla.

___

### createAddress

- **createAddress**(`username`: de usuario: string: `contraseña`: string): *Promise‹string›*

*Definido en [src/apis/avm/api.ts:298](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/api.ts#L298)*

Crea una dirección (y teclas privadas asociadas) en un usuario en un blockchain.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `Nombre de usuario` | cadena de producción | Nombre del usuario para crear la dirección bajo |
| `contraseña` | cadena de producción | Contraseña para desbloquear el usuario y cifrar la clave privada |

**Returns:** *Promise‹string›*

Promete una cadena que representa la dirección creada por el vm.

___

### createFixedCapAsset createFixedCapAsset

- **createFixedCapAsset(username: de usuario:**`` string, `contraseña`: string, `nombre`: string, `símbolo`: string, `denomination`: number, `createFixedCapAsset(username`: []objeto): *Promise‹string›*

*Definido en [src/apis/avm/api.ts:333](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/api.ts#L333)*

Crear un nuevo activo fungible y fijo. Una cantidad de ella se crea en la inicialización y no se crea nunca más.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `Nombre de usuario` | cadena de producción | El usuario que paga la cuota de transacción (en $AVAX) por creación de activos |
| `contraseña` | cadena de producción | La contraseña para el usuario que paga la cuota de transacción (en $AVAX) para la creación de activos |
| `Nombre del nombre` | cadena de producción | El nombre legible por el hombre para el activo |
| `Sí, sí.` | cadena de producción | Opcional. El símbolo de la corta para el activo. Entre 0 y 4 caracteres |
| `denominación` | Número de números | Opcional. Determina cómo los saldos de este activo se muestran por las interfaces de usuario. El predeterminado es 0 |
| `initialHolders` | objeto de la operación[] | Una serie de objetos que contienen el campo "dirección" y "cantidad" para establecer los valores de génesis para el nuevo activo ```js Ejemplo initialHolders: [ ${ "address": "X-avax1kj06lhgx84h39snsljcey3tpc046ze68mek3g5", "address" 10000 }, ${ "address": "X-avax1am4w6hfrvmh3akduzkjthtqafalce6an8cr", "address" 50000 } ]``` |

**Returns:** *Promise‹string›*

Devuelve una promesa<string>que contiene la base 58 de la representación de cadena del ID del activo recién creado.

___

### createVariableCapAsset

- **createVariableCapAsset**(`username`: de usuario: string, `contraseña`: string, `nombre`: string, `símbolo`: string, `denomination`: number, `minterSets`: []objeto): *Promise‹string›*

*Definido en [src/apis/avm/api.ts:378](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/api.ts#L378)*

Crear un nuevo activo fungible y variable cap. No existen unidades del activo en la inicialización. Los minters pueden minar unidades de este activo utilizando createMintTx, signMintTx y sendMintTx.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `Nombre de usuario` | cadena de producción | El usuario que paga la cuota de transacción (en $AVAX) por creación de activos |
| `contraseña` | cadena de producción | La contraseña para el usuario que paga la cuota de transacción (en $AVAX) para la creación de activos |
| `Nombre del nombre` | cadena de producción | El nombre legible por el hombre para el activo |
| `Sí, sí.` | cadena de producción | Opcional. El símbolo de la pista para el activo - entre 0 y 4 caracteres |
| `denominación` | Número de números | Opcional. Determina cómo los saldos de este activo se muestran por las interfaces de usuario. El predeterminado es 0 |
| `minterSets` | objeto de la operación[] | es una lista en la que cada elemento especifica que el umbral de las direcciones en mineros puede mintar más del activo mediante la firma de una operación de menta ```js minterSets: [ ${ "minters":[ "X-avax1am4w6hfrvmh3akduzkjthtqafalce6an8cr"], "umbral": 1 }, ${ "minters": [ "X-avax1am4w6hfrvmh3akduzkjthtqafalce6an8cr", "X-avax1kj06lhgx84h39snsljcey3tpc046ze68mek3g5", "X-avax1yell3e4nln0m39cfpdhgqprsd87jkh4qnakkkklx"], "umbral": 2 } ]``` |

**Returns:** *Promise‹string›*

Devuelve una promesa<string>que contiene la base 58 de la representación de cadena del ID del activo recién creado.

___

### exportación de productos

- **export**(`username`: de usuario: string, `contraseña`: string, string, `suma`: BN, `assetID`: `string)`: *Promise‹string›*

*Definido en [src/apis/avm/api.ts:481](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/api.ts#L481)*

Enviar activos ANT (Avalanche Native Token) incluyendo AVAX desde la X-Chain a una cuenta en la cadena P o C-Chain.

Después de llamar a este método, debe llamar al `importAVAX` de la cadena P-Chain's o al método `de importación` de la cadena P-Chain's para completar la transferencia.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `Nombre de usuario` | cadena de producción | El usuario de Keystore que controla la cuenta de cadena P o cadena `C` especificada en |
| `contraseña` | cadena de producción | La contraseña del usuario de Keystore |
| `a la hora de que se le dé a la` | cadena de producción | La cuenta de la cadena P o la cadena C para enviar el activo a. |
| `importe de la cantidad de dinero` | BN | Importe de activos a exportar como [BN](https://github.com/indutny/bn.js/) |
| `activos` | cadena de producción | El id de activos que se envía |

**Returns:** *Promise‹string›*

Corriente que representa el id de la transacción

___

### exportAVAX

- **exportAVAX**(`username`: de usuario: string, `contraseña`: string, `a`: string, `sumite`: BN): *Promise‹string›*

*Definido en [src/apis/avm/api.ts:505](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/api.ts#L505)*

Enviar AVAX desde la cadena X a una cuenta en la cadena P o C-Chain.

Después de llamar a este método, debe llamar al método importAVAX de la cadena P-Chain’s o P-Chain’s para completar la transferencia.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `Nombre de usuario` | cadena de producción | El usuario de Keystore que controla la cuenta de la cadena P especificada `en` |
| `contraseña` | cadena de producción | La contraseña del usuario de Keystore |
| `a la hora de que se le dé a la` | cadena de producción | La cuenta de la cadena P o la cadena C para enviar el AVAX a. |
| `importe de la cantidad de dinero` | BN | Cantidad de AVAX para exportar como [BN](https://github.com/indutny/bn.js/) |

**Returns:** *Promise‹string›*

Corriente que representa el id de la transacción

___

### exportKey

- **exportKey**(`username`: de usuario: string, `contraseña`: string, `dirección`: string): *Promise‹string›*

*Definido en [src/apis/avm/api.ts:435](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/api.ts#L435)*

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

*Definido en [src/apis/avm/api.ts:139](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/api.ts#L139)*

Toma el AVAX AssetID y lo devuelve en una Promesa.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `refrescarse` | booleano | falso | Esta función encauza la respuesta. Refresh = true will el caché. |

**Returns:** *Promise‹Buffer›* ›

La cadena proporcionada que representa el AVAX AssetID

___

### getAllBalances

- **getAllBalances**(`address`: string): *[]Promise‹object›*

*Definido en [src/apis/avm/api.ts:587](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/api.ts#L587)*

Recupera todos los activos para una dirección en un servidor y sus saldos asociados.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `Dirección de la dirección` | cadena de producción | La dirección para obtener una lista de activos |

**Returns:** *Promise‹object[]›*

Promete un sistema de asignación de objetos de cadenas de activos con equilibrio [BN](https://github.com/indutny/bn.js/) para la dirección del blockchain.

___

### getAssetDescription

- **getAssetDescription**(`assetID`: Buffer | string): *Promise‹object›*

*Definido en [src/apis/avm/api.ts:606](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/api.ts#L606)*

Recupera un nombre y símbolo de activos.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `activos` | Buffer &#124; cadena | O bien un [Buffer](https://github.com/feross/buffer) o una cadena serializada b58 para el AssetID o su alias. |

**Returns:** *Promise‹object›*

Devuelve una Promesa <object>con las teclas "nombre" y "símbolo".

___

### getBalance

- **getBalance**(`address`: string, `assetID`: string): *Promise‹object›*

*Definido en [src/apis/avm/api.ts:277](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/api.ts#L277)*

Obtiene el equilibrio de un activo particular en un blockchain.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `Dirección de la dirección` | cadena de producción | La dirección para sacar el saldo de activos de |
| `activos` | cadena de producción | El activo para sacar el equilibrio de |

**Returns:** *Promise‹object›*

Promete con el saldo del activo como [BN](https://github.com/indutny/bn.js/) en la dirección proporcionada para el blockchain.

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

*Definido en [src/apis/avm/api.ts:63](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/api.ts#L63)*

Obtiene el alias para el blockchainID si existe, de lo contrario devuelve `indefinido`.

**Return:** *string*

El alias para el blockchainID

___

### getBlockchainID

- **getBlockchainID**(): *string*

*Definido en [src/apis/avm/api.ts:94](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/api.ts#L94)*

Obtiene el blockchainID y lo devuelve

**Return:** *string*

El blockchainID

___

### getCreationTxFee

- **getCreationTxFee**(): *BN*

*Definido en [src/apis/avm/api.ts:211](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/api.ts#L211)*

Obtiene la cuota de creación por esta cadena.

**Returns:** *BN*

La cuota de creación como [BN](https://github.com/indutny/bn.js/)

___

### getDB

- **getDB**(): *StoreAPI*

*Heredada de [APIbase.getDB](common_apibase.apibase.md)[](common_apibase.apibase.md#getdb)*

*Definido en [src/comm/apibase.ts:58](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/apibase.ts#L58)*

Devuelve la base de datos del baseurl's

**Retornos:** *StoreAPI*

___

### getDefaultCreationTxFee

- **getDefaultCreationTxFee**(): *BN*

*Definido en [src/apis/avm/api.ts:202](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/api.ts#L202)*

Obtiene la cuota de creación por defecto para esta cadena.

**Returns:** *BN*

La cuota de creación por defecto como [BN](https://github.com/indutny/bn.js/)

___

### getDefaultTxFee

- **getDefaultTxFee**(): *BN*

*Definido en [src/apis/avm/api.ts:171](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/api.ts#L171)*

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

### getTx

- **getTx**(`txid`: string): *Promise‹string›*

*Definido en [src/apis/avm/api.ts:632](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/api.ts#L632)*

Devuelve los datos de la acción de un ID de transacción proporcionado llamando al método `getTx` del nodo.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `txid` | cadena de producción | La representación de cadena del ID de transacción |

**Returns:** *Promise‹string›*

Devuelve una promesa<string>que contengan los bytes recuperados del nodo

___

### getTxFee

- **getTxFee**(): *BN*

*Definido en [src/apis/avm/api.ts:180](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/api.ts#L180)*

Obtiene la cuota de tx por esta cadena.

**Returns:** *BN*

La tasa tx como [BN](https://github.com/indutny/bn.js/)

___

### getTxStatus

- **getTxStatus**(`txid`: string): *Promise‹string›*

*Definido en [src/apis/avm/api.ts:647](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/api.ts#L647)*

Devuelve el estado de un ID de transacción proporcionado llamando al método `getTxStatus` del nodo.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `txid` | cadena de producción | La representación de cadena del ID de transacción |

**Returns:** *Promise‹string›*

Devuelve una promesa<string>que contiene el estado recuperado del nodo

___

### getUTXOs

- **getUTXOs(addresses:**`` string []| string, `sourceChain`: string, `limit`: número, `startIndex`: objeto, `getUTXOs(addresses`: [getUTXOs(addresses:](utils_persistanceoptions.persistanceoptions.md) *Promise‹object›*

*Definido en [src/apis/avm/api.ts:670](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/api.ts#L670)*

Recupera las UTXOs relacionadas con las direcciones proporcionadas del método `getUTXOS` del nodo.

**`observaciones sobre las observaciones formuladas`** persistOpts es opcional y debe ser de tipo [PersistanceOptions](utils_persistanceoptions.persistanceoptions.md)

**Parámetros:**

• **direcciones**: *cadena []| string*

Una serie de direcciones como cadenas o direcciones cb58 como [Buffer](https://github.com/feross/buffer)s

• **Fuente** `de valor` ▪Default s*tring=* undefined

Una cadena para que la cadena busque la UTXO's. El predeterminado es utilizar esta cadena, pero si existen UTXOs exportados de otras cadenas, esto puede utilizarse para tirarlos en su lugar.

• **Límite** `de valor` predeterminado: *número=* 0

Opcional. Devuelve en la mayoría [de] las direcciones limitadas. Si [límite] == 0 o > [maxUTXOsToFetch], llega hasta [maxUTXOsToFetch].

`• Índice de inicio de valor`**** predeterminado: *objeto=* indefinido.

Opcional. [StartIndex] define dónde empezar a buscar UTXOS (para la paginación.) UTXOs traídos son de direcciones iguales o mayores que [StartIndex.Address] Para la dirección [StartIndex.Address], solo UTXOs con ID mayores que [StartIndex.Utxo] será devuelto .

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `Dirección de la dirección` | cadena de producción |
| `utxo` | cadena de producción |

• **Persistencia** `de valor` ▪Default P*[ersistanceOptions=](utils_persistanceoptions.persistanceoptions.md)* indefinidas.

Opciones disponibles para persistir estos UTXOS en almacenamiento local

**Returns:** *Promise‹object›*

___

### importación de productos

- **import**(`username`: de usuario: string, `contraseña`: string, `sourceChain```: string): *Promise‹string›*

*Definido en [src/apis/avm/api.ts:529](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/api.ts#L529)*

Enviar activos ANT (Avalanche Native Token) incluyendo AVAX desde una cuenta en la cadena P o C-Chain a una dirección en la cadena X. Esta transacción deberá firmar con la clave de la cuenta de la que se envía el activo y que paga la cuota de transacción.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `Nombre de usuario` | cadena de producción | El usuario de `Keystore` que controla la cuenta especificada en |
| `contraseña` | cadena de producción | La contraseña del usuario de Keystore |
| `a la hora de que se le dé a la` | cadena de producción | La dirección de la cuenta a la que se envía el activo. |
| `sourceChain` | cadena de producción | El chainID de donde vienen los fondos. Ex: "C" |

**Returns:** *Promise‹string›*

Promesa para una cadena de transacción, que debe enviarse a la red llamando a issueTx.

___

### importAVAX

- **importAVAX**(`username`: de `usuario`: string, `contraseña`: string, `sourceChain`: string): *Promise‹string›*

*Definido en [src/apis/avm/api.ts:552](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/api.ts#L552)*

Finalizar una transferencia de AVAX de la cadena P a la cadena X.

Antes de que se llame este método, debe llamar al método `exportAVAX` de la cadena P-P-para iniciar la transferencia.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `Nombre de usuario` | cadena de producción | El usuario de `Keystore` que controla la dirección especificada en |
| `contraseña` | cadena de producción | La contraseña del usuario de Keystore |
| `a la hora de que se le dé a la` | cadena de producción | La dirección a la AVAX se envía a la dirección. Esto debe ser lo mismo que el argumento de la llamada correspondiente a la exportación exportAVAX, de la cadena P-Chain’s excepto que la X prepended debe incluirse en este argumento. |
| `sourceChain` | cadena de producción | Encadena, los fondos vienen de. |

**Returns:** *Promise‹string›*

Corriente que representa el id de la transacción

___

### importKey

- **importKey**(`username`: de usuario: string, `contraseña`: string, `privateKey`: string): *Promise‹string›*

*Definido en [src/apis/avm/api.ts:458](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/api.ts#L458)*

Importa una clave privada en el keystore del nodo bajo un usuario y para un blockchain.

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

- **issueTx**(`tx`: string | Buffer | [Tx):](api_avm_transactions.tx.md) *Promise‹string›*

*Definido en [src/apis/avm/api.ts:1296](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/api.ts#L1296)*

Llama el método issueTx del nodo desde la API y devuelve el ID de transacción resultante como una cadena.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `txx` | string &#124; Buffer &#124; [Tx](api_avm_transactions.tx.md) | Una cadena, [Buffer](https://github.com/feross/buffer) o [Tx](api_platformvm_transactions.tx.md) que representa una transacción |

**Returns:** *Promise‹string›*

Una promesa<string>representando el ID de transacción de la transacción publicada.

___

### keyChain

- **keyChain**(): *[KeyChain](api_avm_keychain.keychain.md)*

*Definido en [src/apis/avm/api.ts:232](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/api.ts#L232)*

Obtiene una referencia al llavero para esta clase.

**Retornos:** *[KeyChain](api_avm_keychain.keychain.md)*

La instancia de [KeyChain](api_platformvm_keychain.keychain.md) para esta clase

___

### listAddresses

- **listAddresses**(`username`: de `usuario`: string: string): *[]Promise‹string›*

*Definido en [src/apis/avm/api.ts:571](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/api.ts#L571)*

Listas todas las direcciones bajo un usuario.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `Nombre de usuario` | cadena de producción | El usuario enumerará las direcciones |
| `contraseña` | cadena de producción | La contraseña del usuario para enumerar las direcciones |

**Returns:** *Promise‹string[]›*

Promete una serie de cadenas de direcciones en el formato especificado por el blockchain.

___

### menta

- **mint(username: de usuario:**`` string, `contraseña`: string, `monto`: number | BN, `assetID`: Buffer | string, `to`: string, `minters`: []string): *Promise‹string›*

*Definido en [src/apis/avm/api.ts:401](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/api.ts#L401)*

Crear una transacción sin firmar para mintar más de un activo.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `Nombre de usuario` | cadena de producción | - |
| `contraseña` | cadena de producción | - |
| `importe de la cantidad de dinero` | número &#124; BN | Las unidades del activo a la menta |
| `activos` | Buffer &#124; cadena | El ID del activo a la menta |
| `a la hora de que se le dé a la` | cadena de producción | La dirección para asignar las unidades del activo minado |
| `minters` | cadena de producción[] | Direcciones de los mineros responsables de la firma de la transacción |

**Returns:** *Promise‹string›*

Devuelve una promesa<string>que contiene la representación de cadena de la base 58 de la transacción no firmada.

___

### parseAddress

- **parseAddress**(`addr`: string): *Buffer*

*Definido en [src/apis/avm/api.ts:120](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/api.ts#L120)*

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

*Definido en [src/apis/avm/api.ts:103](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/api.ts#L103)*

Refrescar blockchainID, y si se pasa un blockchainID dentro, utilice eso.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `blockchainID` | cadena de producción | no definido. |

**Return:** *booleano*

El blockchainID

___

### enviar a un correo electrónico

[][]- **send**(`username`: de usuario: string, `contraseña`: string, `assetID`: string | Buffer, `sumo`: number | BN, `to`: string, `from`: string | Buffer, `changeAddr`: string, `memo`: string | Buffer): *Promise‹object›*

*Definido en [src/apis/avm/api.ts:1331](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/api.ts#L1331)*

Envía una cantidad de activos a la dirección especificada de una lista de propiedad de direcciones.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `Nombre de usuario` | cadena de producción | - | El usuario que `posee` las teclas privadas asociadas con las direcciones |
| `contraseña` | cadena de producción | - | La contraseña desbloquear el usuario |
| `activos` | string &#124; Buffer | - | El activo de la entidad a enviar |
| `importe de la cantidad de dinero` | número &#124; BN | - | El importe del activo que se enviará |
| `a la hora de que se le dé a la` | cadena de producción | - | Dirección del destinatario |
| `de la` | string[] &#124; Buffer[] | no definido. | Opcional. Una serie de direcciones gestionadas por el keystore del nodo para este blockchain que financiará esta transacción |
| `changeAddr` | cadena de producción | no definido. | Opcional. Una dirección para enviar el cambio |
| `meme` | string &#124; Buffer | no definido. | Opcional. CB58 Buffer o String que contiene bytes arbitrarios, hasta 256 bytes |

**Returns:** *Promise‹object›*

Promesa para la cadena que representa la identificación de la transacción.

___

### sendMultiple

- **sendMultiple**`(username```: de usuario: string, contraseña: string, `password`: []objeto, `desde`: string []| Buffer, `changeAddr`: string, `memo`: string | []Buffer): *Promise‹object›*

*Definido en [src/apis/avm/api.ts:1395](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/api.ts#L1395) 1395*

Envía una cantidad de activos de identificación a una serie de direcciones especificadas de una lista de propiedad de direcciones.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `Nombre de usuario` | cadena de producción | - | El usuario que `posee` las teclas privadas asociadas con las direcciones |
| `contraseña` | cadena de producción | - | La contraseña desbloquear el usuario |
| `sendOutputs` | objeto de la operación[] | - | La variedad de Salidas. A SendOutput es un material de objeto que contiene un assetID, cantidad y a. |
| `de la` | string[] &#124; Buffer[] | no definido. | Opcional. Una serie de direcciones gestionadas por el keystore del nodo para este blockchain que financiará esta transacción |
| `changeAddr` | cadena de producción | no definido. | Opcional. Una dirección para enviar el cambio |
| `meme` | string &#124; Buffer | no definido. | Opcional. CB58 Buffer o String que contiene bytes arbitrarios, hasta 256 bytes |

**Returns:** *Promise‹object›*

Promesa para la cadena que representa la identificación de la transacción.

___

### setAVAXAssetID

- **setAVAXAssetID**(`avaxAssetID`: string | Buffer): *nul*

*Definido en [src/apis/avm/api.ts:159](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/api.ts#L159)*

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

*Definido en [src/apis/avm/api.ts:83](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/api.ts#L83)*

Establece el alias para el blockchainID.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `alias` | cadena de producción | Los alias para el blockchainID. |

**Return:** *string*

___

### setCreationTxFee

- **setCreationTxFee**(`fee`: BN): *void*

*Definido en [src/apis/avm/api.ts:223](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/api.ts#L223)*

Establece la cuota de creación para esta cadena.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `Cuota de pago` | BN | El importe de la cuota de creación para establecer como [BN](https://github.com/indutny/bn.js/) |

**Retornos:** *vacío*

___

### setTxFee

- **setTxFee**(`fee`: BN): *nul*

*Definido en [src/apis/avm/api.ts:192](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/api.ts#L192)*

Establece la cuota tx por esta cadena.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `Cuota de pago` | BN | El importe de la tasa tx para establecer como [BN](https://github.com/indutny/bn.js/) |

**Retornos:** *vacío*

___

### signTx

- **signTx(utx:**`` [signTx(utx:](api_avm_transactions.unsignedtx.md) *[Tx](api_avm_transactions.tx.md)*

*Definido en [src/apis/avm/api.ts:1287](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/api.ts#L1287)*

Función de ayuda que toma una transacción sin firmar y la firma de, devolviendo el [Tx](api_platformvm_transactions.tx.md) resultante.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `utt` | [Sin UnsignedTx](api_avm_transactions.unsignedtx.md) | La transacción no firmada del tipo [UnsignedTx](api_platformvm_transactions.unsignedtx.md) |

**Returns:** *[Tx](api_avm_transactions.tx.md)*

Una transacción firmada de tipo [Tx](api_platformvm_transactions.tx.md)
