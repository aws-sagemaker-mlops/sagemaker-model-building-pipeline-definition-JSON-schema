## 1 Type

unknown

# 1 Properties

| Property                    | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                       |
| :-------------------------- | :------- | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Name](#name)               | `string` | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-stepname.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/FailStep/properties/Name")                           |
| [Type](#type)               | `string` | Required | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-failstep-properties-type.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/FailStep/properties/Type")           |
| [DependsOn](#dependson)     | `array`  | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-failstep-properties-dependson.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/FailStep/properties/DependsOn") |
| [DisplayName](#displayname) | `string` | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-stepname.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/FailStep/properties/DisplayName")                    |
| [Description](#description) | `string` | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-parameterdescription.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/FailStep/properties/Description")        |
| [Arguments](#arguments)     | `object` | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-failstep-properties-arguments.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/FailStep/properties/Arguments") |

## Name



`Name`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-stepname.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/FailStep/properties/Name")

### Name Type

`string`

### Name Constraints

**pattern**: the string must match the following regular expression:&#x20;

```regexp
^[A-Za-z0-9\-_]{1,64}$
```

[try pattern](https://regexr.com/?expression=%5E%5BA-Za-z0-9%5C-_%5D%7B1%2C64%7D%24 "try regular expression with regexr.com")

## Type



`Type`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-failstep-properties-type.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/FailStep/properties/Type")

### Type Type

`string`

### Type Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value    | Explanation |
| :------- | :---------- |
| `"Fail"` |             |

## DependsOn



`DependsOn`

*   is optional

*   Type: `string[]`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-failstep-properties-dependson.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/FailStep/properties/DependsOn")

### DependsOn Type

`string[]`

## DisplayName



`DisplayName`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-stepname.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/FailStep/properties/DisplayName")

### DisplayName Type

`string`

### DisplayName Constraints

**pattern**: the string must match the following regular expression:&#x20;

```regexp
^[A-Za-z0-9\-_]{1,64}$
```

[try pattern](https://regexr.com/?expression=%5E%5BA-Za-z0-9%5C-_%5D%7B1%2C64%7D%24 "try regular expression with regexr.com")

## Description



`Description`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-parameterdescription.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/FailStep/properties/Description")

### Description Type

`string`

### Description Constraints

**maximum length**: the maximum number of characters for this string is: `4096`

**minimum length**: the minimum number of characters for this string is: `0`

## Arguments



`Arguments`

*   is optional

*   Type: `object` ([Details](pipeline-definition-definitions-failstep-properties-arguments.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-failstep-properties-arguments.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/FailStep/properties/Arguments")

### Arguments Type

`object` ([Details](pipeline-definition-definitions-failstep-properties-arguments.md))
