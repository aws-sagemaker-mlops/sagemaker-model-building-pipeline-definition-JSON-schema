# Untitled object in SageMaker Pipeline Definition JSON schema Schema

```txt
https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/RegisterModelStep/properties/Arguments/properties/ModelMetrics/properties/DeploymentSpecification/properties/HealthCheckConfig
```



| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                           |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :--------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Forbidden             | none                | [pipeline-definition.schema.json*](../../out/pipeline-definition.schema.json "open original schema") |

## HealthCheckConfig Type

`object` ([Details](pipeline-definition-definitions-registermodelstep-properties-arguments-properties-modelmetrics-properties-deploymentspecification-properties-healthcheckconfig.md))

# HealthCheckConfig Properties

| Property                                  | Type   | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                                                                                         |
| :---------------------------------------- | :----- | :------- | :------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [NumPayloads](#numpayloads)               | Merged | Optional | cannot be null | [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-integerargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/RegisterModelStep/properties/Arguments/properties/ModelMetrics/properties/DeploymentSpecification/properties/HealthCheckConfig/properties/NumPayloads")        |
| [NumFailuresAllowed](#numfailuresallowed) | Merged | Optional | cannot be null | [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-integerargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/RegisterModelStep/properties/Arguments/properties/ModelMetrics/properties/DeploymentSpecification/properties/HealthCheckConfig/properties/NumFailuresAllowed") |

## NumPayloads



`NumPayloads`

*   is optional

*   Type: merged type ([Details](pipeline-definition-definitions-integerargumentvalue.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-integerargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/RegisterModelStep/properties/Arguments/properties/ModelMetrics/properties/DeploymentSpecification/properties/HealthCheckConfig/properties/NumPayloads")

### NumPayloads Type

merged type ([Details](pipeline-definition-definitions-integerargumentvalue.md))

one (and only one) of

*   [Untitled integer in SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-integerargumentvalue-oneof-0.md "check type definition")

*   [Untitled object in SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-getfunction.md "check type definition")

## NumFailuresAllowed



`NumFailuresAllowed`

*   is optional

*   Type: merged type ([Details](pipeline-definition-definitions-integerargumentvalue.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-integerargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/RegisterModelStep/properties/Arguments/properties/ModelMetrics/properties/DeploymentSpecification/properties/HealthCheckConfig/properties/NumFailuresAllowed")

### NumFailuresAllowed Type

merged type ([Details](pipeline-definition-definitions-integerargumentvalue.md))

one (and only one) of

*   [Untitled integer in SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-integerargumentvalue-oneof-0.md "check type definition")

*   [Untitled object in SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-getfunction.md "check type definition")
