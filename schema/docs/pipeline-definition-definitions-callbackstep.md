## 7 Type

`object` ([Details](pipeline-definition-definitions-callbackstep.md))

# 7 Properties

| Property                              | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                    |
| :------------------------------------ | :------- | :------- | :------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Name](#name)                         | `string` | Required | cannot be null | [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-stepname.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/CallbackStep/properties/Name")                                             |
| [Type](#type)                         | `string` | Required | cannot be null | [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-callbackstep-properties-type.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/CallbackStep/properties/Type")                         |
| [DependsOn](#dependson)               | `array`  | Optional | cannot be null | [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-callbackstep-properties-dependson.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/CallbackStep/properties/DependsOn")               |
| [DisplayName](#displayname)           | `string` | Optional | cannot be null | [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-stepname.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/CallbackStep/properties/DisplayName")                                      |
| [Description](#description)           | `string` | Optional | cannot be null | [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-parameterdescription.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/CallbackStep/properties/Description")                          |
| [SqsQueueUrl](#sqsqueueurl)           | `string` | Required | cannot be null | [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-callbackstep-properties-sqsqueueurl.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/CallbackStep/properties/SqsQueueUrl")           |
| [CacheConfig](#cacheconfig)           | `object` | Optional | cannot be null | [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-cacheconfig.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/CallbackStep/properties/CacheConfig")                                   |
| [Arguments](#arguments)               | `object` | Optional | cannot be null | [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-callbackstep-properties-arguments.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/CallbackStep/properties/Arguments")               |
| [OutputParameters](#outputparameters) | `array`  | Optional | cannot be null | [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-callbackstep-properties-outputparameters.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/CallbackStep/properties/OutputParameters") |

## Name



`Name`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-stepname.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/CallbackStep/properties/Name")

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

*   defined in: [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-callbackstep-properties-type.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/CallbackStep/properties/Type")

### Type Type

`string`

### Type Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value        | Explanation |
| :----------- | :---------- |
| `"Callback"` |             |

## DependsOn



`DependsOn`

*   is optional

*   Type: `string[]`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-callbackstep-properties-dependson.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/CallbackStep/properties/DependsOn")

### DependsOn Type

`string[]`

## DisplayName



`DisplayName`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-stepname.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/CallbackStep/properties/DisplayName")

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

*   defined in: [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-parameterdescription.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/CallbackStep/properties/Description")

### Description Type

`string`

### Description Constraints

**maximum length**: the maximum number of characters for this string is: `4096`

**minimum length**: the minimum number of characters for this string is: `0`

## SqsQueueUrl



`SqsQueueUrl`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-callbackstep-properties-sqsqueueurl.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/CallbackStep/properties/SqsQueueUrl")

### SqsQueueUrl Type

`string`

## CacheConfig



`CacheConfig`

*   is optional

*   Type: `object` ([Details](pipeline-definition-definitions-cacheconfig.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-cacheconfig.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/CallbackStep/properties/CacheConfig")

### CacheConfig Type

`object` ([Details](pipeline-definition-definitions-cacheconfig.md))

## Arguments



`Arguments`

*   is optional

*   Type: `object` ([Details](pipeline-definition-definitions-callbackstep-properties-arguments.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-callbackstep-properties-arguments.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/CallbackStep/properties/Arguments")

### Arguments Type

`object` ([Details](pipeline-definition-definitions-callbackstep-properties-arguments.md))

## OutputParameters



`OutputParameters`

*   is optional

*   Type: `object[]` ([Details](pipeline-definition-definitions-callbackstep-properties-outputparameters-items.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-callbackstep-properties-outputparameters.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/CallbackStep/properties/OutputParameters")

### OutputParameters Type

`object[]` ([Details](pipeline-definition-definitions-callbackstep-properties-outputparameters-items.md))
