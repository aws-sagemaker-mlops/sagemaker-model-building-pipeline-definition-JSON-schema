# Untitled object in SageMaker Pipeline Definition JSON schema Schema

```txt
https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TrainingStep/properties/Arguments/properties/DebugHookConfig/properties/CollectionConfigurations/items
```



| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                           |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :--------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Forbidden             | none                | [pipeline-definition.schema.json*](../../out/pipeline-definition.schema.json "open original schema") |

## items Type

`object` ([Details](pipeline-definition-definitions-trainingstep-properties-arguments-properties-debughookconfig-properties-collectionconfigurations-items.md))

# items Properties

| Property                                      | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| :-------------------------------------------- | :------- | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [CollectionName](#collectionname)             | Merged   | Optional | cannot be null | [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TrainingStep/properties/Arguments/properties/DebugHookConfig/properties/CollectionConfigurations/items/properties/CollectionName")                                                                                                                          |
| [CollectionParameters](#collectionparameters) | `object` | Optional | cannot be null | [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-trainingstep-properties-arguments-properties-debughookconfig-properties-collectionconfigurations-items-properties-collectionparameters.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TrainingStep/properties/Arguments/properties/DebugHookConfig/properties/CollectionConfigurations/items/properties/CollectionParameters") |

## CollectionName



`CollectionName`

*   is optional

*   Type: merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TrainingStep/properties/Arguments/properties/DebugHookConfig/properties/CollectionConfigurations/items/properties/CollectionName")

### CollectionName Type

merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

one (and only one) of

*   [Untitled string in SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-stringargumentvalue-oneof-0.md "check type definition")

*   [Untitled object in SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-getfunction.md "check type definition")

## CollectionParameters



`CollectionParameters`

*   is optional

*   Type: `object` ([Details](pipeline-definition-definitions-trainingstep-properties-arguments-properties-debughookconfig-properties-collectionconfigurations-items-properties-collectionparameters.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-trainingstep-properties-arguments-properties-debughookconfig-properties-collectionconfigurations-items-properties-collectionparameters.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TrainingStep/properties/Arguments/properties/DebugHookConfig/properties/CollectionConfigurations/items/properties/CollectionParameters")

### CollectionParameters Type

`object` ([Details](pipeline-definition-definitions-trainingstep-properties-arguments-properties-debughookconfig-properties-collectionconfigurations-items-properties-collectionparameters.md))
