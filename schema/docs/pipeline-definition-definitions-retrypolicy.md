## items Type

`object` ([Details](pipeline-definition-definitions-retrypolicy.md))

# items Properties

| Property                            | Type      | Required | Nullable       | Defined by                                                                                                                                                                                                                                                         |
| :---------------------------------- | :-------- | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [ExceptionType](#exceptiontype)     | `string`  | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-retrypolicy-properties-exceptiontype.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/RetryPolicy/properties/ExceptionType")     |
| [IntervalSeconds](#intervalseconds) | `integer` | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-retrypolicy-properties-intervalseconds.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/RetryPolicy/properties/IntervalSeconds") |
| [BackoffRate](#backoffrate)         | `number`  | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-retrypolicy-properties-backoffrate.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/RetryPolicy/properties/BackoffRate")         |
| [ExpireAfterMin](#expireaftermin)   | `integer` | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-retrypolicy-properties-expireaftermin.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/RetryPolicy/properties/ExpireAfterMin")   |
| [MaxAttempts](#maxattempts)         | `integer` | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-retrypolicy-properties-maxattempts.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/RetryPolicy/properties/MaxAttempts")         |

## ExceptionType



`ExceptionType`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-retrypolicy-properties-exceptiontype.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/RetryPolicy/properties/ExceptionType")

### ExceptionType Type

`string`

### ExceptionType Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                            | Explanation |
| :------------------------------- | :---------- |
| `"Step.SERVICE_FAULT"`           |             |
| `"Step.THROTTLING"`              |             |
| `"SageMaker.JOB_INTERNAL_ERROR"` |             |
| `"SageMaker.CAPACITY_ERROR"`     |             |
| `"SageMaker.RESOURCE_LIMIT"`     |             |
| `"Emr.RESOURCE_LIMIT"`           |             |

## IntervalSeconds



`IntervalSeconds`

*   is optional

*   Type: `integer`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-retrypolicy-properties-intervalseconds.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/RetryPolicy/properties/IntervalSeconds")

### IntervalSeconds Type

`integer`

## BackoffRate



`BackoffRate`

*   is optional

*   Type: `number`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-retrypolicy-properties-backoffrate.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/RetryPolicy/properties/BackoffRate")

### BackoffRate Type

`number`

## ExpireAfterMin



`ExpireAfterMin`

*   is optional

*   Type: `integer`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-retrypolicy-properties-expireaftermin.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/RetryPolicy/properties/ExpireAfterMin")

### ExpireAfterMin Type

`integer`

## MaxAttempts



`MaxAttempts`

*   is optional

*   Type: `integer`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-retrypolicy-properties-maxattempts.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/RetryPolicy/properties/MaxAttempts")

### MaxAttempts Type

`integer`
