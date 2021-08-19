# Untitled object in SageMaker Pipeline Definition JSON schema Schema

```txt
https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/OrCondition/properties/Conditions/items/anyOf/0
```



| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                           |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :--------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Forbidden             | none                | [pipeline-definition.schema.json*](../../out/pipeline-definition.schema.json "open original schema") |

## 0 Type

`object` ([Details](pipeline-definition-definitions-binarycondition.md))

# 0 Properties

| Property                  | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                   |
| :------------------------ | :------- | :------- | :------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [LeftValue](#leftvalue)   | Merged   | Required | cannot be null | [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-binarycondition-properties-leftvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/BinaryCondition/properties/LeftValue")   |
| [RightValue](#rightvalue) | Merged   | Required | cannot be null | [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-binarycondition-properties-rightvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/BinaryCondition/properties/RightValue") |
| [Type](#type)             | `string` | Required | cannot be null | [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-binarycondition-properties-type.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/BinaryCondition/properties/Type")             |

## LeftValue



`LeftValue`

*   is required

*   Type: merged type ([Details](pipeline-definition-definitions-binarycondition-properties-leftvalue.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-binarycondition-properties-leftvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/BinaryCondition/properties/LeftValue")

### LeftValue Type

merged type ([Details](pipeline-definition-definitions-binarycondition-properties-leftvalue.md))

any of

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

## RightValue



`RightValue`

*   is required

*   Type: merged type ([Details](pipeline-definition-definitions-binarycondition-properties-rightvalue.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-binarycondition-properties-rightvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/BinaryCondition/properties/RightValue")

### RightValue Type

merged type ([Details](pipeline-definition-definitions-binarycondition-properties-rightvalue.md))

any of

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

## Type



`Type`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-binarycondition-properties-type.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/BinaryCondition/properties/Type")

### Type Type

`string`

### Type Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                    | Explanation |
| :----------------------- | :---------- |
| `"GreaterThan"`          |             |
| `"LessThan"`             |             |
| `"LessThanOrEqualTo"`    |             |
| `"GreaterThanOrEqualTo"` |             |
| `"Equals"`               |             |
| `"NotEquals"`            |             |
