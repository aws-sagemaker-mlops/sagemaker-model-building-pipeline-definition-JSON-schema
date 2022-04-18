## items Type

`object` ([Details](pipeline-definition-definitions-hyperparametertrainingjobdefinition-properties-inputdataconfig-items.md))

# items Properties

| Property                                | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                                                                                              |
| :-------------------------------------- | :------- | :------- | :------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [ChannelName](#channelname)             | Merged   | Optional | cannot be null | [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/HyperParameterTrainingJobDefinition/properties/InputDataConfig/items/properties/ChannelName")                                                                             |
| [CompressionType](#compressiontype)     | Merged   | Optional | cannot be null | [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/HyperParameterTrainingJobDefinition/properties/InputDataConfig/items/properties/CompressionType")                                                                         |
| [ContentType](#contenttype)             | Merged   | Optional | cannot be null | [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/HyperParameterTrainingJobDefinition/properties/InputDataConfig/items/properties/ContentType")                                                                             |
| [DataSource](#datasource)               | `object` | Optional | cannot be null | [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-hyperparametertrainingjobdefinition-properties-inputdataconfig-items-properties-datasource.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/HyperParameterTrainingJobDefinition/properties/InputDataConfig/items/properties/DataSource")       |
| [InputMode](#inputmode)                 | Merged   | Optional | cannot be null | [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/HyperParameterTrainingJobDefinition/properties/InputDataConfig/items/properties/InputMode")                                                                               |
| [RecordWrapperType](#recordwrappertype) | Merged   | Optional | cannot be null | [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/HyperParameterTrainingJobDefinition/properties/InputDataConfig/items/properties/RecordWrapperType")                                                                       |
| [ShuffleConfig](#shuffleconfig)         | `object` | Optional | cannot be null | [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-hyperparametertrainingjobdefinition-properties-inputdataconfig-items-properties-shuffleconfig.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/HyperParameterTrainingJobDefinition/properties/InputDataConfig/items/properties/ShuffleConfig") |

## ChannelName



`ChannelName`

*   is optional

*   Type: merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/HyperParameterTrainingJobDefinition/properties/InputDataConfig/items/properties/ChannelName")

### ChannelName Type

merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

one (and only one) of

*   [Untitled string in SageMaker Pipeline Definition Schema](pipeline-definition-definitions-stringargumentvalue-oneof-0.md "check type definition")

*   [Untitled object in SageMaker Pipeline Definition Schema](pipeline-definition-definitions-getfunction.md "check type definition")

## CompressionType



`CompressionType`

*   is optional

*   Type: merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/HyperParameterTrainingJobDefinition/properties/InputDataConfig/items/properties/CompressionType")

### CompressionType Type

merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

one (and only one) of

*   [Untitled string in SageMaker Pipeline Definition Schema](pipeline-definition-definitions-stringargumentvalue-oneof-0.md "check type definition")

*   [Untitled object in SageMaker Pipeline Definition Schema](pipeline-definition-definitions-getfunction.md "check type definition")

## ContentType



`ContentType`

*   is optional

*   Type: merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/HyperParameterTrainingJobDefinition/properties/InputDataConfig/items/properties/ContentType")

### ContentType Type

merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

one (and only one) of

*   [Untitled string in SageMaker Pipeline Definition Schema](pipeline-definition-definitions-stringargumentvalue-oneof-0.md "check type definition")

*   [Untitled object in SageMaker Pipeline Definition Schema](pipeline-definition-definitions-getfunction.md "check type definition")

## DataSource



`DataSource`

*   is optional

*   Type: `object` ([Details](pipeline-definition-definitions-hyperparametertrainingjobdefinition-properties-inputdataconfig-items-properties-datasource.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-hyperparametertrainingjobdefinition-properties-inputdataconfig-items-properties-datasource.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/HyperParameterTrainingJobDefinition/properties/InputDataConfig/items/properties/DataSource")

### DataSource Type

`object` ([Details](pipeline-definition-definitions-hyperparametertrainingjobdefinition-properties-inputdataconfig-items-properties-datasource.md))

## InputMode



`InputMode`

*   is optional

*   Type: merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/HyperParameterTrainingJobDefinition/properties/InputDataConfig/items/properties/InputMode")

### InputMode Type

merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

one (and only one) of

*   [Untitled string in SageMaker Pipeline Definition Schema](pipeline-definition-definitions-stringargumentvalue-oneof-0.md "check type definition")

*   [Untitled object in SageMaker Pipeline Definition Schema](pipeline-definition-definitions-getfunction.md "check type definition")

## RecordWrapperType



`RecordWrapperType`

*   is optional

*   Type: merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/HyperParameterTrainingJobDefinition/properties/InputDataConfig/items/properties/RecordWrapperType")

### RecordWrapperType Type

merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

one (and only one) of

*   [Untitled string in SageMaker Pipeline Definition Schema](pipeline-definition-definitions-stringargumentvalue-oneof-0.md "check type definition")

*   [Untitled object in SageMaker Pipeline Definition Schema](pipeline-definition-definitions-getfunction.md "check type definition")

## ShuffleConfig



`ShuffleConfig`

*   is optional

*   Type: `object` ([Details](pipeline-definition-definitions-hyperparametertrainingjobdefinition-properties-inputdataconfig-items-properties-shuffleconfig.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-hyperparametertrainingjobdefinition-properties-inputdataconfig-items-properties-shuffleconfig.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/HyperParameterTrainingJobDefinition/properties/InputDataConfig/items/properties/ShuffleConfig")

### ShuffleConfig Type

`object` ([Details](pipeline-definition-definitions-hyperparametertrainingjobdefinition-properties-inputdataconfig-items-properties-shuffleconfig.md))
