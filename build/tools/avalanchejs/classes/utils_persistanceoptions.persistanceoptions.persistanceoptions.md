[avalancha](../README.md) › [Utils-PersistanceOptions](../modules/utils_persistanceoptions.md)[](utils_persistanceoptions.persistanceoptions.md) › Opciones de resistencia

# Clase: Opciones de Resistencia

Una clase para definir el comportamiento de resistencia de esta llamada de API.

## Jerarquía

* **Opciones de resistencia**

## Índice de participación

### Constructores

* [constructor](utils_persistanceoptions.persistanceoptions.md#constructor)

### Propiedades de las propiedades

* [mergeRule](utils_persistanceoptions.persistanceoptions.md#protected-mergerule)
* [Nombre del nombre](utils_persistanceoptions.persistanceoptions.md#protected-name)
* [sobreescribir](utils_persistanceoptions.persistanceoptions.md#protected-overwrite)

### Métodos de trabajo

* [getMergeRule](utils_persistanceoptions.persistanceoptions.md#getmergerule)
* [getName](utils_persistanceoptions.persistanceoptions.md#getname)
* [getOverwrite](utils_persistanceoptions.persistanceoptions.md#getoverwrite)

## Constructores

### constructor

\+ nuevas *[Opciones](utils_persistanceoptions.persistanceoptions.md)* **de PersistanceOptions(name:**`` string: `overwrite`: boolean, `mergeRule`: [MergeRule](../modules/utils_constants.md#mergerule)): PersistanceOptions

*Definido en [src/utils/persistenceoptions.ts:31](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/persistenceoptions.ts#L31)*

**`observaciones sobre las observaciones formuladas`** Las reglas de fusión son las siguientes:
* "intersección" - la intersección del conjunto
* "differenceSelf" - la diferencia entre los datos existentes y el nuevo conjunto
* "differenceNew" - la diferencia entre los nuevos datos y el conjunto existente
* "symDifference" - la unión de las diferencias entre ambos conjuntos de datos
* "unión" - el conjunto único de todos los elementos contenidos en ambos conjuntos
* "unionMinusNew" - el conjunto único de todos los elementos contenidos en ambos conjuntos, excluidos los valores solo encontrados en el nuevo conjunto
* "unionMinusSelf" - el conjunto único de todos los elementos contenidos en ambos conjuntos, excluidos los valores solo encontrados en el conjunto existente

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial | Descripción |
------ | ------ | ------ | ------ |
| `Nombre del nombre` | cadena de producción | - | El espacio de nombres de la base de datos de los datos |
| `sobreescribir` | booleano | falso | Verdadero si los datos deben ser completos, sobrescritos |
| `mergeRule` | [Regla de fusión](../modules/utils_constants.md#mergerule) | - | - |

**Returns:** *[Opciones de Resistencia](utils_persistanceoptions.persistanceoptions.md)*

## Propiedades de las propiedades

### mergeRule `protegida`

• **mergeRule**: *[MergeRule](../modules/utils_constants.md#mergerule)* = "unión"

*Definido en [src/utils/persistenceoptions.ts:16](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/persistenceoptions.ts#L16)*

___

### Nombre `protegido`

• **nombre**: *cadena* = indefinida

*Definido en [src/utils/persistenceoptions.ts:12](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/persistenceoptions.ts#L12)*

___

### overwrite `protegida`

• **sobrescribe**: *booleano* = falso

*Definido en [src/utils/persistenceoptions.ts:14](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/persistenceoptions.ts#L14)*

## Métodos de trabajo

### getMergeRule

- **getMergeRule**(): *[Regla de fusión](../modules/utils_constants.md#mergerule)*

*Definido en [src/utils/persistenceoptions.ts:31](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/persistenceoptions.ts#L31)*

Devuelve la [regla](../modules/utils_constants.md#mergerule) de fusión de la instancia

**Returns:** *[Regla de fusión](../modules/utils_constants.md#mergerule)*

___

### getName

- **getName**(): *string*

*Definido en [src/utils/persistenceoptions.ts:21](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/persistenceoptions.ts#L21)*

Devuelve el espacio de nombres de la instancia

**Return:** *string*

___

### getOverwrite

- **getOverwrite**(): *booleano*

*Definido en [src/utils/persistenceoptions.ts:26](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/persistenceoptions.ts#L26)*

Devuelve la regla de sobreescritura de la instancia

**Return:** *booleano*
