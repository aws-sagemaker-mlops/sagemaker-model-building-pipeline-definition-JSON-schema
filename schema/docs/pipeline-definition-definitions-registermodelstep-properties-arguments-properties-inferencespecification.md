# Untitled object in SageMaker Pipeline Definition JSON schema Schema

```txt
https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/RegisterModelStep/properties/Arguments/properties/InferenceSpecification
```



| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                           |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :--------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Forbidden             | none                | [pipeline-definition.schema.json*](../../out/pipeline-definition.schema.json "open original schema") |

## InferenceSpecification Type

`object` ([Details](pipeline-definition-definitions-registermodelstep-properties-arguments-properties-inferencespecification.md))

# InferenceSpecification Properties

| Property                                                                            | Type    | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| :---------------------------------------------------------------------------------- | :------ | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Containers](#containers)                                                           | `array` | Optional | cannot be null | [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-registermodelstep-properties-arguments-properties-inferencespecification-properties-containers.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/RegisterModelStep/properties/Arguments/properties/InferenceSpecification/properties/Containers")                                                           |
| [SupportedContentTypes](#supportedcontenttypes)                                     | `array` | Optional | cannot be null | [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-registermodelstep-properties-arguments-properties-inferencespecification-properties-supportedcontenttypes.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/RegisterModelStep/properties/Arguments/properties/InferenceSpecification/properties/SupportedContentTypes")                                     |
| [SupportedRealtimeInferenceInstanceTypes](#supportedrealtimeinferenceinstancetypes) | `array` | Optional | cannot be null | [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-registermodelstep-properties-arguments-properties-inferencespecification-properties-supportedrealtimeinferenceinstancetypes.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/RegisterModelStep/properties/Arguments/properties/InferenceSpecification/properties/SupportedRealtimeInferenceInstanceTypes") |
| [SupportedResponseMIMETypes](#supportedresponsemimetypes)                           | `array` | Optional | cannot be null | [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-registermodelstep-properties-arguments-properties-inferencespecification-properties-supportedresponsemimetypes.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/RegisterModelStep/properties/Arguments/properties/InferenceSpecification/properties/SupportedResponseMIMETypes")                           |
| [SupportedTransformInstanceTypes](#supportedtransforminstancetypes)                 | `array` | Optional | cannot be null | [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-registermodelstep-properties-arguments-properties-inferencespecification-properties-supportedtransforminstancetypes.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/RegisterModelStep/properties/Arguments/properties/InferenceSpecification/properties/SupportedTransformInstanceTypes")                 |

## Containers



`Containers`

*   is optional

*   Type: `object[]` ([Details](pipeline-definition-definitions-registermodelstep-properties-arguments-properties-inferencespecification-properties-containers-items.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-registermodelstep-properties-arguments-properties-inferencespecification-properties-containers.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/RegisterModelStep/properties/Arguments/properties/InferenceSpecification/properties/Containers")

### Containers Type

`object[]` ([Details](pipeline-definition-definitions-registermodelstep-properties-arguments-properties-inferencespecification-properties-containers-items.md))

## SupportedContentTypes



`SupportedContentTypes`

*   is optional

*   Type: an array of merged types ([Details](pipeline-definition-definitions-stringargumentvalue.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-registermodelstep-properties-arguments-properties-inferencespecification-properties-supportedcontenttypes.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/RegisterModelStep/properties/Arguments/properties/InferenceSpecification/properties/SupportedContentTypes")

### SupportedContentTypes Type

an array of merged types ([Details](pipeline-definition-definitions-stringargumentvalue.md))

## SupportedRealtimeInferenceInstanceTypes



`SupportedRealtimeInferenceInstanceTypes`

*   is optional

*   Type: an array of merged types ([Details](pipeline-definition-definitions-stringargumentvalue.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-registermodelstep-properties-arguments-properties-inferencespecification-properties-supportedrealtimeinferenceinstancetypes.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/RegisterModelStep/properties/Arguments/properties/InferenceSpecification/properties/SupportedRealtimeInferenceInstanceTypes")

### SupportedRealtimeInferenceInstanceTypes Type

an array of merged types ([Details](pipeline-definition-definitions-stringargumentvalue.md))

## SupportedResponseMIMETypes



`SupportedResponseMIMETypes`

*   is optional

*   Type: an array of merged types ([Details](pipeline-definition-definitions-stringargumentvalue.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-registermodelstep-properties-arguments-properties-inferencespecification-properties-supportedresponsemimetypes.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/RegisterModelStep/properties/Arguments/properties/InferenceSpecification/properties/SupportedResponseMIMETypes")

### SupportedResponseMIMETypes Type

an array of merged types ([Details](pipeline-definition-definitions-stringargumentvalue.md))

## SupportedTransformInstanceTypes



`SupportedTransformInstanceTypes`

*   is optional

*   Type: an array of merged types ([Details](pipeline-definition-definitions-stringargumentvalue.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-registermodelstep-properties-arguments-properties-inferencespecification-properties-supportedtransforminstancetypes.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/RegisterModelStep/properties/Arguments/properties/InferenceSpecification/properties/SupportedTransformInstanceTypes")

### SupportedTransformInstanceTypes Type

an array of merged types ([Details](pipeline-definition-definitions-stringargumentvalue.md))
