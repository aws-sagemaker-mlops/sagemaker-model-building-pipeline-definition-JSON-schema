## 2 Type

unknown

# 2 Properties

| Property                      | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                         |
| :---------------------------- | :------- | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Name](#name)                 | `string` | Required | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-parametername.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/FloatParameter/properties/Name")                                  |
| [Description](#description)   | `string` | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-parameterdescription.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/FloatParameter/properties/Description")                    |
| [DefaultValue](#defaultvalue) | `number` | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-floatparameter-properties-defaultvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/FloatParameter/properties/DefaultValue") |
| [Type](#type)                 | `string` | Required | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-floatparameter-properties-type.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/FloatParameter/properties/Type")                 |

## Name



`Name`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-parametername.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/FloatParameter/properties/Name")

### Name Type

`string`

### Name Constraints

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

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-parameterdescription.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/FloatParameter/properties/Description")

### Description Type

`string`

### Description Constraints

**maximum length**: the maximum number of characters for this string is: `4096`

**minimum length**: the minimum number of characters for this string is: `0`

## DefaultValue



`DefaultValue`

*   is optional

*   Type: `number`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-floatparameter-properties-defaultvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/FloatParameter/properties/DefaultValue")

### DefaultValue Type

`number`

## Type



`Type`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-floatparameter-properties-type.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/FloatParameter/properties/Type")

### Type Type

`string`

### Type Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value     | Explanation |
| :-------- | :---------- |
| `"Float"` |             |
