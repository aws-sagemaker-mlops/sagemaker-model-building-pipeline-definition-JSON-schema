# Untitled object in SageMaker Pipeline Definition JSON schema Schema

```txt
https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ConditionStep/properties/Arguments/properties/Conditions/items/oneOf/2
```



| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                           |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :--------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Forbidden             | none                | [pipeline-definition.schema.json*](../../out/pipeline-definition.schema.json "open original schema") |

## 2 Type

`object` ([Details](pipeline-definition-definitions-orcondition.md))

# 2 Properties

| Property                  | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                           |
| :------------------------ | :------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Type](#type)             | `string` | Required | cannot be null | [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-orcondition-properties-type.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/OrCondition/properties/Type")             |
| [Conditions](#conditions) | `array`  | Required | cannot be null | [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-orcondition-properties-conditions.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/OrCondition/properties/Conditions") |

## Type



`Type`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-orcondition-properties-type.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/OrCondition/properties/Type")

### Type Type

`string`

### Type Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value  | Explanation |
| :----- | :---------- |
| `"Or"` |             |

## Conditions



`Conditions`

*   is required

*   Type: an array of merged types ([Details](pipeline-definition-definitions-orcondition-properties-conditions-items.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-orcondition-properties-conditions.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/OrCondition/properties/Conditions")

### Conditions Type

an array of merged types ([Details](pipeline-definition-definitions-orcondition-properties-conditions-items.md))
