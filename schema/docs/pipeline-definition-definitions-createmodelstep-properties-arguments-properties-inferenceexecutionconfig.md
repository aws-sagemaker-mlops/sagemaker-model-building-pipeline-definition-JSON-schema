## InferenceExecutionConfig Type

`object` ([Details](pipeline-definition-definitions-createmodelstep-properties-arguments-properties-inferenceexecutionconfig.md))

# InferenceExecutionConfig Properties

| Property      | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                                                                                    |
| :------------ | :------- | :------- | :------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Mode](#mode) | `string` | Optional | cannot be null | [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-createmodelstep-properties-arguments-properties-inferenceexecutionconfig-properties-mode.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/CreateModelStep/properties/Arguments/properties/InferenceExecutionConfig/properties/Mode") |

## Mode



`Mode`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-createmodelstep-properties-arguments-properties-inferenceexecutionconfig-properties-mode.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/CreateModelStep/properties/Arguments/properties/InferenceExecutionConfig/properties/Mode")

### Mode Type

`string`

### Mode Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value      | Explanation |
| :--------- | :---------- |
| `"Serial"` |             |
| `"Direct"` |             |
