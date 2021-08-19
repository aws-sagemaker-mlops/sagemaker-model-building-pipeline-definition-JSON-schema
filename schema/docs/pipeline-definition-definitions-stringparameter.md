# Untitled undefined type in SageMaker Pipeline Definition JSON schema Schema

```txt
https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/properties/Parameters/items/oneOf/0
```



| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                           |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :--------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Forbidden             | none                | [pipeline-definition.schema.json*](../../out/pipeline-definition.schema.json "open original schema") |

## 0 Type

unknown

# 0 Properties

| Property                      | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                       |
| :---------------------------- | :------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Name](#name)                 | `string` | Required | cannot be null | [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-parametername.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/StringParameter/properties/Name")                                   |
| [Description](#description)   | `string` | Optional | cannot be null | [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-parameterdescription.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/StringParameter/properties/Description")                     |
| [DefaultValue](#defaultvalue) | `string` | Optional | cannot be null | [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-stringparameter-properties-defaultvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/StringParameter/properties/DefaultValue") |
| [Type](#type)                 | `string` | Optional | cannot be null | [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-stringparameter-properties-type.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/StringParameter/properties/Type")                 |

## Name



`Name`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-parametername.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/StringParameter/properties/Name")

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

*   defined in: [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-parameterdescription.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/StringParameter/properties/Description")

### Description Type

`string`

### Description Constraints

**maximum length**: the maximum number of characters for this string is: `4096`

**minimum length**: the minimum number of characters for this string is: `0`

## DefaultValue



`DefaultValue`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-stringparameter-properties-defaultvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/StringParameter/properties/DefaultValue")

### DefaultValue Type

`string`

### DefaultValue Constraints

**maximum length**: the maximum number of characters for this string is: `4096`

## Type



`Type`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition JSON schema](pipeline-definition-definitions-stringparameter-properties-type.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/StringParameter/properties/Type")

### Type Type

`string`

### Type Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value      | Explanation |
| :--------- | :---------- |
| `"String"` |             |
