## Arguments Type

`object` ([Details](pipeline-definition-definitions-tuningstep-properties-arguments.md))

# Arguments Properties

| Property                                                        | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                                             |
| :-------------------------------------------------------------- | :------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [HyperParameterTuningJobConfig](#hyperparametertuningjobconfig) | `object` | Required | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-tuningstep-properties-arguments-properties-hyperparametertuningjobconfig.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TuningStep/properties/Arguments/properties/HyperParameterTuningJobConfig") |
| [Tags](#tags)                                                   | `array`  | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-tuningstep-properties-arguments-properties-tags.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TuningStep/properties/Arguments/properties/Tags")                                                   |
| [TrainingJobDefinition](#trainingjobdefinition)                 | `object` | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-hyperparametertrainingjobdefinition.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TuningStep/properties/Arguments/properties/TrainingJobDefinition")                                              |
| [TrainingJobDefinitions](#trainingjobdefinitions)               | `array`  | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-tuningstep-properties-arguments-properties-trainingjobdefinitions.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TuningStep/properties/Arguments/properties/TrainingJobDefinitions")               |
| [WarmStartConfig](#warmstartconfig)                             | `object` | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-tuningstep-properties-arguments-properties-warmstartconfig.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TuningStep/properties/Arguments/properties/WarmStartConfig")                             |

## HyperParameterTuningJobConfig



`HyperParameterTuningJobConfig`

*   is required

*   Type: `object` ([Details](pipeline-definition-definitions-tuningstep-properties-arguments-properties-hyperparametertuningjobconfig.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-tuningstep-properties-arguments-properties-hyperparametertuningjobconfig.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TuningStep/properties/Arguments/properties/HyperParameterTuningJobConfig")

### HyperParameterTuningJobConfig Type

`object` ([Details](pipeline-definition-definitions-tuningstep-properties-arguments-properties-hyperparametertuningjobconfig.md))

## Tags



`Tags`

*   is optional

*   Type: `object[]` ([Details](pipeline-definition-definitions-tag.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-tuningstep-properties-arguments-properties-tags.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TuningStep/properties/Arguments/properties/Tags")

### Tags Type

`object[]` ([Details](pipeline-definition-definitions-tag.md))

## TrainingJobDefinition



`TrainingJobDefinition`

*   is optional

*   Type: `object` ([Details](pipeline-definition-definitions-hyperparametertrainingjobdefinition.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-hyperparametertrainingjobdefinition.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TuningStep/properties/Arguments/properties/TrainingJobDefinition")

### TrainingJobDefinition Type

`object` ([Details](pipeline-definition-definitions-hyperparametertrainingjobdefinition.md))

## TrainingJobDefinitions



`TrainingJobDefinitions`

*   is optional

*   Type: `object[]` ([Details](pipeline-definition-definitions-hyperparametertrainingjobdefinition.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-tuningstep-properties-arguments-properties-trainingjobdefinitions.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TuningStep/properties/Arguments/properties/TrainingJobDefinitions")

### TrainingJobDefinitions Type

`object[]` ([Details](pipeline-definition-definitions-hyperparametertrainingjobdefinition.md))

### TrainingJobDefinitions Constraints

**maximum number of items**: the maximum number of items for this array is: `10`

**minimum number of items**: the minimum number of items for this array is: `0`

## WarmStartConfig



`WarmStartConfig`

*   is optional

*   Type: `object` ([Details](pipeline-definition-definitions-tuningstep-properties-arguments-properties-warmstartconfig.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-tuningstep-properties-arguments-properties-warmstartconfig.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TuningStep/properties/Arguments/properties/WarmStartConfig")

### WarmStartConfig Type

`object` ([Details](pipeline-definition-definitions-tuningstep-properties-arguments-properties-warmstartconfig.md))
