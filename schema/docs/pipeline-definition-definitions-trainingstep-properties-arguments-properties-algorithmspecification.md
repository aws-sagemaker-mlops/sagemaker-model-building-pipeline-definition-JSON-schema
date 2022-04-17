## AlgorithmSpecification Type

`object` ([Details](pipeline-definition-definitions-trainingstep-properties-arguments-properties-algorithmspecification.md))

# AlgorithmSpecification Properties

| Property                                                              | Type    | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                                                                                             |
| :-------------------------------------------------------------------- | :------ | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [AlgorithmName](#algorithmname)                                       | Merged  | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TrainingStep/properties/Arguments/properties/AlgorithmSpecification/properties/AlgorithmName")                                                                                  |
| [EnableSageMakerMetricsTimeSeries](#enablesagemakermetricstimeseries) | Merged  | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-booleanargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TrainingStep/properties/Arguments/properties/AlgorithmSpecification/properties/EnableSageMakerMetricsTimeSeries")                                                              |
| [MetricDefinitions](#metricdefinitions)                               | `array` | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-trainingstep-properties-arguments-properties-algorithmspecification-properties-metricdefinitions.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TrainingStep/properties/Arguments/properties/AlgorithmSpecification/properties/MetricDefinitions") |
| [TrainingImage](#trainingimage)                                       | Merged  | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TrainingStep/properties/Arguments/properties/AlgorithmSpecification/properties/TrainingImage")                                                                                  |
| [TrainingInputMode](#traininginputmode)                               | Merged  | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TrainingStep/properties/Arguments/properties/AlgorithmSpecification/properties/TrainingInputMode")                                                                              |

## AlgorithmName



`AlgorithmName`

*   is optional

*   Type: merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TrainingStep/properties/Arguments/properties/AlgorithmSpecification/properties/AlgorithmName")

### AlgorithmName Type

merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

one (and only one) of

*   [Untitled string in SageMaker Pipeline Definition](pipeline-definition-definitions-stringargumentvalue-oneof-0.md "check type definition")

*   [Untitled object in SageMaker Pipeline Definition](pipeline-definition-definitions-getfunction.md "check type definition")

## EnableSageMakerMetricsTimeSeries



`EnableSageMakerMetricsTimeSeries`

*   is optional

*   Type: merged type ([Details](pipeline-definition-definitions-booleanargumentvalue.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-booleanargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TrainingStep/properties/Arguments/properties/AlgorithmSpecification/properties/EnableSageMakerMetricsTimeSeries")

### EnableSageMakerMetricsTimeSeries Type

merged type ([Details](pipeline-definition-definitions-booleanargumentvalue.md))

one (and only one) of

*   [Untitled boolean in SageMaker Pipeline Definition](pipeline-definition-definitions-booleanargumentvalue-oneof-0.md "check type definition")

*   [Untitled object in SageMaker Pipeline Definition](pipeline-definition-definitions-getfunction.md "check type definition")

## MetricDefinitions



`MetricDefinitions`

*   is optional

*   Type: `object[]` ([Details](pipeline-definition-definitions-trainingstep-properties-arguments-properties-algorithmspecification-properties-metricdefinitions-items.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-trainingstep-properties-arguments-properties-algorithmspecification-properties-metricdefinitions.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TrainingStep/properties/Arguments/properties/AlgorithmSpecification/properties/MetricDefinitions")

### MetricDefinitions Type

`object[]` ([Details](pipeline-definition-definitions-trainingstep-properties-arguments-properties-algorithmspecification-properties-metricdefinitions-items.md))

## TrainingImage



`TrainingImage`

*   is optional

*   Type: merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TrainingStep/properties/Arguments/properties/AlgorithmSpecification/properties/TrainingImage")

### TrainingImage Type

merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

one (and only one) of

*   [Untitled string in SageMaker Pipeline Definition](pipeline-definition-definitions-stringargumentvalue-oneof-0.md "check type definition")

*   [Untitled object in SageMaker Pipeline Definition](pipeline-definition-definitions-getfunction.md "check type definition")

## TrainingInputMode



`TrainingInputMode`

*   is optional

*   Type: merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TrainingStep/properties/Arguments/properties/AlgorithmSpecification/properties/TrainingInputMode")

### TrainingInputMode Type

merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

one (and only one) of

*   [Untitled string in SageMaker Pipeline Definition](pipeline-definition-definitions-stringargumentvalue-oneof-0.md "check type definition")

*   [Untitled object in SageMaker Pipeline Definition](pipeline-definition-definitions-getfunction.md "check type definition")
