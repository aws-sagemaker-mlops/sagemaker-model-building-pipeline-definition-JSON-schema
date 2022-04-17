## HyperParameterTuningJobObjective Type

`object` ([Details](pipeline-definition-definitions-tuningstep-properties-arguments-properties-hyperparametertuningjobconfig-properties-hyperparametertuningjobobjective.md))

# HyperParameterTuningJobObjective Properties

| Property                  | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| :------------------------ | :------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [MetricName](#metricname) | Merged   | Required | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TuningStep/properties/Arguments/properties/HyperParameterTuningJobConfig/properties/HyperParameterTuningJobObjective/properties/MetricName")                                                                                                            |
| [Type](#type)             | `string` | Required | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-tuningstep-properties-arguments-properties-hyperparametertuningjobconfig-properties-hyperparametertuningjobobjective-properties-type.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TuningStep/properties/Arguments/properties/HyperParameterTuningJobConfig/properties/HyperParameterTuningJobObjective/properties/Type") |

## MetricName



`MetricName`

*   is required

*   Type: merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TuningStep/properties/Arguments/properties/HyperParameterTuningJobConfig/properties/HyperParameterTuningJobObjective/properties/MetricName")

### MetricName Type

merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

one (and only one) of

*   [Untitled string in SageMaker Pipeline Definition](pipeline-definition-definitions-stringargumentvalue-oneof-0.md "check type definition")

*   [Untitled object in SageMaker Pipeline Definition](pipeline-definition-definitions-getfunction.md "check type definition")

## Type



`Type`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-tuningstep-properties-arguments-properties-hyperparametertuningjobconfig-properties-hyperparametertuningjobobjective-properties-type.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TuningStep/properties/Arguments/properties/HyperParameterTuningJobConfig/properties/HyperParameterTuningJobObjective/properties/Type")

### Type Type

`string`

### Type Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value        | Explanation |
| :----------- | :---------- |
| `"Maximize"` |             |
| `"Minimize"` |             |
