## MultiModelConfig Type

`object` ([Details](pipeline-definition-definitions-containerdefinition-properties-multimodelconfig.md))

# MultiModelConfig Properties

| Property                                | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                                                     |
| :-------------------------------------- | :------- | :------- | :------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [ModelCacheSetting](#modelcachesetting) | `string` | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-containerdefinition-properties-multimodelconfig-properties-modelcachesetting.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ContainerDefinition/properties/MultiModelConfig/properties/ModelCacheSetting") |

## ModelCacheSetting



`ModelCacheSetting`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-containerdefinition-properties-multimodelconfig-properties-modelcachesetting.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ContainerDefinition/properties/MultiModelConfig/properties/ModelCacheSetting")

### ModelCacheSetting Type

`string`

### ModelCacheSetting Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value        | Explanation |
| :----------- | :---------- |
| `"Enabled"`  |             |
| `"Disabled"` |             |
