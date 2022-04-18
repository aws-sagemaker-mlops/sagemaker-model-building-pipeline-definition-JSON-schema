## HyperParameterTuningJobConfig Type

`object` ([Details](pipeline-definition-definitions-tuningstep-properties-arguments-properties-hyperparametertuningjobconfig.md))

# HyperParameterTuningJobConfig Properties

| Property                                                              | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                                                                                                                                            |
| :-------------------------------------------------------------------- | :------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [HyperParameterTuningJobObjective](#hyperparametertuningjobobjective) | `object` | Optional | cannot be null | [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-tuningstep-properties-arguments-properties-hyperparametertuningjobconfig-properties-hyperparametertuningjobobjective.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TuningStep/properties/Arguments/properties/HyperParameterTuningJobConfig/properties/HyperParameterTuningJobObjective") |
| [ParameterRanges](#parameterranges)                                   | `object` | Optional | cannot be null | [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-parameterranges.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TuningStep/properties/Arguments/properties/HyperParameterTuningJobConfig/properties/ParameterRanges")                                                                                                                       |
| [ResourceLimits](#resourcelimits)                                     | `object` | Required | cannot be null | [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-tuningstep-properties-arguments-properties-hyperparametertuningjobconfig-properties-resourcelimits.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TuningStep/properties/Arguments/properties/HyperParameterTuningJobConfig/properties/ResourceLimits")                                     |
| [Strategy](#strategy)                                                 | `string` | Required | cannot be null | [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-tuningstep-properties-arguments-properties-hyperparametertuningjobconfig-properties-strategy.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TuningStep/properties/Arguments/properties/HyperParameterTuningJobConfig/properties/Strategy")                                                 |
| [TrainingJobEarlyStoppingType](#trainingjobearlystoppingtype)         | `string` | Optional | cannot be null | [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-tuningstep-properties-arguments-properties-hyperparametertuningjobconfig-properties-trainingjobearlystoppingtype.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TuningStep/properties/Arguments/properties/HyperParameterTuningJobConfig/properties/TrainingJobEarlyStoppingType")         |
| [TuningJobCompletionCriteria](#tuningjobcompletioncriteria)           | `object` | Optional | cannot be null | [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-tuningstep-properties-arguments-properties-hyperparametertuningjobconfig-properties-tuningjobcompletioncriteria.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TuningStep/properties/Arguments/properties/HyperParameterTuningJobConfig/properties/TuningJobCompletionCriteria")           |

## HyperParameterTuningJobObjective



`HyperParameterTuningJobObjective`

*   is optional

*   Type: `object` ([Details](pipeline-definition-definitions-tuningstep-properties-arguments-properties-hyperparametertuningjobconfig-properties-hyperparametertuningjobobjective.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-tuningstep-properties-arguments-properties-hyperparametertuningjobconfig-properties-hyperparametertuningjobobjective.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TuningStep/properties/Arguments/properties/HyperParameterTuningJobConfig/properties/HyperParameterTuningJobObjective")

### HyperParameterTuningJobObjective Type

`object` ([Details](pipeline-definition-definitions-tuningstep-properties-arguments-properties-hyperparametertuningjobconfig-properties-hyperparametertuningjobobjective.md))

## ParameterRanges



`ParameterRanges`

*   is optional

*   Type: `object` ([Details](pipeline-definition-definitions-parameterranges.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-parameterranges.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TuningStep/properties/Arguments/properties/HyperParameterTuningJobConfig/properties/ParameterRanges")

### ParameterRanges Type

`object` ([Details](pipeline-definition-definitions-parameterranges.md))

## ResourceLimits



`ResourceLimits`

*   is required

*   Type: `object` ([Details](pipeline-definition-definitions-tuningstep-properties-arguments-properties-hyperparametertuningjobconfig-properties-resourcelimits.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-tuningstep-properties-arguments-properties-hyperparametertuningjobconfig-properties-resourcelimits.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TuningStep/properties/Arguments/properties/HyperParameterTuningJobConfig/properties/ResourceLimits")

### ResourceLimits Type

`object` ([Details](pipeline-definition-definitions-tuningstep-properties-arguments-properties-hyperparametertuningjobconfig-properties-resourcelimits.md))

## Strategy



`Strategy`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-tuningstep-properties-arguments-properties-hyperparametertuningjobconfig-properties-strategy.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TuningStep/properties/Arguments/properties/HyperParameterTuningJobConfig/properties/Strategy")

### Strategy Type

`string`

### Strategy Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value        | Explanation |
| :----------- | :---------- |
| `"Bayesian"` |             |
| `"Random"`   |             |

## TrainingJobEarlyStoppingType



`TrainingJobEarlyStoppingType`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-tuningstep-properties-arguments-properties-hyperparametertuningjobconfig-properties-trainingjobearlystoppingtype.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TuningStep/properties/Arguments/properties/HyperParameterTuningJobConfig/properties/TrainingJobEarlyStoppingType")

### TrainingJobEarlyStoppingType Type

`string`

### TrainingJobEarlyStoppingType Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value    | Explanation |
| :------- | :---------- |
| `"Off"`  |             |
| `"Auto"` |             |

## TuningJobCompletionCriteria



`TuningJobCompletionCriteria`

*   is optional

*   Type: `object` ([Details](pipeline-definition-definitions-tuningstep-properties-arguments-properties-hyperparametertuningjobconfig-properties-tuningjobcompletioncriteria.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-tuningstep-properties-arguments-properties-hyperparametertuningjobconfig-properties-tuningjobcompletioncriteria.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TuningStep/properties/Arguments/properties/HyperParameterTuningJobConfig/properties/TuningJobCompletionCriteria")

### TuningJobCompletionCriteria Type

`object` ([Details](pipeline-definition-definitions-tuningstep-properties-arguments-properties-hyperparametertuningjobconfig-properties-tuningjobcompletioncriteria.md))
