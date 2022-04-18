## Arguments Type

`object` ([Details](pipeline-definition-definitions-createmodelstep-properties-arguments.md))

# Arguments Properties

| Property                                              | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                                                    |
| :---------------------------------------------------- | :------- | :------- | :------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Containers](#containers)                             | `array`  | Optional | cannot be null | [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-createmodelstep-properties-arguments-properties-containers.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/CreateModelStep/properties/Arguments/properties/Containers")                             |
| [EnableNetworkIsolation](#enablenetworkisolation)     | Merged   | Optional | cannot be null | [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-booleanargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/CreateModelStep/properties/Arguments/properties/EnableNetworkIsolation")                                                       |
| [ExecutionRoleArn](#executionrolearn)                 | Merged   | Required | cannot be null | [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/CreateModelStep/properties/Arguments/properties/ExecutionRoleArn")                                                              |
| [InferenceExecutionConfig](#inferenceexecutionconfig) | `object` | Optional | cannot be null | [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-createmodelstep-properties-arguments-properties-inferenceexecutionconfig.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/CreateModelStep/properties/Arguments/properties/InferenceExecutionConfig") |
| [PrimaryContainer](#primarycontainer)                 | `object` | Optional | cannot be null | [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-containerdefinition.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/CreateModelStep/properties/Arguments/properties/PrimaryContainer")                                                              |
| [Tags](#tags)                                         | `array`  | Optional | cannot be null | [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-createmodelstep-properties-arguments-properties-tags.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/CreateModelStep/properties/Arguments/properties/Tags")                                         |
| [VpcConfig](#vpcconfig)                               | `object` | Optional | cannot be null | [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-createmodelstep-properties-arguments-properties-vpcconfig.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/CreateModelStep/properties/Arguments/properties/VpcConfig")                               |

## Containers



`Containers`

*   is optional

*   Type: `object[]` ([Details](pipeline-definition-definitions-containerdefinition.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-createmodelstep-properties-arguments-properties-containers.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/CreateModelStep/properties/Arguments/properties/Containers")

### Containers Type

`object[]` ([Details](pipeline-definition-definitions-containerdefinition.md))

## EnableNetworkIsolation



`EnableNetworkIsolation`

*   is optional

*   Type: merged type ([Details](pipeline-definition-definitions-booleanargumentvalue.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-booleanargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/CreateModelStep/properties/Arguments/properties/EnableNetworkIsolation")

### EnableNetworkIsolation Type

merged type ([Details](pipeline-definition-definitions-booleanargumentvalue.md))

one (and only one) of

*   [Untitled boolean in SageMaker Pipeline Definition Schema](pipeline-definition-definitions-booleanargumentvalue-oneof-0.md "check type definition")

*   [Untitled object in SageMaker Pipeline Definition Schema](pipeline-definition-definitions-getfunction.md "check type definition")

## ExecutionRoleArn



`ExecutionRoleArn`

*   is required

*   Type: merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/CreateModelStep/properties/Arguments/properties/ExecutionRoleArn")

### ExecutionRoleArn Type

merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

one (and only one) of

*   [Untitled string in SageMaker Pipeline Definition Schema](pipeline-definition-definitions-stringargumentvalue-oneof-0.md "check type definition")

*   [Untitled object in SageMaker Pipeline Definition Schema](pipeline-definition-definitions-getfunction.md "check type definition")

## InferenceExecutionConfig



`InferenceExecutionConfig`

*   is optional

*   Type: `object` ([Details](pipeline-definition-definitions-createmodelstep-properties-arguments-properties-inferenceexecutionconfig.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-createmodelstep-properties-arguments-properties-inferenceexecutionconfig.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/CreateModelStep/properties/Arguments/properties/InferenceExecutionConfig")

### InferenceExecutionConfig Type

`object` ([Details](pipeline-definition-definitions-createmodelstep-properties-arguments-properties-inferenceexecutionconfig.md))

## PrimaryContainer



`PrimaryContainer`

*   is optional

*   Type: `object` ([Details](pipeline-definition-definitions-containerdefinition.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-containerdefinition.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/CreateModelStep/properties/Arguments/properties/PrimaryContainer")

### PrimaryContainer Type

`object` ([Details](pipeline-definition-definitions-containerdefinition.md))

## Tags



`Tags`

*   is optional

*   Type: `object[]` ([Details](pipeline-definition-definitions-tag.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-createmodelstep-properties-arguments-properties-tags.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/CreateModelStep/properties/Arguments/properties/Tags")

### Tags Type

`object[]` ([Details](pipeline-definition-definitions-tag.md))

## VpcConfig



`VpcConfig`

*   is optional

*   Type: `object` ([Details](pipeline-definition-definitions-createmodelstep-properties-arguments-properties-vpcconfig.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-createmodelstep-properties-arguments-properties-vpcconfig.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/CreateModelStep/properties/Arguments/properties/VpcConfig")

### VpcConfig Type

`object` ([Details](pipeline-definition-definitions-createmodelstep-properties-arguments-properties-vpcconfig.md))
