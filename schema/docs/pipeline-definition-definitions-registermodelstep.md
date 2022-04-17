## 5 Type

`object` ([Details](pipeline-definition-definitions-registermodelstep.md))

# 5 Properties

| Property                        | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                 |
| :------------------------------ | :------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Name](#name)                   | `string` | Required | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-stepname.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/RegisterModelStep/properties/Name")                                            |
| [Type](#type)                   | `string` | Required | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-registermodelstep-properties-type.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/RegisterModelStep/properties/Type")                   |
| [DependsOn](#dependson)         | `array`  | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-registermodelstep-properties-dependson.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/RegisterModelStep/properties/DependsOn")         |
| [DisplayName](#displayname)     | `string` | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-stepname.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/RegisterModelStep/properties/DisplayName")                                     |
| [Description](#description)     | `string` | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-parameterdescription.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/RegisterModelStep/properties/Description")                         |
| [RetryPolicies](#retrypolicies) | `array`  | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-registermodelstep-properties-retrypolicies.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/RegisterModelStep/properties/RetryPolicies") |
| [Arguments](#arguments)         | `object` | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-registermodelstep-properties-arguments.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/RegisterModelStep/properties/Arguments")         |

## Name



`Name`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-stepname.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/RegisterModelStep/properties/Name")

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

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-registermodelstep-properties-type.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/RegisterModelStep/properties/Type")

### Type Type

`string`

### Type Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value             | Explanation |
| :---------------- | :---------- |
| `"RegisterModel"` |             |

## DependsOn



`DependsOn`

*   is optional

*   Type: `string[]`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-registermodelstep-properties-dependson.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/RegisterModelStep/properties/DependsOn")

### DependsOn Type

`string[]`

## DisplayName



`DisplayName`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-stepname.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/RegisterModelStep/properties/DisplayName")

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

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-parameterdescription.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/RegisterModelStep/properties/Description")

### Description Type

`string`

### Description Constraints

**maximum length**: the maximum number of characters for this string is: `4096`

**minimum length**: the minimum number of characters for this string is: `0`

## RetryPolicies



`RetryPolicies`

*   is optional

*   Type: `object[]` ([Details](pipeline-definition-definitions-retrypolicy.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-registermodelstep-properties-retrypolicies.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/RegisterModelStep/properties/RetryPolicies")

### RetryPolicies Type

`object[]` ([Details](pipeline-definition-definitions-retrypolicy.md))

## Arguments



`Arguments`

*   is optional

*   Type: `object` ([Details](pipeline-definition-definitions-registermodelstep-properties-arguments.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-registermodelstep-properties-arguments.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/RegisterModelStep/properties/Arguments")

### Arguments Type

`object` ([Details](pipeline-definition-definitions-registermodelstep-properties-arguments.md))
