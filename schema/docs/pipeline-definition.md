## SageMaker Pipeline Definition Type

`object` ([SageMaker Pipeline Definition](pipeline-definition.md))

# SageMaker Pipeline Definition Properties

| Property                  | Type     | Required | Nullable       | Defined by                                                                                                                                                                                               |
| :------------------------ | :------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Version](#version)       | `string` | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-properties-version.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/properties/Version")       |
| [Metadata](#metadata)     | `object` | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-properties-metadata.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/properties/Metadata")     |
| [Parameters](#parameters) | `array`  | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-properties-parameters.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/properties/Parameters") |
| [Steps](#steps)           | `array`  | Required | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-properties-steps.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/properties/Steps")           |

## Version



`Version`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-properties-version.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/properties/Version")

### Version Type

`string`

### Version Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value          | Explanation |
| :------------- | :---------- |
| `"2020-12-01"` |             |

## Metadata



`Metadata`

*   is optional

*   Type: `object` ([Details](pipeline-definition-properties-metadata.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-properties-metadata.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/properties/Metadata")

### Metadata Type

`object` ([Details](pipeline-definition-properties-metadata.md))

## Parameters



`Parameters`

*   is optional

*   Type: an array of merged types ([Details](pipeline-definition-properties-parameters-items.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-properties-parameters.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/properties/Parameters")

### Parameters Type

an array of merged types ([Details](pipeline-definition-properties-parameters-items.md))

## Steps



`Steps`

*   is required

*   Type: an array of merged types ([Details](pipeline-definition-properties-steps-items.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-properties-steps.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/properties/Steps")

### Steps Type

an array of merged types ([Details](pipeline-definition-properties-steps-items.md))

# SageMaker Pipeline Definition Definitions

## Definitions group ParameterName

Reference this group by using

```json
{"$ref":"https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ParameterName"}
```

| Property | Type | Required | Nullable | Defined by |
| :------- | :--- | :------- | :------- | :--------- |

## Definitions group ParameterDescription

Reference this group by using

```json
{"$ref":"https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ParameterDescription"}
```

| Property | Type | Required | Nullable | Defined by |
| :------- | :--- | :------- | :------- | :--------- |

## Definitions group StringParameter

Reference this group by using

```json
{"$ref":"https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/StringParameter"}
```

| Property                      | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                           |
| :---------------------------- | :------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Name](#name)                 | `string` | Required | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-stringparameter-properties-name.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/StringParameter/properties/Name")                 |
| [Description](#description)   | `string` | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-stringparameter-properties-description.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/StringParameter/properties/Description")   |
| [DefaultValue](#defaultvalue) | `string` | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-stringparameter-properties-defaultvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/StringParameter/properties/DefaultValue") |
| [Type](#type)                 | `string` | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-stringparameter-properties-type.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/StringParameter/properties/Type")                 |

### Name



`Name`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-stringparameter-properties-name.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/StringParameter/properties/Name")

#### Name Type

`string`

#### Name Constraints

**pattern**: the string must match the following regular expression:&#x20;

```regexp
^[A-Za-z0-9\-_]{1,64}$
```

[try pattern](https://regexr.com/?expression=%5E%5BA-Za-z0-9%5C-_%5D%7B1%2C64%7D%24 "try regular expression with regexr.com")

### Description



`Description`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-stringparameter-properties-description.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/StringParameter/properties/Description")

#### Description Type

`string`

#### Description Constraints

**maximum length**: the maximum number of characters for this string is: `4096`

**minimum length**: the minimum number of characters for this string is: `0`

### DefaultValue



`DefaultValue`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-stringparameter-properties-defaultvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/StringParameter/properties/DefaultValue")

#### DefaultValue Type

`string`

#### DefaultValue Constraints

**maximum length**: the maximum number of characters for this string is: `4096`

### Type



`Type`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-stringparameter-properties-type.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/StringParameter/properties/Type")

#### Type Type

`string`

#### Type Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value      | Explanation |
| :--------- | :---------- |
| `"String"` |             |

## Definitions group IntegerParameter

Reference this group by using

```json
{"$ref":"https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/IntegerParameter"}
```

| Property                        | Type      | Required | Nullable       | Defined by                                                                                                                                                                                                                                                             |
| :------------------------------ | :-------- | :------- | :------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Name](#name-1)                 | `string`  | Required | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-integerparameter-properties-name.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/IntegerParameter/properties/Name")                 |
| [Description](#description-1)   | `string`  | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-integerparameter-properties-description.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/IntegerParameter/properties/Description")   |
| [DefaultValue](#defaultvalue-1) | `integer` | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-integerparameter-properties-defaultvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/IntegerParameter/properties/DefaultValue") |
| [Type](#type-1)                 | `string`  | Required | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-integerparameter-properties-type.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/IntegerParameter/properties/Type")                 |

### Name



`Name`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-integerparameter-properties-name.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/IntegerParameter/properties/Name")

#### Name Type

`string`

#### Name Constraints

**pattern**: the string must match the following regular expression:&#x20;

```regexp
^[A-Za-z0-9\-_]{1,64}$
```

[try pattern](https://regexr.com/?expression=%5E%5BA-Za-z0-9%5C-_%5D%7B1%2C64%7D%24 "try regular expression with regexr.com")

### Description



`Description`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-integerparameter-properties-description.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/IntegerParameter/properties/Description")

#### Description Type

`string`

#### Description Constraints

**maximum length**: the maximum number of characters for this string is: `4096`

**minimum length**: the minimum number of characters for this string is: `0`

### DefaultValue



`DefaultValue`

*   is optional

*   Type: `integer`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-integerparameter-properties-defaultvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/IntegerParameter/properties/DefaultValue")

#### DefaultValue Type

`integer`

### Type



`Type`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-integerparameter-properties-type.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/IntegerParameter/properties/Type")

#### Type Type

`string`

#### Type Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value       | Explanation |
| :---------- | :---------- |
| `"Integer"` |             |

## Definitions group FloatParameter

Reference this group by using

```json
{"$ref":"https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/FloatParameter"}
```

| Property                        | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                         |
| :------------------------------ | :------- | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Name](#name-2)                 | `string` | Required | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-floatparameter-properties-name.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/FloatParameter/properties/Name")                 |
| [Description](#description-2)   | `string` | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-floatparameter-properties-description.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/FloatParameter/properties/Description")   |
| [DefaultValue](#defaultvalue-2) | `number` | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-floatparameter-properties-defaultvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/FloatParameter/properties/DefaultValue") |
| [Type](#type-2)                 | `string` | Required | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-floatparameter-properties-type.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/FloatParameter/properties/Type")                 |

### Name



`Name`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-floatparameter-properties-name.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/FloatParameter/properties/Name")

#### Name Type

`string`

#### Name Constraints

**pattern**: the string must match the following regular expression:&#x20;

```regexp
^[A-Za-z0-9\-_]{1,64}$
```

[try pattern](https://regexr.com/?expression=%5E%5BA-Za-z0-9%5C-_%5D%7B1%2C64%7D%24 "try regular expression with regexr.com")

### Description



`Description`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-floatparameter-properties-description.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/FloatParameter/properties/Description")

#### Description Type

`string`

#### Description Constraints

**maximum length**: the maximum number of characters for this string is: `4096`

**minimum length**: the minimum number of characters for this string is: `0`

### DefaultValue



`DefaultValue`

*   is optional

*   Type: `number`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-floatparameter-properties-defaultvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/FloatParameter/properties/DefaultValue")

#### DefaultValue Type

`number`

### Type



`Type`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-floatparameter-properties-type.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/FloatParameter/properties/Type")

#### Type Type

`string`

#### Type Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value     | Explanation |
| :-------- | :---------- |
| `"Float"` |             |

## Definitions group BooleanParameter

Reference this group by using

```json
{"$ref":"https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/BooleanParameter"}
```

| Property                        | Type      | Required | Nullable       | Defined by                                                                                                                                                                                                                                                             |
| :------------------------------ | :-------- | :------- | :------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Name](#name-3)                 | `string`  | Required | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-booleanparameter-properties-name.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/BooleanParameter/properties/Name")                 |
| [Description](#description-3)   | `string`  | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-booleanparameter-properties-description.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/BooleanParameter/properties/Description")   |
| [DefaultValue](#defaultvalue-3) | `boolean` | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-booleanparameter-properties-defaultvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/BooleanParameter/properties/DefaultValue") |
| [Type](#type-3)                 | `string`  | Required | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-booleanparameter-properties-type.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/BooleanParameter/properties/Type")                 |

### Name



`Name`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-booleanparameter-properties-name.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/BooleanParameter/properties/Name")

#### Name Type

`string`

#### Name Constraints

**pattern**: the string must match the following regular expression:&#x20;

```regexp
^[A-Za-z0-9\-_]{1,64}$
```

[try pattern](https://regexr.com/?expression=%5E%5BA-Za-z0-9%5C-_%5D%7B1%2C64%7D%24 "try regular expression with regexr.com")

### Description



`Description`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-booleanparameter-properties-description.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/BooleanParameter/properties/Description")

#### Description Type

`string`

#### Description Constraints

**maximum length**: the maximum number of characters for this string is: `4096`

**minimum length**: the minimum number of characters for this string is: `0`

### DefaultValue



`DefaultValue`

*   is optional

*   Type: `boolean`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-booleanparameter-properties-defaultvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/BooleanParameter/properties/DefaultValue")

#### DefaultValue Type

`boolean`

### Type



`Type`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-booleanparameter-properties-type.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/BooleanParameter/properties/Type")

#### Type Type

`string`

#### Type Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value       | Explanation |
| :---------- | :---------- |
| `"Boolean"` |             |

## Definitions group GetFunction

Reference this group by using

```json
{"$ref":"https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/GetFunction"}
```

| Property    | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                 |
| :---------- | :------- | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Get](#get) | `string` | Required | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-getfunction-properties-get.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/GetFunction/properties/Get") |

### Get



`Get`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-getfunction-properties-get.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/GetFunction/properties/Get")

#### Get Type

`string`

## Definitions group JoinFunction

Reference this group by using

```json
{"$ref":"https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/JoinFunction"}
```

| Property             | Type          | Required | Nullable       | Defined by                                                                                                                                                                                                                                            |
| :------------------- | :------------ | :------- | :------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Std:Join](#stdjoin) | Not specified | Required | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-joinfunction-properties-stdjoin.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/JoinFunction/properties/Std:Join") |

### Std:Join



`Std:Join`

*   is required

*   Type: unknown

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-joinfunction-properties-stdjoin.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/JoinFunction/properties/Std:Join")

#### Std:Join Type

unknown

## Definitions group StringArgumentValue

Reference this group by using

```json
{"$ref":"https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/StringArgumentValue"}
```

| Property | Type | Required | Nullable | Defined by |
| :------- | :--- | :------- | :------- | :--------- |

## Definitions group IntegerArgumentValue

Reference this group by using

```json
{"$ref":"https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/IntegerArgumentValue"}
```

| Property | Type | Required | Nullable | Defined by |
| :------- | :--- | :------- | :------- | :--------- |

## Definitions group FloatArgumentValue

Reference this group by using

```json
{"$ref":"https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/FloatArgumentValue"}
```

| Property | Type | Required | Nullable | Defined by |
| :------- | :--- | :------- | :------- | :--------- |

## Definitions group BooleanArgumentValue

Reference this group by using

```json
{"$ref":"https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/BooleanArgumentValue"}
```

| Property | Type | Required | Nullable | Defined by |
| :------- | :--- | :------- | :------- | :--------- |

## Definitions group StepName

Reference this group by using

```json
{"$ref":"https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/StepName"}
```

| Property | Type | Required | Nullable | Defined by |
| :------- | :--- | :------- | :------- | :--------- |

## Definitions group BinaryCondition

Reference this group by using

```json
{"$ref":"https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/BinaryCondition"}
```

| Property                  | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                       |
| :------------------------ | :------- | :------- | :------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [LeftValue](#leftvalue)   | Merged   | Required | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-binarycondition-properties-leftvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/BinaryCondition/properties/LeftValue")   |
| [RightValue](#rightvalue) | Merged   | Required | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-binarycondition-properties-rightvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/BinaryCondition/properties/RightValue") |
| [Type](#type-4)           | `string` | Required | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-binarycondition-properties-type.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/BinaryCondition/properties/Type")             |

### LeftValue



`LeftValue`

*   is required

*   Type: merged type ([Details](pipeline-definition-definitions-binarycondition-properties-leftvalue.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-binarycondition-properties-leftvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/BinaryCondition/properties/LeftValue")

#### LeftValue Type

merged type ([Details](pipeline-definition-definitions-binarycondition-properties-leftvalue.md))

any of

*   one (and only one) of

    *   [Untitled string in SageMaker Pipeline Definition](pipeline-definition-definitions-stringargumentvalue-oneof-0.md "check type definition")

    *   [Untitled object in SageMaker Pipeline Definition](pipeline-definition-definitions-getfunction.md "check type definition")

*   one (and only one) of

    *   [Untitled boolean in SageMaker Pipeline Definition](pipeline-definition-definitions-booleanargumentvalue-oneof-0.md "check type definition")

    *   [Untitled object in SageMaker Pipeline Definition](pipeline-definition-definitions-getfunction.md "check type definition")

*   one (and only one) of

    *   [Untitled integer in SageMaker Pipeline Definition](pipeline-definition-definitions-integerargumentvalue-oneof-0.md "check type definition")

    *   [Untitled object in SageMaker Pipeline Definition](pipeline-definition-definitions-getfunction.md "check type definition")

*   one (and only one) of

    *   [Untitled number in SageMaker Pipeline Definition](pipeline-definition-definitions-floatargumentvalue-oneof-0.md "check type definition")

    *   [Untitled object in SageMaker Pipeline Definition](pipeline-definition-definitions-getfunction.md "check type definition")

### RightValue



`RightValue`

*   is required

*   Type: merged type ([Details](pipeline-definition-definitions-binarycondition-properties-rightvalue.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-binarycondition-properties-rightvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/BinaryCondition/properties/RightValue")

#### RightValue Type

merged type ([Details](pipeline-definition-definitions-binarycondition-properties-rightvalue.md))

any of

*   one (and only one) of

    *   [Untitled string in SageMaker Pipeline Definition](pipeline-definition-definitions-stringargumentvalue-oneof-0.md "check type definition")

    *   [Untitled object in SageMaker Pipeline Definition](pipeline-definition-definitions-getfunction.md "check type definition")

*   one (and only one) of

    *   [Untitled boolean in SageMaker Pipeline Definition](pipeline-definition-definitions-booleanargumentvalue-oneof-0.md "check type definition")

    *   [Untitled object in SageMaker Pipeline Definition](pipeline-definition-definitions-getfunction.md "check type definition")

*   one (and only one) of

    *   [Untitled integer in SageMaker Pipeline Definition](pipeline-definition-definitions-integerargumentvalue-oneof-0.md "check type definition")

    *   [Untitled object in SageMaker Pipeline Definition](pipeline-definition-definitions-getfunction.md "check type definition")

*   one (and only one) of

    *   [Untitled number in SageMaker Pipeline Definition](pipeline-definition-definitions-floatargumentvalue-oneof-0.md "check type definition")

    *   [Untitled object in SageMaker Pipeline Definition](pipeline-definition-definitions-getfunction.md "check type definition")

### Type



`Type`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-binarycondition-properties-type.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/BinaryCondition/properties/Type")

#### Type Type

`string`

#### Type Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                    | Explanation |
| :----------------------- | :---------- |
| `"GreaterThan"`          |             |
| `"LessThan"`             |             |
| `"LessThanOrEqualTo"`    |             |
| `"GreaterThanOrEqualTo"` |             |
| `"Equals"`               |             |
| `"NotEquals"`            |             |

## Definitions group InCondition

Reference this group by using

```json
{"$ref":"https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/InCondition"}
```

| Property        | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                     |
| :-------------- | :------- | :------- | :------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Type](#type-5) | `string` | Required | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-incondition-properties-type.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/InCondition/properties/Type")   |
| [Value](#value) | Merged   | Required | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-incondition-properties-value.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/InCondition/properties/Value") |
| [In](#in)       | `array`  | Required | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-incondition-properties-in.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/InCondition/properties/In")       |

### Type



`Type`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-incondition-properties-type.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/InCondition/properties/Type")

#### Type Type

`string`

#### Type Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value     | Explanation |
| :-------- | :---------- |
| `"In"`    |             |
| `"NotIn"` |             |

### Value



`Value`

*   is required

*   Type: merged type ([Details](pipeline-definition-definitions-incondition-properties-value.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-incondition-properties-value.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/InCondition/properties/Value")

#### Value Type

merged type ([Details](pipeline-definition-definitions-incondition-properties-value.md))

one (and only one) of

*   one (and only one) of

    *   [Untitled string in SageMaker Pipeline Definition](pipeline-definition-definitions-stringargumentvalue-oneof-0.md "check type definition")

    *   [Untitled object in SageMaker Pipeline Definition](pipeline-definition-definitions-getfunction.md "check type definition")

*   one (and only one) of

    *   [Untitled boolean in SageMaker Pipeline Definition](pipeline-definition-definitions-booleanargumentvalue-oneof-0.md "check type definition")

    *   [Untitled object in SageMaker Pipeline Definition](pipeline-definition-definitions-getfunction.md "check type definition")

*   one (and only one) of

    *   [Untitled integer in SageMaker Pipeline Definition](pipeline-definition-definitions-integerargumentvalue-oneof-0.md "check type definition")

    *   [Untitled object in SageMaker Pipeline Definition](pipeline-definition-definitions-getfunction.md "check type definition")

*   one (and only one) of

    *   [Untitled number in SageMaker Pipeline Definition](pipeline-definition-definitions-floatargumentvalue-oneof-0.md "check type definition")

    *   [Untitled object in SageMaker Pipeline Definition](pipeline-definition-definitions-getfunction.md "check type definition")

### In



`In`

*   is required

*   Type: an array of merged types ([Details](pipeline-definition-definitions-incondition-properties-in-items.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-incondition-properties-in.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/InCondition/properties/In")

#### In Type

an array of merged types ([Details](pipeline-definition-definitions-incondition-properties-in-items.md))

## Definitions group OrCondition

Reference this group by using

```json
{"$ref":"https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/OrCondition"}
```

| Property                  | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                               |
| :------------------------ | :------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Type](#type-6)           | `string` | Required | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-orcondition-properties-type.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/OrCondition/properties/Type")             |
| [Conditions](#conditions) | `array`  | Required | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-orcondition-properties-conditions.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/OrCondition/properties/Conditions") |

### Type



`Type`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-orcondition-properties-type.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/OrCondition/properties/Type")

#### Type Type

`string`

#### Type Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value  | Explanation |
| :----- | :---------- |
| `"Or"` |             |

### Conditions



`Conditions`

*   is required

*   Type: an array of merged types ([Details](pipeline-definition-definitions-orcondition-properties-conditions-items.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-orcondition-properties-conditions.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/OrCondition/properties/Conditions")

#### Conditions Type

an array of merged types ([Details](pipeline-definition-definitions-orcondition-properties-conditions-items.md))

## Definitions group RetryPolicy

Reference this group by using

```json
{"$ref":"https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/RetryPolicy"}
```

| Property                            | Type      | Required | Nullable       | Defined by                                                                                                                                                                                                                                                         |
| :---------------------------------- | :-------- | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [ExceptionType](#exceptiontype)     | `string`  | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-retrypolicy-properties-exceptiontype.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/RetryPolicy/properties/ExceptionType")     |
| [IntervalSeconds](#intervalseconds) | `integer` | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-retrypolicy-properties-intervalseconds.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/RetryPolicy/properties/IntervalSeconds") |
| [BackoffRate](#backoffrate)         | `number`  | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-retrypolicy-properties-backoffrate.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/RetryPolicy/properties/BackoffRate")         |
| [ExpireAfterMin](#expireaftermin)   | `integer` | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-retrypolicy-properties-expireaftermin.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/RetryPolicy/properties/ExpireAfterMin")   |
| [MaxAttempts](#maxattempts)         | `integer` | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-retrypolicy-properties-maxattempts.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/RetryPolicy/properties/MaxAttempts")         |

### ExceptionType



`ExceptionType`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-retrypolicy-properties-exceptiontype.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/RetryPolicy/properties/ExceptionType")

#### ExceptionType Type

`string`

#### ExceptionType Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                            | Explanation |
| :------------------------------- | :---------- |
| `"Step.SERVICE_FAULT"`           |             |
| `"Step.THROTTLING"`              |             |
| `"SageMaker.JOB_INTERNAL_ERROR"` |             |
| `"SageMaker.CAPACITY_ERROR"`     |             |
| `"SageMaker.RESOURCE_LIMIT"`     |             |
| `"Emr.RESOURCE_LIMIT"`           |             |

### IntervalSeconds



`IntervalSeconds`

*   is optional

*   Type: `integer`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-retrypolicy-properties-intervalseconds.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/RetryPolicy/properties/IntervalSeconds")

#### IntervalSeconds Type

`integer`

### BackoffRate



`BackoffRate`

*   is optional

*   Type: `number`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-retrypolicy-properties-backoffrate.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/RetryPolicy/properties/BackoffRate")

#### BackoffRate Type

`number`

### ExpireAfterMin



`ExpireAfterMin`

*   is optional

*   Type: `integer`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-retrypolicy-properties-expireaftermin.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/RetryPolicy/properties/ExpireAfterMin")

#### ExpireAfterMin Type

`integer`

### MaxAttempts



`MaxAttempts`

*   is optional

*   Type: `integer`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-retrypolicy-properties-maxattempts.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/RetryPolicy/properties/MaxAttempts")

#### MaxAttempts Type

`integer`

## Definitions group ConditionStep

Reference this group by using

```json
{"$ref":"https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ConditionStep"}
```

| Property                      | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                     |
| :---------------------------- | :------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Name](#name-4)               | `string` | Required | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-conditionstep-properties-name.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ConditionStep/properties/Name")               |
| [Type](#type-7)               | `string` | Required | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-conditionstep-properties-type.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ConditionStep/properties/Type")               |
| [DependsOn](#dependson)       | `array`  | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-conditionstep-properties-dependson.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ConditionStep/properties/DependsOn")     |
| [DisplayName](#displayname)   | `string` | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-conditionstep-properties-displayname.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ConditionStep/properties/DisplayName") |
| [Description](#description-4) | `string` | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-conditionstep-properties-description.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ConditionStep/properties/Description") |
| [Arguments](#arguments)       | `object` | Required | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-conditionstep-properties-arguments.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ConditionStep/properties/Arguments")     |

### Name



`Name`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-conditionstep-properties-name.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ConditionStep/properties/Name")

#### Name Type

`string`

#### Name Constraints

**pattern**: the string must match the following regular expression:&#x20;

```regexp
^[A-Za-z0-9\-_]{1,64}$
```

[try pattern](https://regexr.com/?expression=%5E%5BA-Za-z0-9%5C-_%5D%7B1%2C64%7D%24 "try regular expression with regexr.com")

### Type



`Type`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-conditionstep-properties-type.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ConditionStep/properties/Type")

#### Type Type

`string`

#### Type Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value         | Explanation |
| :------------ | :---------- |
| `"Condition"` |             |

### DependsOn



`DependsOn`

*   is optional

*   Type: `string[]`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-conditionstep-properties-dependson.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ConditionStep/properties/DependsOn")

#### DependsOn Type

`string[]`

### DisplayName



`DisplayName`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-conditionstep-properties-displayname.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ConditionStep/properties/DisplayName")

#### DisplayName Type

`string`

#### DisplayName Constraints

**pattern**: the string must match the following regular expression:&#x20;

```regexp
^[A-Za-z0-9\-_]{1,64}$
```

[try pattern](https://regexr.com/?expression=%5E%5BA-Za-z0-9%5C-_%5D%7B1%2C64%7D%24 "try regular expression with regexr.com")

### Description



`Description`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-conditionstep-properties-description.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ConditionStep/properties/Description")

#### Description Type

`string`

#### Description Constraints

**maximum length**: the maximum number of characters for this string is: `4096`

**minimum length**: the minimum number of characters for this string is: `0`

### Arguments



`Arguments`

*   is required

*   Type: `object` ([Details](pipeline-definition-definitions-conditionstep-properties-arguments.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-conditionstep-properties-arguments.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ConditionStep/properties/Arguments")

#### Arguments Type

`object` ([Details](pipeline-definition-definitions-conditionstep-properties-arguments.md))

## Definitions group TrainingStep

Reference this group by using

```json
{"$ref":"https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TrainingStep"}
```

| Property                        | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                       |
| :------------------------------ | :------- | :------- | :------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Name](#name-5)                 | `string` | Required | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-trainingstep-properties-name.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TrainingStep/properties/Name")                   |
| [Type](#type-8)                 | `string` | Required | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-trainingstep-properties-type.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TrainingStep/properties/Type")                   |
| [DependsOn](#dependson-1)       | `array`  | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-trainingstep-properties-dependson.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TrainingStep/properties/DependsOn")         |
| [DisplayName](#displayname-1)   | `string` | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-trainingstep-properties-displayname.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TrainingStep/properties/DisplayName")     |
| [Description](#description-5)   | `string` | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-trainingstep-properties-description.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TrainingStep/properties/Description")     |
| [RetryPolicies](#retrypolicies) | `array`  | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-trainingstep-properties-retrypolicies.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TrainingStep/properties/RetryPolicies") |
| [Arguments](#arguments-1)       | `object` | Required | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-trainingstep-properties-arguments.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TrainingStep/properties/Arguments")         |

### Name



`Name`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-trainingstep-properties-name.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TrainingStep/properties/Name")

#### Name Type

`string`

#### Name Constraints

**pattern**: the string must match the following regular expression:&#x20;

```regexp
^[A-Za-z0-9\-_]{1,64}$
```

[try pattern](https://regexr.com/?expression=%5E%5BA-Za-z0-9%5C-_%5D%7B1%2C64%7D%24 "try regular expression with regexr.com")

### Type



`Type`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-trainingstep-properties-type.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TrainingStep/properties/Type")

#### Type Type

`string`

#### Type Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value        | Explanation |
| :----------- | :---------- |
| `"Training"` |             |

### DependsOn



`DependsOn`

*   is optional

*   Type: `string[]`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-trainingstep-properties-dependson.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TrainingStep/properties/DependsOn")

#### DependsOn Type

`string[]`

### DisplayName



`DisplayName`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-trainingstep-properties-displayname.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TrainingStep/properties/DisplayName")

#### DisplayName Type

`string`

#### DisplayName Constraints

**pattern**: the string must match the following regular expression:&#x20;

```regexp
^[A-Za-z0-9\-_]{1,64}$
```

[try pattern](https://regexr.com/?expression=%5E%5BA-Za-z0-9%5C-_%5D%7B1%2C64%7D%24 "try regular expression with regexr.com")

### Description



`Description`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-trainingstep-properties-description.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TrainingStep/properties/Description")

#### Description Type

`string`

#### Description Constraints

**maximum length**: the maximum number of characters for this string is: `4096`

**minimum length**: the minimum number of characters for this string is: `0`

### RetryPolicies



`RetryPolicies`

*   is optional

*   Type: `object[]` ([Details](pipeline-definition-definitions-retrypolicy.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-trainingstep-properties-retrypolicies.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TrainingStep/properties/RetryPolicies")

#### RetryPolicies Type

`object[]` ([Details](pipeline-definition-definitions-retrypolicy.md))

### Arguments



`Arguments`

*   is required

*   Type: `object` ([Details](pipeline-definition-definitions-trainingstep-properties-arguments.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-trainingstep-properties-arguments.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TrainingStep/properties/Arguments")

#### Arguments Type

`object` ([Details](pipeline-definition-definitions-trainingstep-properties-arguments.md))

## Definitions group ProcessingStep

Reference this group by using

```json
{"$ref":"https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ProcessingStep"}
```

| Property                          | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                           |
| :-------------------------------- | :------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Name](#name-6)                   | `string` | Required | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-processingstep-properties-name.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ProcessingStep/properties/Name")                   |
| [Type](#type-9)                   | `string` | Required | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-processingstep-properties-type.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ProcessingStep/properties/Type")                   |
| [DependsOn](#dependson-2)         | `array`  | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-processingstep-properties-dependson.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ProcessingStep/properties/DependsOn")         |
| [DisplayName](#displayname-2)     | `string` | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-processingstep-properties-displayname.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ProcessingStep/properties/DisplayName")     |
| [Description](#description-6)     | `string` | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-processingstep-properties-description.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ProcessingStep/properties/Description")     |
| [RetryPolicies](#retrypolicies-1) | `array`  | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-processingstep-properties-retrypolicies.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ProcessingStep/properties/RetryPolicies") |
| [Arguments](#arguments-2)         | `object` | Required | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-processingstep-properties-arguments.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ProcessingStep/properties/Arguments")         |

### Name



`Name`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-processingstep-properties-name.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ProcessingStep/properties/Name")

#### Name Type

`string`

#### Name Constraints

**pattern**: the string must match the following regular expression:&#x20;

```regexp
^[A-Za-z0-9\-_]{1,64}$
```

[try pattern](https://regexr.com/?expression=%5E%5BA-Za-z0-9%5C-_%5D%7B1%2C64%7D%24 "try regular expression with regexr.com")

### Type



`Type`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-processingstep-properties-type.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ProcessingStep/properties/Type")

#### Type Type

`string`

#### Type Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value          | Explanation |
| :------------- | :---------- |
| `"Processing"` |             |

### DependsOn



`DependsOn`

*   is optional

*   Type: `string[]`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-processingstep-properties-dependson.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ProcessingStep/properties/DependsOn")

#### DependsOn Type

`string[]`

### DisplayName



`DisplayName`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-processingstep-properties-displayname.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ProcessingStep/properties/DisplayName")

#### DisplayName Type

`string`

#### DisplayName Constraints

**pattern**: the string must match the following regular expression:&#x20;

```regexp
^[A-Za-z0-9\-_]{1,64}$
```

[try pattern](https://regexr.com/?expression=%5E%5BA-Za-z0-9%5C-_%5D%7B1%2C64%7D%24 "try regular expression with regexr.com")

### Description



`Description`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-processingstep-properties-description.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ProcessingStep/properties/Description")

#### Description Type

`string`

#### Description Constraints

**maximum length**: the maximum number of characters for this string is: `4096`

**minimum length**: the minimum number of characters for this string is: `0`

### RetryPolicies



`RetryPolicies`

*   is optional

*   Type: `object[]` ([Details](pipeline-definition-definitions-retrypolicy.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-processingstep-properties-retrypolicies.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ProcessingStep/properties/RetryPolicies")

#### RetryPolicies Type

`object[]` ([Details](pipeline-definition-definitions-retrypolicy.md))

### Arguments



`Arguments`

*   is required

*   Type: `object` ([Details](pipeline-definition-definitions-processingstep-properties-arguments.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-processingstep-properties-arguments.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ProcessingStep/properties/Arguments")

#### Arguments Type

`object` ([Details](pipeline-definition-definitions-processingstep-properties-arguments.md))

## Definitions group TransformStep

Reference this group by using

```json
{"$ref":"https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TransformStep"}
```

| Property                          | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                         |
| :-------------------------------- | :------- | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Name](#name-7)                   | `string` | Required | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-transformstep-properties-name.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TransformStep/properties/Name")                   |
| [Type](#type-10)                  | `string` | Required | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-transformstep-properties-type.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TransformStep/properties/Type")                   |
| [DependsOn](#dependson-3)         | `array`  | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-transformstep-properties-dependson.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TransformStep/properties/DependsOn")         |
| [DisplayName](#displayname-3)     | `string` | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-transformstep-properties-displayname.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TransformStep/properties/DisplayName")     |
| [Description](#description-7)     | `string` | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-transformstep-properties-description.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TransformStep/properties/Description")     |
| [RetryPolicies](#retrypolicies-2) | `array`  | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-transformstep-properties-retrypolicies.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TransformStep/properties/RetryPolicies") |
| [Arguments](#arguments-3)         | `object` | Required | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-transformstep-properties-arguments.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TransformStep/properties/Arguments")         |

### Name



`Name`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-transformstep-properties-name.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TransformStep/properties/Name")

#### Name Type

`string`

#### Name Constraints

**pattern**: the string must match the following regular expression:&#x20;

```regexp
^[A-Za-z0-9\-_]{1,64}$
```

[try pattern](https://regexr.com/?expression=%5E%5BA-Za-z0-9%5C-_%5D%7B1%2C64%7D%24 "try regular expression with regexr.com")

### Type



`Type`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-transformstep-properties-type.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TransformStep/properties/Type")

#### Type Type

`string`

#### Type Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value         | Explanation |
| :------------ | :---------- |
| `"Transform"` |             |

### DependsOn



`DependsOn`

*   is optional

*   Type: `string[]`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-transformstep-properties-dependson.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TransformStep/properties/DependsOn")

#### DependsOn Type

`string[]`

### DisplayName



`DisplayName`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-transformstep-properties-displayname.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TransformStep/properties/DisplayName")

#### DisplayName Type

`string`

#### DisplayName Constraints

**pattern**: the string must match the following regular expression:&#x20;

```regexp
^[A-Za-z0-9\-_]{1,64}$
```

[try pattern](https://regexr.com/?expression=%5E%5BA-Za-z0-9%5C-_%5D%7B1%2C64%7D%24 "try regular expression with regexr.com")

### Description



`Description`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-transformstep-properties-description.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TransformStep/properties/Description")

#### Description Type

`string`

#### Description Constraints

**maximum length**: the maximum number of characters for this string is: `4096`

**minimum length**: the minimum number of characters for this string is: `0`

### RetryPolicies



`RetryPolicies`

*   is optional

*   Type: `object[]` ([Details](pipeline-definition-definitions-retrypolicy.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-transformstep-properties-retrypolicies.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TransformStep/properties/RetryPolicies")

#### RetryPolicies Type

`object[]` ([Details](pipeline-definition-definitions-retrypolicy.md))

### Arguments



`Arguments`

*   is required

*   Type: `object` ([Details](pipeline-definition-definitions-transformstep-properties-arguments.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-transformstep-properties-arguments.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TransformStep/properties/Arguments")

#### Arguments Type

`object` ([Details](pipeline-definition-definitions-transformstep-properties-arguments.md))

## Definitions group CreateModelStep

Reference this group by using

```json
{"$ref":"https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/CreateModelStep"}
```

| Property                          | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                             |
| :-------------------------------- | :------- | :------- | :------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Name](#name-8)                   | `string` | Required | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-createmodelstep-properties-name.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/CreateModelStep/properties/Name")                   |
| [Type](#type-11)                  | `string` | Required | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-createmodelstep-properties-type.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/CreateModelStep/properties/Type")                   |
| [DependsOn](#dependson-4)         | `array`  | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-createmodelstep-properties-dependson.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/CreateModelStep/properties/DependsOn")         |
| [DisplayName](#displayname-4)     | `string` | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-createmodelstep-properties-displayname.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/CreateModelStep/properties/DisplayName")     |
| [Description](#description-8)     | `string` | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-createmodelstep-properties-description.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/CreateModelStep/properties/Description")     |
| [RetryPolicies](#retrypolicies-3) | `array`  | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-createmodelstep-properties-retrypolicies.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/CreateModelStep/properties/RetryPolicies") |
| [Arguments](#arguments-4)         | `object` | Required | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-createmodelstep-properties-arguments.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/CreateModelStep/properties/Arguments")         |

### Name



`Name`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-createmodelstep-properties-name.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/CreateModelStep/properties/Name")

#### Name Type

`string`

#### Name Constraints

**pattern**: the string must match the following regular expression:&#x20;

```regexp
^[A-Za-z0-9\-_]{1,64}$
```

[try pattern](https://regexr.com/?expression=%5E%5BA-Za-z0-9%5C-_%5D%7B1%2C64%7D%24 "try regular expression with regexr.com")

### Type



`Type`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-createmodelstep-properties-type.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/CreateModelStep/properties/Type")

#### Type Type

`string`

#### Type Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value           | Explanation |
| :-------------- | :---------- |
| `"CreateModel"` |             |

### DependsOn



`DependsOn`

*   is optional

*   Type: `string[]`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-createmodelstep-properties-dependson.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/CreateModelStep/properties/DependsOn")

#### DependsOn Type

`string[]`

### DisplayName



`DisplayName`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-createmodelstep-properties-displayname.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/CreateModelStep/properties/DisplayName")

#### DisplayName Type

`string`

#### DisplayName Constraints

**pattern**: the string must match the following regular expression:&#x20;

```regexp
^[A-Za-z0-9\-_]{1,64}$
```

[try pattern](https://regexr.com/?expression=%5E%5BA-Za-z0-9%5C-_%5D%7B1%2C64%7D%24 "try regular expression with regexr.com")

### Description



`Description`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-createmodelstep-properties-description.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/CreateModelStep/properties/Description")

#### Description Type

`string`

#### Description Constraints

**maximum length**: the maximum number of characters for this string is: `4096`

**minimum length**: the minimum number of characters for this string is: `0`

### RetryPolicies



`RetryPolicies`

*   is optional

*   Type: `object[]` ([Details](pipeline-definition-definitions-retrypolicy.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-createmodelstep-properties-retrypolicies.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/CreateModelStep/properties/RetryPolicies")

#### RetryPolicies Type

`object[]` ([Details](pipeline-definition-definitions-retrypolicy.md))

### Arguments



`Arguments`

*   is required

*   Type: `object` ([Details](pipeline-definition-definitions-createmodelstep-properties-arguments.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-createmodelstep-properties-arguments.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/CreateModelStep/properties/Arguments")

#### Arguments Type

`object` ([Details](pipeline-definition-definitions-createmodelstep-properties-arguments.md))

## Definitions group RegisterModelStep

Reference this group by using

```json
{"$ref":"https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/RegisterModelStep"}
```

| Property                          | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                 |
| :-------------------------------- | :------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Name](#name-9)                   | `string` | Required | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-registermodelstep-properties-name.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/RegisterModelStep/properties/Name")                   |
| [Type](#type-12)                  | `string` | Required | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-registermodelstep-properties-type.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/RegisterModelStep/properties/Type")                   |
| [DependsOn](#dependson-5)         | `array`  | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-registermodelstep-properties-dependson.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/RegisterModelStep/properties/DependsOn")         |
| [DisplayName](#displayname-5)     | `string` | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-registermodelstep-properties-displayname.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/RegisterModelStep/properties/DisplayName")     |
| [Description](#description-9)     | `string` | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-registermodelstep-properties-description.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/RegisterModelStep/properties/Description")     |
| [RetryPolicies](#retrypolicies-4) | `array`  | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-registermodelstep-properties-retrypolicies.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/RegisterModelStep/properties/RetryPolicies") |
| [Arguments](#arguments-5)         | `object` | Required | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-registermodelstep-properties-arguments.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/RegisterModelStep/properties/Arguments")         |

### Name



`Name`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-registermodelstep-properties-name.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/RegisterModelStep/properties/Name")

#### Name Type

`string`

#### Name Constraints

**pattern**: the string must match the following regular expression:&#x20;

```regexp
^[A-Za-z0-9\-_]{1,64}$
```

[try pattern](https://regexr.com/?expression=%5E%5BA-Za-z0-9%5C-_%5D%7B1%2C64%7D%24 "try regular expression with regexr.com")

### Type



`Type`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-registermodelstep-properties-type.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/RegisterModelStep/properties/Type")

#### Type Type

`string`

#### Type Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value             | Explanation |
| :---------------- | :---------- |
| `"RegisterModel"` |             |

### DependsOn



`DependsOn`

*   is optional

*   Type: `string[]`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-registermodelstep-properties-dependson.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/RegisterModelStep/properties/DependsOn")

#### DependsOn Type

`string[]`

### DisplayName



`DisplayName`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-registermodelstep-properties-displayname.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/RegisterModelStep/properties/DisplayName")

#### DisplayName Type

`string`

#### DisplayName Constraints

**pattern**: the string must match the following regular expression:&#x20;

```regexp
^[A-Za-z0-9\-_]{1,64}$
```

[try pattern](https://regexr.com/?expression=%5E%5BA-Za-z0-9%5C-_%5D%7B1%2C64%7D%24 "try regular expression with regexr.com")

### Description



`Description`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-registermodelstep-properties-description.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/RegisterModelStep/properties/Description")

#### Description Type

`string`

#### Description Constraints

**maximum length**: the maximum number of characters for this string is: `4096`

**minimum length**: the minimum number of characters for this string is: `0`

### RetryPolicies



`RetryPolicies`

*   is optional

*   Type: `object[]` ([Details](pipeline-definition-definitions-retrypolicy.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-registermodelstep-properties-retrypolicies.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/RegisterModelStep/properties/RetryPolicies")

#### RetryPolicies Type

`object[]` ([Details](pipeline-definition-definitions-retrypolicy.md))

### Arguments



`Arguments`

*   is required

*   Type: `object` ([Details](pipeline-definition-definitions-registermodelstep-properties-arguments.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-registermodelstep-properties-arguments.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/RegisterModelStep/properties/Arguments")

#### Arguments Type

`object` ([Details](pipeline-definition-definitions-registermodelstep-properties-arguments.md))

## Definitions group LambdaStep

Reference this group by using

```json
{"$ref":"https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/LambdaStep"}
```

| Property | Type | Required | Nullable | Defined by |
| :------- | :--- | :------- | :------- | :--------- |

## Definitions group CallbackStep

Reference this group by using

```json
{"$ref":"https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/CallbackStep"}
```

| Property | Type | Required | Nullable | Defined by |
| :------- | :--- | :------- | :------- | :--------- |

## Definitions group TuningStep

Reference this group by using

```json
{"$ref":"https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TuningStep"}
```

| Property | Type | Required | Nullable | Defined by |
| :------- | :--- | :------- | :------- | :--------- |

## Definitions group ClarifyCheckStep

Reference this group by using

```json
{"$ref":"https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ClarifyCheckStep"}
```

| Property | Type | Required | Nullable | Defined by |
| :------- | :--- | :------- | :------- | :--------- |

## Definitions group QualityCheckStep

Reference this group by using

```json
{"$ref":"https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/QualityCheckStep"}
```

| Property | Type | Required | Nullable | Defined by |
| :------- | :--- | :------- | :------- | :--------- |

## Definitions group EMRStep

Reference this group by using

```json
{"$ref":"https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/EMRStep"}
```

| Property | Type | Required | Nullable | Defined by |
| :------- | :--- | :------- | :------- | :--------- |

## Definitions group FailStep

Reference this group by using

```json
{"$ref":"https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/FailStep"}
```

| Property                       | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                           |
| :----------------------------- | :------- | :------- | :------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Name](#name-10)               | `string` | Required | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-failstep-properties-name.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/FailStep/properties/Name")               |
| [Type](#type-13)               | `string` | Required | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-failstep-properties-type.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/FailStep/properties/Type")               |
| [DependsOn](#dependson-6)      | `array`  | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-failstep-properties-dependson.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/FailStep/properties/DependsOn")     |
| [DisplayName](#displayname-6)  | `string` | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-failstep-properties-displayname.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/FailStep/properties/DisplayName") |
| [Description](#description-10) | `string` | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-failstep-properties-description.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/FailStep/properties/Description") |
| [Arguments](#arguments-6)      | `object` | Required | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-failstep-properties-arguments.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/FailStep/properties/Arguments")     |

### Name



`Name`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-failstep-properties-name.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/FailStep/properties/Name")

#### Name Type

`string`

#### Name Constraints

**pattern**: the string must match the following regular expression:&#x20;

```regexp
^[A-Za-z0-9\-_]{1,64}$
```

[try pattern](https://regexr.com/?expression=%5E%5BA-Za-z0-9%5C-_%5D%7B1%2C64%7D%24 "try regular expression with regexr.com")

### Type



`Type`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-failstep-properties-type.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/FailStep/properties/Type")

#### Type Type

`string`

#### Type Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value    | Explanation |
| :------- | :---------- |
| `"Fail"` |             |

### DependsOn



`DependsOn`

*   is optional

*   Type: `string[]`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-failstep-properties-dependson.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/FailStep/properties/DependsOn")

#### DependsOn Type

`string[]`

### DisplayName



`DisplayName`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-failstep-properties-displayname.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/FailStep/properties/DisplayName")

#### DisplayName Type

`string`

#### DisplayName Constraints

**pattern**: the string must match the following regular expression:&#x20;

```regexp
^[A-Za-z0-9\-_]{1,64}$
```

[try pattern](https://regexr.com/?expression=%5E%5BA-Za-z0-9%5C-_%5D%7B1%2C64%7D%24 "try regular expression with regexr.com")

### Description



`Description`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-failstep-properties-description.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/FailStep/properties/Description")

#### Description Type

`string`

#### Description Constraints

**maximum length**: the maximum number of characters for this string is: `4096`

**minimum length**: the minimum number of characters for this string is: `0`

### Arguments



`Arguments`

*   is required

*   Type: `object` ([Details](pipeline-definition-definitions-failstep-properties-arguments.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-failstep-properties-arguments.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/FailStep/properties/Arguments")

#### Arguments Type

`object` ([Details](pipeline-definition-definitions-failstep-properties-arguments.md))
