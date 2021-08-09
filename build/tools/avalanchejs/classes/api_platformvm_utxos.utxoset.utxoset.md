[avalancha](../README.md) › [API-PlatformVM-UTXOS](../modules/api_platformvm_utxos.md) › [UTXOSet](api_platformvm_utxos.utxoset.md)

# Clase: UTXOSet

Clase que representa un conjunto de [UTXO](api_platformvm_utxos.utxo.md)s.

## Jerarquía

[m. StandardUTXOSet‹UTXO](api_platformvm_utxos.utxo.md)[](common_utxos.standardutxoset.md)›

de **UTXOSet**

## Índice de participación

### Propiedades de las propiedades

* [_codecid](api_platformvm_utxos.utxoset.md#protected-_codecid)
* [_typeID](api_platformvm_utxos.utxoset.md#protected-_typeid)
* [_typeName](api_platformvm_utxos.utxoset.md#protected-_typename)
* [dirección addressUTXOs](api_platformvm_utxos.utxoset.md#protected-addressutxos)
* [utxos](api_platformvm_utxos.utxoset.md#protected-utxos)

### Métodos de trabajo

* [_feeCheck](api_platformvm_utxos.utxoset.md#_feecheck)
* [añadir a la lista de las partes](api_platformvm_utxos.utxoset.md#add)
* [addArray](api_platformvm_utxos.utxoset.md#addarray)
* [buildAddDelegatorTx](api_platformvm_utxos.utxoset.md#buildadddelegatortx)
* [buildAddValidatorTx](api_platformvm_utxos.utxoset.md#buildaddvalidatortx)
* [buildBaseTx](api_platformvm_utxos.utxoset.md#buildbasetx)
* [buildCreateSubnetTx](api_platformvm_utxos.utxoset.md#buildcreatesubnettx)
* [buildExportTx](api_platformvm_utxos.utxoset.md#buildexporttx)
* [buildImportTx](api_platformvm_utxos.utxoset.md#buildimporttx)
* [clon](api_platformvm_utxos.utxoset.md#clone)
* [crear un entorno de creación](api_platformvm_utxos.utxoset.md#create)
* [deserie](api_platformvm_utxos.utxoset.md#deserialize)
* [diferencia entre la diferencia entre la diferencia y la diferencia entre la diferencia](api_platformvm_utxos.utxoset.md#difference)
* [filtro de filtro](api_platformvm_utxos.utxoset.md#filter)
* [getAddresses](api_platformvm_utxos.utxoset.md#getaddresses)
* [getAllUTXOStrings](api_platformvm_utxos.utxoset.md#getallutxostrings)
* [getAllUTXOs](api_platformvm_utxos.utxoset.md#getallutxos)
* [getAssetIDs](api_platformvm_utxos.utxoset.md#getassetids)
* [getBalance](api_platformvm_utxos.utxoset.md#getbalance)
* [getCodecid](api_platformvm_utxos.utxoset.md#getcodecid)
* [getConsumableUXTO](api_platformvm_utxos.utxoset.md#getconsumableuxto)
* [getMinimumSpendable](api_platformvm_utxos.utxoset.md#getminimumspendable)
* [getTypeID](api_platformvm_utxos.utxoset.md#gettypeid)
* [getTypeName](api_platformvm_utxos.utxoset.md#gettypename)
* [getutXO](api_platformvm_utxos.utxoset.md#getutxo)
* [getUTXOIDs](api_platformvm_utxos.utxoset.md#getutxoids)
* [incluye las siguientes](api_platformvm_utxos.utxoset.md#includes)
* [intersección](api_platformvm_utxos.utxoset.md#intersection)
* [fusión](api_platformvm_utxos.utxoset.md#merge)
* [mergeByRule](api_platformvm_utxos.utxoset.md#mergebyrule)
* [parseUTXO](api_platformvm_utxos.utxoset.md#parseutxo)
* [eliminar las emisiones de gases](api_platformvm_utxos.utxoset.md#remove)
* [removeArray](api_platformvm_utxos.utxoset.md#removearray)
* [serializar](api_platformvm_utxos.utxoset.md#serialize)
* [simular Diferencia](api_platformvm_utxos.utxoset.md#symdifference)
* [Unión Europea](api_platformvm_utxos.utxoset.md#union)

## Propiedades de las propiedades

### _codecid `protegido`

• **_codecid**: *número* = indefinido.

*Heredada de [SigIdx](common_signature.sigidx.md)[._codecid](common_signature.sigidx.md#protected-_codecid)*

*Definido en [src/utils/serialización.ts:40](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/serialization.ts#L40)*

___

### `Protegido` _typeID

• **_typeID**: *any* = undefined

*Overrides [StandardUTXOSet](common_utxos.standardutxoset.md).[_typeID](common_utxos.standardutxoset.md#protected-_typeid)*

*Definido en [src/apis/platformvm/utxos.ts:116](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/utxos.ts#L116)*

___

### _typeName `protegido`

• **_typeName**: *string* = "UTXOSet"

*Overrides [StandardUTXOSet](common_utxos.standardutxoset.md).[_typeName](common_utxos.standardutxoset.md#protected-_typename)*

*Definido en [src/apis/platformvm/utxos.ts:115](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/utxos.ts#L115)*

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

* \[ **utxoid**: *string*\]: [UTXO](api_platformvm_utxos.utxo.md)

## Métodos de trabajo

### _feeCheck

- **_feeCheck**`(fee`: BN, `feeAssetID`: Buffer): *boolean*

*Definido en [src/apis/platformvm/utxos.ts:167](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/utxos.ts#L167)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `Cuota de pago` | BN |
| `feeAssetID` | Buffer |

**Return:** *booleano*

___

### añadir a la lista de las partes

- **add**(`utxo`: [UTXO](api_platformvm_utxos.utxo.md) | string, `overwrite`: boolean): *[UTXO](api_platformvm_utxos.utxo.md)*

*Heredada de [StandardUTXOSet](common_utxos.standardutxoset.md).[add](common_utxos.standardutxoset.md#add)*

*Definido en [src/comm/utxos.ts:228](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/utxos.ts#L228)*

Añade un [StandardUTXO](common_utxos.standardutxo.md) al StandardUTXOSet.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `utxo` | [UTXO](api_platformvm_utxos.utxo.md) &#124; cadena | - | O bien una cadena serializada cb58 que representa una [StandardUTXO](common_utxos.standardutxo.md) |
| `sobreescribir` | booleano | falso | Si es cierto, si ya existe el UTXOID, sobrescribirlo... falso predeterminado |

**Returns:** *[UTXO](api_platformvm_utxos.utxo.md)*

Una [StandardUTXO](common_utxos.standardutxo.md) si uno fue agregado e indefinido si nada fue añadido.

___

### addArray

- **addArray**(`utxos`: string []| [UTXO](api_platformvm_utxos.utxo.md)[], `overwrite`: boolean): *[StandardUTXO](common_utxos.standardutxo.md)[]*

*Heredado de [StandardUTXOSet](common_utxos.standardutxoset.md).[addArray](common_utxos.standardutxoset.md#addarray)*

*Definido en [src/comm/utxos.ts:266](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/utxos.ts#L266)*

Añade una variedad de [StandardUTXOS](common_utxos.standardutxo.md) al [StandardUTXOSet](common_utxos.standardutxoset.md).

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `utxos` | string[] &#124; [UTXO](api_platformvm_utxos.utxo.md)[] | - | - |
| `sobreescribir` | booleano | falso | Si es cierto, si ya existe el UTXOID, sobrescribirlo... falso predeterminado |

**Returns:** *[StandardUTXO](common_utxos.standardutxo.md)[]*

Una serie de StandardUTXOS que se añadieron.

___

### buildAddDelegatorTx

[][][]- **buildAddDelegatorTx(networkID:**`` number, `blockchainID`: Buffer, `avaxAssetID`: Buffer, `buildAddDelegatorTx(networkID`: Buffer, `buildAddDelegatorTx(networkID`: Buffer, `buildAddDelegatorTx(networkID`: Buffer, `nodeID`: Buffer, `startTime`: BN, `endTime`: BN, `buildAddDelegatorTx(networkID`: BN, `buildAddDelegatorTx(networkID`: BN, `buildAddDelegatorTx(networkID`: número, `buildAddDelegatorTx(networkID`: []Buffer, `buildAddDelegatorTx(networkID```: Buffer, `memo`: Buffer, `buffer,` como: BN): *[UnsignedTx](api_platformvm_transactions.unsignedtx.md)*

*Definido en [src/apis/platformvm/utxos.ts:829](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/utxos.ts#L829)*

Clase que representa una transacción de [AddDelegatorTx](api_platformvm_validationtx.adddelegatortx.md) sin firmar.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `networkID` | Número de números | DefaultNetworkID | Networkid, [DefaultNetworkID](../modules/utils_constants.md#const-defaultnetworkid) |
| `blockchainID` | Buffer | - | Blockchainid, por defecto sin definir |
| `avaxAssetID` | Buffer | - | [Buffer](https://github.com/feross/buffer) del ID de activos para AVAX |
| `toAddresses` | Buffer[] | - | Una serie de direcciones como [Buffer](https://github.com/feross/buffer) recaba la estaca al final del período de grapado |
| `fromAddresses` | Buffer[] | - | Una serie de direcciones como [Buffer](https://github.com/feross/buffer) que paga las tarifas y la estaca |
| `changeAddresses` | Buffer[] | - | Una serie de direcciones como [Buffer](https://github.com/feross/buffer) que obtiene el cambio sobrante del pago de grapado |
| `nodeID` | Buffer | - | El ID del nodo del validador que se añade. |
| `startTime` | BN | - | El tiempo Unix cuando el validador comienza a validar la Red Primaria. |
| `endTime` | BN | - | El tiempo Unix cuando el validador deja de validar la Red Primaria (y se devuelve AVAX almacenado). |
| `Importe de la participación` | BN | - | Un [BN](https://github.com/indutny/bn.js/) para la cantidad de participación que se delegará en nAVAX. |
| `rewardLocktime de bloqueo` | BN | - | El campo de bloqueo creado en las salidas de recompensa resultantes |
| `rewardThreshold` | Número de números | - | El número de firmas necesarias para gastar los fondos en la recompensa resultante UTXO |
| `recompensas Direcciones` | Buffer[] | - | Las direcciones que la recompensa del validador va. |
| `Cuota de pago` | BN | no definido. | Opcional. La cantidad de tasas a quemar en su denominación más pequeña, representada como [BN](https://github.com/indutny/bn.js/) |
| `feeAssetID` | Buffer | no definido. | Opcional. El activo de las tarifas que se están quemando. |
| `meme` | Buffer | no definido. | Opcional contiene bytes arbitrarios, hasta 256 bytes |
| `as.` | BN | UnixNow() | Opcional. La marca de tiempo para verificar la transacción contra un [BN](https://github.com/indutny/bn.js/) |

**Returns:** *[Sin](api_platformvm_transactions.unsignedtx.md)* Returns:

Una transacción no firmada creada a partir de los parámetros pasados.

___

### buildAddValidatorTx

[][][]- **buildAddValidatorTx(networkID:**`` number, `blockchainID`: Buffer, `avaxAssetID`: Buffer, `toAddresses`: Buffer, `buildAddValidatorTx(networkID`: Buffer, `buildAddValidatorTx(networkID`: Buffer, `nodeID`: Buffer, `startTime`: BN, `endTime```: BN, `buildAddValidatorTx(networkID`: BN, `buildAddValidatorTx(networkID```: BN, buildAddValidatorTx(networkID: número, `buildAddValidatorTx(networkID`: []Buffer, buildAddValidatorTx(networkID: número: BN, `feeAssetID```: Buffer, `memo`: Buffer, `como`: BN): *[UnsignedTx](api_platformvm_transactions.unsignedtx.md)*

*Definido en [src/apis/platformvm/utxos.ts:908](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/utxos.ts#L908)*

Clase que representa una transacción de [AddValidatorTx](api_platformvm_validationtx.addvalidatortx.md) sin firmar.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `networkID` | Número de números | DefaultNetworkID | NetworkID, [DefaultNetworkID](../modules/utils_constants.md#const-defaultnetworkid) |
| `blockchainID` | Buffer | - | BlockchainID, por defecto sin definir |
| `avaxAssetID` | Buffer | - | [Buffer](https://github.com/feross/buffer) del ID de activos para AVAX |
| `toAddresses` | Buffer[] | - | Una serie de direcciones como [Buffer](https://github.com/feross/buffer) recaba la estaca al final del período de grapado |
| `fromAddresses` | Buffer[] | - | Una serie de direcciones como [Buffer](https://github.com/feross/buffer) que paga las tarifas y la estaca |
| `changeAddresses` | Buffer[] | - | Una serie de direcciones como [Buffer](https://github.com/feross/buffer) que obtiene el cambio sobrante del pago de grapado |
| `nodeID` | Buffer | - | El ID del nodo del validador que se añade. |
| `startTime` | BN | - | El tiempo Unix cuando el validador comienza a validar la Red Primaria. |
| `endTime` | BN | - | El tiempo Unix cuando el validador deja de validar la Red Primaria (y se devuelve AVAX almacenado). |
| `Importe de la participación` | BN | - | Un [BN](https://github.com/indutny/bn.js/) para la cantidad de participación que se delegará en nAVAX. |
| `rewardLocktime de bloqueo` | BN | - | El campo de bloqueo creado en las salidas de recompensa resultantes |
| `rewardThreshold` | Número de números | - | El número de firmas necesarias para gastar los fondos en la recompensa resultante UTXO |
| `recompensas Direcciones` | Buffer[] | - | Las direcciones que la recompensa del validador va. |
| `DelegationFee` | Número de números | - | Un número para el porcentaje de recompensa que se le dará al validador cuando alguien se delega en ellos. Debe estar entre 0 y 100. |
| `Cuota de pago` | BN | no definido. | Opcional. La cantidad de tasas a quemar en su denominación más pequeña, representada como [BN](https://github.com/indutny/bn.js/) |
| `feeAssetID` | Buffer | no definido. | Opcional. El activo de las tarifas que se están quemando. |
| `meme` | Buffer | no definido. | Opcional contiene bytes arbitrarios, hasta 256 bytes |
| `as.` | BN | UnixNow() | Opcional. La marca de tiempo para verificar la transacción contra un [BN](https://github.com/indutny/bn.js/) |

**Returns:** *[Sin](api_platformvm_transactions.unsignedtx.md)* Returns:

Una transacción no firmada creada a partir de los parámetros pasados.

___

### buildBaseTx

[][][]- **buildBaseTx(networkID:**`` número, `blockchainID`: Buffer, `monto`: BN, `assetID`: Buffer, `buildBaseTx(networkID`: Buffer, `buildBaseTx(networkID`: Buffer, `buildBaseTx(networkID`: Buffer, `honorario`: BN, `feeAssetID`: Buffer, `buildBaseTx(networkID`: Buffer, `comode`: BN, `locktime`: BN, `umbral`: número): *[UnsignedTx](api_platformvm_transactions.unsignedtx.md)*

*Definido en [src/apis/platformvm/utxos.ts:483](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/utxos.ts#L483)*

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

**Returns:** *[Sin](api_platformvm_transactions.unsignedtx.md)* Returns:

Una transacción no firmada creada a partir de los parámetros pasados.

___

### buildCreateSubnetTx

[][]- **buildCreateSubnetTx(networkID:**`` número, `blockchainID`: Buffer, `buildCreateSubnetTx(networkID```: Buffer, buildCreateSubnetTx(networkID: Buffer, `buildCreateSubnetTx(networkID`: []Buffer, `buildCreateSubnetTx(networkID`: número, `honorario`: BN, `feeAssetID`: Buffer, `memo`: Buffer, `comode`: BN): *[UnsignedTx](api_platformvm_transactions.unsignedtx.md)*

*Definido en [src/apis/platformvm/utxos.ts:983](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/utxos.ts#L983)*

Clase que representa una transacción de [CreateSubnetTx](api_platformvm_createsubnettx.createsubnettx.md) sin firmar.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `networkID` | Número de números | DefaultNetworkID | Networkid, [DefaultNetworkID](../modules/utils_constants.md#const-defaultnetworkid) |
| `blockchainID` | Buffer | - | Blockchainid, por defecto sin definir |
| `fromAddresses` | Buffer[] | - | Las direcciones que se utilizan para enviar los fondos del [Buffer](https://github.com/feross/buffer) UTXOS |
| `changeAddresses` | Buffer[] | - | Las direcciones que pueden gastar el cambio restante de las UTXOs. |
| `subnetOwnerAddresses Direcciones` | Buffer[] | - | Una matriz de [Buffer](https://github.com/feross/buffer) para que las direcciones se añadan a un subnet |
| `subnetOwnerThreshold` | Número de números | - | El número de firmas de los propietarios requeridas para añadir un validador a la red |
| `Cuota de pago` | BN | no definido. | Opcional. La cantidad de tasas a quemar en su denominación más pequeña, representada como [BN](https://github.com/indutny/bn.js/) |
| `feeAssetID` | Buffer | no definido. | Opcional. El activo de las tasas que se están quemando |
| `meme` | Buffer | no definido. | Opcional contiene bytes arbitrarios, hasta 256 bytes |
| `as.` | BN | UnixNow() | Opcional. La marca de tiempo para verificar la transacción contra un [BN](https://github.com/indutny/bn.js/) |

**Returns:** *[Sin](api_platformvm_transactions.unsignedtx.md)* Returns:

Una transacción no firmada creada a partir de los parámetros pasados.

___

### buildExportTx

[][][]- **buildExportTx(networkID:**`` number, `blockchainID```: Buffer, `sumo`: BN, `avaxAssetID`: Buffer, `buildExportTx(networkID`: Buffer, `buildExportTx(networkID```: Buffer, buildExportTx(networkID: Buffer, buildExportTx(networkID: Buffer, `honorario`: BN, `feeAssetID`: Buffer, `memo`: Buffer, `como`: BN, `locktime`: BN, `umbral`: número): *[UnsignedTx](api_platformvm_transactions.unsignedtx.md)*

*Definido en [src/apis/platformvm/utxos.ts:675](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/utxos.ts#L675)*

Crea una transacción ExportTx sin firmar.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `networkID` | Número de números | - | El número que representa a NetworkID del nodo |
| `blockchainID` | Buffer | - | El [Buffer](https://github.com/feross/buffer) que representa el BlockchainID para la transacción |
| `importe de la cantidad de dinero` | BN | - | La cantidad que se exportará como [BN](https://github.com/indutny/bn.js/) |
| `avaxAssetID` | Buffer | - | [Buffer](https://github.com/feross/buffer) del ID de activos para AVAX |
| `toAddresses` | Buffer[] | - | Una serie de direcciones como [Buffer](https://github.com/feross/buffer) que recaba el AVAX |
| `fromAddresses` | Buffer[] | - | Una serie de direcciones como [Buffer](https://github.com/feross/buffer) que posee el AVAX |
| `changeAddresses` | Buffer[] | no definido. | Una serie de direcciones como [Buffer](https://github.com/feross/buffer) que obtiene el cambio sobrante de la AVAX |
| `destinationChain de destino` | Buffer | no definido. | Opcional. Un [buffer](https://github.com/feross/buffer) para el chainid donde enviar el activo. |
| `Cuota de pago` | BN | no definido. | Opcional. La cantidad de tasas a quemar en su denominación más pequeña, representada como [BN](https://github.com/indutny/bn.js/) |
| `feeAssetID` | Buffer | no definido. | Opcional. El activo de las tarifas que se están quemando. |
| `meme` | Buffer | no definido. | Opcional contiene bytes arbitrarios, hasta 256 bytes |
| `as.` | BN | UnixNow() | Opcional. La marca de tiempo para verificar la transacción contra un [BN](https://github.com/indutny/bn.js/) |
| `Tiempo de bloqueo` | BN | nuevo BN(0) | Opcional. El campo de bloqueo creado en las salidas resultantes |
| `umbral` | Número de números | 1 1 | Opcional. El número de firmas necesarias para gastar los fondos en la UTXO resultante |

**Returns:** *[Sin](api_platformvm_transactions.unsignedtx.md)* Returns:

Una transacción no firmada creada a partir de los parámetros pasados.

___

### buildImportTx

[][]- **buildImportTx(networkID:**`` number, `blockchainID`: Buffer, `buildImportTx(networkID```: Buffer, `buildImportTx(networkID`: []Buffer, buildImportTx(networkID: Buffer, `atomics`: [UTXO](api_platformvm_utxos.utxo.md)[], `sourceChain`: Buffer, `feeAssetID```: Buffer, `memo`: Buffer, `como`: BN, `locktime`: BN, `umbral`: número): *[UnsignedTx](api_platformvm_transactions.unsignedtx.md)*

*Definido en [src/apis/platformvm/utxos.ts:563](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/utxos.ts#L563)*

Crea una transacción de ImportTx sin firmar.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `networkID` | Número de números | - | El número que representa a NetworkID del nodo |
| `blockchainID` | Buffer | - | El [Buffer](https://github.com/feross/buffer) que representa el BlockchainID para la transacción |
| `toAddresses` | Buffer[] | - | Las direcciones para enviar los fondos |
| `fromAddresses` | Buffer[] | - | Las direcciones que se utilizan para enviar los fondos del [Buffer](https://github.com/feross/buffer) UTXOS |
| `changeAddresses` | Buffer[] | - | Opcional. Las direcciones que pueden gastar el cambio restante de las UTXOs. Default: toAddresses |
| `átomos` | [UTXO](api_platformvm_utxos.utxo.md)[] | - | - |
| `sourceChain` | Buffer | no definido. | Un [buffer](https://github.com/feross/buffer) para el chainid de donde vienen las importaciones. |
| `Cuota de pago` | BN | no definido. | Opcional. La cantidad de tasas a quemar en su denominación más pequeña, representada como [BN](https://github.com/indutny/bn.js/). La tarifa vendrá de las entradas primero, si pueden. |
| `feeAssetID` | Buffer | no definido. | Opcional. El activo de las tarifas que se están quemando. |
| `meme` | Buffer | no definido. | Opcional contiene bytes arbitrarios, hasta 256 bytes |
| `as.` | BN | UnixNow() | Opcional. La marca de tiempo para verificar la transacción contra un [BN](https://github.com/indutny/bn.js/) |
| `Tiempo de bloqueo` | BN | nuevo BN(0) | Opcional. El campo de bloqueo creado en las salidas resultantes |
| `umbral` | Número de números | 1 1 | Opcional. El número de firmas necesarias para gastar los fondos en la UTXO resultante |

**Returns:** *[Sin](api_platformvm_transactions.unsignedtx.md)* Returns:

Una transacción no firmada creada a partir de los parámetros pasados.

___

### clon

- **clone**(): *esto*

*Overrides [StandardUTXOSet](common_utxos.standardutxoset.md).[clone](common_utxos.standardutxoset.md#abstract-clone)*

*Definido en [src/apis/platformvm/utxos.ts:160](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/utxos.ts#L160)*

**Returns:** *esto*

___

### crear un entorno de creación

*-* **create**(...`args`: []cualquiera

*Overrides [StandardUTXOSet](common_utxos.standardutxoset.md).[create](common_utxos.standardutxoset.md#abstract-create)*

*Definido en [src/apis/platformvm/utxos.ts:156](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/utxos.ts#L156)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `..args` | cualquier otra cosa que no sea[] |

**Returns:** *esto*

___

### deserie

- **deserialize**(`fields`: objeto, `codificación`: [SerializedEncoding](../modules/src_utils.md#serializedencoding)): *vacío*

*Superaciones [StandardParseableInput](common_inputs.standardparseableinput.md).[deserialize](common_inputs.standardparseableinput.md#deserialize)*

*Definido en [src/apis/platformvm/utxos.ts:120](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/utxos.ts#L120)*

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

- (`utxo`: [UTXO](api_platformvm_utxos.utxo.md), .`..largos`: []any): *booleano*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `utxo` | [UTXO](api_platformvm_utxos.utxo.md) |
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

- **getAllUTXOs**(`utxoids`: []string): *[UTXO](api_platformvm_utxos.utxo.md)[]*

*Heredada de [StandardUTXOSet](common_utxos.standardutxoset.md)[.getAllUTXOS](common_utxos.standardutxoset.md#getallutxos)*

*Definido en [src/comm/utxos.ts:346](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/utxos.ts#L346)*

Obtiene todos los [StandardUTXO](common_utxos.standardutxo.md)s, opcionalmente que coincida con UTXOIDs en una matriz

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `utxoids` | cadena de producción[] | no definido. | Una matriz opcional de UTXOIDs, devuelve todos los [StandardUTXO](common_utxos.standardutxo.md)s si no se proporciona |

**Returns:** *[UTXO](api_platformvm_utxos.utxo.md)[]*

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

### getConsumableUXTO

- **getConsumableUXTO(asOf:**`` BN, `getConsumableUXTO(asOf`: booleano): *[UTXO](api_platformvm_utxos.utxo.md)[]*

*Definido en [src/apis/platformvm/utxos.ts:174](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/utxos.ts#L174)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `as.` | BN | UnixNow() |
| `Apuesta` | booleano | falso |

**Returns:** *[UTXO](api_platformvm_utxos.utxo.md)[]*

___

### getMinimumSpendable

- **getMinimumSpendable(aad:**`` [getMinimumSpendable(aad:](api_platformvm_utxos.assetamountdestination.md) `como`: BN, `tiempo de` bloqueo: BN, `umbral`: número, `hoguera`: boolean): *[Error](src_utils.avalancheerror.md#static-error)*

*Definido en [src/apis/platformvm/utxos.ts:197](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/utxos.ts#L197)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `a)` | [AssetAmountDestination](api_platformvm_utxos.assetamountdestination.md) | - |
| `as.` | BN | UnixNow() |
| `Tiempo de bloqueo` | BN | nuevo BN(0) |
| `umbral` | Número de números | 1 1 |
| `Apuesta` | booleano | falso |

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

- **getUTXO**(`utxoid`: string): *[UTXO](api_platformvm_utxos.utxo.md)*

*Heredada de [StandardUTXOSet](common_utxos.standardutxoset.md).[getUTXO](common_utxos.standardutxoset.md#getutxo)*

*Definido en [src/comm/utxos.ts:337](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/utxos.ts#L337)*

Obtiene un [StandardUTXO](common_utxos.standardutxo.md) desde el [StandardUTXOSet](common_utxos.standardutxoset.md) por su UTXOID.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `utxoid` | cadena de producción | Cadena que representa el UTXOID |

**Returns:** *[UTXO](api_platformvm_utxos.utxo.md)*

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

- **includes**(`utxo`: [UTXO](api_platformvm_utxos.utxo.md) | string): *booleano*

*Heredado de [StandardUTXOSet](common_utxos.standardutxoset.md).[includes](common_utxos.standardutxoset.md#includes)*

*Definido en [src/comm/utxos.ts:203](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/utxos.ts#L203)*

Devuelve cierto si el [StandardUTXO](common_utxos.standardutxo.md) está en el StandardUTXOSet.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `utxo` | [UTXO](api_platformvm_utxos.utxo.md) &#124; cadena | O bien una cadena serializada cb58 que representa una [StandardUTXO](common_utxos.standardutxo.md) |

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

- **parseUTXO**(`utxo`: [UTXO](api_platformvm_utxos.utxo.md) | string): *[UTXO](api_platformvm_utxos.utxo.md)*

*Overrides [StandardUTXOSet](common_utxos.standardutxoset.md).[parseUTXO](common_utxos.standardutxoset.md#abstract-parseutxo)*

*Definido en [src/apis/platformvm/utxos.ts:142](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/platformvm/utxos.ts#L142)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `utxo` | [UTXO](api_platformvm_utxos.utxo.md) &#124; cadena |

**Returns:** *[UTXO](api_platformvm_utxos.utxo.md)*

___

### eliminar las emisiones de gases

- **remove**(`utxo`: [UTXO](api_platformvm_utxos.utxo.md) | string): *[UTXO](api_platformvm_utxos.utxo.md)*

*Heredado de [StandardUTXOSet](common_utxos.standardutxoset.md).[remove](common_utxos.standardutxoset.md#remove)*

*Definido en [src/comm/utxos.ts:284](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/utxos.ts#L284)*

Elimina un [StandardUTXO](common_utxos.standardutxo.md) del [StandardUTXOSet](common_utxos.standardutxoset.md) si existe.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `utxo` | [UTXO](api_platformvm_utxos.utxo.md) &#124; cadena | O bien una cadena serializada cb58 que representa una [StandardUTXO](common_utxos.standardutxo.md) |

**Returns:** *[UTXO](api_platformvm_utxos.utxo.md)*

Una [StandardUTXO](common_utxos.standardutxo.md) si fue removido y sin definir si nada fue eliminado.

___

### removeArray

- **removeArray**(`utxos`: string []| [UTXO):](api_platformvm_utxos.utxo.md) []*[UTXO](api_platformvm_utxos.utxo.md)[]*

*Heredado de [StandardUTXOSet](common_utxos.standardutxoset.md).[removeArray](common_utxos.standardutxoset.md#removearray)*

*Definido en [src/comm/utxos.ts:319](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/utxos.ts#L319)*

Elimina una variedad de [StandardUTXOS](common_utxos.standardutxo.md) al [StandardUTXOSet](common_utxos.standardutxoset.md).

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `utxos` | string[] &#124; [UTXO](api_platformvm_utxos.utxo.md)[] |

**Returns:** *[UTXO](api_platformvm_utxos.utxo.md)[]*

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
