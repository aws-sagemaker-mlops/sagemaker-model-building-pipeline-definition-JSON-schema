## Arguments Type

`object` ([Details](pipeline-definition-definitions-createmodelstep-properties-arguments.md))

# Arguments Properties

| Property                                          | Type    | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                 |
| :------------------------------------------------ | :------ | :------- | :------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Containers](#containers)                         | `array` | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-createmodelstep-properties-arguments-properties-containers.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/CreateModelStep/properties/Arguments/properties/Containers") |
| [EnableNetworkIsolation](#enablenetworkisolation) | Merged  | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-booleanargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/CreateModelStep/properties/Arguments/properties/EnableNetworkIsolation")                           |

## Containers



`Containers`

*   is optional

*   Type: `object[]` ([Details](pipeline-definition-definitions-createmodelstep-properties-arguments-properties-containers-items.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-createmodelstep-properties-arguments-properties-containers.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/CreateModelStep/properties/Arguments/properties/Containers")

### Containers Type

`object[]` ([Details](pipeline-definition-definitions-createmodelstep-properties-arguments-properties-containers-items.md))

## EnableNetworkIsolation



`EnableNetworkIsolation`

*   is optional

*   Type: merged type ([Details](pipeline-definition-definitions-booleanargumentvalue.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-booleanargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/CreateModelStep/properties/Arguments/properties/EnableNetworkIsolation")

### EnableNetworkIsolation Type

merged type ([Details](pipeline-definition-definitions-booleanargumentvalue.md))

one (and only one) of

*   [Untitled boolean in SageMaker Pipeline Definition](pipeline-definition-definitions-booleanargumentvalue-oneof-0.md "check type definition")

*   [Untitled object in SageMaker Pipeline Definition](pipeline-definition-definitions-getfunction.md "check type definition")
