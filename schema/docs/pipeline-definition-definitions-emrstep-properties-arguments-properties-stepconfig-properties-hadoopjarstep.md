## HadoopJarStep Type

`object` ([Details](pipeline-definition-definitions-emrstep-properties-arguments-properties-stepconfig-properties-hadoopjarstep.md))

# HadoopJarStep Properties

| Property                  | Type    | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                                                                                               |
| :------------------------ | :------ | :------- | :------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Args](#args)             | `array` | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-emrstep-properties-arguments-properties-stepconfig-properties-hadoopjarstep-properties-args.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/EMRStep/properties/Arguments/properties/StepConfig/properties/HadoopJarStep/properties/Args")             |
| [Jar](#jar)               | Merged  | Required | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/EMRStep/properties/Arguments/properties/StepConfig/properties/HadoopJarStep/properties/Jar")                                                                                      |
| [MainClass](#mainclass)   | Merged  | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/EMRStep/properties/Arguments/properties/StepConfig/properties/HadoopJarStep/properties/MainClass")                                                                                |
| [Properties](#properties) | `array` | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-emrstep-properties-arguments-properties-stepconfig-properties-hadoopjarstep-properties-properties.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/EMRStep/properties/Arguments/properties/StepConfig/properties/HadoopJarStep/properties/Properties") |

## Args



`Args`

*   is optional

*   Type: an array of merged types ([Details](pipeline-definition-definitions-stringargumentvalue.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-emrstep-properties-arguments-properties-stepconfig-properties-hadoopjarstep-properties-args.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/EMRStep/properties/Arguments/properties/StepConfig/properties/HadoopJarStep/properties/Args")

### Args Type

an array of merged types ([Details](pipeline-definition-definitions-stringargumentvalue.md))

## Jar



`Jar`

*   is required

*   Type: merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/EMRStep/properties/Arguments/properties/StepConfig/properties/HadoopJarStep/properties/Jar")

### Jar Type

merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

one (and only one) of

*   [Untitled string in SageMaker Pipeline Definition](pipeline-definition-definitions-stringargumentvalue-oneof-0.md "check type definition")

*   [Untitled object in SageMaker Pipeline Definition](pipeline-definition-definitions-getfunction.md "check type definition")

## MainClass



`MainClass`

*   is optional

*   Type: merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/EMRStep/properties/Arguments/properties/StepConfig/properties/HadoopJarStep/properties/MainClass")

### MainClass Type

merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

one (and only one) of

*   [Untitled string in SageMaker Pipeline Definition](pipeline-definition-definitions-stringargumentvalue-oneof-0.md "check type definition")

*   [Untitled object in SageMaker Pipeline Definition](pipeline-definition-definitions-getfunction.md "check type definition")

## Properties



`Properties`

*   is optional

*   Type: `object[]` ([Details](pipeline-definition-definitions-emrstep-properties-arguments-properties-stepconfig-properties-hadoopjarstep-properties-properties-items.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-emrstep-properties-arguments-properties-stepconfig-properties-hadoopjarstep-properties-properties.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/EMRStep/properties/Arguments/properties/StepConfig/properties/HadoopJarStep/properties/Properties")

### Properties Type

`object[]` ([Details](pipeline-definition-definitions-emrstep-properties-arguments-properties-stepconfig-properties-hadoopjarstep-properties-properties-items.md))
