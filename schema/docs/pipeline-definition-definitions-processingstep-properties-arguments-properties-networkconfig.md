# Untitled object in SageMaker Pipeline Definition JSON schema Schema

```txt
https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ProcessingStep/properties/Arguments/properties/NetworkConfig
```



| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                           |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :--------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Forbidden             | none                | [pipeline-definition.schema.json*](../../out/pipeline-definition.schema.json "open original schema") |

## NetworkConfig Type

`object` ([Details](pipeline-definition-definitions-processingstep-properties-arguments-properties-networkconfig.md))

# NetworkConfig Properties

| Property                                                                        | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                                                                           |
| :------------------------------------------------------------------------------ | :------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [EnableInterContainerTrafficEncryption](#enableintercontainertrafficencryption) | Merged   | Optional | cannot be null | [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-booleanargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ProcessingStep/properties/Arguments/properties/NetworkConfig/properties/EnableInterContainerTrafficEncryption")                                  |
| [EnableNetworkIsolation](#enablenetworkisolation)                               | Merged   | Optional | cannot be null | [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-booleanargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ProcessingStep/properties/Arguments/properties/NetworkConfig/properties/EnableNetworkIsolation")                                                 |
| [VpcConfig](#vpcconfig)                                                         | `object` | Optional | cannot be null | [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-processingstep-properties-arguments-properties-networkconfig-properties-vpcconfig.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ProcessingStep/properties/Arguments/properties/NetworkConfig/properties/VpcConfig") |

## EnableInterContainerTrafficEncryption



`EnableInterContainerTrafficEncryption`

*   is optional

*   Type: merged type ([Details](pipeline-definition-definitions-booleanargumentvalue.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-booleanargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ProcessingStep/properties/Arguments/properties/NetworkConfig/properties/EnableInterContainerTrafficEncryption")

### EnableInterContainerTrafficEncryption Type

merged type ([Details](pipeline-definition-definitions-booleanargumentvalue.md))

one (and only one) of

*   [Untitled boolean in SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-booleanargumentvalue-oneof-0.md "check type definition")

*   [Untitled object in SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-getfunction.md "check type definition")

## EnableNetworkIsolation



`EnableNetworkIsolation`

*   is optional

*   Type: merged type ([Details](pipeline-definition-definitions-booleanargumentvalue.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-booleanargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ProcessingStep/properties/Arguments/properties/NetworkConfig/properties/EnableNetworkIsolation")

### EnableNetworkIsolation Type

merged type ([Details](pipeline-definition-definitions-booleanargumentvalue.md))

one (and only one) of

*   [Untitled boolean in SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-booleanargumentvalue-oneof-0.md "check type definition")

*   [Untitled object in SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-getfunction.md "check type definition")

## VpcConfig



`VpcConfig`

*   is optional

*   Type: `object` ([Details](pipeline-definition-definitions-processingstep-properties-arguments-properties-networkconfig-properties-vpcconfig.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-processingstep-properties-arguments-properties-networkconfig-properties-vpcconfig.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ProcessingStep/properties/Arguments/properties/NetworkConfig/properties/VpcConfig")

### VpcConfig Type

`object` ([Details](pipeline-definition-definitions-processingstep-properties-arguments-properties-networkconfig-properties-vpcconfig.md))
