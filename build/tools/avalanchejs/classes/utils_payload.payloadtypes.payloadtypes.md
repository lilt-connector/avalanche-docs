[avalanche](../README.md) › [Utils-Payload](../modules/utils_payload.md) › [PayloadTypes](utils_payload.payloadtypes.md)

# Clase: Tipos de carga

Clase para determinar los tipos de carga útil y gestionar la tabla de búsqueda.

## Jerarquía

* **Tipos de carga**

## Índice de participación

### Constructores

* [constructor](utils_payload.payloadtypes.md#private-constructor)

### Propiedades de las propiedades

* [tipos de interés](utils_payload.payloadtypes.md#protected-types)
* [instancia de parte de la](utils_payload.payloadtypes.md#static-private-instance)

### Métodos de trabajo

* [getContent](utils_payload.payloadtypes.md#getcontent)
* [getPayload](utils_payload.payloadtypes.md#getpayload)
* [getTypeID](utils_payload.payloadtypes.md#gettypeid)
* [lookupID](utils_payload.payloadtypes.md#lookupid)
* [lookupType](utils_payload.payloadtypes.md#lookuptype)
* [refundido](utils_payload.payloadtypes.md#recast)
* [seleccionar](utils_payload.payloadtypes.md#select)
* [getInstance](utils_payload.payloadtypes.md#static-getinstance)

## Constructores

### Constructor `privado`

\+ **nuevos tipos de** *[PayloadTypes(): PayloadTypes](utils_payload.payloadtypes.md)*

*Definido en [src/utils/payload.ts:153](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/payload.ts#L153)*

**Returns:** *[PayloadTypes](utils_payload.payloadtypes.md)*

## Propiedades de las propiedades

### Tipos `protegidos`

• **tipos**: *cadena[]* =[]

*Definido en [src/utils/payload.ts:23](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/payload.ts#L23)*

___

### Casación `privada` `estática`

• **instancia**: *[Tipos de carga útil](utils_payload.payloadtypes.md)*

*Definido en [src/utils/payload.ts:22](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/payload.ts#L22)*

## Métodos de trabajo

### getContent

- **getContent**(`payload`: útil: Buffer): *Buffer*

*Definido en [src/utils/payload.ts:28](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/payload.ts#L28)*

Dado que un buffer de carga útil codificado devuelve el contenido de carga útil (menos typeID).

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `carga útil` | Buffer |

**Returns:** *Buffer*

___

### getPayload

- **getPayload**(`payload`: útil: Buffer): *Buffer*

*Definido en [src/utils/payload.ts:36](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/payload.ts#L36)*

Dado que un buffer de carga útil codificado devuelve la carga útil (con typeID).

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `carga útil` | Buffer |

**Returns:** *Buffer*

___

### getTypeID

- **getTypeID**(`payload`: útil: Buffer): *número*

*Definido en [src/utils/payload.ts:44](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/payload.ts#L44)*

Dado que un buffer de carga útil devuelve el TypeID adecuado.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `carga útil` | Buffer |

**Retornos:** *número*

___

### lookupID

- **lookupID**(`typestr`: string): *number*

*Definido en [src/utils/payload.ts:55](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/payload.ts#L55)*

Dado que una cadena de tipo devuelve el TypeID adecuado.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `typestr` | cadena de producción |

**Retornos:** *número*

___

### lookupType

- **lookupType**(`value`: número): *string*

*Definido en [src/utils/payload.ts:62](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/payload.ts#L62)*

Dado que un TypeID devuelve una cadena que describe el tipo de carga útil.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `valor` | Número de números |

**Return:** *string*

___

### refundido

- **recast**(`unknowPayload`: [PayloadBase):](utils_payload.payloadbase.md) *[PayloadBase](utils_payload.payloadbase.md)*

*Definido en [src/utils/payload.ts:140](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/payload.ts#L140)*

Dado una [Base](utils_payload.payloadbase.md) PayloadBase que puede no ser echada correctamente, devuelve una [Base PayloadBase](utils_payload.payloadbase.md).

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `unknowPayload` | [Base de datos](utils_payload.payloadbase.md) |

**Returns:** *[PayloadBase](utils_payload.payloadbase.md)*

___

### seleccionar

- **select**(`typeid`: number, ...`args`: []any): *[PayloadBase](utils_payload.payloadbase.md)*

*Definido en [src/utils/payload.ts:69](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/payload.ts#L69)*

Dado que un TypeID devuelve la base [de carga útil](utils_payload.payloadbase.md) adecuada.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `typeid` | Número de números |
| `..args` | cualquier otra cosa que no sea[] |

**Returns:** *[PayloadBase](utils_payload.payloadbase.md)*

___

### GetInstance `estática`

- **getInstance**(): *[PayloadTypes](utils_payload.payloadtypes.md)*

*Definido en [src/utils/payload.ts:147](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/payload.ts#L147)*

Devuelve el singleton de [PayloadTypes](utils_payload.payloadtypes.md).

**Returns:** *[PayloadTypes](utils_payload.payloadtypes.md)*
