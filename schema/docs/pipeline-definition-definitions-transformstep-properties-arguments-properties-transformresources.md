# Untitled object in SageMaker Pipeline Definition JSON schema Schema

```txt
https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TransformStep/properties/Arguments/properties/TransformResources
```



| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                           |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :--------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Forbidden             | none                | [pipeline-definition.schema.json*](../../out/pipeline-definition.schema.json "open original schema") |

## TransformResources Type

`object` ([Details](pipeline-definition-definitions-transformstep-properties-arguments-properties-transformresources.md))

# TransformResources Properties

| Property                          | Type   | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                      |
| :-------------------------------- | :----- | :------- | :------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [InstanceCount](#instancecount)   | Merged | Optional | cannot be null | [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-integerargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TransformStep/properties/Arguments/properties/TransformResources/properties/InstanceCount") |
| [InstanceType](#instancetype)     | Merged | Optional | cannot be null | [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TransformStep/properties/Arguments/properties/TransformResources/properties/InstanceType")   |
| [VolumeKmsKeyId](#volumekmskeyid) | Merged | Optional | cannot be null | [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TransformStep/properties/Arguments/properties/TransformResources/properties/VolumeKmsKeyId") |

## InstanceCount



`InstanceCount`

*   is optional

*   Type: merged type ([Details](pipeline-definition-definitions-integerargumentvalue.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-integerargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TransformStep/properties/Arguments/properties/TransformResources/properties/InstanceCount")

### InstanceCount Type

merged type ([Details](pipeline-definition-definitions-integerargumentvalue.md))

one (and only one) of

*   [Untitled integer in SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-integerargumentvalue-oneof-0.md "check type definition")

*   [Untitled object in SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-getfunction.md "check type definition")

## InstanceType



`InstanceType`

*   is optional

*   Type: merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TransformStep/properties/Arguments/properties/TransformResources/properties/InstanceType")

### InstanceType Type

merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

one (and only one) of

*   [Untitled string in SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-stringargumentvalue-oneof-0.md "check type definition")

*   [Untitled object in SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-getfunction.md "check type definition")

## VolumeKmsKeyId



`VolumeKmsKeyId`

*   is optional

*   Type: merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TransformStep/properties/Arguments/properties/TransformResources/properties/VolumeKmsKeyId")

### VolumeKmsKeyId Type

merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

one (and only one) of

*   [Untitled string in SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-stringargumentvalue-oneof-0.md "check type definition")

*   [Untitled object in SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-getfunction.md "check type definition")
