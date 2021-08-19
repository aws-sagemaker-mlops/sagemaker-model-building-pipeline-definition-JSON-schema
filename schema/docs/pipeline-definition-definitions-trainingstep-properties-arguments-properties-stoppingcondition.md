# Untitled object in SageMaker Pipeline Definition JSON schema Schema

```txt
https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TrainingStep/properties/Arguments/properties/StoppingCondition
```



| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                           |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :--------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Forbidden             | none                | [pipeline-definition.schema.json*](../../out/pipeline-definition.schema.json "open original schema") |

## StoppingCondition Type

`object` ([Details](pipeline-definition-definitions-trainingstep-properties-arguments-properties-stoppingcondition.md))

# StoppingCondition Properties

| Property                                      | Type   | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                           |
| :-------------------------------------------- | :----- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [MaxRuntimeInSeconds](#maxruntimeinseconds)   | Merged | Optional | cannot be null | [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-integerargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TrainingStep/properties/Arguments/properties/StoppingCondition/properties/MaxRuntimeInSeconds")  |
| [MaxWaitTimeInSeconds](#maxwaittimeinseconds) | Merged | Optional | cannot be null | [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-integerargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TrainingStep/properties/Arguments/properties/StoppingCondition/properties/MaxWaitTimeInSeconds") |

## MaxRuntimeInSeconds



`MaxRuntimeInSeconds`

*   is optional

*   Type: merged type ([Details](pipeline-definition-definitions-integerargumentvalue.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-integerargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TrainingStep/properties/Arguments/properties/StoppingCondition/properties/MaxRuntimeInSeconds")

### MaxRuntimeInSeconds Type

merged type ([Details](pipeline-definition-definitions-integerargumentvalue.md))

one (and only one) of

*   [Untitled integer in SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-integerargumentvalue-oneof-0.md "check type definition")

*   [Untitled object in SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-getfunction.md "check type definition")

## MaxWaitTimeInSeconds



`MaxWaitTimeInSeconds`

*   is optional

*   Type: merged type ([Details](pipeline-definition-definitions-integerargumentvalue.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-integerargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TrainingStep/properties/Arguments/properties/StoppingCondition/properties/MaxWaitTimeInSeconds")

### MaxWaitTimeInSeconds Type

merged type ([Details](pipeline-definition-definitions-integerargumentvalue.md))

one (and only one) of

*   [Untitled integer in SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-integerargumentvalue-oneof-0.md "check type definition")

*   [Untitled object in SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-getfunction.md "check type definition")
