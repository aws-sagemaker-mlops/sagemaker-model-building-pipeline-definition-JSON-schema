# Untitled object in SageMaker Pipeline Definition JSON schema Schema

```txt
https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/OrCondition/properties/Conditions/items/anyOf/1
```



| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                           |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :--------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Forbidden             | none                | [pipeline-definition.schema.json*](../../out/pipeline-definition.schema.json "open original schema") |

## 1 Type

`object` ([Details](pipeline-definition-definitions-incondition.md))

# 1 Properties

| Property        | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                 |
| :-------------- | :------- | :------- | :------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Type](#type)   | `string` | Required | cannot be null | [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-incondition-properties-type.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/InCondition/properties/Type")   |
| [Value](#value) | Merged   | Required | cannot be null | [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-incondition-properties-value.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/InCondition/properties/Value") |
| [In](#in)       | `array`  | Required | cannot be null | [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-incondition-properties-in.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/InCondition/properties/In")       |

## Type



`Type`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-incondition-properties-type.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/InCondition/properties/Type")

### Type Type

`string`

### Type Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value     | Explanation |
| :-------- | :---------- |
| `"In"`    |             |
| `"NotIn"` |             |

## Value



`Value`

*   is required

*   Type: merged type ([Details](pipeline-definition-definitions-incondition-properties-value.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-incondition-properties-value.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/InCondition/properties/Value")

### Value Type

merged type ([Details](pipeline-definition-definitions-incondition-properties-value.md))

one (and only one) of

*   one (and only one) of

    *   [Untitled string in SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-stringargumentvalue-oneof-0.md "check type definition")

    *   [Untitled object in SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-getfunction.md "check type definition")

*   one (and only one) of

    *   [Untitled boolean in SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-booleanargumentvalue-oneof-0.md "check type definition")

    *   [Untitled object in SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-getfunction.md "check type definition")

*   one (and only one) of

    *   [Untitled integer in SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-integerargumentvalue-oneof-0.md "check type definition")

    *   [Untitled object in SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-getfunction.md "check type definition")

*   one (and only one) of

    *   [Untitled number in SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-floatargumentvalue-oneof-0.md "check type definition")

    *   [Untitled object in SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-getfunction.md "check type definition")

## In



`In`

*   is required

*   Type: an array of merged types ([Details](pipeline-definition-definitions-incondition-properties-in-items.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-incondition-properties-in.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/InCondition/properties/In")

### In Type

an array of merged types ([Details](pipeline-definition-definitions-incondition-properties-in-items.md))
