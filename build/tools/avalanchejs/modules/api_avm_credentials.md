[avalancha](../README.md) › [API-AVM-Credentials](api_avm_credentials.md)

# Módulo de Credenciales API-AVM-Credentials

## Índice de participación

### Clases de tipo

* [NFTCredential](../classes/api_avm_credentials.nftcredential.md)
* [SECPCredential](../classes/api_avm_credentials.secpcredential.md)

### Funciones de las Naciones Unidas

* [SelectCredentialClass](api_avm_credentials.md#const-selectcredentialclass)

## Funciones de las Naciones Unidas

### `Const` SelectCredentialClass

- **SelectCredentialClass(credid:**`` número, ..`args`: []SelectCredentialClass(credid: *[Credencial](../classes/common_signature.credential.md)*

*Definido en [src/apis/avm/credenciales.ts:17](https://github.com/ava-labs/avalanchejs/blob/ae78dee/src/apis/avm/credentials.ts#L17)*

Toma un buffer que representa la credencial y devuelve la instancia [de Credencial](../classes/common_signature.credential.md) adecuada.

**Parámetros:**

| Nombre del nombre de la empresa | Tipo de cambio | Descripción |
------ | ------ | ------ |
| `credo` | Número de números | Un número que representa el ID de credencial analizado antes de los bytes pasados en |
| `..args` | cualquier otra cosa que no sea[] | - |

**Retornos:** *[Credencial](../classes/common_signature.credential.md)*

Una instancia de una clase [de extensión](../classes/common_signature.credential.md) credencial.
