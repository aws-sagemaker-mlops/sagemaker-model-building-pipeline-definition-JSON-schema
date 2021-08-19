# Untitled object in SageMaker Pipeline Definition JSON schema Schema

```txt
https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ProcessingStep/properties/Arguments/properties/ProcessingOutputConfig/properties/Outputs/items
```



| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                           |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :--------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Forbidden             | none                | [pipeline-definition.schema.json*](../../out/pipeline-definition.schema.json "open original schema") |

## items Type

`object` ([Details](pipeline-definition-definitions-processingstep-properties-arguments-properties-processingoutputconfig-properties-outputs-items.md))

# items Properties

| Property                  | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                                                                                                                                             |
| :------------------------ | :------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [OutputName](#outputname) | Merged   | Optional | cannot be null | [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ProcessingStep/properties/Arguments/properties/ProcessingOutputConfig/properties/Outputs/items/properties/OutputName")                                                                                              |
| [S3Output](#s3output)     | `object` | Optional | cannot be null | [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-processingstep-properties-arguments-properties-processingoutputconfig-properties-outputs-items-properties-s3output.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ProcessingStep/properties/Arguments/properties/ProcessingOutputConfig/properties/Outputs/items/properties/S3Output") |

## OutputName



`OutputName`

*   is optional

*   Type: merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ProcessingStep/properties/Arguments/properties/ProcessingOutputConfig/properties/Outputs/items/properties/OutputName")

### OutputName Type

merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

one (and only one) of

*   [Untitled string in SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-stringargumentvalue-oneof-0.md "check type definition")

*   [Untitled object in SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-getfunction.md "check type definition")

## S3Output



`S3Output`

*   is optional

*   Type: `object` ([Details](pipeline-definition-definitions-processingstep-properties-arguments-properties-processingoutputconfig-properties-outputs-items-properties-s3output.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-processingstep-properties-arguments-properties-processingoutputconfig-properties-outputs-items-properties-s3output.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ProcessingStep/properties/Arguments/properties/ProcessingOutputConfig/properties/Outputs/items/properties/S3Output")

### S3Output Type

`object` ([Details](pipeline-definition-definitions-processingstep-properties-arguments-properties-processingoutputconfig-properties-outputs-items-properties-s3output.md))
