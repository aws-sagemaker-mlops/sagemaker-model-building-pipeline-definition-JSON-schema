## StepConfig Type

`object` ([Details](pipeline-definition-definitions-emrstep-properties-arguments-properties-stepconfig.md))

# StepConfig Properties

| Property                            | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                                                       |
| :---------------------------------- | :------- | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Name](#name)                       | Merged   | Required | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/EMRStep/properties/Arguments/properties/StepConfig/properties/Name")                                                                      |
| [HadoopJarStep](#hadoopjarstep)     | `object` | Required | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-emrstep-properties-arguments-properties-stepconfig-properties-hadoopjarstep.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/EMRStep/properties/Arguments/properties/StepConfig/properties/HadoopJarStep")     |
| [ActionOnFailure](#actiononfailure) | `string` | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-emrstep-properties-arguments-properties-stepconfig-properties-actiononfailure.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/EMRStep/properties/Arguments/properties/StepConfig/properties/ActionOnFailure") |

## Name



`Name`

*   is required

*   Type: merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/EMRStep/properties/Arguments/properties/StepConfig/properties/Name")

### Name Type

merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

one (and only one) of

*   [Untitled string in SageMaker Pipeline Definition](pipeline-definition-definitions-stringargumentvalue-oneof-0.md "check type definition")

*   [Untitled object in SageMaker Pipeline Definition](pipeline-definition-definitions-getfunction.md "check type definition")

## HadoopJarStep



`HadoopJarStep`

*   is required

*   Type: `object` ([Details](pipeline-definition-definitions-emrstep-properties-arguments-properties-stepconfig-properties-hadoopjarstep.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-emrstep-properties-arguments-properties-stepconfig-properties-hadoopjarstep.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/EMRStep/properties/Arguments/properties/StepConfig/properties/HadoopJarStep")

### HadoopJarStep Type

`object` ([Details](pipeline-definition-definitions-emrstep-properties-arguments-properties-stepconfig-properties-hadoopjarstep.md))

## ActionOnFailure



`ActionOnFailure`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-emrstep-properties-arguments-properties-stepconfig-properties-actiononfailure.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/EMRStep/properties/Arguments/properties/StepConfig/properties/ActionOnFailure")

### ActionOnFailure Type

`string`

### ActionOnFailure Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                  | Explanation |
| :--------------------- | :---------- |
| `"TERMINATE_JOB_FLOW"` |             |
| `"TERMINATE_CLUSTER"`  |             |
| `"CANCEL_AND_WAIT"`    |             |
| `"CONTINUE"`           |             |
