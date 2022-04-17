## WarmStartConfig Type

`object` ([Details](pipeline-definition-definitions-tuningstep-properties-arguments-properties-warmstartconfig.md))

# WarmStartConfig Properties

| Property                                                          | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                                                                                                     |
| :---------------------------------------------------------------- | :------- | :------- | :------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [ParentHyperParameterTuningJobs](#parenthyperparametertuningjobs) | `array`  | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-tuningstep-properties-arguments-properties-warmstartconfig-properties-parenthyperparametertuningjobs.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TuningStep/properties/Arguments/properties/WarmStartConfig/properties/ParentHyperParameterTuningJobs") |
| [WarmStartType](#warmstarttype)                                   | `string` | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-tuningstep-properties-arguments-properties-warmstartconfig-properties-warmstarttype.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TuningStep/properties/Arguments/properties/WarmStartConfig/properties/WarmStartType")                                   |

## ParentHyperParameterTuningJobs



`ParentHyperParameterTuningJobs`

*   is optional

*   Type: `object[]` ([Details](pipeline-definition-definitions-tuningstep-properties-arguments-properties-warmstartconfig-properties-parenthyperparametertuningjobs-items.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-tuningstep-properties-arguments-properties-warmstartconfig-properties-parenthyperparametertuningjobs.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TuningStep/properties/Arguments/properties/WarmStartConfig/properties/ParentHyperParameterTuningJobs")

### ParentHyperParameterTuningJobs Type

`object[]` ([Details](pipeline-definition-definitions-tuningstep-properties-arguments-properties-warmstartconfig-properties-parenthyperparametertuningjobs-items.md))

## WarmStartType



`WarmStartType`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-tuningstep-properties-arguments-properties-warmstartconfig-properties-warmstarttype.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TuningStep/properties/Arguments/properties/WarmStartConfig/properties/WarmStartType")

### WarmStartType Type

`string`

### WarmStartType Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                         | Explanation |
| :---------------------------- | :---------- |
| `"IdenticalDataAndAlgorithm"` |             |
| `"TransferLearning"`          |             |
