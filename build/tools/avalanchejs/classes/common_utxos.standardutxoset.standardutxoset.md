[avalancha](../README.md) › [Common-UTXOs](../modules/common_utxos.md) › [StandardUTXOSet](common_utxos.standardutxoset.md)

# Clase: StandardUTXOSet ‹**UTXOClass**›

Clase que representa un conjunto de [StandardUTXO](common_utxos.standardutxo.md)s.

## Parámetros de tipo

• **UTXOClass**: *[StandardUTXO](common_utxos.standardutxo.md)*

## Jerarquía

* [Serializable](utils_serialization.serializable.md)

   de la norma **StandardUTXOSet**

   de [UTXOSet](api_platformvm_utxos.utxoset.md)

   de [UTXOSet](api_avm_utxos.utxoset.md)

   de [UTXOSet](api_evm_utxos.utxoset.md)

## Índice de participación

### Propiedades de las propiedades

* [_codecid](common_utxos.standardutxoset.md#protected-_codecid)
* [_typeID](common_utxos.standardutxoset.md#protected-_typeid)
* [_typeName](common_utxos.standardutxoset.md#protected-_typename)
* [dirección addressUTXOs](common_utxos.standardutxoset.md#protected-addressutxos)
* [utxos](common_utxos.standardutxoset.md#protected-utxos)

### Métodos de trabajo

* [añadir a la lista de las partes](common_utxos.standardutxoset.md#add)
* [addArray](common_utxos.standardutxoset.md#addarray)
* [clon](common_utxos.standardutxoset.md#abstract-clone)
* [crear un entorno de creación](common_utxos.standardutxoset.md#abstract-create)
* [deserie](common_utxos.standardutxoset.md#deserialize)
* [diferencia entre la diferencia entre la diferencia y la diferencia entre la diferencia](common_utxos.standardutxoset.md#difference)
* [filtro de filtro](common_utxos.standardutxoset.md#filter)
* [getAddresses](common_utxos.standardutxoset.md#getaddresses)
* [getAllUTXOStrings](common_utxos.standardutxoset.md#getallutxostrings)
* [getAllUTXOs](common_utxos.standardutxoset.md#getallutxos)
* [getAssetIDs](common_utxos.standardutxoset.md#getassetids)
* [getBalance](common_utxos.standardutxoset.md#getbalance)
* [getCodecid](common_utxos.standardutxoset.md#getcodecid)
* [getTypeID](common_utxos.standardutxoset.md#gettypeid)
* [getTypeName](common_utxos.standardutxoset.md#gettypename)
* [getutXO](common_utxos.standardutxoset.md#getutxo)
* [getUTXOIDs](common_utxos.standardutxoset.md#getutxoids)
* [incluye las siguientes](common_utxos.standardutxoset.md#includes)
* [intersección](common_utxos.standardutxoset.md#intersection)
* [fusión](common_utxos.standardutxoset.md#merge)
* [mergeByRule](common_utxos.standardutxoset.md#mergebyrule)
* [parseUTXO](common_utxos.standardutxoset.md#abstract-parseutxo)
* [eliminar las emisiones de gases](common_utxos.standardutxoset.md#remove)
* [removeArray](common_utxos.standardutxoset.md#removearray)
* [serializar](common_utxos.standardutxoset.md#serialize)
* [simular Diferencia](common_utxos.standardutxoset.md#symdifference)
* [Unión Europea](common_utxos.standardutxoset.md#union)

## Propiedades de las propiedades

### _codecid `protegido`

• **_codecid**: *número* = indefinido.

*Heredada de [SigIdx](common_signature.sigidx.md)[._codecid](common_signature.sigidx.md#protected-_codecid)*

*Definido en [src/utils/serialización.ts:40](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/serialization.ts#L40)*

___

### `Protegido` _typeID

• **_typeID**: *any* = undefined

*Superes [Serializable](utils_serialization.serializable.md).[_typeID](utils_serialization.serializable.md#protected-_typeid)*

*Definido en [src/comm/utxos.ts:167](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/utxos.ts#L167)*

___

### _typeName `protegido`

• **_typeName**: *string* = "StandardUTXOSet"

*Superes [Serializable](utils_serialization.serializable.md).[_typeName](utils_serialization.serializable.md#protected-_typename)*

*Definido en [src/comm/utxos.ts:166](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/utxos.ts#L166)*

___

### Dirección `Protected`

• **addressUTXOs**: *objeto*

*Definido en [src/comm/utxos.ts:194](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/utxos.ts#L194)*

#### Declaración de tipo:

* \[ **dirección**: *string*\]: objeto

* \[ **utxoid**: *string*\]: BN

___

### utxos `protegidos`

• **utxos**: *objeto*

*Definido en [src/comm/utxos.ts:193](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/utxos.ts#L193)*

#### Declaración de tipo:

* \[ **utxoid**: *string*\]: UTXOClass

## Métodos de trabajo

### añadir a la lista de las partes

- **add**(`utxo`: UTXOClass | string, `overwrite`: boolean): *UTXOClass*

*Definido en [src/comm/utxos.ts:228](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/utxos.ts#L228)*

Añade un [StandardUTXO](common_utxos.standardutxo.md) al StandardUTXOSet.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `utxo` | UTXOClass & #124; cadena | - | O bien una cadena serializada cb58 que representa una [StandardUTXO](common_utxos.standardutxo.md) |
| `sobreescribir` | booleano | falso | Si es cierto, si ya existe el UTXOID, sobrescribirlo... falso predeterminado |

**Returns:** *UTXOClass*

Una [StandardUTXO](common_utxos.standardutxo.md) si uno fue agregado e indefinido si nada fue añadido.

___

### addArray

- **addArray(utxos:**`` string []| []UTXOClass, `addArray(utxos`: boolean): *[StandardUTXO](common_utxos.standardutxo.md)[]*

*Definido en [src/comm/utxos.ts:266](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/utxos.ts#L266)*

Añade una variedad de [StandardUTXOS](common_utxos.standardutxo.md) al [StandardUTXOSet](common_utxos.standardutxoset.md).

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `utxos` | string[] &#124; UTXOClass[] | - | - |
| `sobreescribir` | booleano | falso | Si es cierto, si ya existe el UTXOID, sobrescribirlo... falso predeterminado |

**Returns:** *[StandardUTXO](common_utxos.standardutxo.md)[]*

Una serie de StandardUTXOS que se añadieron.

___

### Clon `abstracto`

- **clone**(): *esto*

*Definido en [src/comm/utxos.ts:473](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/utxos.ts#L473)*

**Returns:** *esto*

___

### `Crear, abstracta,`

*-* **create**(...`args`: []cualquiera

*Definido en [src/comm/utxos.ts:475](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/utxos.ts#L475)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `..args` | cualquier otra cosa que no sea[] |

**Returns:** *esto*

___

### deserie

- **deserialize**(`fields`: objeto, `codificación?`: [SerializedEncoding](../modules/src_utils.md#serializedencoding)): *void*

*Heredada de [StandardParseableInput](common_inputs.standardparseableinput.md).[deserialize](common_inputs.standardparseableinput.md#deserialize)*

*Definido en [src/utils/serialización.ts:72](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/serialization.ts#L72)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `campos de cultivo` | objeto de la operación |
| `¿codificar?` | [SerializedEncoding](../modules/src_utils.md#serializedencoding) |

**Retornos:** *vacío*

___

### diferencia entre la diferencia entre la diferencia y la diferencia entre la diferencia

- **difference**(`utxoset`: este): *esto*

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

*Definido en [src/comm/utxos.ts:477](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/utxos.ts#L477)*

**Parámetros:**

• **args**: *cualquier[]*

• **lambda**: *función*

- (`utxo`: UTXOClass, .`..largos`: []any): *booleano*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `utxo` | UTXOClass |
| `...grandes` | cualquier otra cosa que no sea[] |

**Returns:** *esto*

___

### getAddresses

- **gets():** *Buffer[]*

*Definido en [src/comm/utxos.ts:416](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/utxos.ts#L416)*

Obtiene las direcciones en el [StandardUTXOSet](common_utxos.standardutxoset.md) y devuelve una matriz de [Buffer](https://github.com/feross/buffer).

**Returns:** *Buffer[]*

___

### getAllUTXOStrings

- **getAllUTXOStrings**(`utxoids`: []string): *string[]*

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

- **getAllUTXOs**(`utxoids`: []string): *UTXOClass[]*

*Definido en [src/comm/utxos.ts:346](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/utxos.ts#L346)*

Obtiene todos los [StandardUTXO](common_utxos.standardutxo.md)s, opcionalmente que coincida con UTXOIDs en una matriz

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `utxoids` | cadena de producción[] | no definido. | Una matriz opcional de UTXOIDs, devuelve todos los [StandardUTXO](common_utxos.standardutxo.md)s si no se proporciona |

**Returns:** *UTXOClass[]*

Una serie de [StandardUTXO](common_utxos.standardutxo.md)s.

___

### getAssetIDs

- **getAssetIDs**(`addresses`: []Buffer): *Buffer[]*

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

- **getUTXO**(`utxoid`: string): *UTXOClass*

*Definido en [src/comm/utxos.ts:337](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/utxos.ts#L337)*

Obtiene un [StandardUTXO](common_utxos.standardutxo.md) desde el [StandardUTXOSet](common_utxos.standardutxoset.md) por su UTXOID.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `utxoid` | cadena de producción | Cadena que representa el UTXOID |

**Returns:** *UTXOClass*

Una [StandardUTXO](common_utxos.standardutxo.md) si existe en el conjunto.

___

### getUTXOIDs

- **getUTXOIDs**(`addresses`: []Buffer, `gastable`: booleano): *string[]*

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

- **includes**(`utxo`: UTXOClass | string): *booleano*

*Definido en [src/comm/utxos.ts:203](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/utxos.ts#L203)*

Devuelve cierto si el [StandardUTXO](common_utxos.standardutxo.md) está en el StandardUTXOSet.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `utxo` | UTXOClass & #124; cadena | O bien una cadena serializada cb58 que representa una [StandardUTXO](common_utxos.standardutxo.md) |

**Return:** *booleano*

___

### intersección

- **intersection**(`utxoset`: este): *esto*

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

### `ParseUTXO abstracto`

- **parseUTXO**(`utxo`: UTXOClass | string): *UTXOClass*

*Definido en [src/comm/utxos.ts:196](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/utxos.ts#L196)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `utxo` | UTXOClass & #124; cadena |

**Returns:** *UTXOClass*

___

### eliminar las emisiones de gases

- **remove**(`utxo`: UTXOClass | string): *UTXOClass*

*Definido en [src/comm/utxos.ts:284](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/utxos.ts#L284)*

Elimina un [StandardUTXO](common_utxos.standardutxo.md) del [StandardUTXOSet](common_utxos.standardutxoset.md) si existe.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `utxo` | UTXOClass & #124; cadena | O bien una cadena serializada cb58 que representa una [StandardUTXO](common_utxos.standardutxo.md) |

**Returns:** *UTXOClass*

Una [StandardUTXO](common_utxos.standardutxo.md) si fue removido y sin definir si nada fue eliminado.

___

### removeArray

- **removeArray**(`utxos`: string []| UTXOClass): []*UTXOClass[]*

*Definido en [src/comm/utxos.ts:319](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/utxos.ts#L319)*

Elimina una variedad de [StandardUTXOS](common_utxos.standardutxo.md) al [StandardUTXOSet](common_utxos.standardutxoset.md).

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `utxos` | string[] &#124; UTXOClass[] |

**Returns:** *UTXOClass[]*

Una serie de UTXOS que fueron eliminados.

___

### serializar

- **serialize**(`encoding`: [SerializedEncoding](../modules/src_utils.md#serializedencoding)): *objeto*

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

*Definido en [src/comm/utxos.ts:558](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/utxos.ts#L558)*

Establecer unión entre este conjunto y un parámetro.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `utxoset` | Esto es lo que es un problema | El conjunto de la unión |

**Returns:** *esto*

Un nuevo StandardUTXOSet que contiene el sindicato
