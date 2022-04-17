## items Type

`object` ([Details](pipeline-definition-definitions-lambdastep-properties-outputparameters-items.md))

# items Properties

| Property                  | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                                 |
| :------------------------ | :------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [OutputName](#outputname) | Merged   | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/LambdaStep/properties/OutputParameters/items/properties/OutputName")                                                |
| [OutputType](#outputtype) | `string` | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-lambdastep-properties-outputparameters-items-properties-outputtype.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/LambdaStep/properties/OutputParameters/items/properties/OutputType") |

## OutputName



`OutputName`

*   is optional

*   Type: merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/LambdaStep/properties/OutputParameters/items/properties/OutputName")

### OutputName Type

merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

one (and only one) of

*   [Untitled string in SageMaker Pipeline Definition](pipeline-definition-definitions-stringargumentvalue-oneof-0.md "check type definition")

*   [Untitled object in SageMaker Pipeline Definition](pipeline-definition-definitions-getfunction.md "check type definition")

## OutputType



`OutputType`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-lambdastep-properties-outputparameters-items-properties-outputtype.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/LambdaStep/properties/OutputParameters/items/properties/OutputType")

### OutputType Type

`string`

### OutputType Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value       | Explanation |
| :---------- | :---------- |
| `"String"`  |             |
| `"Integer"` |             |
| `"Boolean"` |             |
| `"Float"`   |             |
