# Untitled object in SageMaker Pipeline Definition JSON schema Schema

```txt
https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TrainingStep/properties/Arguments/properties/InputDataConfig/items/properties/DataSource
```



| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                           |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :--------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [pipeline-definition.schema.json*](../../out/pipeline-definition.schema.json "open original schema") |

## DataSource Type

`object` ([Details](pipeline-definition-definitions-trainingstep-properties-arguments-properties-inputdataconfig-items-properties-datasource.md))

# DataSource Properties

| Property                                      | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| :-------------------------------------------- | :------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [FileSystemDataSource](#filesystemdatasource) | `object` | Optional | cannot be null | [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-trainingstep-properties-arguments-properties-inputdataconfig-items-properties-datasource-properties-filesystemdatasource.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TrainingStep/properties/Arguments/properties/InputDataConfig/items/properties/DataSource/properties/FileSystemDataSource") |
| [S3DataSource](#s3datasource)                 | `object` | Optional | cannot be null | [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-trainingstep-properties-arguments-properties-inputdataconfig-items-properties-datasource-properties-s3datasource.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TrainingStep/properties/Arguments/properties/InputDataConfig/items/properties/DataSource/properties/S3DataSource")                 |

## FileSystemDataSource



`FileSystemDataSource`

*   is optional

*   Type: `object` ([Details](pipeline-definition-definitions-trainingstep-properties-arguments-properties-inputdataconfig-items-properties-datasource-properties-filesystemdatasource.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-trainingstep-properties-arguments-properties-inputdataconfig-items-properties-datasource-properties-filesystemdatasource.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TrainingStep/properties/Arguments/properties/InputDataConfig/items/properties/DataSource/properties/FileSystemDataSource")

### FileSystemDataSource Type

`object` ([Details](pipeline-definition-definitions-trainingstep-properties-arguments-properties-inputdataconfig-items-properties-datasource-properties-filesystemdatasource.md))

## S3DataSource



`S3DataSource`

*   is optional

*   Type: `object` ([Details](pipeline-definition-definitions-trainingstep-properties-arguments-properties-inputdataconfig-items-properties-datasource-properties-s3datasource.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-trainingstep-properties-arguments-properties-inputdataconfig-items-properties-datasource-properties-s3datasource.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TrainingStep/properties/Arguments/properties/InputDataConfig/items/properties/DataSource/properties/S3DataSource")

### S3DataSource Type

`object` ([Details](pipeline-definition-definitions-trainingstep-properties-arguments-properties-inputdataconfig-items-properties-datasource-properties-s3datasource.md))
