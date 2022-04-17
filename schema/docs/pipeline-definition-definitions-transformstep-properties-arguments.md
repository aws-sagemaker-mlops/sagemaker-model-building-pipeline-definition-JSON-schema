## Arguments Type

`object` ([Details](pipeline-definition-definitions-transformstep-properties-arguments.md))

# Arguments Properties

| Property                                            | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                             |
| :-------------------------------------------------- | :------- | :------- | :------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [BatchStrategy](#batchstrategy)                     | Merged   | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TransformStep/properties/Arguments/properties/BatchStrategy")                                                   |
| [DataProcessing](#dataprocessing)                   | `object` | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-transformstep-properties-arguments-properties-dataprocessing.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TransformStep/properties/Arguments/properties/DataProcessing")         |
| [Environment](#environment)                         | `object` | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-transformstep-properties-arguments-properties-environment.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TransformStep/properties/Arguments/properties/Environment")               |
| [ExperimentConfig](#experimentconfig)               | `object` | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-transformstep-properties-arguments-properties-experimentconfig.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TransformStep/properties/Arguments/properties/ExperimentConfig")     |
| [MaxConcurrentTransforms](#maxconcurrenttransforms) | Merged   | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-integerargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TransformStep/properties/Arguments/properties/MaxConcurrentTransforms")                                        |
| [MaxPayloadInMB](#maxpayloadinmb)                   | Merged   | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-integerargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TransformStep/properties/Arguments/properties/MaxPayloadInMB")                                                 |
| [ModelClientConfig](#modelclientconfig)             | `object` | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-transformstep-properties-arguments-properties-modelclientconfig.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TransformStep/properties/Arguments/properties/ModelClientConfig")   |
| [Tags](#tags)                                       | `array`  | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-transformstep-properties-arguments-properties-tags.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TransformStep/properties/Arguments/properties/Tags")                             |
| [ModelName](#modelname)                             | Merged   | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TransformStep/properties/Arguments/properties/ModelName")                                                       |
| [TransformInput](#transforminput)                   | `object` | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-transformstep-properties-arguments-properties-transforminput.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TransformStep/properties/Arguments/properties/TransformInput")         |
| [TransformJobName](#transformjobname)               | Merged   | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TransformStep/properties/Arguments/properties/TransformJobName")                                                |
| [TransformOutput](#transformoutput)                 | `object` | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-transformstep-properties-arguments-properties-transformoutput.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TransformStep/properties/Arguments/properties/TransformOutput")       |
| [TransformResources](#transformresources)           | `object` | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-transformstep-properties-arguments-properties-transformresources.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TransformStep/properties/Arguments/properties/TransformResources") |

## BatchStrategy



`BatchStrategy`

*   is optional

*   Type: merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TransformStep/properties/Arguments/properties/BatchStrategy")

### BatchStrategy Type

merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

one (and only one) of

*   [Untitled string in SageMaker Pipeline Definition](pipeline-definition-definitions-stringargumentvalue-oneof-0.md "check type definition")

*   [Untitled object in SageMaker Pipeline Definition](pipeline-definition-definitions-getfunction.md "check type definition")

## DataProcessing



`DataProcessing`

*   is optional

*   Type: `object` ([Details](pipeline-definition-definitions-transformstep-properties-arguments-properties-dataprocessing.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-transformstep-properties-arguments-properties-dataprocessing.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TransformStep/properties/Arguments/properties/DataProcessing")

### DataProcessing Type

`object` ([Details](pipeline-definition-definitions-transformstep-properties-arguments-properties-dataprocessing.md))

## Environment



`Environment`

*   is optional

*   Type: `object` ([Details](pipeline-definition-definitions-transformstep-properties-arguments-properties-environment.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-transformstep-properties-arguments-properties-environment.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TransformStep/properties/Arguments/properties/Environment")

### Environment Type

`object` ([Details](pipeline-definition-definitions-transformstep-properties-arguments-properties-environment.md))

## ExperimentConfig



`ExperimentConfig`

*   is optional

*   Type: `object` ([Details](pipeline-definition-definitions-transformstep-properties-arguments-properties-experimentconfig.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-transformstep-properties-arguments-properties-experimentconfig.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TransformStep/properties/Arguments/properties/ExperimentConfig")

### ExperimentConfig Type

`object` ([Details](pipeline-definition-definitions-transformstep-properties-arguments-properties-experimentconfig.md))

## MaxConcurrentTransforms



`MaxConcurrentTransforms`

*   is optional

*   Type: merged type ([Details](pipeline-definition-definitions-integerargumentvalue.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-integerargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TransformStep/properties/Arguments/properties/MaxConcurrentTransforms")

### MaxConcurrentTransforms Type

merged type ([Details](pipeline-definition-definitions-integerargumentvalue.md))

one (and only one) of

*   [Untitled integer in SageMaker Pipeline Definition](pipeline-definition-definitions-integerargumentvalue-oneof-0.md "check type definition")

*   [Untitled object in SageMaker Pipeline Definition](pipeline-definition-definitions-getfunction.md "check type definition")

## MaxPayloadInMB



`MaxPayloadInMB`

*   is optional

*   Type: merged type ([Details](pipeline-definition-definitions-integerargumentvalue.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-integerargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TransformStep/properties/Arguments/properties/MaxPayloadInMB")

### MaxPayloadInMB Type

merged type ([Details](pipeline-definition-definitions-integerargumentvalue.md))

one (and only one) of

*   [Untitled integer in SageMaker Pipeline Definition](pipeline-definition-definitions-integerargumentvalue-oneof-0.md "check type definition")

*   [Untitled object in SageMaker Pipeline Definition](pipeline-definition-definitions-getfunction.md "check type definition")

## ModelClientConfig



`ModelClientConfig`

*   is optional

*   Type: `object` ([Details](pipeline-definition-definitions-transformstep-properties-arguments-properties-modelclientconfig.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-transformstep-properties-arguments-properties-modelclientconfig.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TransformStep/properties/Arguments/properties/ModelClientConfig")

### ModelClientConfig Type

`object` ([Details](pipeline-definition-definitions-transformstep-properties-arguments-properties-modelclientconfig.md))

## Tags



`Tags`

*   is optional

*   Type: `object[]` ([Details](pipeline-definition-definitions-tag.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-transformstep-properties-arguments-properties-tags.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TransformStep/properties/Arguments/properties/Tags")

### Tags Type

`object[]` ([Details](pipeline-definition-definitions-tag.md))

## ModelName



`ModelName`

*   is optional

*   Type: merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TransformStep/properties/Arguments/properties/ModelName")

### ModelName Type

merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

one (and only one) of

*   [Untitled string in SageMaker Pipeline Definition](pipeline-definition-definitions-stringargumentvalue-oneof-0.md "check type definition")

*   [Untitled object in SageMaker Pipeline Definition](pipeline-definition-definitions-getfunction.md "check type definition")

## TransformInput



`TransformInput`

*   is optional

*   Type: `object` ([Details](pipeline-definition-definitions-transformstep-properties-arguments-properties-transforminput.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-transformstep-properties-arguments-properties-transforminput.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TransformStep/properties/Arguments/properties/TransformInput")

### TransformInput Type

`object` ([Details](pipeline-definition-definitions-transformstep-properties-arguments-properties-transforminput.md))

## TransformJobName



`TransformJobName`

*   is optional

*   Type: merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TransformStep/properties/Arguments/properties/TransformJobName")

### TransformJobName Type

merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

one (and only one) of

*   [Untitled string in SageMaker Pipeline Definition](pipeline-definition-definitions-stringargumentvalue-oneof-0.md "check type definition")

*   [Untitled object in SageMaker Pipeline Definition](pipeline-definition-definitions-getfunction.md "check type definition")

## TransformOutput



`TransformOutput`

*   is optional

*   Type: `object` ([Details](pipeline-definition-definitions-transformstep-properties-arguments-properties-transformoutput.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-transformstep-properties-arguments-properties-transformoutput.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TransformStep/properties/Arguments/properties/TransformOutput")

### TransformOutput Type

`object` ([Details](pipeline-definition-definitions-transformstep-properties-arguments-properties-transformoutput.md))

## TransformResources



`TransformResources`

*   is optional

*   Type: `object` ([Details](pipeline-definition-definitions-transformstep-properties-arguments-properties-transformresources.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-transformstep-properties-arguments-properties-transformresources.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TransformStep/properties/Arguments/properties/TransformResources")

### TransformResources Type

`object` ([Details](pipeline-definition-definitions-transformstep-properties-arguments-properties-transformresources.md))
