# Untitled object in SageMaker Pipeline Definition JSON schema Schema

```txt
https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TransformStep/properties/Arguments/properties/TransformInput
```



| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                           |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :--------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Forbidden             | none                | [pipeline-definition.schema.json*](../../out/pipeline-definition.schema.json "open original schema") |

## TransformInput Type

`object` ([Details](pipeline-definition-definitions-transformstep-properties-arguments-properties-transforminput.md))

# TransformInput Properties

| Property                            | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                                                                             |
| :---------------------------------- | :------- | :------- | :------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [CompressionType](#compressiontype) | Merged   | Optional | cannot be null | [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TransformStep/properties/Arguments/properties/TransformInput/properties/CompressionType")                                                           |
| [ContentType](#contenttype)         | Merged   | Optional | cannot be null | [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TransformStep/properties/Arguments/properties/TransformInput/properties/ContentType")                                                               |
| [DataSource](#datasource)           | `object` | Optional | cannot be null | [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-transformstep-properties-arguments-properties-transforminput-properties-datasource.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TransformStep/properties/Arguments/properties/TransformInput/properties/DataSource") |
| [SplitType](#splittype)             | Merged   | Optional | cannot be null | [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TransformStep/properties/Arguments/properties/TransformInput/properties/SplitType")                                                                 |

## CompressionType



`CompressionType`

*   is optional

*   Type: merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TransformStep/properties/Arguments/properties/TransformInput/properties/CompressionType")

### CompressionType Type

merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

one (and only one) of

*   [Untitled string in SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-stringargumentvalue-oneof-0.md "check type definition")

*   [Untitled object in SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-getfunction.md "check type definition")

## ContentType



`ContentType`

*   is optional

*   Type: merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TransformStep/properties/Arguments/properties/TransformInput/properties/ContentType")

### ContentType Type

merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

one (and only one) of

*   [Untitled string in SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-stringargumentvalue-oneof-0.md "check type definition")

*   [Untitled object in SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-getfunction.md "check type definition")

## DataSource



`DataSource`

*   is optional

*   Type: `object` ([Details](pipeline-definition-definitions-transformstep-properties-arguments-properties-transforminput-properties-datasource.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-transformstep-properties-arguments-properties-transforminput-properties-datasource.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TransformStep/properties/Arguments/properties/TransformInput/properties/DataSource")

### DataSource Type

`object` ([Details](pipeline-definition-definitions-transformstep-properties-arguments-properties-transforminput-properties-datasource.md))

## SplitType



`SplitType`

*   is optional

*   Type: merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TransformStep/properties/Arguments/properties/TransformInput/properties/SplitType")

### SplitType Type

merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

one (and only one) of

*   [Untitled string in SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-stringargumentvalue-oneof-0.md "check type definition")

*   [Untitled object in SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-getfunction.md "check type definition")
