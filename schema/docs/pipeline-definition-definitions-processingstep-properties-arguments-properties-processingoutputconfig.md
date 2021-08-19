# Untitled object in SageMaker Pipeline Definition JSON schema Schema

```txt
https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ProcessingStep/properties/Arguments/properties/ProcessingOutputConfig
```



| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                           |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :--------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Forbidden             | none                | [pipeline-definition.schema.json*](../../out/pipeline-definition.schema.json "open original schema") |

## ProcessingOutputConfig Type

`object` ([Details](pipeline-definition-definitions-processingstep-properties-arguments-properties-processingoutputconfig.md))

# ProcessingOutputConfig Properties

| Property              | Type    | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                                                                                         |
| :-------------------- | :------ | :------- | :------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [KmsKeyId](#kmskeyid) | Merged  | Optional | cannot be null | [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ProcessingStep/properties/Arguments/properties/ProcessingOutputConfig/properties/KmsKeyId")                                                                     |
| [Outputs](#outputs)   | `array` | Optional | cannot be null | [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-processingstep-properties-arguments-properties-processingoutputconfig-properties-outputs.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ProcessingStep/properties/Arguments/properties/ProcessingOutputConfig/properties/Outputs") |

## KmsKeyId



`KmsKeyId`

*   is optional

*   Type: merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ProcessingStep/properties/Arguments/properties/ProcessingOutputConfig/properties/KmsKeyId")

### KmsKeyId Type

merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

one (and only one) of

*   [Untitled string in SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-stringargumentvalue-oneof-0.md "check type definition")

*   [Untitled object in SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-getfunction.md "check type definition")

## Outputs



`Outputs`

*   is optional

*   Type: `object[]` ([Details](pipeline-definition-definitions-processingstep-properties-arguments-properties-processingoutputconfig-properties-outputs-items.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-processingstep-properties-arguments-properties-processingoutputconfig-properties-outputs.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ProcessingStep/properties/Arguments/properties/ProcessingOutputConfig/properties/Outputs")

### Outputs Type

`object[]` ([Details](pipeline-definition-definitions-processingstep-properties-arguments-properties-processingoutputconfig-properties-outputs-items.md))
