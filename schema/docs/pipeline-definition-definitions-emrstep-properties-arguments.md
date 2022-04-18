## Arguments Type

`object` ([Details](pipeline-definition-definitions-emrstep-properties-arguments.md))

# Arguments Properties

| Property                  | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                 |
| :------------------------ | :------- | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [ClusterId](#clusterid)   | Merged   | Required | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/EMRStep/properties/Arguments/properties/ClusterId")                                 |
| [StepConfig](#stepconfig) | `object` | Required | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-emrstep-properties-arguments-properties-stepconfig.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/EMRStep/properties/Arguments/properties/StepConfig") |

## ClusterId



`ClusterId`

*   is required

*   Type: merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/EMRStep/properties/Arguments/properties/ClusterId")

### ClusterId Type

merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

one (and only one) of

*   [Untitled string in SageMaker Pipeline Definition](pipeline-definition-definitions-stringargumentvalue-oneof-0.md "check type definition")

*   [Untitled object in SageMaker Pipeline Definition](pipeline-definition-definitions-getfunction.md "check type definition")

## StepConfig



`StepConfig`

*   is required

*   Type: `object` ([Details](pipeline-definition-definitions-emrstep-properties-arguments-properties-stepconfig.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-emrstep-properties-arguments-properties-stepconfig.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/EMRStep/properties/Arguments/properties/StepConfig")

### StepConfig Type

`object` ([Details](pipeline-definition-definitions-emrstep-properties-arguments-properties-stepconfig.md))
