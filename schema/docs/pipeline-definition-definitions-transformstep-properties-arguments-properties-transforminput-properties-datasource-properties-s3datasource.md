# Untitled object in SageMaker Pipeline Definition JSON schema Schema

```txt
https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TransformStep/properties/Arguments/properties/TransformInput/properties/DataSource/properties/S3DataSource
```



| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                           |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :--------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Forbidden             | none                | [pipeline-definition.schema.json*](../../out/pipeline-definition.schema.json "open original schema") |

## S3DataSource Type

`object` ([Details](pipeline-definition-definitions-transformstep-properties-arguments-properties-transforminput-properties-datasource-properties-s3datasource.md))

# S3DataSource Properties

| Property                  | Type   | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                                                            |
| :------------------------ | :----- | :------- | :------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [S3DataType](#s3datatype) | Merged | Optional | cannot be null | [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TransformStep/properties/Arguments/properties/TransformInput/properties/DataSource/properties/S3DataSource/properties/S3DataType") |
| [S3Uri](#s3uri)           | Merged | Optional | cannot be null | [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TransformStep/properties/Arguments/properties/TransformInput/properties/DataSource/properties/S3DataSource/properties/S3Uri")      |

## S3DataType



`S3DataType`

*   is optional

*   Type: merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TransformStep/properties/Arguments/properties/TransformInput/properties/DataSource/properties/S3DataSource/properties/S3DataType")

### S3DataType Type

merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

one (and only one) of

*   [Untitled string in SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-stringargumentvalue-oneof-0.md "check type definition")

*   [Untitled object in SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-getfunction.md "check type definition")

## S3Uri



`S3Uri`

*   is optional

*   Type: merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TransformStep/properties/Arguments/properties/TransformInput/properties/DataSource/properties/S3DataSource/properties/S3Uri")

### S3Uri Type

merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

one (and only one) of

*   [Untitled string in SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-stringargumentvalue-oneof-0.md "check type definition")

*   [Untitled object in SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-getfunction.md "check type definition")
