## ImageConfig Type

`object` ([Details](pipeline-definition-definitions-containerdefinition-properties-imageconfig.md))

# ImageConfig Properties

| Property                                      | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                                                        |
| :-------------------------------------------- | :------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [RepositoryAccessMode](#repositoryaccessmode) | `string` | Required | cannot be null | [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-containerdefinition-properties-imageconfig-properties-repositoryaccessmode.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ContainerDefinition/properties/ImageConfig/properties/RepositoryAccessMode") |
| [RepositoryAuthConfig](#repositoryauthconfig) | `object` | Optional | cannot be null | [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-containerdefinition-properties-imageconfig-properties-repositoryauthconfig.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ContainerDefinition/properties/ImageConfig/properties/RepositoryAuthConfig") |

## RepositoryAccessMode



`RepositoryAccessMode`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-containerdefinition-properties-imageconfig-properties-repositoryaccessmode.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ContainerDefinition/properties/ImageConfig/properties/RepositoryAccessMode")

### RepositoryAccessMode Type

`string`

### RepositoryAccessMode Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value        | Explanation |
| :----------- | :---------- |
| `"Platform"` |             |
| `"Vpc"`      |             |

## RepositoryAuthConfig



`RepositoryAuthConfig`

*   is optional

*   Type: `object` ([Details](pipeline-definition-definitions-containerdefinition-properties-imageconfig-properties-repositoryauthconfig.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-containerdefinition-properties-imageconfig-properties-repositoryauthconfig.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ContainerDefinition/properties/ImageConfig/properties/RepositoryAuthConfig")

### RepositoryAuthConfig Type

`object` ([Details](pipeline-definition-definitions-containerdefinition-properties-imageconfig-properties-repositoryauthconfig.md))
