[avalanche](../README.md) › [API-PlatformVM](../modules/api_platformvm.md) › [PlatformVMAPI](api_platformvm.platformvmapi.md)

# Clase: PlatformVMAPI

Clase para interactuar con la plataforma de un node's

**`comentarios`** Esto extiende la clase [JRPCAPI](common_jrpcapi.jrpcapi.md). Esta clase no debe ser llamada directamente. En cambio, utilice la función [Avalanche.addAPI](avalanche.avalanche-1.md#addapi) para registrar esta interfaz con Avalanche.

## Jerarquía

m. [JRPCAPI](common_jrpcapi.jrpcapi.md)

m. **PlatformVMAPI**

## Índice de participación

### Constructores

* [constructor](api_platformvm.platformvmapi.md#constructor)

### Propiedades de las propiedades

* [AVAXAssetID](api_platformvm.platformvmapi.md#protected-avaxassetid)
* [baseurl](api_platformvm.platformvmapi.md#protected-baseurl)
* [blockchainAlias](api_platformvm.platformvmapi.md#protected-blockchainalias)
* [blockchainID](api_platformvm.platformvmapi.md#protected-blockchainid)
* [núcleo de la](api_platformvm.platformvmapi.md#protected-core)
* [creationTxFee](api_platformvm.platformvmapi.md#protected-creationtxfee)
* [db](api_platformvm.platformvmapi.md#protected-db)
* [jrpcVersion](api_platformvm.platformvmapi.md#protected-jrpcversion)
* [minDelegatorStake](api_platformvm.platformvmapi.md#protected-mindelegatorstake)
* [minValidatorStake](api_platformvm.platformvmapi.md#protected-minvalidatorstake)
* [rpcid](api_platformvm.platformvmapi.md#protected-rpcid)
* [txFee](api_platformvm.platformvmapi.md#protected-txfee)

### Métodos de trabajo

* [addDelegator](api_platformvm.platformvmapi.md#adddelegator)
* [addSubnetValidator](api_platformvm.platformvmapi.md#addsubnetvalidator)
* [addValidator](api_platformvm.platformvmapi.md#addvalidator)
* [addressFromBuffer](api_platformvm.platformvmapi.md#addressfrombuffer)
* [buildAddDelegatorTx](api_platformvm.platformvmapi.md#buildadddelegatortx)
* [buildAddValidatorTx](api_platformvm.platformvmapi.md#buildaddvalidatortx)
* [buildCreateSubnetTx](api_platformvm.platformvmapi.md#buildcreatesubnettx)
* [buildExportTx](api_platformvm.platformvmapi.md#buildexporttx)
* [buildImportTx](api_platformvm.platformvmapi.md#buildimporttx)
* [callMethod](api_platformvm.platformvmapi.md#callmethod)
* [checkGooseEgg](api_platformvm.platformvmapi.md#checkgooseegg)
* [createAddress](api_platformvm.platformvmapi.md#createaddress)
* [createBlockchain](api_platformvm.platformvmapi.md#createblockchain)
* [createSubnet](api_platformvm.platformvmapi.md#createsubnet)
* [exportAVAX](api_platformvm.platformvmapi.md#exportavax)
* [exportKey](api_platformvm.platformvmapi.md#exportkey)
* [getAVAXAssetID](api_platformvm.platformvmapi.md#getavaxassetid)
* [getBalance](api_platformvm.platformvmapi.md#getbalance)
* [getBaseURL](api_platformvm.platformvmapi.md#getbaseurl)
* [getBlockchainAlias](api_platformvm.platformvmapi.md#getblockchainalias)
* [getBlockchainID](api_platformvm.platformvmapi.md#getblockchainid)
* [getBlockchainstatus](api_platformvm.platformvmapi.md#getblockchainstatus)
* [getBlockchains](api_platformvm.platformvmapi.md#getblockchains)
* [getCreationTxFee](api_platformvm.platformvmapi.md#getcreationtxfee)
* [getCurrentSupply](api_platformvm.platformvmapi.md#getcurrentsupply)
* [getCurrentValidators](api_platformvm.platformvmapi.md#getcurrentvalidators)
* [getDB](api_platformvm.platformvmapi.md#getdb)
* [getDefaultCreationTxFee](api_platformvm.platformvmapi.md#getdefaultcreationtxfee)
* [getDefaultTxFee](api_platformvm.platformvmapi.md#getdefaulttxfee)
* [getHeight](api_platformvm.platformvmapi.md#getheight)
* [getMinStake](api_platformvm.platformvmapi.md#getminstake)
* [getPendingValidators](api_platformvm.platformvmapi.md#getpendingvalidators)
* [getRPCID](api_platformvm.platformvmapi.md#getrpcid)
* [getRewardUTXOS](api_platformvm.platformvmapi.md#getrewardutxos)
* [getStake](api_platformvm.platformvmapi.md#getstake)
* [getStakingAssetID Asset](api_platformvm.platformvmapi.md#getstakingassetid)
* [getSubnets](api_platformvm.platformvmapi.md#getsubnets)
* [getTx](api_platformvm.platformvmapi.md#gettx)
* [getTxFee](api_platformvm.platformvmapi.md#gettxfee)
* [getTxStatus](api_platformvm.platformvmapi.md#gettxstatus)
* [getUTXOs](api_platformvm.platformvmapi.md#getutxos)
* [importAVAX](api_platformvm.platformvmapi.md#importavax)
* [importKey](api_platformvm.platformvmapi.md#importkey)
* [issueTx](api_platformvm.platformvmapi.md#issuetx)
* [keyChain](api_platformvm.platformvmapi.md#keychain)
* [listAddresses](api_platformvm.platformvmapi.md#listaddresses)
* [parseAddress](api_platformvm.platformvmapi.md#parseaddress)
* [refreshBlockchainID](api_platformvm.platformvmapi.md#refreshblockchainid)
* [sampleValidators](api_platformvm.platformvmapi.md#samplevalidators)
* [setAVAXAssetID](api_platformvm.platformvmapi.md#setavaxassetid)
* [setBaseURL](api_platformvm.platformvmapi.md#setbaseurl)
* [setBlockchainAlias](api_platformvm.platformvmapi.md#setblockchainalias)
* [setCreationTxFee](api_platformvm.platformvmapi.md#setcreationtxfee)
* [setMinStake](api_platformvm.platformvmapi.md#setminstake)
* [setTxFee](api_platformvm.platformvmapi.md#settxfee)
* [validado por](api_platformvm.platformvmapi.md#validatedby)
* [validar](api_platformvm.platformvmapi.md#validates)

## Constructores

### constructor

\+ **nueva** PlatformVMAPI(`core`: [AvalancheCore](avalanchecore.avalanchecore-1.md), `baseurl`: string): *[PlatformVMAPI](api_platformvm.platformvmapi.md)*

*Superación [JRPCAPI](common_jrpcapi.jrpcapi.md).[constructor](common_jrpcapi.jrpcapi.md#constructor)*

*Definido en [src/apis/platformvm/api.ts:1443](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/api.ts#L1443)*

Esta clase no debe ser instantiated directamente. En lugar de ello, utilice el método [Avalanche.addAPI](avalanche.avalanche-1.md#addapi).

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `núcleo de la` | [AvalancheCore](avalanchecore.avalanchecore-1.md) | - | Una referencia a la clase Avalanche |
| `baseurl` | cadena de producción | "/ext/bc/P" | Default a la cadena "/ext/P" como la ruta hacia el baseurl de blockchain. |

**Retornos:** *[PlatformVMAPI](api_platformvm.platformvmapi.md)*

## Propiedades de las propiedades

### AVAXAssetID `protegido`

• **AVAXAssetID**: *Buffer* = indefinido.

*Definido en [src/apis/platformvm/api.ts:56](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/api.ts#L56)*

___

### Base `protegida`

• **baseurl**: *cadena*

*Heredada de [APIBase](common_apibase.apibase.md).[baseurl](common_apibase.apibase.md#protected-baseurl)*

*Definido en [src/comm/apibase.ts:28](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/apibase.ts#L28)*

___

### blockchainAlias `protegidas`

• **blockchainAlias**: *string* = undefined

*Definido en [src/apis/platformvm/api.ts:54](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/api.ts#L54)*

___

### blockchainID `protegido`

• **blockchainID**: *string* = PlatformChainID

*Definido en [src/apis/platformvm/api.ts:52](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/api.ts#L52)*

___

### Correa `protegida`

• **núcleo**: *[AvalancheCore](avalanchecore.avalanchecore-1.md)*

*Heredada de [APIbase.core](common_apibase.apibase.md)[](common_apibase.apibase.md#protected-core)*

*Definido en [src/comm/apibase.ts:26](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/apibase.ts#L26)*

___

### Creación `Protected`

• **creationTxFee**: *BN* = indefinido.

*Definido en [src/apis/platformvm/api.ts:60](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/api.ts#L60)*

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

### minDelegatorStake `Protected`

• **minDelegatorStake**: *BN* = indefinido.

*Definido en [src/apis/platformvm/api.ts:64](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/api.ts#L64)*

___

### minValidatorStake `protegido` Stom

• **minValidatorStake**: *BN* = undefined

*Definido en [src/apis/platformvm/api.ts:62](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/api.ts#L62)*

___

### rpcid `protegido`

• **rpcid**: *número* = 1

*Heredada de [JRPCAPI](common_jrpcapi.jrpcapi.md).[rpcid](common_jrpcapi.jrpcapi.md#protected-rpcid)*

*Definido en [src/comm/jrpcapi.ts:12](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/jrpcapi.ts#L12)*

___

### TxFee `protegido`

• **txFee**: *BN* = indefinido.

*Definido en [src/apis/platformvm/api.ts:58](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/api.ts#L58)*

## Métodos de trabajo

### addDelegator

- **addDelegator(username: de usuario:**`` string, contraseña: string, `nodeID`: string, `startTime```: Fecha, addDelegator(username: Fecha, `addDelegator(username```: BN, `password`: string): *Promise‹string›*

*Definido en [src/apis/platformvm/api.ts:559](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/api.ts#L559)*

Añada un delegado a la Red Primaria.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `Nombre de usuario` | cadena de producción | El nombre de usuario del usuario de Keystore |
| `contraseña` | cadena de producción | La contraseña del usuario de Keystore |
| `nodeID` | cadena de producción | El ID del nodo del delegado |
| `startTime` | Fecha de la fecha de la fecha de la | Javascript Fecha objeto para cuando el delegado comienza a delegar |
| `endTime` | Fecha de la fecha de la fecha de la | Javascript Fecha objeto para cuando el delegado comienza a delegar |
| `Importe de la participación` | BN | La cantidad de nAVAX el delegado está fijando como [BN](https://github.com/indutny/bn.js/) |
| `rewardAddress` | cadena de producción | La dirección de la cuenta se envía al final Time la recompensa de la AVAX y la validación (si procede) |

**Returns:** *Promise‹string›*

Promete para una variedad de stakingIDs de validador.

___

### addSubnetValidator

- **addSubnetValidator(username: de usuario:**`` string, `contraseña`: string, `nodeID`: string, `subnetID`: Buffer | string, `startTime`: Fecha, `addSubnetValidator(username`: Fecha, `peso`: number): *Promise‹string›*

*Definido en [src/apis/platformvm/api.ts:517](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/api.ts#L517)*

Añada un validador a un subnet distinto de la Red Primaria. El validador debe validar la Red Primaria durante toda la duración que validen este Subnet.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `Nombre de usuario` | cadena de producción | El nombre de usuario del usuario de Keystore |
| `contraseña` | cadena de producción | La contraseña del usuario de Keystore |
| `nodeID` | cadena de producción | El ID del nodo del validador |
| `subnetID` | Buffer &#124; cadena | O bien un [Buffer](https://github.com/feross/buffer) o una cadena serializada cb58 para el SubnetID o su alias. |
| `startTime` | Fecha de la fecha de la fecha de la | Javascript Objeto de fecha para el comienzo de la hora de validar |
| `endTime` | Fecha de la fecha de la fecha de la | Javascript Objeto de fecha para el fin del tiempo para validar |
| `peso` | Número de números | Peso del validador utilizado para el muestreo |

**Returns:** *Promise‹string›*

Promesa para la transacción no firmada. Debe ser firmado (utilizando el signo) por el número adecuado de las claves de control del Subnet y por la clave de la cuenta que paga la cuota de transacción antes de que pueda ser expedida.

___

### addValidator

- **addValidator(username: de usuario:**`` string, `contraseña`: string, `nodeID`: string, `startTime```: Fecha, addValidator(username: Fecha, `addValidator(username`: BN, `password`: string, `password`: BN): *Promise‹string›*

*Definido en [src/apis/platformvm/api.ts:478](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/api.ts#L478)*

Añada un validador a la Red Primaria.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `Nombre de usuario` | cadena de producción | - | El nombre de usuario del usuario de Keystore |
| `contraseña` | cadena de producción | - | La contraseña del usuario de Keystore |
| `nodeID` | cadena de producción | - | El ID del nodo del validador |
| `startTime` | Fecha de la fecha de la fecha de la | - | Javascript Objeto de fecha para el comienzo de la hora de validar |
| `endTime` | Fecha de la fecha de la fecha de la | - | Javascript Objeto de fecha para el fin del tiempo para validar |
| `Importe de la participación` | BN | - | La cantidad de nAVAX el validador está fijando como [BN](https://github.com/indutny/bn.js/) |
| `rewardAddress` | cadena de producción | - | La dirección de la recompensa del validador se dirigirá, si hay una. |
| `delegationFeeRate de gastos` | BN | no definido. | Opcional. Un [BN](https://github.com/indutny/bn.js/) por el porcentaje de honorarios que este validador cobra cuando otros delegan en ellos la estaca. Hasta 4 lugares decimales permitidos lugares decimales adicionales son ignorados. Debe ser entre 0 y 100, inclusive. Por ejemplo, si la delegationFeeRate es 1.2345 y alguien delega en este validador, entonces cuando el período de delegación haya terminado, el 1.2345% de la recompensa va al validador y el resto va al delegador. |

**Returns:** *Promise‹string›*

Promete una cadena base58 de la transacción no firmada.

___

### addressFromBuffer

- **addressFromBuffer**`(address: (dirección`: Buffer): *string*

*Definido en [src/apis/platformvm/api.ts:134](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/api.ts#L134)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `Dirección de la dirección` | Buffer |

**Return:** *string*

___

### buildAddDelegatorTx

- **buildAddDelegatorTx(utxoset:**`` [UTXOSet](api_platformvm_utxos.utxoset.md): `buildAddDelegatorTx(utxoset```: string, `deDirecciones`: []string, buildAddDelegatorTx(utxoset: []string, `nodeID`: string, `startTime`: BN, `endTime`: BN, `buildAddDelegatorTx(utxoset`: BN, `buildAddDelegatorTx(utxoset`````: []string, buildAddDelegatorTx(utxoset: BN, buildAddDelegatorTx(utxoset: numero, `memo`: [PayloadBase](utils_payload.payloadbase.md) | []Buffer, `asOf`: BN): *Promise‹[UnsignedTx](api_platformvm_transactions.unsignedtx.md)›*

*Definido en [src/apis/platformvm/api.ts:1218](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/api.ts#L1218)*

Función de ayuda que crea un [AddDelegatorTx](api_platformvm_validationtx.adddelegatortx.md). Para un control más granular, usted puede crear su propio No [UnsignedTx](api_platformvm_transactions.unsignedtx.md) manualmente e importar la clase [AddDelegatorTx](api_platformvm_validationtx.adddelegatortx.md) directamente.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `utxoset` | [UTXOSet](api_platformvm_utxos.utxoset.md) | - | Un conjunto de UTXOS en el que se basa la transacción |
| `toAddresses` | cadena de producción[] | - | Una serie de direcciones como [Buffer](https://github.com/feross/buffer) que recibió las fichas estranguladas al final del período de grapado |
| `fromAddresses` | cadena de producción[] | - | Una serie de direcciones como [Buffer](https://github.com/feross/buffer) que posee los UTXOS de fijación de los honorarios en AVAX |
| `changeAddresses` | cadena de producción[] | - | Una serie de direcciones como [Buffer](https://github.com/feross/buffer) que obtiene el cambio sobrante del pago de honorarios |
| `nodeID` | cadena de producción | - | El ID del nodo del validador que se añade. |
| `startTime` | BN | - | El tiempo Unix cuando el validador comienza a validar la Red Primaria. |
| `endTime` | BN | - | El tiempo Unix cuando el validador deja de validar la Red Primaria (y se devuelve AVAX almacenado). |
| `Importe de la participación` | BN | - | El importe que se delega como [BN](https://github.com/indutny/bn.js/) |
| `recompensas Direcciones` | cadena de producción[] | - | Las direcciones que obtendrán las recompensas de la hoguera delegada. |
| `rewardLocktime de bloqueo` | BN | nuevo BN(0) | Opcional. El campo de bloqueo creado en las salidas de recompensa resultantes |
| `rewardThreshold` | Número de números | 1 1 | Opional. El número de firmas necesarias para gastar los fondos en la recompensa resultante UTXO. Predeterminado 1. |
| `meme` | [PayloadBase](utils_payload.payloadbase.md) &#124; Buffer | no definido. | Opcional contiene bytes arbitrarios, hasta 256 bytes |
| `as.` | BN | UnixNow() | Opcional. La marca de tiempo para verificar la transacción contra un [BN](https://github.com/indutny/bn.js/) |

**Returns:** *Promise‹[UnsignedTx](api_platformvm_transactions.unsignedtx.md)›*

Una transacción no firmada creada a partir de los parámetros pasados.

___

### buildAddValidatorTx

- **buildAddValidatorTx(utxoset:**`` [UTXOSet](api_platformvm_utxos.utxoset.md), `toAddresses```: string, `deDirecciones`: []string, buildAddValidatorTx(utxoset: []string, `nodeID`: string, `startTime`: BN, `endTime`: BN, `buildAddValidatorTx(utxoset`: BN, `buildAddValidatorTx(utxoset```: []string, `buildAddValidatorTx(utxoset`: número, buildAddValidatorTx(utxoset: BN, `buildAddValidatorTx(utxoset`: número, `memo`: [PayloadBase](utils_payload.payloadbase.md) | []Buffer, `comode`: BN): *Promise‹[UnsignedTx](api_platformvm_transactions.unsignedtx.md)›*

*Definido en [src/apis/platformvm/api.ts:1302](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/api.ts#L1302)*

Función de ayuda que crea un [AddValidatorTx](api_platformvm_validationtx.addvalidatortx.md). Para un control más granular, usted puede crear su propio [UnsignedTx](api_platformvm_transactions.unsignedtx.md) manualmente e importar la clase [AddValidatorTx](api_platformvm_validationtx.addvalidatortx.md) directamente.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `utxoset` | [UTXOSet](api_platformvm_utxos.utxoset.md) | - | Un conjunto de UTXOS en el que se basa la transacción |
| `toAddresses` | cadena de producción[] | - | Una serie de direcciones como [Buffer](https://github.com/feross/buffer) que recibió las fichas estranguladas al final del período de grapado |
| `fromAddresses` | cadena de producción[] | - | Una serie de direcciones como [Buffer](https://github.com/feross/buffer) que posee los UTXOS de fijación de los honorarios en AVAX |
| `changeAddresses` | cadena de producción[] | - | Una serie de direcciones como [Buffer](https://github.com/feross/buffer) que obtiene el cambio sobrante del pago de honorarios |
| `nodeID` | cadena de producción | - | El ID del nodo del validador que se añade. |
| `startTime` | BN | - | El tiempo Unix cuando el validador comienza a validar la Red Primaria. |
| `endTime` | BN | - | El tiempo Unix cuando el validador deja de validar la Red Primaria (y se devuelve AVAX almacenado). |
| `Importe de la participación` | BN | - | El importe que se delega como [BN](https://github.com/indutny/bn.js/) |
| `recompensas Direcciones` | cadena de producción[] | - | Las direcciones que obtendrán las recompensas de la hoguera delegada. |
| `DelegationFee` | Número de números | - | Un número para el porcentaje de recompensa que se le dará al validador cuando alguien se delega en ellos. Debe estar entre 0 y 100. |
| `rewardLocktime de bloqueo` | BN | nuevo BN(0) | Opcional. El campo de bloqueo creado en las salidas de recompensa resultantes |
| `rewardThreshold` | Número de números | 1 1 | Opional. El número de firmas necesarias para gastar los fondos en la recompensa resultante UTXO. Predeterminado 1. |
| `meme` | [PayloadBase](utils_payload.payloadbase.md) &#124; Buffer | no definido. | Opcional contiene bytes arbitrarios, hasta 256 bytes |
| `as.` | BN | UnixNow() | Opcional. La marca de tiempo para verificar la transacción contra un [BN](https://github.com/indutny/bn.js/) |

**Returns:** *Promise‹[UnsignedTx](api_platformvm_transactions.unsignedtx.md)›*

Una transacción no firmada creada a partir de los parámetros pasados.

___

### buildCreateSubnetTx

[]- **buildCreateSubnetTx(utxoset:**`` [UTXOSet](api_platformvm_utxos.utxoset.md), `buildCreateSubnetTx(utxoset```: string, `buildCreateSubnetTx(utxoset`: string, buildCreateSubnetTx(utxoset: []string, `subnetOwnerThreshold`: número, `buildCreateSubnetTx(utxoset`: [PayloadBase](utils_payload.payloadbase.md) | []Buffer, `asOf`: BN): *Promise‹[UnsignedTx](api_platformvm_transactions.unsignedtx.md)›*

*Definido en [src/apis/platformvm/api.ts:1383](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/api.ts#L1383)*

Clase que representa una transacción de [CreateSubnetTx](api_platformvm_createsubnettx.createsubnettx.md) sin firmar.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `utxoset` | [UTXOSet](api_platformvm_utxos.utxoset.md) | - | Un conjunto de UTXOS en el que se basa la transacción |
| `fromAddresses` | cadena de producción[] | - | Las direcciones que se utilizan para enviar los fondos del [Buffer](https://github.com/feross/buffer) UTXOS |
| `changeAddresses` | cadena de producción[] | - | Las direcciones que pueden gastar el cambio restante de UTXOs gastado |
| `subnetOwnerAddresses Direcciones` | cadena de producción[] | - | Una serie de direcciones para los propietarios de la nueva subred |
| `subnetOwnerThreshold` | Número de números | - | Número que indica el importe de las firmas necesarias para añadir validadores a un subnet |
| `meme` | [PayloadBase](utils_payload.payloadbase.md) &#124; Buffer | no definido. | Opcional contiene bytes arbitrarios, hasta 256 bytes |
| `as.` | BN | UnixNow() | Opcional. La marca de tiempo para verificar la transacción contra un [BN](https://github.com/indutny/bn.js/) |

**Returns:** *Promise‹[UnsignedTx](api_platformvm_transactions.unsignedtx.md)›*

Una transacción no firmada creada a partir de los parámetros pasados.

___

### buildExportTx

- **buildExportTx(utxoset:**`` [UTXOSet](api_platformvm_utxos.utxoset.md), `monto`: BN, `buildExportTx(utxoset`: Buffer | string, `buildExportTx(utxoset`: []string, `deDirecciones`: string, `buildExportTx(utxoset`: [][]string, `memo`: [PayloadBase](utils_payload.payloadbase.md) | Buffer, `comode`: BN, `locktime`: BN, `umbral`: número): *Promise‹[UnsignedTx](api_platformvm_transactions.unsignedtx.md)›*

*Definido en [src/apis/platformvm/api.ts:1061](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/api.ts#L1061)*

Función de ayuda que crea una Export Tx sin firmar. Para un control más granular, usted puede crear su propio [Sin firmar Tx](api_platformvm_transactions.unsignedtx.md) manualmente (con sus correspondientes [Entradas,](api_platformvm_inputs.transferableinput.md) [Productos Transferibles](api_platformvm_outputs.transferableoutput.md) y [[TransferOperation]]s).

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `utxoset` | [UTXOSet](api_platformvm_utxos.utxoset.md) | - | Un conjunto de UTXOS en el que se basa la transacción |
| `importe de la cantidad de dinero` | BN | - | La cantidad que se exportará como [BN](https://github.com/indutny/bn.js/) |
| `destinationChain de destino` | Buffer &#124; cadena | - | El chainid para donde se enviarán los activos. |
| `toAddresses` | cadena de producción[] | - | Las direcciones para enviar los fondos |
| `fromAddresses` | cadena de producción[] | - | Las direcciones que se utilizan para enviar los fondos de UTXOs proporcionadas |
| `changeAddresses` | cadena de producción[] | no definido. | Las direcciones que pueden gastar el cambio restante de UTXOs gastado |
| `meme` | [PayloadBase](utils_payload.payloadbase.md) &#124; Buffer | no definido. | Opcional contiene bytes arbitrarios, hasta 256 bytes |
| `as.` | BN | UnixNow() | Opcional. La marca de tiempo para verificar la transacción contra un [BN](https://github.com/indutny/bn.js/) |
| `Tiempo de bloqueo` | BN | nuevo BN(0) | Opcional. El campo de bloqueo creado en las salidas resultantes |
| `umbral` | Número de números | 1 1 | Opcional. El número de firmas necesarias para gastar los fondos en la UTXO resultante |

**Returns:** *Promise‹[UnsignedTx](api_platformvm_transactions.unsignedtx.md)›*

Una transacción no firmada ([UnsignedTx](api_platformvm_transactions.unsignedtx.md)) que contiene una [ExportTx](api_platformvm_exporttx.exporttx.md).

___

### buildImportTx

[][]- **buildImportTx**(`utxoset`: [UTXOSet](api_platformvm_utxos.utxoset.md), `ownerAddresses```: string, `sourceChain`: Buffer | string, `ownerAddresses`: string, `deDirecciones`: string, ownerAddresses: []string, `memo`: [PayloadBase](utils_payload.payloadbase.md) | Buffer, `comoDe`: BN, `locktime`: []BN, `umbral`: número): *Promise‹[UnsignedTx](api_platformvm_transactions.unsignedtx.md)›*

*Definido en [src/apis/platformvm/api.ts:987](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/api.ts#L987)*

Función de ayuda que crea un Tx de importación sin firmar. Para un control más granular, usted puede crear su propio [Sin firmar Tx](api_platformvm_transactions.unsignedtx.md) manualmente (con sus correspondientes [Entradas,](api_platformvm_inputs.transferableinput.md) [Productos Transferibles](api_platformvm_outputs.transferableoutput.md) y [[TransferOperation]]s).

**`observaciones sobre las observaciones formuladas`** Este ayudante existe porque la API de endpoint debe ser el punto principal de entrada para la mayoría de la funcionalidad.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `utxoset` | [UTXOSet](api_platformvm_utxos.utxoset.md) | - | Un conjunto de UTXOS en el que se basa la transacción |
| `ownerAddresses` | cadena de producción[] | - | Las direcciones que se utilizan para importar |
| `sourceChain` | Buffer &#124; cadena | - | El chainid para donde viene la importación. |
| `toAddresses` | cadena de producción[] | - | Las direcciones para enviar los fondos |
| `fromAddresses` | cadena de producción[] | - | Las direcciones que se utilizan para enviar los fondos de UTXOs proporcionadas |
| `changeAddresses` | cadena de producción[] | no definido. | Las direcciones que pueden gastar el cambio restante de UTXOs gastado |
| `meme` | [PayloadBase](utils_payload.payloadbase.md) &#124; Buffer | no definido. | Opcional contiene bytes arbitrarios, hasta 256 bytes |
| `as.` | BN | UnixNow() | Opcional. La marca de tiempo para verificar la transacción contra un [BN](https://github.com/indutny/bn.js/) |
| `Tiempo de bloqueo` | BN | nuevo BN(0) | Opcional. El campo de bloqueo creado en las salidas resultantes |
| `umbral` | Número de números | 1 1 | Opcional. El número de firmas necesarias para gastar los fondos en la UTXO resultante |

**Returns:** *Promise‹[UnsignedTx](api_platformvm_transactions.unsignedtx.md)›*

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

### checkGooseEgg

- **checkGooseEgg**(`utx`: [UnsignedTx](api_platformvm_transactions.unsignedtx.md), `outTotal`: BN): *Promise‹boolean›*

*Definido en [src/apis/platformvm/api.ts:261](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/api.ts#L261)*

Función de ayuda que determina si una tx es una transacción de huevo de ganso.

**`observaciones sobre las observaciones formuladas`** Una "Transacción de huevo de ganso" es cuando la cuota supera con creces una cantidad razonable

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `utt` | [Sin UnsignedTx](api_platformvm_transactions.unsignedtx.md) | - | Un Tx Sin Firmar. |
| `outTotal` | BN | nuevo BN(0) | - |

**Returns:** *Promise‹boolean›*

booleano verdadero si pasa la prueba de huevo de ganso y falso si falla.

___

### createAddress

- **createAddress**(`username`: de usuario: string: `contraseña`: string): *Promise‹string›*

*Definido en [src/apis/platformvm/api.ts:345](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/api.ts#L345)*

Crear una dirección en la tienda de llaves del nodo.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `Nombre de usuario` | cadena de producción | El nombre de usuario del usuario de Keystore que controla la nueva cuenta |
| `contraseña` | cadena de producción | La contraseña del usuario de Keystore que controla la nueva cuenta |

**Returns:** *Promise‹string›*

Promete una cadena de la dirección de cuenta recientemente creada.

___

### createBlockchain

- **createBlockchain**(`username`: de usuario: string, `contraseña`: string, `subnetID`: Buffer | string, `vmID`: string, `fxIDs`: []number, `name`: string, `génesis`: string): *Promise‹string›*

*Definido en [src/apis/platformvm/api.ts:295](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/api.ts#L295)*

Crea un nuevo blockchain.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `Nombre de usuario` | cadena de producción | - | El nombre de usuario del usuario de Keystore que controla la nueva cuenta |
| `contraseña` | cadena de producción | - | La contraseña del usuario de Keystore que controla la nueva cuenta |
| `subnetID` | Buffer &#124; cadena | no definido. | Opcional. O bien un [Buffer](https://github.com/feross/buffer) o una cadena serializada cb58 para el SubnetID o su alias. |
| `vmID` | cadena de producción | - | El ID de la Máquina Virtual se ejecuta el blockchain. También puede ser un alias de la Máquina Virtual. |
| `fxIDs` | Número de números[] | - | - |
| `Nombre del nombre` | cadena de producción | - | Un nombre legible por el hombre para el nuevo blockchain |
| `génesis` | cadena de producción | - | La base 58 (con suma de checksum) representación del estado de génesis del nuevo blockchain. Las máquinas virtuales deben tener un método de API estático llamado buildGenesis que puede ser utilizado para generar genesisData. |

**Returns:** *Promise‹string›*

Promete que la transacción no firmada cree este blockchain. Debe ser firmado por un número suficiente de las teclas de control del Subnet y por la cuenta que paga la cuota de transacción.

___

### createSubnet

[]- **createSubnet**(`username`: de usuario: string, `contraseña`: string, `controlKeys`: string, `umbral`: number): *Promise‹string›*

*Definido en [src/apis/platformvm/api.ts:593](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/api.ts#L593)*

Crear una transacción sin firmar para crear un nuevo Subnet. La transacción no firmada debe ser firmado con la clave de la cuenta pagando la cuota de transacción. El ID de Subnet es el ID de la transacción que la crea (es decir, la respuesta de issueTx al emitir la transacción firmada).

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `Nombre de usuario` | cadena de producción | El nombre de usuario del usuario de Keystore |
| `contraseña` | cadena de producción | La contraseña del usuario de Keystore |
| `controlKeys` | cadena de producción[] | Conjunto de direcciones de plataforma como cadenas |
| `umbral` | Número de números | Para añadir un validador a este Subnet, una transacción debe tener firmas de umbral, donde cada firma proviene de una clave cuya dirección es un elemento de `controlKeys` |

**Returns:** *Promise‹string›*

Promete una cadena con la operación sin firmar codificada como base58.

___

### exportAVAX

- **exportAVAX**(`username`: de usuario: string, `contraseña`: string, `monto`: BN, `a`: string): *Promise‹string›*

*Definido en [src/apis/platformvm/api.ts:671](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/api.ts#L671)*

Enviar AVAX desde una cuenta en la cadena P a una dirección en la cadena X. Esta transacción deberá firmar con la clave de la cuenta de la que se envía el AVAX y que paga el honorarios de transacción. Después de emitir esta transacción, debe llamar la importación de la cadena X-Chain’s método para completar la transferencia.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `Nombre de usuario` | cadena de producción | El usuario de `Keystore` que controla la cuenta especificada en |
| `contraseña` | cadena de producción | La contraseña del usuario de Keystore |
| `importe de la cantidad de dinero` | BN | Cantidad de AVAX para exportar como [BN](https://github.com/indutny/bn.js/) |
| `a la hora de que se le dé a la` | cadena de producción | La dirección de la cadena X para enviar el AVAX a. No incluya X- en la dirección |

**Returns:** *Promise‹string›*

Promesa de que una transacción no firmada sea firmada por la cuenta que el AVAX es enviado desde y paga la cuota de transacción.

___

### exportKey

- **exportKey**(`username`: de usuario: string, `contraseña`: string, `dirección`: string): *Promise‹string›*

*Definido en [src/apis/platformvm/api.ts:839](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/api.ts#L839)*

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

*Definido en [src/apis/platformvm/api.ts:147](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/api.ts#L147)*

Toma el AVAX AssetID y lo devuelve en una Promesa.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `refrescarse` | booleano | falso | Esta función encauza la respuesta. Refresh = true will el caché. |

**Returns:** *Promise‹Buffer›* ›

La cadena proporcionada que representa el AVAX AssetID

___

### getBalance

- **getBalance**(`address`: string): *Promise‹object›*

*Definido en [src/apis/platformvm/api.ts:365](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/api.ts#L365)*

Obtiene el equilibrio de un activo en particular.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `Dirección de la dirección` | cadena de producción | La dirección para sacar el saldo de activos de |

**Returns:** *Promise‹object›*

Promete con el equilibrio como [BN](https://github.com/indutny/bn.js/) en la dirección proporcionada.

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

*Definido en [src/apis/platformvm/api.ts:71](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/api.ts#L71)*

Obtiene el alias para el blockchainID si existe, de lo contrario devuelve `indefinido`.

**Return:** *string*

El alias para el blockchainID

___

### getBlockchainID

- **getBlockchainID**(): *string*

*Definido en [src/apis/platformvm/api.ts:102](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/api.ts#L102)*

Obtiene el blockchainID y lo devuelve

**Return:** *string*

El blockchainID

___

### getBlockchainstatus

- **getBlockchainStatus**(`blockchainID`: string): *Promise‹string›*

*Definido en [src/apis/platformvm/api.ts:329](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/api.ts#L329)*

Obtiene el estado de un blockchain.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `blockchainID` | cadena de producción | El blockchainID solicitando una actualización de estado |

**Returns:** *Promise‹string›*

Promesa para una cadena de uno de: "Validating", "Creado", "Preferred", "Unknown".

___

### getBlockchains

- **getBlockchains**(): *[]Promise‹object›*

*Definido en [src/apis/platformvm/api.ts:652](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/api.ts#L652)*

Obtén todas las cadenas de bloqueo que existen (excluyendo la cadena P).

**Returns:** *Promise‹object[]›*

Promete una serie de objetos que contienen campos "id", "subnetID" y "vmID".

___

### getCreationTxFee

- **getCreationTxFee**(): *BN*

*Definido en [src/apis/platformvm/api.ts:214](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/api.ts#L214)*

Obtiene la cuota de creación por esta cadena.

**Returns:** *BN*

La cuota de creación como [BN](https://github.com/indutny/bn.js/)

___

### getCurrentSupply

- **getCurrentSupply**(): *Promise‹BN›*

*Definido en [src/apis/platformvm/api.ts:740](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/api.ts#L740)*

Devuelve una parte superior en la cantidad de fichas que existen. No aumenta monotónicamente porque este número puede descender si se niega la recompensa de un staker.

**Returns:** *Promise‹BN›*

___

### getCurrentValidators

- **getCurrentValidators**(`subnetID`: Buffer | string): *Promise‹object›*

*Definido en [src/apis/platformvm/api.ts:403](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/api.ts#L403)*

Listas el conjunto de validadores actuales.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `subnetID` | Buffer &#124; cadena | no definido. | Opcional. O bien un [Buffer](https://github.com/feross/buffer) o una cadena serializada cb58 para el SubnetID o su alias. |

**Returns:** *Promise‹object›*

Promete para una variedad de validadores que actualmente están estancando, ver: [platform.getCurrentValidators documentación](https://docs.avax.network/v1.0/en/api/platform/#platformgetcurrentvalidators).

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

*Definido en [src/apis/platformvm/api.ts:205](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/api.ts#L205)*

Obtiene la cuota de creación por defecto para esta cadena.

**Returns:** *BN*

La cuota de creación por defecto como [BN](https://github.com/indutny/bn.js/)

___

### getDefaultTxFee

- **getDefaultTxFee**(): *BN*

*Definido en [src/apis/platformvm/api.ts:174](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/api.ts#L174)*

Obtiene la cuota tx predeterminada para esta cadena.

**Returns:** *BN*

La tasa tx predeterminada como [BN](https://github.com/indutny/bn.js/)

___

### getHeight

- **getHeight**(): *Promise‹BN›*

*Definido en [src/apis/platformvm/api.ts:748](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/api.ts#L748)*

Devuelve la altura de la cadena de plataforma.

**Returns:** *Promise‹BN›*

___

### getMinStake

- **getMinStake**(`refresh`: boolean): *Promise‹object›*

*Definido en [src/apis/platformvm/api.ts:758](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/api.ts#L758)*

Obtiene la cantidad mínima de grapado.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `refrescarse` | booleano | falso | Un booleano para evitar el valor local caché de la cantidad mínima de toma que se encuentre, en su lugar, el nodo en el lugar. |

**Returns:** *Promise‹object›*

___

### getPendingValidators

- **getPendingValidators**(`subnetID`: Buffer | string): *Promise‹object›*

*Definido en [src/apis/platformvm/api.ts:423](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/api.ts#L423)*

Listas el conjunto de validadores pendientes.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `subnetID` | Buffer &#124; cadena | no definido. | Opcional. O bien un [Buffer](https://github.com/feross/buffer) o una cadena serializada cb58 para el SubnetID o su alias. |

**Returns:** *Promise‹object›*

Promete para una serie de validadores que están pendientes de almacenamiento, ver: [platform.getPendingValidators documentación](https://docs.avax.network/v1.0/en/api/platform/#platformgetpendingvalidators).

___

### getRPCID

- **getRPCID**(): *número*

*Heredada de [JRPCAPI](common_jrpcapi.jrpcapi.md).[getRPCID](common_jrpcapi.jrpcapi.md#getrpcid)*

*Definido en [src/comm/jrpcapi.ts:69](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/jrpcapi.ts#L69)*

Devuelve el rpcid, un número de aumento estricto, a partir de 1, indicando el siguiente solicitar identificación que se enviará.

**Retornos:** *número*

___

### getRewardUTXOS

▸ string, **getRewardUTXOs**`(txID```: string): *Promise‹[GetRewardUTXOsResponse](../interfaces/common_interfaces.getrewardutxosresponse.md)›*

*Definido en [src/apis/platformvm/api.ts:1469](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/api.ts#L1469)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `txID` | cadena de producción |
| `¿codificar?` | cadena de producción |

**Returns:** *Promise‹[GetRewardUTXOsResponse](../interfaces/common_interfaces.getrewardutxosresponse.md)›*

las UTXOs que fueron recompensadas después de que terminara el período de fijación o delegación de la transacción proporcionada.

___

### getStake

- **getStake**(`addresses`: []string, `codificación`: string): *Promise‹[GetStakeResponse](../interfaces/common_interfaces.getstakeresponse.md)›*

*Definido en [src/apis/platformvm/api.ts:791](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/api.ts#L791)*

Obtiene la cantidad total almacenada para una serie de direcciones.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `direcciones` | cadena de producción[] | - |
| `codificación` | cadena de producción | "cb58" |

**Returns:** *Promise‹[GetStakeResponse](../interfaces/common_interfaces.getstakeresponse.md)›*

___

### getStakingAssetID Asset

- **getStakingAssetID**(): *Promise‹string›*

*Definido en [src/apis/platformvm/api.ts:277](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/api.ts#L277)*

Recupera un asset de enganche para un conjunto de assset de grapado.

**Returns:** *Promise‹string›*

Devuelve una promesa<string>con valor codificado cb58 del activo ID.

___

### getSubnets

- **getSubnets**(`ids`: []string): *[]Promise‹object›*

*Definido en [src/apis/platformvm/api.ts:821](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/api.ts#L821)*

Consigue todas las subredes que existen.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `IDS` | cadena de producción[] | no definido. | Identificadores de las subredes para recuperar información sobre. Si se omitida, obtiene todas las subredes |

**Returns:** *Promise‹object[]›*

Promete para una serie de objetos que contienen campos "id", «controlKeys» y «umbral».

___

### getTx

- **getTx**(`txid`: string): *Promise‹string›*

*Definido en [src/apis/platformvm/api.ts:875](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/api.ts#L875)*

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

*Definido en [src/apis/platformvm/api.ts:183](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/api.ts#L183)*

Obtiene la cuota de tx por esta cadena.

**Returns:** *BN*

La tasa tx como [BN](https://github.com/indutny/bn.js/)

___

### getTxStatus

- **getTxStatus(txid:**`` string: `stard,` getTxStatus(txid: boolean): *Promise‹string | objeto›*

*Definido en [src/apis/platformvm/api.ts:891](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/api.ts#L891)*

Devuelve el estado de un ID de transacción proporcionado llamando al método `getTxStatus` del nodo.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `txid` | cadena de producción | - | La representación de cadena del ID de transacción |
| `incluir la razón por la que` | booleano | Verdadero | Devuelve la razón por la que se ha abandonado tx, si procede. Defaults a verdad |

**Returns:** *Promise‹string | objeto›*

Devuelve una promesa<string>que contenga el estado recuperado del nodo y la razón por la que se ha abandonado un tx, si procede.

___

### getUTXOs

- **getUTXOs(addresses:**`` string []| string, `sourceChain`: string, `limit`: número, `startIndex`: objeto, `getUTXOs(addresses`: [getUTXOs(addresses:](utils_persistanceoptions.persistanceoptions.md) *Promise‹object›*

*Definido en [src/apis/platformvm/api.ts:915](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/api.ts#L915)*

Recupera las UTXOs relacionadas con las direcciones proporcionadas del método `getUTXOS` del nodo.

**`observaciones sobre las observaciones formuladas`** persistOpts es opcional y debe ser de tipo [PersistanceOptions](utils_persistanceoptions.persistanceoptions.md)

**Parámetros:**

• **direcciones**: *cadena []| string*

Una serie de direcciones como cadenas o direcciones cb58 como [Buffer](https://github.com/feross/buffer)s

• **Fuente** `de valor` ▪Default s*tring=* undefined

Una cadena para que la cadena busque las UTXO"s. El predeterminado es utilizar esta cadena, pero si existen UTXOs exportados de otras cadenas, esto puede utilizarse para tirarlos en su lugar.

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

### importAVAX

- **importAVAX**(`username`: de `usuario`: string, `contraseña`: string, `sourceChain`: string): *Promise‹string›*

*Definido en [src/apis/platformvm/api.ts:697](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/api.ts#L697)*

Enviar AVAX desde una cuenta en la cadena P a una dirección en la cadena X. Esta transacción deberá firmar con la clave de la cuenta de la que se envía el AVAX y que paga la cuota de transacción. Después de emitir esta transacción, debe llamar a la X-Chain’s importAVAX método para completar la transferencia.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `Nombre de usuario` | cadena de producción | El usuario de `Keystore` que controla la cuenta especificada en |
| `contraseña` | cadena de producción | La contraseña del usuario de Keystore |
| `a la hora de que se le dé a la` | cadena de producción | El ID de la cuenta a la que se envía AVAX. Esto debe ser lo mismo que el argumento de la llamada correspondiente a la exportación exportAVAX de la cadena X. |
| `sourceChain` | cadena de producción | El chainID de donde vienen los fondos. |

**Returns:** *Promise‹string›*

Promesa para una cadena de transacción, que debe enviarse a la red llamando a issueTx.

___

### importKey

- **importKey**(`username`: de usuario: string, `contraseña`: string, `privateKey`: string): *Promise‹string›*

*Definido en [src/apis/platformvm/api.ts:858](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/api.ts#L858)*

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

- **issueTx**(`tx`: string | Buffer | [Tx):](api_platformvm_transactions.tx.md) *Promise‹string›*

*Definido en [src/apis/platformvm/api.ts:716](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/api.ts#L716)*

Llama el método issueTx del nodo desde la API y devuelve el ID de transacción resultante como una cadena.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `txx` | string &#124; Buffer &#124; [Tx](api_platformvm_transactions.tx.md) | Una cadena, [Buffer](https://github.com/feross/buffer) o [Tx](api_platformvm_transactions.tx.md) que representa una transacción |

**Returns:** *Promise‹string›*

Una promesa<string>representando el ID de transacción de la transacción publicada.

___

### keyChain

- **keyChain**(): *[KeyChain](api_platformvm_keychain.keychain.md)*

*Definido en [src/apis/platformvm/api.ts:235](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/api.ts#L235)*

Obtiene una referencia al llavero para esta clase.

**Retornos:** *[KeyChain](api_platformvm_keychain.keychain.md)*

La instancia de [][] para esta clase

___

### listAddresses

- **listAddresses**(`username`: de `usuario`: string: string): *[]Promise‹string›*

*Definido en [src/apis/platformvm/api.ts:385](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/api.ts#L385)*

Lista, las direcciones controladas por el usuario.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `Nombre de usuario` | cadena de producción | El nombre de usuario del usuario de Keystore |
| `contraseña` | cadena de producción | La contraseña del usuario de Keystore |

**Returns:** *Promise‹string[]›*

Promete una serie de direcciones.

___

### parseAddress

- **parseAddress**(`addr`: string): *Buffer*

*Definido en [src/apis/platformvm/api.ts:128](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/api.ts#L128)*

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

*Definido en [src/apis/platformvm/api.ts:111](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/api.ts#L111)*

Refrescar blockchainID, y si se pasa un blockchainID dentro, utilice eso.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `blockchainID` | cadena de producción | no definido. |

**Return:** *booleano*

El blockchainID

___

### sampleValidators

- **sampleValidators**(`sampleSize`: número, `subnetID`: Buffer | string): *[]Promise‹string›*

*Definido en [src/apis/platformvm/api.ts:444](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/api.ts#L444)*

Muestras `Validadores de tamaño` del conjunto actual de validadores.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `sampleSize` | Número de números | - | Del universo total de validadores, seleccione estos muchos al azar |
| `subnetID` | Buffer &#124; cadena | no definido. | Opcional. O bien un [Buffer](https://github.com/feross/buffer) o una cadena serializada cb58 para el SubnetID o su alias. |

**Returns:** *Promise‹string[]›*

Promete para una variedad de stakingIDs de validador.

___

### setAVAXAssetID

- **setAVAXAssetID**(`avaxAssetID`: string | Buffer): *nul*

*Definido en [src/apis/platformvm/api.ts:162](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/api.ts#L162)*

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

*Definido en [src/apis/platformvm/api.ts:91](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/api.ts#L91)*

Establece el alias para el blockchainID.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `alias` | cadena de producción | Los alias para el blockchainID. |

**Return:** *string*

___

### setCreationTxFee

- **setCreationTxFee**(`fee`: BN): *void*

*Definido en [src/apis/platformvm/api.ts:226](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/api.ts#L226)*

Establece la cuota de creación para esta cadena.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `Cuota de pago` | BN | El importe de la cuota de creación para establecer como [BN](https://github.com/indutny/bn.js/) |

**Retornos:** *vacío*

___

### setMinStake

- **setMinstake(minValidatorStake:**`` BN, `minDelegatorStake`: BN): *nul*

*Definido en [src/apis/platformvm/api.ts:779](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/api.ts#L779)*

Establece la estaca mínima en esta clase.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `minValidatorStake` | BN | no definido. | Un [BN](https://github.com/indutny/bn.js/) para establecer la cantidad mínima de participación almacenada en esta clase. |
| `minDelegatorStake` | BN | no definido. | Un [BN](https://github.com/indutny/bn.js/) para establecer el importe mínimo de delegación almacenada en esta clase. |

**Retornos:** *vacío*

___

### setTxFee

- **setTxFee**(`fee`: BN): *nul*

*Definido en [src/apis/platformvm/api.ts:195](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/api.ts#L195)*

Establece la cuota tx por esta cadena.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `Cuota de pago` | BN | El importe de la tasa tx para establecer como [BN](https://github.com/indutny/bn.js/) |

**Retornos:** *vacío*

___

### validado por

- **validatedBy**(`blockchainID`: string): *Promise‹string›*

*Definido en [src/apis/platformvm/api.ts:618](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/api.ts#L618)*

Consigue el Subred que valida un blockchain determinado.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `blockchainID` | cadena de producción | O bien un [Buffer](https://github.com/feross/buffer) o una cadena codificada cb58 para el blockchainID o su alias. |

**Returns:** *Promise‹string›*

Promete una cadena de la subnetID que valida la cadena de bloqueo.

___

### validar

- **validates**(`subnetID`: Buffer | string): *[]Promise‹string›*

*Definido en [src/apis/platformvm/api.ts:634](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/api.ts#L634)*

Consigue las ID de las cadenas de bloqueo que un Subnet valida

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `subnetID` | Buffer &#124; cadena | O bien un [Buffer](https://github.com/feross/buffer) o una cadena serializada AVAX para el SubnetID o su alias. |

**Returns:** *Promise‹string[]›*

Promete para una serie de blockchainIDs que el subnet valida .
