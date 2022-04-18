## NetworkConfig Type

`object` ([Details](pipeline-definition-definitions-processingargs-properties-networkconfig.md))

# NetworkConfig Properties

| Property                                                                        | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                     |
| :------------------------------------------------------------------------------ | :------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [EnableInterContainerTrafficEncryption](#enableintercontainertrafficencryption) | Merged   | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-booleanargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ProcessingArgs/properties/NetworkConfig/properties/EnableInterContainerTrafficEncryption")             |
| [EnableNetworkIsolation](#enablenetworkisolation)                               | Merged   | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-booleanargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ProcessingArgs/properties/NetworkConfig/properties/EnableNetworkIsolation")                            |
| [VpcConfig](#vpcconfig)                                                         | `object` | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-processingargs-properties-networkconfig-properties-vpcconfig.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ProcessingArgs/properties/NetworkConfig/properties/VpcConfig") |

## EnableInterContainerTrafficEncryption



`EnableInterContainerTrafficEncryption`

*   is optional

*   Type: merged type ([Details](pipeline-definition-definitions-booleanargumentvalue.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-booleanargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ProcessingArgs/properties/NetworkConfig/properties/EnableInterContainerTrafficEncryption")

### EnableInterContainerTrafficEncryption Type

merged type ([Details](pipeline-definition-definitions-booleanargumentvalue.md))

one (and only one) of

*   [Untitled boolean in SageMaker Pipeline Definition](pipeline-definition-definitions-booleanargumentvalue-oneof-0.md "check type definition")

*   [Untitled object in SageMaker Pipeline Definition](pipeline-definition-definitions-getfunction.md "check type definition")

## EnableNetworkIsolation



`EnableNetworkIsolation`

*   is optional

*   Type: merged type ([Details](pipeline-definition-definitions-booleanargumentvalue.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-booleanargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ProcessingArgs/properties/NetworkConfig/properties/EnableNetworkIsolation")

### EnableNetworkIsolation Type

merged type ([Details](pipeline-definition-definitions-booleanargumentvalue.md))

one (and only one) of

*   [Untitled boolean in SageMaker Pipeline Definition](pipeline-definition-definitions-booleanargumentvalue-oneof-0.md "check type definition")

*   [Untitled object in SageMaker Pipeline Definition](pipeline-definition-definitions-getfunction.md "check type definition")

## VpcConfig



`VpcConfig`

*   is optional

*   Type: `object` ([Details](pipeline-definition-definitions-processingargs-properties-networkconfig-properties-vpcconfig.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-processingargs-properties-networkconfig-properties-vpcconfig.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ProcessingArgs/properties/NetworkConfig/properties/VpcConfig")

### VpcConfig Type

`object` ([Details](pipeline-definition-definitions-processingargs-properties-networkconfig-properties-vpcconfig.md))
