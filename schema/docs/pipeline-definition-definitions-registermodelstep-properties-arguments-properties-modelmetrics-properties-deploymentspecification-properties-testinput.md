# Untitled object in SageMaker Pipeline Definition JSON schema Schema

```txt
https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/RegisterModelStep/properties/Arguments/properties/ModelMetrics/properties/DeploymentSpecification/properties/TestInput
```



| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                           |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :--------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Forbidden             | none                | [pipeline-definition.schema.json*](../../out/pipeline-definition.schema.json "open original schema") |

## TestInput Type

`object` ([Details](pipeline-definition-definitions-registermodelstep-properties-arguments-properties-modelmetrics-properties-deploymentspecification-properties-testinput.md))

# TestInput Properties

| Property                            | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| :---------------------------------- | :------- | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [CompressionType](#compressiontype) | Merged   | Optional | cannot be null | [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/RegisterModelStep/properties/Arguments/properties/ModelMetrics/properties/DeploymentSpecification/properties/TestInput/properties/CompressionType")                                                                                                                     |
| [ContentType](#contenttype)         | Merged   | Optional | cannot be null | [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/RegisterModelStep/properties/Arguments/properties/ModelMetrics/properties/DeploymentSpecification/properties/TestInput/properties/ContentType")                                                                                                                         |
| [DataSource](#datasource)           | `object` | Optional | cannot be null | [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-registermodelstep-properties-arguments-properties-modelmetrics-properties-deploymentspecification-properties-testinput-properties-datasource.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/RegisterModelStep/properties/Arguments/properties/ModelMetrics/properties/DeploymentSpecification/properties/TestInput/properties/DataSource") |
| [SplitType](#splittype)             | Merged   | Optional | cannot be null | [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/RegisterModelStep/properties/Arguments/properties/ModelMetrics/properties/DeploymentSpecification/properties/TestInput/properties/SplitType")                                                                                                                           |

## CompressionType



`CompressionType`

*   is optional

*   Type: merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/RegisterModelStep/properties/Arguments/properties/ModelMetrics/properties/DeploymentSpecification/properties/TestInput/properties/CompressionType")

### CompressionType Type

merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

one (and only one) of

*   [Untitled string in SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-stringargumentvalue-oneof-0.md "check type definition")

*   [Untitled object in SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-getfunction.md "check type definition")

## ContentType



`ContentType`

*   is optional

*   Type: merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/RegisterModelStep/properties/Arguments/properties/ModelMetrics/properties/DeploymentSpecification/properties/TestInput/properties/ContentType")

### ContentType Type

merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

one (and only one) of

*   [Untitled string in SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-stringargumentvalue-oneof-0.md "check type definition")

*   [Untitled object in SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-getfunction.md "check type definition")

## DataSource



`DataSource`

*   is optional

*   Type: `object` ([Details](pipeline-definition-definitions-registermodelstep-properties-arguments-properties-modelmetrics-properties-deploymentspecification-properties-testinput-properties-datasource.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-registermodelstep-properties-arguments-properties-modelmetrics-properties-deploymentspecification-properties-testinput-properties-datasource.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/RegisterModelStep/properties/Arguments/properties/ModelMetrics/properties/DeploymentSpecification/properties/TestInput/properties/DataSource")

### DataSource Type

`object` ([Details](pipeline-definition-definitions-registermodelstep-properties-arguments-properties-modelmetrics-properties-deploymentspecification-properties-testinput-properties-datasource.md))

## SplitType



`SplitType`

*   is optional

*   Type: merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/RegisterModelStep/properties/Arguments/properties/ModelMetrics/properties/DeploymentSpecification/properties/TestInput/properties/SplitType")

### SplitType Type

merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

one (and only one) of

*   [Untitled string in SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-stringargumentvalue-oneof-0.md "check type definition")

*   [Untitled object in SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-getfunction.md "check type definition")
