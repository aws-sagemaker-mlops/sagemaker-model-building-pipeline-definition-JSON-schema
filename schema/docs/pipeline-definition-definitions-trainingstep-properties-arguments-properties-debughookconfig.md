## DebugHookConfig Type

`object` ([Details](pipeline-definition-definitions-trainingstep-properties-arguments-properties-debughookconfig.md))

# DebugHookConfig Properties

| Property                                              | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                                                                                                    |
| :---------------------------------------------------- | :------- | :------- | :------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [CollectionConfigurations](#collectionconfigurations) | `array`  | Optional | cannot be null | [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-trainingstep-properties-arguments-properties-debughookconfig-properties-collectionconfigurations.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TrainingStep/properties/Arguments/properties/DebugHookConfig/properties/CollectionConfigurations") |
| [HookParameters](#hookparameters)                     | `object` | Optional | cannot be null | [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-trainingstep-properties-arguments-properties-debughookconfig-properties-hookparameters.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TrainingStep/properties/Arguments/properties/DebugHookConfig/properties/HookParameters")                     |
| [LocalPath](#localpath)                               | Merged   | Optional | cannot be null | [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TrainingStep/properties/Arguments/properties/DebugHookConfig/properties/LocalPath")                                                                                             |
| [S3OutputPath](#s3outputpath)                         | Merged   | Optional | cannot be null | [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TrainingStep/properties/Arguments/properties/DebugHookConfig/properties/S3OutputPath")                                                                                          |

## CollectionConfigurations



`CollectionConfigurations`

*   is optional

*   Type: `object[]` ([Details](pipeline-definition-definitions-trainingstep-properties-arguments-properties-debughookconfig-properties-collectionconfigurations-items.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-trainingstep-properties-arguments-properties-debughookconfig-properties-collectionconfigurations.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TrainingStep/properties/Arguments/properties/DebugHookConfig/properties/CollectionConfigurations")

### CollectionConfigurations Type

`object[]` ([Details](pipeline-definition-definitions-trainingstep-properties-arguments-properties-debughookconfig-properties-collectionconfigurations-items.md))

## HookParameters



`HookParameters`

*   is optional

*   Type: `object` ([Details](pipeline-definition-definitions-trainingstep-properties-arguments-properties-debughookconfig-properties-hookparameters.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-trainingstep-properties-arguments-properties-debughookconfig-properties-hookparameters.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TrainingStep/properties/Arguments/properties/DebugHookConfig/properties/HookParameters")

### HookParameters Type

`object` ([Details](pipeline-definition-definitions-trainingstep-properties-arguments-properties-debughookconfig-properties-hookparameters.md))

## LocalPath



`LocalPath`

*   is optional

*   Type: merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TrainingStep/properties/Arguments/properties/DebugHookConfig/properties/LocalPath")

### LocalPath Type

merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

one (and only one) of

*   [Untitled string in SageMaker Pipeline Definition Schema](pipeline-definition-definitions-stringargumentvalue-oneof-0.md "check type definition")

*   [Untitled object in SageMaker Pipeline Definition Schema](pipeline-definition-definitions-getfunction.md "check type definition")

## S3OutputPath



`S3OutputPath`

*   is optional

*   Type: merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TrainingStep/properties/Arguments/properties/DebugHookConfig/properties/S3OutputPath")

### S3OutputPath Type

merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

one (and only one) of

*   [Untitled string in SageMaker Pipeline Definition Schema](pipeline-definition-definitions-stringargumentvalue-oneof-0.md "check type definition")

*   [Untitled object in SageMaker Pipeline Definition Schema](pipeline-definition-definitions-getfunction.md "check type definition")
