# Untitled object in SageMaker Pipeline Definition JSON schema Schema

```txt
https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/properties/Steps/items/oneOf/2
```



| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                           |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :--------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Forbidden             | none                | [pipeline-definition.schema.json*](../../out/pipeline-definition.schema.json "open original schema") |

## 2 Type

`object` ([Details](pipeline-definition-definitions-processingstep.md))

# 2 Properties

| Property                | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                               |
| :---------------------- | :------- | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Name](#name)           | `string` | Required | cannot be null | [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-stepname.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ProcessingStep/properties/Name")                                 |
| [Type](#type)           | `string` | Required | cannot be null | [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-processingstep-properties-type.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ProcessingStep/properties/Type")           |
| [Arguments](#arguments) | `object` | Optional | cannot be null | [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-processingstep-properties-arguments.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ProcessingStep/properties/Arguments") |

## Name



`Name`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-stepname.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ProcessingStep/properties/Name")

### Name Type

`string`

### Name Constraints

**pattern**: the string must match the following regular expression: 

```regexp
^[A-Za-z0-9\-_]{1,64}$
```

[try pattern](https://regexr.com/?expression=%5E%5BA-Za-z0-9%5C-\_%5D%7B1%2C64%7D%24 "try regular expression with regexr.com")

## Type



`Type`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-processingstep-properties-type.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ProcessingStep/properties/Type")

### Type Type

`string`

### Type Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value          | Explanation |
| :------------- | :---------- |
| `"Processing"` |             |

## Arguments



`Arguments`

*   is optional

*   Type: `object` ([Details](pipeline-definition-definitions-processingstep-properties-arguments.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-processingstep-properties-arguments.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ProcessingStep/properties/Arguments")

### Arguments Type

`object` ([Details](pipeline-definition-definitions-processingstep-properties-arguments.md))
