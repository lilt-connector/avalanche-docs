[avalancha](../README.md) › [Firma común](../modules/common_signature.md) › [Credencial](common_signature.credential.md)

# Clase: Credencial

## Jerarquía

* [Serializable](utils_serialization.serializable.md)

   **m. Credencial**

   de la sección [SECPCredential](api_platformvm_credentials.secpcredential.md)

   de la sección [SECPCredential](api_avm_credentials.secpcredential.md)

   [↳](api_avm_credentials.nftcredential.md)

   de la sección [SECPCredential](api_evm_credentials.secpcredential.md)

## Índice de participación

### Constructores

* [constructor](common_signature.credential.md#constructor)

### Propiedades de las propiedades

* [_codecid](common_signature.credential.md#protected-_codecid)
* [_typeID](common_signature.credential.md#protected-_typeid)
* [_typeName](common_signature.credential.md#protected-_typename)
* [sigArray](common_signature.credential.md#protected-sigarray)

### Métodos de trabajo

* [addSignature](common_signature.credential.md#addsignature)
* [clon](common_signature.credential.md#abstract-clone)
* [crear un entorno de creación](common_signature.credential.md#abstract-create)
* [deserie](common_signature.credential.md#deserialize)
* [deBuffer](common_signature.credential.md#frombuffer)
* [getCodecid](common_signature.credential.md#getcodecid)
* [getCredentialID](common_signature.credential.md#abstract-getcredentialid)
* [getTypeID](common_signature.credential.md#gettypeid)
* [getTypeName](common_signature.credential.md#gettypename)
* [seleccionar](common_signature.credential.md#abstract-select)
* [serializar](common_signature.credential.md#serialize)
* [setCodecid](common_signature.credential.md#setcodecid)
* [toBuffer](common_signature.credential.md#tobuffer)

## Constructores

### constructor

\+ **nuevo Credential(sigarray:***[](common_signature.credential.md)*`` [Firma):](common_signature.signature.md)[] Credencial

*Definido en [src/común/credenciales.ts:167](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/credentials.ts#L167)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `sigarray` | [Firma](common_signature.signature.md)[] | no definido. |

**Retornos:** *[Credencial](common_signature.credential.md)*

## Propiedades de las propiedades

### _codecid `protegido`

• **_codecid**: *número* = indefinido.

*Heredada de [SigIdx](common_signature.sigidx.md)[._codecid](common_signature.sigidx.md#protected-_codecid)*

*Definido en [src/utils/serialización.ts:40](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/serialization.ts#L40)*

___

### `Protegido` _typeID

• **_typeID**: *any* = undefined

*Superes [Serializable](utils_serialization.serializable.md).[_typeID](utils_serialization.serializable.md#protected-_typeid)*

*Definido en [src/común/credenciales.ts:103](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/credentials.ts#L103)*

___

### _typeName `protegido`

• **_typeName**: *string* = "Credencial"

*Superes [Serializable](utils_serialization.serializable.md).[_typeName](utils_serialization.serializable.md#protected-_typename)*

*Definido en [src/común/credenciales.ts:102](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/credentials.ts#L102)*

___

### SigArray `protegido`

• **sigArray**: *[Firma](common_signature.signature.md)[]* =[]

*Definido en [src/común/credenciales.ts:121](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/credentials.ts#L121)*

## Métodos de trabajo

### addSignature

- **addSignature**(`sig`: [Firma):](common_signature.signature.md) *número*

*Definido en [src/común/credenciales.ts:135](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/credentials.ts#L135)*

Añade una firma a las credenciales y devuelve el índice de la firma añadida.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `sig` | [Firma](common_signature.signature.md) |

**Retornos:** *número*

___

### Clon `abstracto`

- **clone**(): *esto*

*Definido en [src/común/credenciales.ts:165](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/credentials.ts#L165)*

**Returns:** *esto*

___

### `Crear, abstracta,`

*-* **create**(...`args`: []cualquiera

*Definido en [src/común/credenciales.ts:166](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/credentials.ts#L166)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `..args` | cualquier otra cosa que no sea[] |

**Returns:** *esto*

___

### deserie

- **deserialize**(`fields`: objeto, `codificación`: [SerializedEncoding](../modules/src_utils.md#serializedencoding)): *vacío*

*Superaciones [StandardParseableInput](common_inputs.standardparseableinput.md).[deserialize](common_inputs.standardparseableinput.md#deserialize)*

*Definido en [src/común/credenciales.ts:112](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/credentials.ts#L112)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `campos de cultivo` | objeto de la operación | - |
| `codificación` | [SerializedEncoding](../modules/src_utils.md#serializedencoding) | "hex" |

**Retornos:** *vacío*

___

### deBuffer

- **fromBuffer**(`bytes`: Buffer, `offset`: número): *número*

*Definido en [src/común/credenciales.ts:140](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/credentials.ts#L140)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `bytes` | Buffer | - |
| `offset` | Número de números | 0 |

**Retornos:** *número*

___

### getCodecid

- **getCodecid():** *número*

*Heredada de [SigIdx](common_signature.sigidx.md)[.getCodecid](common_signature.sigidx.md#getcodecid)*

*Definido en [src/utils/serialización.ts:59](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/utils/serialization.ts#L59)*

Utilizado en serialización. Opcional. TypeID es un número para el tipo de identificación de objeto que se está saliendo.

**Retornos:** *número*

___

### `Resumen` getCredentialID

- **getCredentialID**(): *número*

*Definido en [src/común/credenciales.ts:123](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/credentials.ts#L123)*

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

### `Seleccione abstracto`

- **select(id:**`` número, ...`args`: []select(id: *[Credencial](common_signature.credential.md)*

*Definido en [src/común/credenciales.ts:167](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/credentials.ts#L167)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `I.` | Número de números |
| `..args` | cualquier otra cosa que no sea[] |

**Retornos:** *[Credencial](common_signature.credential.md)*

___

### serializar

- **serialize**(`encoding`: [SerializedEncoding](../modules/src_utils.md#serializedencoding)): *objeto*

*Superaciones [Serializable](utils_serialization.serializable.md).[serialize](utils_serialization.serializable.md#serialize)*

*Definido en [src/común/credenciales.ts:105](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/credentials.ts#L105)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `codificación` | [SerializedEncoding](../modules/src_utils.md#serializedencoding) | "hex" |

**Return:** *objeto*

___

### setCodecid

- **setCodecid(codecid:**`` número): *vacío*

*Definido en [src/común/credenciales.ts:130](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/credentials.ts#L130)*

Configure el codecid

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `codecid` | Número de números | El codecid para configurar |

**Retornos:** *vacío*

___

### toBuffer

- **toBuffer** (): *Buffer*

*Definido en [src/común/credenciales.ts:152](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/credentials.ts#L152)*

**Returns:** *Buffer*
