[avalancha](../README.md) › [Utils-DB](../modules/utils_db.md) › [DB](utils_db.db.md)

# Clase: DB

Una clase para interactuar con el [módulo store2](https://github.com/nbubna/store)

Esta clase nunca debe ser instantiated directamente. En lugar de ello, invocar la estática "DB.getInstance()" función para tomar la instancia de singleton de la base de datos.

```js
const db = DB.getInstance();
const blockchaindb = db.getNamespace("mychain");
```

## Jerarquía

* **DB**

## Índice de participación

### Constructores

* [constructor](utils_db.db.md#private-constructor)

### Propiedades de las propiedades

* [instancia de parte de la](utils_db.db.md#static-private-instance)
* [tienda de venta](utils_db.db.md#static-private-store)

### Métodos de trabajo

* [getInstance](utils_db.db.md#static-getinstance)
* [getNamespace](utils_db.db.md#static-getnamespace)

## Constructores

### Constructor `privado`

\+ **nuevo DB():** *[DB](utils_db.db.md)*

*Definido en [src/utils/db.ts:21](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/db.ts#L21)*

**Returns:** *[DB](utils_db.db.md)*

## Propiedades de las propiedades

### Casación `privada` `estática`

• **instancia de la** *[DB](utils_db.db.md)*

*Definido en [src/utils/db.ts:19](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/db.ts#L19)*

___

### `Tienda` `privada` estática

• **tienda**: tienda *=* tienda

*Definido en [src/utils/db.ts:21](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/db.ts#L21)*

## Métodos de trabajo

### GetInstance `estática`

- **getInstance**(): *[DB](utils_db.db.md)*

*Definido en [src/utils/db.ts:28](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/db.ts#L28)*

Recupera el singleton de la base de datos.

**Returns:** *[DB](utils_db.db.md)*

___

### GetNamespace `estática`

- **getNamespace**(`ns`: string): *StoreAPI*

*Definido en [src/utils/db.ts:40](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/db.ts#L40)*

Obtiene un espacio de nombres del singleton de la base de datos.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `nn` | cadena de producción | El ritmo de los nombres para recuperar. |

**Retornos:** *StoreAPI*
