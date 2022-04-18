## items Type

`object` ([Details](pipeline-definition-definitions-hyperparametertrainingjobdefinition.md))

# items Properties

| Property                                                                        | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                                              |
| :------------------------------------------------------------------------------ | :------- | :------- | :------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [DefinitionName](#definitionname)                                               | Merged   | Optional | cannot be null | [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/HyperParameterTrainingJobDefinition/properties/DefinitionName")                                                           |
| [AlgorithmSpecification](#algorithmspecification)                               | `object` | Required | cannot be null | [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-hyperparametertrainingjobdefinition-properties-algorithmspecification.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/HyperParameterTrainingJobDefinition/properties/AlgorithmSpecification") |
| [CheckpointConfig](#checkpointconfig)                                           | `object` | Optional | cannot be null | [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-hyperparametertrainingjobdefinition-properties-checkpointconfig.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/HyperParameterTrainingJobDefinition/properties/CheckpointConfig")             |
| [EnableInterContainerTrafficEncryption](#enableintercontainertrafficencryption) | Merged   | Optional | cannot be null | [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-booleanargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/HyperParameterTrainingJobDefinition/properties/EnableInterContainerTrafficEncryption")                                   |
| [EnableManagedSpotTraining](#enablemanagedspottraining)                         | Merged   | Optional | cannot be null | [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-booleanargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/HyperParameterTrainingJobDefinition/properties/EnableManagedSpotTraining")                                               |
| [EnableNetworkIsolation](#enablenetworkisolation)                               | Merged   | Optional | cannot be null | [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-booleanargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/HyperParameterTrainingJobDefinition/properties/EnableNetworkIsolation")                                                  |
| [HyperParameterRanges](#hyperparameterranges)                                   | `object` | Optional | cannot be null | [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-parameterranges.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/HyperParameterTrainingJobDefinition/properties/HyperParameterRanges")                                                         |
| [InputDataConfig](#inputdataconfig)                                             | `array`  | Optional | cannot be null | [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-hyperparametertrainingjobdefinition-properties-inputdataconfig.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/HyperParameterTrainingJobDefinition/properties/InputDataConfig")               |
| [OutputDataConfig](#outputdataconfig)                                           | `object` | Required | cannot be null | [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-hyperparametertrainingjobdefinition-properties-outputdataconfig.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/HyperParameterTrainingJobDefinition/properties/OutputDataConfig")             |
| [ResourceConfig](#resourceconfig)                                               | `object` | Required | cannot be null | [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-hyperparametertrainingjobdefinition-properties-resourceconfig.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/HyperParameterTrainingJobDefinition/properties/ResourceConfig")                 |
| [RetryStrategy](#retrystrategy)                                                 | `object` | Optional | cannot be null | [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-hyperparametertrainingjobdefinition-properties-retrystrategy.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/HyperParameterTrainingJobDefinition/properties/RetryStrategy")                   |
| [RoleArn](#rolearn)                                                             | Merged   | Required | cannot be null | [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/HyperParameterTrainingJobDefinition/properties/RoleArn")                                                                  |
| [StaticHyperParameters](#statichyperparameters)                                 | `object` | Optional | cannot be null | [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-hyperparametertrainingjobdefinition-properties-statichyperparameters.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/HyperParameterTrainingJobDefinition/properties/StaticHyperParameters")   |
| [StoppingCondition](#stoppingcondition)                                         | `object` | Required | cannot be null | [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-hyperparametertrainingjobdefinition-properties-stoppingcondition.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/HyperParameterTrainingJobDefinition/properties/StoppingCondition")           |
| [TuningObjective](#tuningobjective)                                             | `object` | Optional | cannot be null | [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-hyperparametertrainingjobdefinition-properties-tuningobjective.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/HyperParameterTrainingJobDefinition/properties/TuningObjective")               |
| [VpcConfig](#vpcconfig)                                                         | `object` | Optional | cannot be null | [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-hyperparametertrainingjobdefinition-properties-vpcconfig.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/HyperParameterTrainingJobDefinition/properties/VpcConfig")                           |

## DefinitionName



`DefinitionName`

*   is optional

*   Type: merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/HyperParameterTrainingJobDefinition/properties/DefinitionName")

### DefinitionName Type

merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

one (and only one) of

*   [Untitled string in SageMaker Pipeline Definition Schema](pipeline-definition-definitions-stringargumentvalue-oneof-0.md "check type definition")

*   [Untitled object in SageMaker Pipeline Definition Schema](pipeline-definition-definitions-getfunction.md "check type definition")

## AlgorithmSpecification



`AlgorithmSpecification`

*   is required

*   Type: `object` ([Details](pipeline-definition-definitions-hyperparametertrainingjobdefinition-properties-algorithmspecification.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-hyperparametertrainingjobdefinition-properties-algorithmspecification.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/HyperParameterTrainingJobDefinition/properties/AlgorithmSpecification")

### AlgorithmSpecification Type

`object` ([Details](pipeline-definition-definitions-hyperparametertrainingjobdefinition-properties-algorithmspecification.md))

## CheckpointConfig



`CheckpointConfig`

*   is optional

*   Type: `object` ([Details](pipeline-definition-definitions-hyperparametertrainingjobdefinition-properties-checkpointconfig.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-hyperparametertrainingjobdefinition-properties-checkpointconfig.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/HyperParameterTrainingJobDefinition/properties/CheckpointConfig")

### CheckpointConfig Type

`object` ([Details](pipeline-definition-definitions-hyperparametertrainingjobdefinition-properties-checkpointconfig.md))

## EnableInterContainerTrafficEncryption



`EnableInterContainerTrafficEncryption`

*   is optional

*   Type: merged type ([Details](pipeline-definition-definitions-booleanargumentvalue.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-booleanargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/HyperParameterTrainingJobDefinition/properties/EnableInterContainerTrafficEncryption")

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

*   defined in: [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-booleanargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/HyperParameterTrainingJobDefinition/properties/EnableManagedSpotTraining")

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

*   defined in: [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-booleanargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/HyperParameterTrainingJobDefinition/properties/EnableNetworkIsolation")

### EnableNetworkIsolation Type

merged type ([Details](pipeline-definition-definitions-booleanargumentvalue.md))

one (and only one) of

*   [Untitled boolean in SageMaker Pipeline Definition Schema](pipeline-definition-definitions-booleanargumentvalue-oneof-0.md "check type definition")

*   [Untitled object in SageMaker Pipeline Definition Schema](pipeline-definition-definitions-getfunction.md "check type definition")

## HyperParameterRanges



`HyperParameterRanges`

*   is optional

*   Type: `object` ([Details](pipeline-definition-definitions-parameterranges.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-parameterranges.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/HyperParameterTrainingJobDefinition/properties/HyperParameterRanges")

### HyperParameterRanges Type

`object` ([Details](pipeline-definition-definitions-parameterranges.md))

## InputDataConfig



`InputDataConfig`

*   is optional

*   Type: `object[]` ([Details](pipeline-definition-definitions-hyperparametertrainingjobdefinition-properties-inputdataconfig-items.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-hyperparametertrainingjobdefinition-properties-inputdataconfig.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/HyperParameterTrainingJobDefinition/properties/InputDataConfig")

### InputDataConfig Type

`object[]` ([Details](pipeline-definition-definitions-hyperparametertrainingjobdefinition-properties-inputdataconfig-items.md))

## OutputDataConfig



`OutputDataConfig`

*   is required

*   Type: `object` ([Details](pipeline-definition-definitions-hyperparametertrainingjobdefinition-properties-outputdataconfig.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-hyperparametertrainingjobdefinition-properties-outputdataconfig.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/HyperParameterTrainingJobDefinition/properties/OutputDataConfig")

### OutputDataConfig Type

`object` ([Details](pipeline-definition-definitions-hyperparametertrainingjobdefinition-properties-outputdataconfig.md))

## ResourceConfig



`ResourceConfig`

*   is required

*   Type: `object` ([Details](pipeline-definition-definitions-hyperparametertrainingjobdefinition-properties-resourceconfig.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-hyperparametertrainingjobdefinition-properties-resourceconfig.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/HyperParameterTrainingJobDefinition/properties/ResourceConfig")

### ResourceConfig Type

`object` ([Details](pipeline-definition-definitions-hyperparametertrainingjobdefinition-properties-resourceconfig.md))

## RetryStrategy



`RetryStrategy`

*   is optional

*   Type: `object` ([Details](pipeline-definition-definitions-hyperparametertrainingjobdefinition-properties-retrystrategy.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-hyperparametertrainingjobdefinition-properties-retrystrategy.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/HyperParameterTrainingJobDefinition/properties/RetryStrategy")

### RetryStrategy Type

`object` ([Details](pipeline-definition-definitions-hyperparametertrainingjobdefinition-properties-retrystrategy.md))

## RoleArn



`RoleArn`

*   is required

*   Type: merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/HyperParameterTrainingJobDefinition/properties/RoleArn")

### RoleArn Type

merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

one (and only one) of

*   [Untitled string in SageMaker Pipeline Definition Schema](pipeline-definition-definitions-stringargumentvalue-oneof-0.md "check type definition")

*   [Untitled object in SageMaker Pipeline Definition Schema](pipeline-definition-definitions-getfunction.md "check type definition")

## StaticHyperParameters



`StaticHyperParameters`

*   is optional

*   Type: `object` ([Details](pipeline-definition-definitions-hyperparametertrainingjobdefinition-properties-statichyperparameters.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-hyperparametertrainingjobdefinition-properties-statichyperparameters.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/HyperParameterTrainingJobDefinition/properties/StaticHyperParameters")

### StaticHyperParameters Type

`object` ([Details](pipeline-definition-definitions-hyperparametertrainingjobdefinition-properties-statichyperparameters.md))

## StoppingCondition



`StoppingCondition`

*   is required

*   Type: `object` ([Details](pipeline-definition-definitions-hyperparametertrainingjobdefinition-properties-stoppingcondition.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-hyperparametertrainingjobdefinition-properties-stoppingcondition.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/HyperParameterTrainingJobDefinition/properties/StoppingCondition")

### StoppingCondition Type

`object` ([Details](pipeline-definition-definitions-hyperparametertrainingjobdefinition-properties-stoppingcondition.md))

## TuningObjective



`TuningObjective`

*   is optional

*   Type: `object` ([Details](pipeline-definition-definitions-hyperparametertrainingjobdefinition-properties-tuningobjective.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-hyperparametertrainingjobdefinition-properties-tuningobjective.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/HyperParameterTrainingJobDefinition/properties/TuningObjective")

### TuningObjective Type

`object` ([Details](pipeline-definition-definitions-hyperparametertrainingjobdefinition-properties-tuningobjective.md))

## VpcConfig



`VpcConfig`

*   is optional

*   Type: `object` ([Details](pipeline-definition-definitions-hyperparametertrainingjobdefinition-properties-vpcconfig.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-hyperparametertrainingjobdefinition-properties-vpcconfig.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/HyperParameterTrainingJobDefinition/properties/VpcConfig")

### VpcConfig Type

`object` ([Details](pipeline-definition-definitions-hyperparametertrainingjobdefinition-properties-vpcconfig.md))
