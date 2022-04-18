## PrimaryContainer Type

`object` ([Details](pipeline-definition-definitions-containerdefinition.md))

# PrimaryContainer Properties

| Property                                                  | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                  |
| :-------------------------------------------------------- | :------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [ContainerHostname](#containerhostname)                   | Merged   | Optional | cannot be null | [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ContainerDefinition/properties/ContainerHostname")                            |
| [Environment](#environment)                               | `object` | Optional | cannot be null | [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-containerdefinition-properties-environment.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ContainerDefinition/properties/Environment")           |
| [Image](#image)                                           | Merged   | Optional | cannot be null | [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ContainerDefinition/properties/Image")                                        |
| [ImageConfig](#imageconfig)                               | `object` | Optional | cannot be null | [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-containerdefinition-properties-imageconfig.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ContainerDefinition/properties/ImageConfig")           |
| [InferenceSpecificationName](#inferencespecificationname) | Merged   | Optional | cannot be null | [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ContainerDefinition/properties/InferenceSpecificationName")                   |
| [Mode](#mode)                                             | `string` | Optional | cannot be null | [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-containerdefinition-properties-mode.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ContainerDefinition/properties/Mode")                         |
| [ModelDataUrl](#modeldataurl)                             | `string` | Optional | cannot be null | [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-containerdefinition-properties-modeldataurl.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ContainerDefinition/properties/ModelDataUrl")         |
| [ModelPackageName](#modelpackagename)                     | Merged   | Optional | cannot be null | [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ContainerDefinition/properties/ModelPackageName")                             |
| [MultiModelConfig](#multimodelconfig)                     | `object` | Optional | cannot be null | [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-containerdefinition-properties-multimodelconfig.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ContainerDefinition/properties/MultiModelConfig") |

## ContainerHostname



`ContainerHostname`

*   is optional

*   Type: merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ContainerDefinition/properties/ContainerHostname")

### ContainerHostname Type

merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

one (and only one) of

*   [Untitled string in SageMaker Pipeline Definition Schema](pipeline-definition-definitions-stringargumentvalue-oneof-0.md "check type definition")

*   [Untitled object in SageMaker Pipeline Definition Schema](pipeline-definition-definitions-getfunction.md "check type definition")

## Environment



`Environment`

*   is optional

*   Type: `object` ([Details](pipeline-definition-definitions-containerdefinition-properties-environment.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-containerdefinition-properties-environment.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ContainerDefinition/properties/Environment")

### Environment Type

`object` ([Details](pipeline-definition-definitions-containerdefinition-properties-environment.md))

## Image



`Image`

*   is optional

*   Type: merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ContainerDefinition/properties/Image")

### Image Type

merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

one (and only one) of

*   [Untitled string in SageMaker Pipeline Definition Schema](pipeline-definition-definitions-stringargumentvalue-oneof-0.md "check type definition")

*   [Untitled object in SageMaker Pipeline Definition Schema](pipeline-definition-definitions-getfunction.md "check type definition")

## ImageConfig



`ImageConfig`

*   is optional

*   Type: `object` ([Details](pipeline-definition-definitions-containerdefinition-properties-imageconfig.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-containerdefinition-properties-imageconfig.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ContainerDefinition/properties/ImageConfig")

### ImageConfig Type

`object` ([Details](pipeline-definition-definitions-containerdefinition-properties-imageconfig.md))

## InferenceSpecificationName



`InferenceSpecificationName`

*   is optional

*   Type: merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ContainerDefinition/properties/InferenceSpecificationName")

### InferenceSpecificationName Type

merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

one (and only one) of

*   [Untitled string in SageMaker Pipeline Definition Schema](pipeline-definition-definitions-stringargumentvalue-oneof-0.md "check type definition")

*   [Untitled object in SageMaker Pipeline Definition Schema](pipeline-definition-definitions-getfunction.md "check type definition")

## Mode



`Mode`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-containerdefinition-properties-mode.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ContainerDefinition/properties/Mode")

### Mode Type

`string`

### Mode Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value           | Explanation |
| :-------------- | :---------- |
| `"SingleModel"` |             |
| `"MultiModel"`  |             |

## ModelDataUrl



`ModelDataUrl`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-containerdefinition-properties-modeldataurl.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ContainerDefinition/properties/ModelDataUrl")

### ModelDataUrl Type

`string`

### ModelDataUrl Constraints

**maximum length**: the maximum number of characters for this string is: `1024`

**minimum length**: the minimum number of characters for this string is: `0`

**pattern**: the string must match the following regular expression:&#x20;

```regexp
^(https|s3)://([^/]+)/?(.*)$
```

[try pattern](https://regexr.com/?expression=%5E\(https%7Cs3\)%3A%2F%2F\(%5B%5E%2F%5D%2B\)%2F%3F\(.*\)%24 "try regular expression with regexr.com")

## ModelPackageName



`ModelPackageName`

*   is optional

*   Type: merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ContainerDefinition/properties/ModelPackageName")

### ModelPackageName Type

merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

one (and only one) of

*   [Untitled string in SageMaker Pipeline Definition Schema](pipeline-definition-definitions-stringargumentvalue-oneof-0.md "check type definition")

*   [Untitled object in SageMaker Pipeline Definition Schema](pipeline-definition-definitions-getfunction.md "check type definition")

## MultiModelConfig



`MultiModelConfig`

*   is optional

*   Type: `object` ([Details](pipeline-definition-definitions-containerdefinition-properties-multimodelconfig.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-containerdefinition-properties-multimodelconfig.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ContainerDefinition/properties/MultiModelConfig")

### MultiModelConfig Type

`object` ([Details](pipeline-definition-definitions-containerdefinition-properties-multimodelconfig.md))
