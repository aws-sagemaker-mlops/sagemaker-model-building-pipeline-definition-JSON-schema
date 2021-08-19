# Untitled undefined type in SageMaker Pipeline Definition JSON schema Schema

```txt
https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/properties/Parameters/items/oneOf/1
```



| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                           |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :--------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Forbidden             | none                | [pipeline-definition.schema.json*](../../out/pipeline-definition.schema.json "open original schema") |

## 1 Type

unknown

# 1 Properties

| Property                      | Type      | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                         |
| :---------------------------- | :-------- | :------- | :------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Name](#name)                 | `string`  | Required | cannot be null | [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-parametername.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/IntegerParameter/properties/Name")                                    |
| [Description](#description)   | `string`  | Optional | cannot be null | [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-parameterdescription.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/IntegerParameter/properties/Description")                      |
| [DefaultValue](#defaultvalue) | `integer` | Optional | cannot be null | [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-integerparameter-properties-defaultvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/IntegerParameter/properties/DefaultValue") |
| [Type](#type)                 | `string`  | Required | cannot be null | [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-integerparameter-properties-type.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/IntegerParameter/properties/Type")                 |

## Name



`Name`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-parametername.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/IntegerParameter/properties/Name")

### Name Type

`string`

### Name Constraints

**pattern**: the string must match the following regular expression: 

```regexp
^[A-Za-z0-9\-_]{1,64}$
```

[try pattern](https://regexr.com/?expression=%5E%5BA-Za-z0-9%5C-\_%5D%7B1%2C64%7D%24 "try regular expression with regexr.com")

## Description



`Description`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-parameterdescription.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/IntegerParameter/properties/Description")

### Description Type

`string`

### Description Constraints

**maximum length**: the maximum number of characters for this string is: `4096`

**minimum length**: the minimum number of characters for this string is: `0`

## DefaultValue



`DefaultValue`

*   is optional

*   Type: `integer`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-integerparameter-properties-defaultvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/IntegerParameter/properties/DefaultValue")

### DefaultValue Type

`integer`

## Type



`Type`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-integerparameter-properties-type.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/IntegerParameter/properties/Type")

### Type Type

`string`

### Type Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value       | Explanation |
| :---------- | :---------- |
| `"Integer"` |             |
