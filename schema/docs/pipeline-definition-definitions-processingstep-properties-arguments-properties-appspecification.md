## AppSpecification Type

`object` ([Details](pipeline-definition-definitions-processingstep-properties-arguments-properties-appspecification.md))

# AppSpecification Properties

| Property                                    | Type    | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                                                                                         |
| :------------------------------------------ | :------ | :------- | :------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [ContainerArguments](#containerarguments)   | `array` | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-processingstep-properties-arguments-properties-appspecification-properties-containerarguments.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ProcessingStep/properties/Arguments/properties/AppSpecification/properties/ContainerArguments")   |
| [ContainerEntrypoint](#containerentrypoint) | `array` | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-processingstep-properties-arguments-properties-appspecification-properties-containerentrypoint.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ProcessingStep/properties/Arguments/properties/AppSpecification/properties/ContainerEntrypoint") |
| [ImageUri](#imageuri)                       | Merged  | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ProcessingStep/properties/Arguments/properties/AppSpecification/properties/ImageUri")                                                                                       |

## ContainerArguments



`ContainerArguments`

*   is optional

*   Type: an array of merged types ([Details](pipeline-definition-definitions-stringargumentvalue.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-processingstep-properties-arguments-properties-appspecification-properties-containerarguments.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ProcessingStep/properties/Arguments/properties/AppSpecification/properties/ContainerArguments")

### ContainerArguments Type

an array of merged types ([Details](pipeline-definition-definitions-stringargumentvalue.md))

## ContainerEntrypoint



`ContainerEntrypoint`

*   is optional

*   Type: an array of merged types ([Details](pipeline-definition-definitions-stringargumentvalue.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-processingstep-properties-arguments-properties-appspecification-properties-containerentrypoint.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ProcessingStep/properties/Arguments/properties/AppSpecification/properties/ContainerEntrypoint")

### ContainerEntrypoint Type

an array of merged types ([Details](pipeline-definition-definitions-stringargumentvalue.md))

## ImageUri



`ImageUri`

*   is optional

*   Type: merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ProcessingStep/properties/Arguments/properties/AppSpecification/properties/ImageUri")

### ImageUri Type

merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

one (and only one) of

*   [Untitled string in SageMaker Pipeline Definition](pipeline-definition-definitions-stringargumentvalue-oneof-0.md "check type definition")

*   [Untitled object in SageMaker Pipeline Definition](pipeline-definition-definitions-getfunction.md "check type definition")
