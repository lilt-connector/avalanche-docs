[avalancha](../README.md) › [API-AVM-UTXOS](../modules/api_avm_utxos.md) › [UTXOSet](api_avm_utxos.utxoset.md)

# Clase: UTXOSet

Clase que representa un conjunto de [UTXO](api_avm_utxos.utxo.md)s.

## Jerarquía

[m. StandardUTXOSet‹UTXO](api_avm_utxos.utxo.md)[](common_utxos.standardutxoset.md)›

de **UTXOSet**

## Índice de participación

### Propiedades de las propiedades

* [_codecid](api_avm_utxos.utxoset.md#protected-_codecid)
* [_typeID](api_avm_utxos.utxoset.md#protected-_typeid)
* [_typeName](api_avm_utxos.utxoset.md#protected-_typename)
* [dirección addressUTXOs](api_avm_utxos.utxoset.md#protected-addressutxos)
* [utxos](api_avm_utxos.utxoset.md#protected-utxos)

### Métodos de trabajo

* [_feeCheck](api_avm_utxos.utxoset.md#_feecheck)
* [añadir a la lista de las partes](api_avm_utxos.utxoset.md#add)
* [addArray](api_avm_utxos.utxoset.md#addarray)
* [buildBaseTx](api_avm_utxos.utxoset.md#buildbasetx)
* [buildCreateAssetTx](api_avm_utxos.utxoset.md#buildcreateassettx)
* [buildCreateNFTAssetTx](api_avm_utxos.utxoset.md#buildcreatenftassettx)
* [buildCreateNFTMintTx](api_avm_utxos.utxoset.md#buildcreatenftminttx)
* [buildExportTx](api_avm_utxos.utxoset.md#buildexporttx)
* [buildImportTx](api_avm_utxos.utxoset.md#buildimporttx)
* [buildNFTTransferTx](api_avm_utxos.utxoset.md#buildnfttransfertx)
* [buildSECPMintTx](api_avm_utxos.utxoset.md#buildsecpminttx)
* [clon](api_avm_utxos.utxoset.md#clone)
* [crear un entorno de creación](api_avm_utxos.utxoset.md#create)
* [deserie](api_avm_utxos.utxoset.md#deserialize)
* [diferencia entre la diferencia entre la diferencia y la diferencia entre la diferencia](api_avm_utxos.utxoset.md#difference)
* [filtro de filtro](api_avm_utxos.utxoset.md#filter)
* [getAddresses](api_avm_utxos.utxoset.md#getaddresses)
* [getAllUTXOStrings](api_avm_utxos.utxoset.md#getallutxostrings)
* [getAllUTXOs](api_avm_utxos.utxoset.md#getallutxos)
* [getAssetIDs](api_avm_utxos.utxoset.md#getassetids)
* [getBalance](api_avm_utxos.utxoset.md#getbalance)
* [getCodecid](api_avm_utxos.utxoset.md#getcodecid)
* [getMinimumSpendable](api_avm_utxos.utxoset.md#getminimumspendable)
* [getTypeID](api_avm_utxos.utxoset.md#gettypeid)
* [getTypeName](api_avm_utxos.utxoset.md#gettypename)
* [getutXO](api_avm_utxos.utxoset.md#getutxo)
* [getUTXOIDs](api_avm_utxos.utxoset.md#getutxoids)
* [incluye las siguientes](api_avm_utxos.utxoset.md#includes)
* [intersección](api_avm_utxos.utxoset.md#intersection)
* [fusión](api_avm_utxos.utxoset.md#merge)
* [mergeByRule](api_avm_utxos.utxoset.md#mergebyrule)
* [parseUTXO](api_avm_utxos.utxoset.md#parseutxo)
* [eliminar las emisiones de gases](api_avm_utxos.utxoset.md#remove)
* [removeArray](api_avm_utxos.utxoset.md#removearray)
* [serializar](api_avm_utxos.utxoset.md#serialize)
* [simular Diferencia](api_avm_utxos.utxoset.md#symdifference)
* [Unión Europea](api_avm_utxos.utxoset.md#union)

## Propiedades de las propiedades

### _codecid `protegido`

• **_codecid**: *número* = indefinido.

*Heredada de [SigIdx](common_signature.sigidx.md)[._codecid](common_signature.sigidx.md#protected-_codecid)*

*Definido en [src/utils/serialización.ts:40](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/serialization.ts#L40)*

___

### `Protegido` _typeID

• **_typeID**: *any* = undefined

*Overrides [StandardUTXOSet](common_utxos.standardutxoset.md).[_typeID](common_utxos.standardutxoset.md#protected-_typeid)*

*Definido en [src/apis/avm/utxos.ts:115](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/utxos.ts#L115)*

___

### _typeName `protegido`

• **_typeName**: *string* = "UTXOSet"

*Overrides [StandardUTXOSet](common_utxos.standardutxoset.md).[_typeName](common_utxos.standardutxoset.md#protected-_typename)*

*Definido en [src/apis/avm/utxos.ts:114](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/utxos.ts#L114)*

___

### Dirección `Protected`

• **addressUTXOs**: *objeto*

*Heredado de [StandardUTXOSet](common_utxos.standardutxoset.md)[.addressUTXOS](common_utxos.standardutxoset.md#protected-addressutxos)*

*Definido en [src/comm/utxos.ts:194](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/utxos.ts#L194)*

#### Declaración de tipo:

* \[ **dirección**: *string*\]: objeto

* \[ **utxoid**: *string*\]: BN

___

### utxos `protegidos`

• **utxos**: *objeto*

*Heredado de [StandardUTXOSet](common_utxos.standardutxoset.md).[utxos](common_utxos.standardutxoset.md#protected-utxos)*

*Definido en [src/comm/utxos.ts:193](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/utxos.ts#L193)*

#### Declaración de tipo:

* \[ **utxoid**: *string*\]: [UTXO](api_avm_utxos.utxo.md)

## Métodos de trabajo

### _feeCheck

- **_feeCheck**`(fee`: BN, `feeAssetID`: Buffer): *boolean*

*Definido en [src/apis/avm/utxos.ts:166](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/utxos.ts#L166)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `Cuota de pago` | BN |
| `feeAssetID` | Buffer |

**Return:** *booleano*

___

### añadir a la lista de las partes

- **add**(`utxo`: [UTXO](api_avm_utxos.utxo.md) | string, `overwrite`: boolean): *[UTXO](api_avm_utxos.utxo.md)*

*Heredada de [StandardUTXOSet](common_utxos.standardutxoset.md).[add](common_utxos.standardutxoset.md#add)*

*Definido en [src/comm/utxos.ts:228](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/utxos.ts#L228)*

Añade un [StandardUTXO](common_utxos.standardutxo.md) al StandardUTXOSet.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `utxo` | [UTXO](api_avm_utxos.utxo.md) &#124; cadena | - | O bien una cadena serializada cb58 que representa una [StandardUTXO](common_utxos.standardutxo.md) |
| `sobreescribir` | booleano | falso | Si es cierto, si ya existe el UTXOID, sobrescribirlo... falso predeterminado |

**Returns:** *[UTXO](api_avm_utxos.utxo.md)*

Una [StandardUTXO](common_utxos.standardutxo.md) si uno fue agregado e indefinido si nada fue añadido.

___

### addArray

- **addArray**(`utxos`: string []| [UTXO](api_avm_utxos.utxo.md)[], `overwrite`: boolean): *[StandardUTXO](common_utxos.standardutxo.md)[]*

*Heredado de [StandardUTXOSet](common_utxos.standardutxoset.md).[addArray](common_utxos.standardutxoset.md#addarray)*

*Definido en [src/comm/utxos.ts:266](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/utxos.ts#L266)*

Añade una variedad de [StandardUTXOS](common_utxos.standardutxo.md) al [StandardUTXOSet](common_utxos.standardutxoset.md).

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `utxos` | string[] &#124; [UTXO](api_avm_utxos.utxo.md)[] | - | - |
| `sobreescribir` | booleano | falso | Si es cierto, si ya existe el UTXOID, sobrescribirlo... falso predeterminado |

**Returns:** *[StandardUTXO](common_utxos.standardutxo.md)[]*

Una serie de StandardUTXOS que se añadieron.

___

### buildBaseTx

[][][]- **buildBaseTx(networkID:**`` número, `blockchainID`: Buffer, `monto`: BN, `assetID`: Buffer, `buildBaseTx(networkID`: Buffer, `buildBaseTx(networkID`: Buffer, `buildBaseTx(networkID`: Buffer, `honorario`: BN, `feeAssetID`: Buffer, `buildBaseTx(networkID`: Buffer, `comode`: BN, `locktime`: BN, `umbral`: número): *[UnsignedTx](api_avm_transactions.unsignedtx.md)*

*Definido en [src/apis/avm/utxos.ts:262](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/utxos.ts#L262)*

Crea un [UnsignedTx](api_platformvm_transactions.unsignedtx.md) envolviendo un [BaseTx](api_platformvm_basetx.basetx.md). Para un control más granular, usted puede crear su propio [UnsignedTx](api_platformvm_transactions.unsignedtx.md) envoltura manualmente [una](api_platformvm_inputs.transferableinput.md) [BaseTx](api_platformvm_basetx.basetx.md) (con sus entradas transferibles y [salidas transferibles).](api_platformvm_outputs.transferableoutput.md)

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `networkID` | Número de números | - | El número que representa a NetworkID del nodo |
| `blockchainID` | Buffer | - | El [Buffer](https://github.com/feross/buffer) que representa el BlockchainID para la transacción |
| `importe de la cantidad de dinero` | BN | - | El importe del activo que se gastará en su denominación más pequeña, representado como [BN](https://github.com/indutny/bn.js/). |
| `activos` | Buffer | - | [Buffer](https://github.com/feross/buffer) del ID de activos para el UTXO |
| `toAddresses` | Buffer[] | - | Las direcciones para enviar los fondos |
| `fromAddresses` | Buffer[] | - | Las direcciones que se utilizan para enviar los fondos del [Buffer](https://github.com/feross/buffer) UTXOS |
| `changeAddresses` | Buffer[] | no definido. | Opcional. Las direcciones que pueden gastar el cambio restante de las UTXOs. Default: toAddresses |
| `Cuota de pago` | BN | no definido. | Opcional. La cantidad de tasas a quemar en su denominación más pequeña, representada como [BN](https://github.com/indutny/bn.js/) |
| `feeAssetID` | Buffer | no definido. | Opcional. El activo de las tarifas que se están quemando. Default: assetID |
| `meme` | Buffer | no definido. | Opcional. Contiene datos arbitrarios, hasta 256 bytes |
| `as.` | BN | UnixNow() | Opcional. La marca de tiempo para verificar la transacción contra un [BN](https://github.com/indutny/bn.js/) |
| `Tiempo de bloqueo` | BN | nuevo BN(0) | Opcional. El campo de bloqueo creado en las salidas resultantes |
| `umbral` | Número de números | 1 1 | Opcional. El número de firmas necesarias para gastar los fondos en la UTXO resultante |

**Returns:** *[Sin](api_avm_transactions.unsignedtx.md)* Returns:

Una transacción no firmada creada a partir de los parámetros pasados.

___

### buildCreateAssetTx

[][]- **buildCreateAssetTx(networkID:**`` number, `blockchainID`: Buffer, `buildCreateAssetTx(networkID```: Buffer, buildCreateAssetTx(networkID: Buffer, `buildCreateAssetTx(networkID`: [number](api_avm_initialstates.initialstates.md), `nombre`: string, `símbolo`: string, `denomination`: number, `buildCreateAssetTx(networkID`: [SECPMintOutput](api_avm_outputs.secpmintoutput.md)[], `honorario`: BN, `feeAssetID`: Buffer, `memo`: Buffer, `como`: BN): *[UnsignedTx](api_avm_transactions.unsignedtx.md)*

*Definido en [src/apis/avm/utxos.ts:344](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/utxos.ts#L344)*

Crea una transacción de creación de activos sin firmar. Para un control más granular, usted puede crear su propio [[CreateAssetTX]] manualmente (con sus entradas [transferibles](api_platformvm_inputs.transferableinput.md) correspondientes, [salidas transferibles).](api_platformvm_outputs.transferableoutput.md)

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `networkID` | Número de números | - | El número que representa a NetworkID del nodo |
| `blockchainID` | Buffer | - | El [Buffer](https://github.com/feross/buffer) que representa el BlockchainID para la transacción |
| `fromAddresses` | Buffer[] | - | Las direcciones que se utilizan para enviar los fondos del [Buffer](https://github.com/feross/buffer) UTXOS |
| `changeAddresses` | Buffer[] | - | Opcional. Las direcciones que pueden gastar el cambio restante de UTXOs gastado |
| `Estado inicial` | [Estados iniciales.](api_avm_initialstates.initialstates.md) | - | Los [Estados](api_avm_initialstates.initialstates.md) iniciales, que representan el estado incial de un activo creado |
| `Nombre del nombre` | cadena de producción | - | Correa para el nombre descriptivo del activo |
| `Sí, sí.` | cadena de producción | - | Cadena para el símbolo de cosquillas del activo |
| `denominación` | Número de números | - | Número opcional para la denominación que es 10^D. D debe ser >= 0 y <= 32: $1 AVAX = 10^9 $nAVAX |
| `mintOutputs` | [SECPMintOutput](api_avm_outputs.secpmintoutput.md)[] | no definido. | Opcional. Conjunto de productos [SECPMintOutput](api_avm_outputs.secpmintoutput.md)s que se incluirán en la transacción. Estos productos pueden gastarse para mentar más tokens. |
| `Cuota de pago` | BN | no definido. | Opcional. La cantidad de tasas a quemar en su denominación más pequeña, representada como [BN](https://github.com/indutny/bn.js/) |
| `feeAssetID` | Buffer | no definido. | Opcional. El activo de las tarifas que se están quemando. |
| `meme` | Buffer | no definido. | Opcional contiene bytes arbitrarios, hasta 256 bytes |
| `as.` | BN | UnixNow() | Opcional. La marca de tiempo para verificar la transacción contra un [BN](https://github.com/indutny/bn.js/) |

**Returns:** *[Sin](api_avm_transactions.unsignedtx.md)* Returns:

Una transacción no firmada creada a partir de los parámetros pasados.

___

### buildCreateNFTAssetTx

[][]- **buildCreateNFTAssetTx(networkID:**`` number, `blockchainID`: Buffer, `buildCreateNFTAssetTx(networkID```: Buffer, buildCreateNFTAssetTx(networkID: Buffer, `minterSets`: [MinterSet](api_avm_minterset.minterset.md)[], `nombre`: string, `símbolo`: string, `feeAssetID```: Buffer, `memo`: Buffer, `comoDe`: BN, `locktime`: BN): *[UnsignedTx](api_avm_transactions.unsignedtx.md)*

*Definido en [src/apis/avm/utxos.ts:482](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/utxos.ts#L482)*

Crea una transacción de creación de activos sin firmar. Para un control más granular, usted puede crear su propio [[CreateAssetTX]] manualmente (con sus entradas [transferibles](api_platformvm_inputs.transferableinput.md) correspondientes, [salidas transferibles).](api_platformvm_outputs.transferableoutput.md)

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `networkID` | Número de números | - | El número que representa a NetworkID del nodo |
| `blockchainID` | Buffer | - | El [Buffer](https://github.com/feross/buffer) que representa el BlockchainID para la transacción |
| `fromAddresses` | Buffer[] | - | Las direcciones que se utilizan para enviar los fondos del [Buffer](https://github.com/feross/buffer) UTXOS |
| `changeAddresses` | Buffer[] | - | Opcional. Las direcciones que pueden gastar el cambio restante de las UTXOs. |
| `minterSets` | [MinterSet](api_avm_minterset.minterset.md)[] | - | Los mineros y umbrales necesarios para la minera de este activo nft |
| `Nombre del nombre` | cadena de producción | - | Correa para el nombre descriptivo del activo nft |
| `Sí, sí.` | cadena de producción | - | Cadena para el símbolo de garrapatas del activo nft |
| `Cuota de pago` | BN | no definido. | Opcional. La cantidad de tasas a quemar en su denominación más pequeña, representada como [BN](https://github.com/indutny/bn.js/) |
| `feeAssetID` | Buffer | no definido. | Opcional. El activo de las tarifas que se están quemando. |
| `meme` | Buffer | no definido. | Opcional contiene bytes arbitrarios, hasta 256 bytes |
| `as.` | BN | UnixNow() | Opcional. La marca de tiempo para verificar la transacción contra un [BN](https://github.com/indutny/bn.js/) |
| `Tiempo de bloqueo` | BN | no definido. | Opcional. El campo de bloqueo creado en la salida de menta resultante |

**Returns:** *[Sin](api_avm_transactions.unsignedtx.md)* Returns:

Una transacción no firmada creada a partir de los parámetros pasados.

___

### buildCreateNFTMintTx

[][]- **buildCreateNFTMintTx(networkID:**`` number, `blockchainID`: Buffer, `dueños`: [buildCreateNFTMintTx(networkID:](common_output.outputowners.md) []buildCreateNFTMintTx(networkID: `Buffer,` `buildCreateNFTMintTx(networkID`: Buffer, `utxoids`: []string, `groupID`: number, `payload`: Buffer, `feeAssetID```: Buffer, `memo`: Buffer, `como`: BN): *[UnsignedTx](api_avm_transactions.unsignedtx.md)*

*Definido en [src/apis/avm/utxos.ts:546](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/utxos.ts#L546)*

Crea una transacción de menta NFT sin firmar. Para un control más granular, usted puede crear su propio [OperationTx](api_avm_operationtx.operationtx.md) manualmente (con sus correspondientes [Entradas,](api_platformvm_inputs.transferableinput.md) [Productos Transferibles](api_platformvm_outputs.transferableoutput.md) y [[TransferOperation]]s).

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `networkID` | Número de números | - | El número que representa a NetworkID del nodo |
| `blockchainID` | Buffer | - | El [Buffer](https://github.com/feross/buffer) que representa el BlockchainID para la transacción |
| `propietarios de los propietarios` | [Propietarios](common_output.outputowners.md)[] | - | Una serie de [Propietarios de Productos](../modules/src_common.md#outputowners) que se les dará a los NFTs. |
| `fromAddresses` | Buffer[] | - | Las direcciones que se utilizan para enviar los fondos de UTXOs |
| `changeAddresses` | Buffer[] | - | Opcional. Las direcciones que pueden gastar el cambio restante de las UTXOs. |
| `utxoids` | cadena de producción[] | - | Una serie de cadenas para los NFTs que se transfieren |
| `groupID` | Número de números | 0 | Opcional. El grupo al que se emite la NFT. |
| `carga útil` | Buffer | no definido. | Opcional. Datos para NFT Payload. |
| `Cuota de pago` | BN | no definido. | Opcional. La cantidad de tasas a quemar en su denominación más pequeña, representada como [BN](https://github.com/indutny/bn.js/) |
| `feeAssetID` | Buffer | no definido. | Opcional. El activo de las tarifas que se están quemando. |
| `meme` | Buffer | no definido. | Opcional contiene bytes arbitrarios, hasta 256 bytes |
| `as.` | BN | UnixNow() | Opcional. La marca de tiempo para verificar la transacción contra un [BN](https://github.com/indutny/bn.js/) |

**Returns:** *[Sin](api_avm_transactions.unsignedtx.md)* Returns:

Una transacción no firmada creada a partir de los parámetros pasados.

___

### buildExportTx

[][]- **buildExportTx(networkID:**`` number, `blockchainID`: Buffer, `sumo`: BN, `assetID`: Buffer, `buildExportTx(networkID`: Buffer, `buildExportTx(networkID`: Buffer, `buildExportTx(networkID`: Buffer, `destinationChain`: de []buffer, `honorario`: BN, `feeAssetID`: Buffer, `memo`: Buffer, `comoDe`: BN, `locktime`: BN, `umbral`: número): *[UnsignedTx](api_avm_transactions.unsignedtx.md)*

*Definido en [src/apis/avm/utxos.ts:815](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/utxos.ts#L815)*

Crea una transacción ExportTx sin firmar.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `networkID` | Número de números | - | El número que representa a NetworkID del nodo |
| `blockchainID` | Buffer | - | El [Buffer](https://github.com/feross/buffer) que representa el BlockchainID para la transacción |
| `importe de la cantidad de dinero` | BN | - | La cantidad que se exportará como [BN](https://github.com/indutny/bn.js/) |
| `activos` | Buffer | - | - |
| `toAddresses` | Buffer[] | - | Una serie de direcciones como [Buffer](https://github.com/feross/buffer) que recaba el AVAX |
| `fromAddresses` | Buffer[] | - | Una serie de direcciones como [Buffer](https://github.com/feross/buffer) que posee el AVAX |
| `changeAddresses` | Buffer[] | no definido. | Opcional. Las direcciones que pueden gastar el cambio restante de las UTXOs. |
| `destinationChain de destino` | Buffer | no definido. | Opcional. Un [buffer](https://github.com/feross/buffer) para el chainid donde enviar el activo. |
| `Cuota de pago` | BN | no definido. | Opcional. La cantidad de tasas a quemar en su denominación más pequeña, representada como [BN](https://github.com/indutny/bn.js/) |
| `feeAssetID` | Buffer | no definido. | Opcional. El activo de las tarifas que se están quemando. |
| `meme` | Buffer | no definido. | Opcional contiene bytes arbitrarios, hasta 256 bytes |
| `as.` | BN | UnixNow() | Opcional. La marca de tiempo para verificar la transacción contra un [BN](https://github.com/indutny/bn.js/) |
| `Tiempo de bloqueo` | BN | nuevo BN(0) | Opcional. El campo de bloqueo creado en las salidas resultantes |
| `umbral` | Número de números | 1 1 | Opcional. El número de firmas necesarias para gastar los fondos en la UTXO resultante |

**Returns:** *[Sin](api_avm_transactions.unsignedtx.md)* Returns:

Una transacción no firmada creada a partir de los parámetros pasados.

___

### buildImportTx

[][]- **buildImportTx(networkID:**`` number, `blockchainID`: Buffer, `buildImportTx(networkID```: Buffer, `buildImportTx(networkID`: []Buffer, buildImportTx(networkID: Buffer, `atomics`: [UTXO](api_avm_utxos.utxo.md)[], `sourceChain`: Buffer, `feeAssetID```: Buffer, `memo`: Buffer, `como`: BN, `locktime`: BN, `umbral`: número): *[UnsignedTx](api_avm_transactions.unsignedtx.md)*

*Definido en [src/apis/avm/utxos.ts:702](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/utxos.ts#L702)*

Crea una transacción de ImportTx sin firmar.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `networkID` | Número de números | - | El número que representa a NetworkID del nodo |
| `blockchainID` | Buffer | - | El [Buffer](https://github.com/feross/buffer) que representa el BlockchainID para la transacción |
| `toAddresses` | Buffer[] | - | Las direcciones para enviar los fondos |
| `fromAddresses` | Buffer[] | - | Las direcciones que se utilizan para enviar los fondos del [Buffer](https://github.com/feross/buffer) UTXOS |
| `changeAddresses` | Buffer[] | - | Opcional. Las direcciones que pueden gastar el cambio restante de las UTXOs. |
| `átomos` | [UTXO](api_avm_utxos.utxo.md)[] | - | - |
| `sourceChain` | Buffer | no definido. | Un [buffer](https://github.com/feross/buffer) para el chainid de donde vienen las importaciones. |
| `Cuota de pago` | BN | no definido. | Opcional. La cantidad de tasas a quemar en su denominación más pequeña, representada como [BN](https://github.com/indutny/bn.js/). La tarifa vendrá de las entradas primero, si pueden. |
| `feeAssetID` | Buffer | no definido. | Opcional. El activo de las tarifas que se están quemando. |
| `meme` | Buffer | no definido. | Opcional contiene bytes arbitrarios, hasta 256 bytes |
| `as.` | BN | UnixNow() | Opcional. La marca de tiempo para verificar la transacción contra un [BN](https://github.com/indutny/bn.js/) |
| `Tiempo de bloqueo` | BN | nuevo BN(0) | Opcional. El campo de bloqueo creado en las salidas resultantes |
| `umbral` | Número de números | 1 1 | Opcional. El número de firmas necesarias para gastar los fondos en la UTXO resultante |

**Returns:** *[Sin](api_avm_transactions.unsignedtx.md)* Returns:

Una transacción no firmada creada a partir de los parámetros pasados.

___

### buildNFTTransferTx

[][][]- **buildNFTTransferTx(networkID:**`` number, `blockchainID`: Buffer, `buildNFTTransferTx(networkID`: Buffer, `buildNFTTransferTx(networkID```: Buffer, buildNFTTransferTx(networkID: Buffer, `utxoids`: []string, `feeAssetID```: Buffer, `memo`: Buffer, `como`: BN, `locktime`: BN, `umbral`: número): *[UnsignedTx](api_avm_transactions.unsignedtx.md)*

*Definido en [src/apis/avm/utxos.ts:623](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/utxos.ts#L623)*

Crea una transacción de transferencia NFT sin firmar. Para un control más granular, usted puede crear su propio [OperationTx](api_avm_operationtx.operationtx.md) manualmente (con sus correspondientes [Entradas,](api_platformvm_inputs.transferableinput.md) [Productos Transferibles](api_platformvm_outputs.transferableoutput.md) y [[TransferOperation]]s).

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `networkID` | Número de números | - | El número que representa a NetworkID del nodo |
| `blockchainID` | Buffer | - | El [Buffer](https://github.com/feross/buffer) que representa el BlockchainID para la transacción |
| `toAddresses` | Buffer[] | - | Una serie de [Buffer](https://github.com/feross/buffer)s que indican quién recibe el NFT |
| `fromAddresses` | Buffer[] | - | Una matriz para [Buffer](https://github.com/feross/buffer) que posee el NFT |
| `changeAddresses` | Buffer[] | - | Opcional. Las direcciones que pueden gastar el cambio restante de las UTXOs. |
| `utxoids` | cadena de producción[] | - | Una serie de cadenas para los NFTs que se transfieren |
| `Cuota de pago` | BN | no definido. | Opcional. La cantidad de tasas a quemar en su denominación más pequeña, representada como [BN](https://github.com/indutny/bn.js/) |
| `feeAssetID` | Buffer | no definido. | Opcional. El activo de las tarifas que se están quemando. |
| `meme` | Buffer | no definido. | Opcional contiene bytes arbitrarios, hasta 256 bytes |
| `as.` | BN | UnixNow() | Opcional. La marca de tiempo para verificar la transacción contra un [BN](https://github.com/indutny/bn.js/) |
| `Tiempo de bloqueo` | BN | nuevo BN(0) | Opcional. El campo de bloqueo creado en las salidas resultantes |
| `umbral` | Número de números | 1 1 | Opcional. El número de firmas necesarias para gastar los fondos en la UTXO resultante |

**Returns:** *[Sin](api_avm_transactions.unsignedtx.md)* Returns:

Una transacción no firmada creada a partir de los parámetros pasados.

___

### buildSECPMintTx

[]- **buildSECPMintTx(networkID:**`` number, `blockchainID`: Buffer, `buildSECPMintTx(networkID```: [SECPMintOutput](api_avm_outputs.secpmintoutput.md), `transferencia`: [SECPTransferOutput](api_avm_outputs.secptransferoutput.md), `buildSECPMintTx(networkID`: []Buffer, `mintUTXOID`: string, `fee`: BN, `feeAssetID`: Buffer, `memo`: Buffer, `como`: BN): *[UnsignedTx](api_avm_transactions.unsignedtx.md)*

*Definido en [src/apis/avm/utxos.ts:404](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/utxos.ts#L404)*

Crea una transacción de menta Secp sin firmar. Para un control más granular, usted puede crear su propio [OperationTx](api_avm_operationtx.operationtx.md) manualmente (con sus correspondientes [Entradas,](api_platformvm_inputs.transferableinput.md) [Productos Transferibles](api_platformvm_outputs.transferableoutput.md) y [[TransferOperation]]s).

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `networkID` | Número de números | - | El número que representa a NetworkID del nodo |
| `blockchainID` | Buffer | - | El [Buffer](https://github.com/feross/buffer) que representa el BlockchainID para la transacción |
| `mintOwner,` | [SECPMintOutput](api_avm_outputs.secpmintoutput.md) | - | Una [SECPMintOutput](api_avm_outputs.secpmintoutput.md) que especifica el nuevo conjunto de mineros |
| `transferOwner` | [SECPTransferOutput](api_avm_outputs.secptransferoutput.md) | - | Una [SECPTransferOutput](api_platformvm_outputs.secptransferoutput.md) que especifica dónde irán las fichas mentadas |
| `fromAddresses` | Buffer[] | - | Las direcciones que se utilizan para enviar los fondos del [Buffer](https://github.com/feross/buffer) UTXOS |
| `changeAddresses` | Buffer[] | - | Las direcciones que pueden gastar el cambio restante de UTXOs gastado |
| `mintutXOID` | cadena de producción | - | El UTXOID para [[SCPMintOutput]] que se está gastando para producir más fichas |
| `Cuota de pago` | BN | no definido. | Opcional. La cantidad de tasas a quemar en su denominación más pequeña, representada como [BN](https://github.com/indutny/bn.js/) |
| `feeAssetID` | Buffer | no definido. | Opcional. El activo de las tarifas que se están quemando. |
| `meme` | Buffer | no definido. | Opcional contiene bytes arbitrarios, hasta 256 bytes |
| `as.` | BN | UnixNow() | Opcional. La marca de tiempo para verificar la transacción contra un [BN](https://github.com/indutny/bn.js/) |

**Returns:** *[Sin](api_avm_transactions.unsignedtx.md)* Returns:

___

### clon

- **clone**(): *esto*

*Overrides [StandardUTXOSet](common_utxos.standardutxoset.md).[clone](common_utxos.standardutxoset.md#abstract-clone)*

*Definido en [src/apis/avm/utxos.ts:159](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/utxos.ts#L159)*

**Returns:** *esto*

___

### crear un entorno de creación

*-* **create**(...`args`: []cualquiera

*Overrides [StandardUTXOSet](common_utxos.standardutxoset.md).[create](common_utxos.standardutxoset.md#abstract-create)*

*Definido en [src/apis/avm/utxos.ts:155](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/utxos.ts#L155)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `..args` | cualquier otra cosa que no sea[] |

**Returns:** *esto*

___

### deserie

- **deserialize**(`fields`: objeto, `codificación`: [SerializedEncoding](../modules/src_utils.md#serializedencoding)): *vacío*

*Superaciones [StandardParseableInput](common_inputs.standardparseableinput.md).[deserialize](common_inputs.standardparseableinput.md#deserialize)*

*Definido en [src/apis/avm/utxos.ts:119](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/utxos.ts#L119)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `campos de cultivo` | objeto de la operación | - |
| `codificación` | [SerializedEncoding](../modules/src_utils.md#serializedencoding) | "hex" |

**Retornos:** *vacío*

___

### diferencia entre la diferencia entre la diferencia y la diferencia entre la diferencia

- **difference**(`utxoset`: este): *esto*

*Heredado de [StandardUTXOSet](common_utxos.standardutxoset.md).[difference](common_utxos.standardutxoset.md#difference) diferencia*

*Definido en [src/comm/utxos.ts:529](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/utxos.ts#L529)*

Establecer la diferencia entre este conjunto y un parámetro.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `utxoset` | Esto es lo que es un problema | El conjunto de la diferencia |

**Returns:** *esto*

Un nuevo StandardUTXOSet que contiene la diferencia

___

### filtro de filtro

- **filter**(`args`: []cualquiera y `lambda`: función): *esto*

*Heredado de [StandardUTXOSet](common_utxos.standardutxoset.md).[filter](common_utxos.standardutxoset.md#filter)*

*Definido en [src/comm/utxos.ts:477](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/utxos.ts#L477)*

**Parámetros:**

• **args**: *cualquier[]*

• **lambda**: *función*

- (`utxo`: [UTXO](api_avm_utxos.utxo.md), .`..largos`: []any): *booleano*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `utxo` | [UTXO](api_avm_utxos.utxo.md) |
| `...grandes` | cualquier otra cosa que no sea[] |

**Returns:** *esto*

___

### getAddresses

- **gets():** *Buffer[]*

*Heredado de [StandardUTXOSet](common_utxos.standardutxoset.md).[getAddresses](common_utxos.standardutxoset.md#getaddresses)*

*Definido en [src/comm/utxos.ts:416](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/utxos.ts#L416)*

Obtiene las direcciones en el [StandardUTXOSet](common_utxos.standardutxoset.md) y devuelve una matriz de [Buffer](https://github.com/feross/buffer).

**Returns:** *Buffer[]*

___

### getAllUTXOStrings

- **getAllUTXOStrings**(`utxoids`: []string): *string[]*

*Heredado de [StandardUTXOSet](common_utxos.standardutxoset.md).[getAllUTXOStrings](common_utxos.standardutxoset.md#getallutxostrings)*

*Definido en [src/comm/utxos.ts:367](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/utxos.ts#L367)*

Obtiene todas las cadenas de [StandardUTXO](common_utxos.standardutxo.md)s como cadenas, opcionalmente que coincidan con UTXOIDs en un array.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `utxoids` | cadena de producción[] | no definido. | Una matriz opcional de UTXOIDs, devuelve todos los [StandardUTXO](common_utxos.standardutxo.md)s si no se proporciona |

**Return:** *string[]*

Una serie de [cadenas](common_utxos.standardutxo.md) estandarizadas como cb58 serializadas.

___

### getAllUTXOs

- **getAllUTXOs**(`utxoids`: []string): *[UTXO](api_avm_utxos.utxo.md)[]*

*Heredada de [StandardUTXOSet](common_utxos.standardutxoset.md)[.getAllUTXOS](common_utxos.standardutxoset.md#getallutxos)*

*Definido en [src/comm/utxos.ts:346](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/utxos.ts#L346)*

Obtiene todos los [StandardUTXO](common_utxos.standardutxo.md)s, opcionalmente que coincida con UTXOIDs en una matriz

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `utxoids` | cadena de producción[] | no definido. | Una matriz opcional de UTXOIDs, devuelve todos los [StandardUTXO](common_utxos.standardutxo.md)s si no se proporciona |

**Returns:** *[UTXO](api_avm_utxos.utxo.md)[]*

Una serie de [StandardUTXO](common_utxos.standardutxo.md)s.

___

### getAssetIDs

- **getAssetIDs**(`addresses`: []Buffer): *Buffer[]*

*Heredada de [StandardUTXOSet](common_utxos.standardutxoset.md).[getAssetIDs](common_utxos.standardutxoset.md#getassetids)*

*Definido en [src/comm/utxos.ts:455](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/utxos.ts#L455)*

Obtiene todos los ID de Activos, opcionalmente que coincida con los ID de activos en una matriz

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `direcciones` | Buffer[] | no definido. |

**Returns:** *Buffer[]*

Una variedad de [Buffer](https://github.com/feross/buffer) que representa las ID de activos.

___

### getBalance

- **getBalance**(`addresses`: Buffer, `assetID`: Buffer | []string, `asOf`: BN): *BN*

*Heredada de [StandardUTXOSet](common_utxos.standardutxoset.md).[getBalance](common_utxos.standardutxoset.md#getbalance)*

*Definido en [src/comm/utxos.ts:428](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/utxos.ts#L428)*

Devuelve el equilibrio de un conjunto de direcciones en el StandardUTXOSet.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `direcciones` | Buffer[] | - | Una serie de direcciones |
| `activos` | Buffer &#124; cadena | - | O bien un [Buffer](https://github.com/feross/buffer) o una representación serializada cb58 de un AssetID |
| `as.` | BN | no definido. | La marca de tiempo para verificar la transacción contra un [BN](https://github.com/indutny/bn.js/) |

**Returns:** *BN*

Devuelve el saldo total como un [BN](https://github.com/indutny/bn.js/).

___

### getCodecid

- **getCodecid():** *número*

*Heredada de [SigIdx](common_signature.sigidx.md)[.getCodecid](common_signature.sigidx.md#getcodecid)*

*Definido en [src/utils/serialización.ts:59](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/serialization.ts#L59)*

Utilizado en serialización. Opcional. TypeID es un número para el tipo de identificación de objeto que se está saliendo.

**Retornos:** *número*

___

### getMinimumSpendable

- **getMinimumSpendable(aad:**`` [getMinimumSpendable(aad:](api_avm_utxos.assetamountdestination.md) `como`: BN, `tiempo de` bloqueo: BN, `umbral`: número): *[Error](src_utils.avalancheerror.md#static-error)*

*Definido en [src/apis/avm/utxos.ts:172](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/utxos.ts#L172)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `a)` | [AssetAmountDestination](api_avm_utxos.assetamountdestination.md) | - |
| `as.` | BN | UnixNow() |
| `Tiempo de bloqueo` | BN | nuevo BN(0) |
| `umbral` | Número de números | 1 1 |

**Returns:** *[Error](src_utils.avalancheerror.md#static-error)*

___

### getTypeID

- **getTypeID**(): *número*

*Heredada de [SigIdx](common_signature.sigidx.md).[getTypeID](common_signature.sigidx.md#gettypeid)*

*Definido en [src/utils/serialización.ts:52](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/serialization.ts#L52)*

Utilizado en serialización. Opcional. TypeID es un número para el tipo de identificación de objeto que se está saliendo.

**Retornos:** *número*

___

### getTypeName

- **getTypeName**(): *string*

*Heredada de [SigIdx](common_signature.sigidx.md).[getTypeName](common_signature.sigidx.md#gettypename)*

*Definido en [src/utils/serialización.ts:45](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/serialization.ts#L45)*

Utilizado en serialización. TypeName es un nombre de cadena para el tipo de objeto que se está saliendo.

**Return:** *string*

___

### getutXO

- **getUTXO**(`utxoid`: string): *[UTXO](api_avm_utxos.utxo.md)*

*Heredada de [StandardUTXOSet](common_utxos.standardutxoset.md).[getUTXO](common_utxos.standardutxoset.md#getutxo)*

*Definido en [src/comm/utxos.ts:337](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/utxos.ts#L337)*

Obtiene un [StandardUTXO](common_utxos.standardutxo.md) desde el [StandardUTXOSet](common_utxos.standardutxoset.md) por su UTXOID.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `utxoid` | cadena de producción | Cadena que representa el UTXOID |

**Returns:** *[UTXO](api_avm_utxos.utxo.md)*

Una [StandardUTXO](common_utxos.standardutxo.md) si existe en el conjunto.

___

### getUTXOIDs

- **getUTXOIDs**(`addresses`: []Buffer, `gastable`: booleano): *string[]*

*Heredado de [StandardUTXOSet](common_utxos.standardutxoset.md).[getUTXOIDs](common_utxos.standardutxoset.md#getutxoids)*

*Definido en [src/comm/utxos.ts:392](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/utxos.ts#L392)*

Dado una dirección o una matriz de direcciones, devuelve todos los UTXOIDs para esas direcciones

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `direcciones` | Buffer[] | no definido. | - |
| `fungible` | booleano | Verdadero | Si es cierto, solo recupera UTXOIDs cuyo tiempo de bloqueo ha pasado |

**Return:** *string[]*

Una serie de direcciones.

___

### incluye las siguientes

- **includes**(`utxo`: [UTXO](api_avm_utxos.utxo.md) | string): *booleano*

*Heredado de [StandardUTXOSet](common_utxos.standardutxoset.md).[includes](common_utxos.standardutxoset.md#includes)*

*Definido en [src/comm/utxos.ts:203](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/utxos.ts#L203)*

Devuelve cierto si el [StandardUTXO](common_utxos.standardutxo.md) está en el StandardUTXOSet.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `utxo` | [UTXO](api_avm_utxos.utxo.md) &#124; cadena | O bien una cadena serializada cb58 que representa una [StandardUTXO](common_utxos.standardutxo.md) |

**Return:** *booleano*

___

### intersección

- **intersection**(`utxoset`: este): *esto*

*Heredada de [StandardUTXOSet](common_utxos.standardutxoset.md).[intersection](common_utxos.standardutxoset.md#intersection)*

*Definido en [src/comm/utxos.ts:515](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/utxos.ts#L515)*

Establece la interconexión entre este conjunto y un parámetro.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `utxoset` | Esto es lo que es un problema | El conjunto para intersecar |

**Returns:** *esto*

Un nuevo StandardUTXOSet que contiene la intersección

___

### fusión

- **merge**(`utxoset`: this, `hasUTXOIDs`: []string): *this*

*Heredado de [StandardUTXOSet](common_utxos.standardutxoset.md).[merge](common_utxos.standardutxoset.md#merge)*

*Definido en [src/comm/utxos.ts:496](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/utxos.ts#L496)*

Devuelve un nuevo conjunto con copia de UTXOs en este parámetro y configura.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `utxoset` | Esto es lo que es un problema | - | El [StandardUTXOSet](common_utxos.standardutxoset.md) para fusionarse con este |
| `hasUTXOIDs` | cadena de producción[] | no definido. | subselect un conjunto de [StandardUTXO](common_utxos.standardutxo.md)s que tienen los UTXOIDs proporcionados en este array, se desplomará a todos los UTXOS |

**Returns:** *esto*

Un nuevo StandardUTXOSet que contiene todos los elementos filtrados.

___

### mergeByRule

- **mergeByRule**(`utxoset`: this, `mergeRule`: [MergeRule](../modules/utils_constants.md#mergerule)): *this*

*Heredado de [StandardUTXOSet](common_utxos.standardutxoset.md).[mergeByRule](common_utxos.standardutxoset.md#mergebyrule)*

*Definido en [src/comm/utxos.ts:578](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/utxos.ts#L578)*

Fuga un conjunto por la regla proporcionada.

**`observaciones sobre las observaciones formuladas`** Las reglas de fusión son las siguientes:
* "intersección" - la intersección del conjunto
* "differenceSelf" - la diferencia entre los datos existentes y el nuevo conjunto
* "differenceNew" - la diferencia entre los nuevos datos y el conjunto existente
* "symDifference" - la unión de las diferencias entre ambos conjuntos de datos
* "unión" - el conjunto único de todos los elementos contenidos en ambos conjuntos
* "unionMinusNew" - el conjunto único de todos los elementos contenidos en ambos conjuntos, excluidos los valores solo encontrados en el nuevo conjunto
* "unionMinusSelf" - el conjunto único de todos los elementos contenidos en ambos conjuntos, excluidos los valores solo encontrados en el conjunto existente

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `utxoset` | Esto es lo que es un problema | El conjunto de la fusión por la Regla de Fusión |
| `mergeRule` | [Regla de fusión](../modules/utils_constants.md#mergerule) | La [regla](../modules/utils_constants.md#mergerule) de fusión aplicable |

**Returns:** *esto*

Un nuevo StandardUTXOSet que contiene los datos fusionados

___

### parseUTXO

- **parseUTXO**(`utxo`: [UTXO](api_avm_utxos.utxo.md) | string): *[UTXO](api_avm_utxos.utxo.md)*

*Overrides [StandardUTXOSet](common_utxos.standardutxoset.md).[parseUTXO](common_utxos.standardutxoset.md#abstract-parseutxo)*

*Definido en [src/apis/avm/utxos.ts:141](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/utxos.ts#L141)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `utxo` | [UTXO](api_avm_utxos.utxo.md) &#124; cadena |

**Returns:** *[UTXO](api_avm_utxos.utxo.md)*

___

### eliminar las emisiones de gases

- **remove**(`utxo`: [UTXO](api_avm_utxos.utxo.md) | string): *[UTXO](api_avm_utxos.utxo.md)*

*Heredado de [StandardUTXOSet](common_utxos.standardutxoset.md).[remove](common_utxos.standardutxoset.md#remove)*

*Definido en [src/comm/utxos.ts:284](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/utxos.ts#L284)*

Elimina un [StandardUTXO](common_utxos.standardutxo.md) del [StandardUTXOSet](common_utxos.standardutxoset.md) si existe.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `utxo` | [UTXO](api_avm_utxos.utxo.md) &#124; cadena | O bien una cadena serializada cb58 que representa una [StandardUTXO](common_utxos.standardutxo.md) |

**Returns:** *[UTXO](api_avm_utxos.utxo.md)*

Una [StandardUTXO](common_utxos.standardutxo.md) si fue removido y sin definir si nada fue eliminado.

___

### removeArray

- **removeArray**(`utxos`: string []| [UTXO):](api_avm_utxos.utxo.md) []*[UTXO](api_avm_utxos.utxo.md)[]*

*Heredado de [StandardUTXOSet](common_utxos.standardutxoset.md).[removeArray](common_utxos.standardutxoset.md#removearray)*

*Definido en [src/comm/utxos.ts:319](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/utxos.ts#L319)*

Elimina una variedad de [StandardUTXOS](common_utxos.standardutxo.md) al [StandardUTXOSet](common_utxos.standardutxoset.md).

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `utxos` | string[] &#124; [UTXO](api_avm_utxos.utxo.md)[] |

**Returns:** *[UTXO](api_avm_utxos.utxo.md)[]*

Una serie de UTXOS que fueron eliminados.

___

### serializar

- **serialize**(`encoding`: [SerializedEncoding](../modules/src_utils.md#serializedencoding)): *objeto*

*Heredada de [StandardUTXOSet](common_utxos.standardutxoset.md).[serialize](common_utxos.standardutxoset.md#serialize)*

*Superaciones [Serializable](utils_serialization.serializable.md).[serialize](utils_serialization.serializable.md#serialize)*

*Definido en [src/comm/utxos.ts:169](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/utxos.ts#L169)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `codificación` | [SerializedEncoding](../modules/src_utils.md#serializedencoding) | "hex" |

**Return:** *objeto*

___

### simular Diferencia

- **symDifference**(`utxoset`: este): *esto*

*Heredada de [StandardUTXOSet](common_utxos.standardutxoset.md).[symDifference](common_utxos.standardutxoset.md#symdifference)*

*Definido en [src/comm/utxos.ts:543](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/utxos.ts#L543)*

Establecer la diferencia simétrica entre este conjunto y un parámetro.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `utxoset` | Esto es lo que es un problema | El conjunto de la diferencia simétrica |

**Returns:** *esto*

Un nuevo StandardUTXOSet que contiene la diferencia simétrica

___

### Unión Europea

- **union**(`utxoset`: este): *esto*

*Heredado de [StandardUTXOSet](common_utxos.standardutxoset.md).[union](common_utxos.standardutxoset.md#union)*

*Definido en [src/comm/utxos.ts:558](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/utxos.ts#L558)*

Establecer unión entre este conjunto y un parámetro.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `utxoset` | Esto es lo que es un problema | El conjunto de la unión |

**Returns:** *esto*

Un nuevo StandardUTXOSet que contiene el sindicato
