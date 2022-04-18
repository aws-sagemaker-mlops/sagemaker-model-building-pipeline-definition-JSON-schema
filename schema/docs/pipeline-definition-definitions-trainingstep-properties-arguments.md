## Arguments Type

`object` ([Details](pipeline-definition-definitions-trainingstep-properties-arguments.md))

# Arguments Properties

| Property                                                                        | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                                            |
| :------------------------------------------------------------------------------ | :------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [AlgorithmSpecification](#algorithmspecification)                               | `object` | Optional | cannot be null | [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-trainingstep-properties-arguments-properties-algorithmspecification.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TrainingStep/properties/Arguments/properties/AlgorithmSpecification")   |
| [CheckpointConfig](#checkpointconfig)                                           | `object` | Optional | cannot be null | [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-trainingstep-properties-arguments-properties-checkpointconfig.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TrainingStep/properties/Arguments/properties/CheckpointConfig")               |
| [DebugHookConfig](#debughookconfig)                                             | `object` | Optional | cannot be null | [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-trainingstep-properties-arguments-properties-debughookconfig.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TrainingStep/properties/Arguments/properties/DebugHookConfig")                 |
| [DebugRuleConfigurations](#debugruleconfigurations)                             | `array`  | Optional | cannot be null | [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-trainingstep-properties-arguments-properties-debugruleconfigurations.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TrainingStep/properties/Arguments/properties/DebugRuleConfigurations") |
| [EnableInterContainerTrafficEncryption](#enableintercontainertrafficencryption) | Merged   | Optional | cannot be null | [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-booleanargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TrainingStep/properties/Arguments/properties/EnableInterContainerTrafficEncryption")                                   |
| [EnableManagedSpotTraining](#enablemanagedspottraining)                         | Merged   | Optional | cannot be null | [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-booleanargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TrainingStep/properties/Arguments/properties/EnableManagedSpotTraining")                                               |
| [EnableNetworkIsolation](#enablenetworkisolation)                               | Merged   | Optional | cannot be null | [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-booleanargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TrainingStep/properties/Arguments/properties/EnableNetworkIsolation")                                                  |
| [HyperParameters](#hyperparameters)                                             | `object` | Optional | cannot be null | [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-trainingstep-properties-arguments-properties-hyperparameters.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TrainingStep/properties/Arguments/properties/HyperParameters")                 |
| [InputDataConfig](#inputdataconfig)                                             | `array`  | Optional | cannot be null | [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-trainingstep-properties-arguments-properties-inputdataconfig.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TrainingStep/properties/Arguments/properties/InputDataConfig")                 |
| [OutputDataConfig](#outputdataconfig)                                           | `object` | Optional | cannot be null | [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-trainingstep-properties-arguments-properties-outputdataconfig.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TrainingStep/properties/Arguments/properties/OutputDataConfig")               |
| [ResourceConfig](#resourceconfig)                                               | `object` | Optional | cannot be null | [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-trainingstep-properties-arguments-properties-resourceconfig.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TrainingStep/properties/Arguments/properties/ResourceConfig")                   |
| [RoleArn](#rolearn)                                                             | Merged   | Optional | cannot be null | [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TrainingStep/properties/Arguments/properties/RoleArn")                                                                  |
| [StoppingCondition](#stoppingcondition)                                         | `object` | Optional | cannot be null | [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-trainingstep-properties-arguments-properties-stoppingcondition.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TrainingStep/properties/Arguments/properties/StoppingCondition")             |
| [Tags](#tags)                                                                   | `array`  | Optional | cannot be null | [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-trainingstep-properties-arguments-properties-tags.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TrainingStep/properties/Arguments/properties/Tags")                                       |
| [TensorBoardOutputConfig](#tensorboardoutputconfig)                             | `object` | Optional | cannot be null | [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-trainingstep-properties-arguments-properties-tensorboardoutputconfig.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TrainingStep/properties/Arguments/properties/TensorBoardOutputConfig") |
| [VpcConfig](#vpcconfig)                                                         | `object` | Optional | cannot be null | [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-trainingstep-properties-arguments-properties-vpcconfig.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TrainingStep/properties/Arguments/properties/VpcConfig")                             |

## AlgorithmSpecification



`AlgorithmSpecification`

*   is optional

*   Type: `object` ([Details](pipeline-definition-definitions-trainingstep-properties-arguments-properties-algorithmspecification.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-trainingstep-properties-arguments-properties-algorithmspecification.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TrainingStep/properties/Arguments/properties/AlgorithmSpecification")

### AlgorithmSpecification Type

`object` ([Details](pipeline-definition-definitions-trainingstep-properties-arguments-properties-algorithmspecification.md))

## CheckpointConfig



`CheckpointConfig`

*   is optional

*   Type: `object` ([Details](pipeline-definition-definitions-trainingstep-properties-arguments-properties-checkpointconfig.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-trainingstep-properties-arguments-properties-checkpointconfig.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TrainingStep/properties/Arguments/properties/CheckpointConfig")

### CheckpointConfig Type

`object` ([Details](pipeline-definition-definitions-trainingstep-properties-arguments-properties-checkpointconfig.md))

## DebugHookConfig



`DebugHookConfig`

*   is optional

*   Type: `object` ([Details](pipeline-definition-definitions-trainingstep-properties-arguments-properties-debughookconfig.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-trainingstep-properties-arguments-properties-debughookconfig.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TrainingStep/properties/Arguments/properties/DebugHookConfig")

### DebugHookConfig Type

`object` ([Details](pipeline-definition-definitions-trainingstep-properties-arguments-properties-debughookconfig.md))

## DebugRuleConfigurations



`DebugRuleConfigurations`

*   is optional

*   Type: `object[]` ([Details](pipeline-definition-definitions-trainingstep-properties-arguments-properties-debugruleconfigurations-items.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-trainingstep-properties-arguments-properties-debugruleconfigurations.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TrainingStep/properties/Arguments/properties/DebugRuleConfigurations")

### DebugRuleConfigurations Type

`object[]` ([Details](pipeline-definition-definitions-trainingstep-properties-arguments-properties-debugruleconfigurations-items.md))

## EnableInterContainerTrafficEncryption



`EnableInterContainerTrafficEncryption`

*   is optional

*   Type: merged type ([Details](pipeline-definition-definitions-booleanargumentvalue.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-booleanargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TrainingStep/properties/Arguments/properties/EnableInterContainerTrafficEncryption")

### EnableInterContainerTrafficEncryption Type

merged type ([Details](pipeline-definition-definitions-booleanargumentvalue.md))

one (and only one) of

*   [Untitled boolean in SageMaker Pipeline Definition Schema](pipeline-definition-definitions-booleanargumentvalue-oneof-0.md "check type definition")

*   [Untitled object in SageMaker Pipeline Definition Schema](pipeline-definition-definitions-getfunction.md "check type definition")

## EnableManagedSpotTraining



`EnableManagedSpotTraining`

*   is optional

*   Type: merged type ([Details](pipeline-definition-definitions-booleanargumentvalue.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-booleanargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TrainingStep/properties/Arguments/properties/EnableManagedSpotTraining")

### EnableManagedSpotTraining Type

merged type ([Details](pipeline-definition-definitions-booleanargumentvalue.md))

one (and only one) of

*   [Untitled boolean in SageMaker Pipeline Definition Schema](pipeline-definition-definitions-booleanargumentvalue-oneof-0.md "check type definition")

*   [Untitled object in SageMaker Pipeline Definition Schema](pipeline-definition-definitions-getfunction.md "check type definition")

## EnableNetworkIsolation



`EnableNetworkIsolation`

*   is optional

*   Type: merged type ([Details](pipeline-definition-definitions-booleanargumentvalue.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-booleanargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TrainingStep/properties/Arguments/properties/EnableNetworkIsolation")

### EnableNetworkIsolation Type

merged type ([Details](pipeline-definition-definitions-booleanargumentvalue.md))

one (and only one) of

*   [Untitled boolean in SageMaker Pipeline Definition Schema](pipeline-definition-definitions-booleanargumentvalue-oneof-0.md "check type definition")

*   [Untitled object in SageMaker Pipeline Definition Schema](pipeline-definition-definitions-getfunction.md "check type definition")

## HyperParameters



`HyperParameters`

*   is optional

*   Type: `object` ([Details](pipeline-definition-definitions-trainingstep-properties-arguments-properties-hyperparameters.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-trainingstep-properties-arguments-properties-hyperparameters.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TrainingStep/properties/Arguments/properties/HyperParameters")

### HyperParameters Type

`object` ([Details](pipeline-definition-definitions-trainingstep-properties-arguments-properties-hyperparameters.md))

## InputDataConfig



`InputDataConfig`

*   is optional

*   Type: `object[]` ([Details](pipeline-definition-definitions-trainingstep-properties-arguments-properties-inputdataconfig-items.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-trainingstep-properties-arguments-properties-inputdataconfig.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TrainingStep/properties/Arguments/properties/InputDataConfig")

### InputDataConfig Type

`object[]` ([Details](pipeline-definition-definitions-trainingstep-properties-arguments-properties-inputdataconfig-items.md))

## OutputDataConfig



`OutputDataConfig`

*   is optional

*   Type: `object` ([Details](pipeline-definition-definitions-trainingstep-properties-arguments-properties-outputdataconfig.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-trainingstep-properties-arguments-properties-outputdataconfig.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TrainingStep/properties/Arguments/properties/OutputDataConfig")

### OutputDataConfig Type

`object` ([Details](pipeline-definition-definitions-trainingstep-properties-arguments-properties-outputdataconfig.md))

## ResourceConfig



`ResourceConfig`

*   is optional

*   Type: `object` ([Details](pipeline-definition-definitions-trainingstep-properties-arguments-properties-resourceconfig.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-trainingstep-properties-arguments-properties-resourceconfig.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TrainingStep/properties/Arguments/properties/ResourceConfig")

### ResourceConfig Type

`object` ([Details](pipeline-definition-definitions-trainingstep-properties-arguments-properties-resourceconfig.md))

## RoleArn



`RoleArn`

*   is optional

*   Type: merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TrainingStep/properties/Arguments/properties/RoleArn")

### RoleArn Type

merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

one (and only one) of

*   [Untitled string in SageMaker Pipeline Definition Schema](pipeline-definition-definitions-stringargumentvalue-oneof-0.md "check type definition")

*   [Untitled object in SageMaker Pipeline Definition Schema](pipeline-definition-definitions-getfunction.md "check type definition")

## StoppingCondition



`StoppingCondition`

*   is optional

*   Type: `object` ([Details](pipeline-definition-definitions-trainingstep-properties-arguments-properties-stoppingcondition.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-trainingstep-properties-arguments-properties-stoppingcondition.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TrainingStep/properties/Arguments/properties/StoppingCondition")

### StoppingCondition Type

`object` ([Details](pipeline-definition-definitions-trainingstep-properties-arguments-properties-stoppingcondition.md))

## Tags



`Tags`

*   is optional

*   Type: `object[]` ([Details](pipeline-definition-definitions-tag.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-trainingstep-properties-arguments-properties-tags.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TrainingStep/properties/Arguments/properties/Tags")

### Tags Type

`object[]` ([Details](pipeline-definition-definitions-tag.md))

## TensorBoardOutputConfig



`TensorBoardOutputConfig`

*   is optional

*   Type: `object` ([Details](pipeline-definition-definitions-trainingstep-properties-arguments-properties-tensorboardoutputconfig.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-trainingstep-properties-arguments-properties-tensorboardoutputconfig.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TrainingStep/properties/Arguments/properties/TensorBoardOutputConfig")

### TensorBoardOutputConfig Type

`object` ([Details](pipeline-definition-definitions-trainingstep-properties-arguments-properties-tensorboardoutputconfig.md))

## VpcConfig



`VpcConfig`

*   is optional

*   Type: `object` ([Details](pipeline-definition-definitions-trainingstep-properties-arguments-properties-vpcconfig.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-trainingstep-properties-arguments-properties-vpcconfig.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TrainingStep/properties/Arguments/properties/VpcConfig")

### VpcConfig Type

`object` ([Details](pipeline-definition-definitions-trainingstep-properties-arguments-properties-vpcconfig.md))
