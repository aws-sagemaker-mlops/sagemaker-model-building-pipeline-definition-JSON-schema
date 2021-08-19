# Untitled object in SageMaker Pipeline Definition JSON schema Schema

```txt
https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TrainingStep/properties/Arguments/properties/VpcConfig
```



| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                           |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :--------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Forbidden             | none                | [pipeline-definition.schema.json*](../../out/pipeline-definition.schema.json "open original schema") |

## VpcConfig Type

`object` ([Details](pipeline-definition-definitions-trainingstep-properties-arguments-properties-vpcconfig.md))

# VpcConfig Properties

| Property                              | Type    | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                                                                             |
| :------------------------------------ | :------ | :------- | :------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [SecurityGroupIds](#securitygroupids) | `array` | Optional | cannot be null | [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-trainingstep-properties-arguments-properties-vpcconfig-properties-securitygroupids.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TrainingStep/properties/Arguments/properties/VpcConfig/properties/SecurityGroupIds") |
| [Subnets](#subnets)                   | `array` | Optional | cannot be null | [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-trainingstep-properties-arguments-properties-vpcconfig-properties-subnets.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TrainingStep/properties/Arguments/properties/VpcConfig/properties/Subnets")                   |

## SecurityGroupIds



`SecurityGroupIds`

*   is optional

*   Type: an array of merged types ([Details](pipeline-definition-definitions-stringargumentvalue.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-trainingstep-properties-arguments-properties-vpcconfig-properties-securitygroupids.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TrainingStep/properties/Arguments/properties/VpcConfig/properties/SecurityGroupIds")

### SecurityGroupIds Type

an array of merged types ([Details](pipeline-definition-definitions-stringargumentvalue.md))

## Subnets



`Subnets`

*   is optional

*   Type: an array of merged types ([Details](pipeline-definition-definitions-stringargumentvalue.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-trainingstep-properties-arguments-properties-vpcconfig-properties-subnets.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TrainingStep/properties/Arguments/properties/VpcConfig/properties/Subnets")

### Subnets Type

an array of merged types ([Details](pipeline-definition-definitions-stringargumentvalue.md))
