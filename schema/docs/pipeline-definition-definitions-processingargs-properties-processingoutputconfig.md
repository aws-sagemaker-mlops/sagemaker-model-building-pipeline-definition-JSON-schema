## ProcessingOutputConfig Type

`object` ([Details](pipeline-definition-definitions-processingargs-properties-processingoutputconfig.md))

# ProcessingOutputConfig Properties

| Property              | Type    | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                                          |
| :-------------------- | :------ | :------- | :------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [KmsKeyId](#kmskeyid) | Merged  | Optional | cannot be null | [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ProcessingArgs/properties/ProcessingOutputConfig/properties/KmsKeyId")                                                |
| [Outputs](#outputs)   | `array` | Optional | cannot be null | [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-processingargs-properties-processingoutputconfig-properties-outputs.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ProcessingArgs/properties/ProcessingOutputConfig/properties/Outputs") |

## KmsKeyId



`KmsKeyId`

*   is optional

*   Type: merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ProcessingArgs/properties/ProcessingOutputConfig/properties/KmsKeyId")

### KmsKeyId Type

merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

one (and only one) of

*   [Untitled string in SageMaker Pipeline Definition Schema](pipeline-definition-definitions-stringargumentvalue-oneof-0.md "check type definition")

*   [Untitled object in SageMaker Pipeline Definition Schema](pipeline-definition-definitions-getfunction.md "check type definition")

## Outputs



`Outputs`

*   is optional

*   Type: `object[]` ([Details](pipeline-definition-definitions-processingargs-properties-processingoutputconfig-properties-outputs-items.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-processingargs-properties-processingoutputconfig-properties-outputs.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ProcessingArgs/properties/ProcessingOutputConfig/properties/Outputs")

### Outputs Type

`object[]` ([Details](pipeline-definition-definitions-processingargs-properties-processingoutputconfig-properties-outputs-items.md))
