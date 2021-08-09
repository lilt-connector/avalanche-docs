[avalancha](../README.md) › [API-AVM-Credentials](../modules/api_avm_credentials.md) › [SECPCredential](api_avm_credentials.secpcredential.md)

# Clase: SECPCredential

## Jerarquía

[m. Credencial](common_signature.credential.md)

de la sección **SECPCredential**

## Índice de participación

### Constructores

* [constructor](api_avm_credentials.secpcredential.md#constructor)

### Propiedades de las propiedades

* [_codecid](api_avm_credentials.secpcredential.md#protected-_codecid)
* [_typeID](api_avm_credentials.secpcredential.md#protected-_typeid)
* [_typeName](api_avm_credentials.secpcredential.md#protected-_typename)
* [sigArray](api_avm_credentials.secpcredential.md#protected-sigarray)

### Métodos de trabajo

* [addSignature](api_avm_credentials.secpcredential.md#addsignature)
* [clon](api_avm_credentials.secpcredential.md#clone)
* [crear un entorno de creación](api_avm_credentials.secpcredential.md#create)
* [deserie](api_avm_credentials.secpcredential.md#deserialize)
* [deBuffer](api_avm_credentials.secpcredential.md#frombuffer)
* [getCodecid](api_avm_credentials.secpcredential.md#getcodecid)
* [getCredentialID](api_avm_credentials.secpcredential.md#getcredentialid)
* [getTypeID](api_avm_credentials.secpcredential.md#gettypeid)
* [getTypeName](api_avm_credentials.secpcredential.md#gettypename)
* [seleccionar](api_avm_credentials.secpcredential.md#select)
* [serializar](api_avm_credentials.secpcredential.md#serialize)
* [setCodecid](api_avm_credentials.secpcredential.md#setcodecid)
* [toBuffer](api_avm_credentials.secpcredential.md#tobuffer)

## Constructores

### constructor

\+ **nuevo** [SECPCredential(sigarray:](common_signature.signature.md)[]`` *[SECPCredential](api_avm_credentials.secpcredential.md)*

*Heredada de [Credential](common_signature.credential.md).[constructor](common_signature.credential.md#constructor)*

*Definido en [src/común/credenciales.ts:167](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/credentials.ts#L167)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Prejudicial |
------ | ------ | ------ |
| `sigarray` | [Firma](common_signature.signature.md)[] | no definido. |

**Retornos:** *[SECPCredential](api_avm_credentials.secpcredential.md)*

## Propiedades de las propiedades

### _codecid `protegido`

• **_codecid**: *número* = AVMConstants.LATESTCODEC

*Overrides [SigIdx](common_signature.sigidx.md)[._codecid](common_signature.sigidx.md#protected-_codecid)*

*Definido en [src/apis/avm/credenciales.ts:29](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/credentials.ts#L29)*

___

### `Protegido` _typeID

• **_typeID**: *number* = this._codecid === 0 ? AVMConstants.SECPCREDENTIAL : AVMConstants.SECPCREDENTIAL AVMConstants.SECPCREDENTIAL_CODECONE

*Superaciones [Credential](common_signature.credential.md).[_typeID](common_signature.credential.md#protected-_typeid)*

*Definido en [src/apis/avm/credenciales.ts:30](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/credentials.ts#L30)*

___

### _typeName `protegido`

• **_typeName**: *string* = "SECPCredential"

*Overrides [Credential](common_signature.credential.md).[_typeName](common_signature.credential.md#protected-_typename)*

*Definido en [src/apis/avm/credenciales.ts:28](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/credentials.ts#L28)*

___

### SigArray `protegido`

• **sigArray**: *[Firma](common_signature.signature.md)[]* =[]

*Heredada de [Credential](common_signature.credential.md).[sigArray](common_signature.credential.md#protected-sigarray)*

*Definido en [src/común/credenciales.ts:121](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/credentials.ts#L121)*

## Métodos de trabajo

### addSignature

- **addSignature**(`sig`: [Firma):](common_signature.signature.md) *número*

*Heredada de [Credential](common_signature.credential.md).[addSignature](common_signature.credential.md#addsignature)*

*Definido en [src/común/credenciales.ts:135](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/credentials.ts#L135)*

Añade una firma a las credenciales y devuelve el índice de la firma añadida.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `sig` | [Firma](common_signature.signature.md) |

**Retornos:** *número*

___

### clon

- **clone**(): *esto*

*Superaciones [Credential](common_signature.credential.md).[clone](common_signature.credential.md#abstract-clone)*

*Definido en [src/apis/avm/credenciales.ts:52](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/credentials.ts#L52)*

**Returns:** *esto*

___

### crear un entorno de creación

*-* **create**(...`args`: []cualquiera

*Supera [Credential](common_signature.credential.md).[create](common_signature.credential.md#abstract-create)*

*Definido en [src/apis/avm/credenciales.ts:58](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/credentials.ts#L58)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `..args` | cualquier otra cosa que no sea[] |

**Returns:** *esto*

___

### deserie

- **deserialize**(`fields`: objeto, `codificación`: [SerializedEncoding](../modules/src_utils.md#serializedencoding)): *vacío*

*Heredada de [Credential](common_signature.credential.md).[deserialize](common_signature.credential.md#deserialize)*

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

*Heredada de [Credential](common_signature.credential.md).[fromBuffer](common_signature.credential.md#frombuffer)*

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

### getCredentialID

- **getCredentialID**(): *número*

*Superaciones [Credential.getCredentialID](common_signature.credential.md)[](common_signature.credential.md#abstract-getcredentialid)*

*Definido en [src/apis/avm/credenciales.ts:48](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/credentials.ts#L48)*

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

### seleccionar

- **select(id:**`` número, ...`args`: []select(id: *[Credencial](common_signature.credential.md)*

*Superaciones [Credential](common_signature.credential.md).[select](common_signature.credential.md#abstract-select)*

*Definido en [src/apis/avm/credenciales.ts:62](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/credentials.ts#L62)*

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio |
------ | ------ |
| `I.` | Número de números |
| `..args` | cualquier otra cosa que no sea[] |

**Retornos:** *[Credencial](common_signature.credential.md)*

___

### serializar

- **serialize**(`encoding`: [SerializedEncoding](../modules/src_utils.md#serializedencoding)): *objeto*

*Heredada de [Credential](common_signature.credential.md).[serialize](common_signature.credential.md#serialize)*

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

*Resources [Credential](common_signature.credential.md).[setCodecID](common_signature.credential.md#setcodecid)*

*Definido en [src/apis/avm/credenciales.ts:39](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/credentials.ts#L39)*

Configure el codecid

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `codecid` | Número de números | El codecid para configurar |

**Retornos:** *vacío*

___

### toBuffer

- **toBuffer** (): *Buffer*

*Heredada de [Credential](common_signature.credential.md).[toBuffer](common_signature.credential.md#tobuffer)*

*Definido en [src/común/credenciales.ts:152](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/common/credentials.ts#L152)*

**Returns:** *Buffer*
