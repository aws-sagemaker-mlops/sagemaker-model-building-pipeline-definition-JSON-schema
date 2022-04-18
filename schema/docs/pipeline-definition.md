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

## Definitions group Tag

Reference this group by using

```json
{"$ref":"https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/Tag"}
```

| Property          | Type   | Required | Nullable       | Defined by                                                                                                                                                                                                                    |
| :---------------- | :----- | :------- | :------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Key](#key)       | Merged | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/Tag/properties/Key")   |
| [Value](#value-1) | Merged | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/Tag/properties/Value") |

### Key



`Key`

*   is optional

*   Type: merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/Tag/properties/Key")

#### Key Type

merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

one (and only one) of

*   [Untitled string in SageMaker Pipeline Definition](pipeline-definition-definitions-stringargumentvalue-oneof-0.md "check type definition")

*   [Untitled object in SageMaker Pipeline Definition](pipeline-definition-definitions-getfunction.md "check type definition")

### Value



`Value`

*   is optional

*   Type: merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/Tag/properties/Value")

#### Value Type

merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

one (and only one) of

*   [Untitled string in SageMaker Pipeline Definition](pipeline-definition-definitions-stringargumentvalue-oneof-0.md "check type definition")

*   [Untitled object in SageMaker Pipeline Definition](pipeline-definition-definitions-getfunction.md "check type definition")

## Definitions group ParameterRanges

Reference this group by using

```json
{"$ref":"https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ParameterRanges"}
```

| Property                                                  | Type    | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                       |
| :-------------------------------------------------------- | :------ | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [CategoricalParameterRanges](#categoricalparameterranges) | `array` | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-parameterranges-properties-categoricalparameterranges.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ParameterRanges/properties/CategoricalParameterRanges") |
| [IntegerParameterRanges](#integerparameterranges)         | `array` | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-parameterranges-properties-integerparameterranges.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ParameterRanges/properties/IntegerParameterRanges")         |
| [ContinuousParameterRanges](#continuousparameterranges)   | `array` | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-parameterranges-properties-continuousparameterranges.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ParameterRanges/properties/ContinuousParameterRanges")   |

### CategoricalParameterRanges



`CategoricalParameterRanges`

*   is optional

*   Type: `object[]` ([Details](pipeline-definition-definitions-parameterranges-properties-categoricalparameterranges-items.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-parameterranges-properties-categoricalparameterranges.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ParameterRanges/properties/CategoricalParameterRanges")

#### CategoricalParameterRanges Type

`object[]` ([Details](pipeline-definition-definitions-parameterranges-properties-categoricalparameterranges-items.md))

#### CategoricalParameterRanges Constraints

**maximum number of items**: the maximum number of items for this array is: `20`

**minimum number of items**: the minimum number of items for this array is: `0`

### IntegerParameterRanges



`IntegerParameterRanges`

*   is optional

*   Type: `object[]` ([Details](pipeline-definition-definitions-parameterranges-properties-integerparameterranges-items.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-parameterranges-properties-integerparameterranges.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ParameterRanges/properties/IntegerParameterRanges")

#### IntegerParameterRanges Type

`object[]` ([Details](pipeline-definition-definitions-parameterranges-properties-integerparameterranges-items.md))

#### IntegerParameterRanges Constraints

**maximum number of items**: the maximum number of items for this array is: `20`

**minimum number of items**: the minimum number of items for this array is: `0`

### ContinuousParameterRanges



`ContinuousParameterRanges`

*   is optional

*   Type: `object[]` ([Details](pipeline-definition-definitions-parameterranges-properties-continuousparameterranges-items.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-parameterranges-properties-continuousparameterranges.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ParameterRanges/properties/ContinuousParameterRanges")

#### ContinuousParameterRanges Type

`object[]` ([Details](pipeline-definition-definitions-parameterranges-properties-continuousparameterranges-items.md))

#### ContinuousParameterRanges Constraints

**maximum number of items**: the maximum number of items for this array is: `20`

**minimum number of items**: the minimum number of items for this array is: `0`

## Definitions group HyperParameterTrainingJobDefinition

Reference this group by using

```json
{"$ref":"https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/HyperParameterTrainingJobDefinition"}
```

| Property                                                                        | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                                       |
| :------------------------------------------------------------------------------ | :------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [DefinitionName](#definitionname)                                               | Merged   | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/HyperParameterTrainingJobDefinition/properties/DefinitionName")                                                           |
| [AlgorithmSpecification](#algorithmspecification)                               | `object` | Required | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-hyperparametertrainingjobdefinition-properties-algorithmspecification.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/HyperParameterTrainingJobDefinition/properties/AlgorithmSpecification") |
| [CheckpointConfig](#checkpointconfig)                                           | `object` | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-hyperparametertrainingjobdefinition-properties-checkpointconfig.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/HyperParameterTrainingJobDefinition/properties/CheckpointConfig")             |
| [EnableInterContainerTrafficEncryption](#enableintercontainertrafficencryption) | Merged   | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-booleanargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/HyperParameterTrainingJobDefinition/properties/EnableInterContainerTrafficEncryption")                                   |
| [EnableManagedSpotTraining](#enablemanagedspottraining)                         | Merged   | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-booleanargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/HyperParameterTrainingJobDefinition/properties/EnableManagedSpotTraining")                                               |
| [EnableNetworkIsolation](#enablenetworkisolation)                               | Merged   | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-booleanargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/HyperParameterTrainingJobDefinition/properties/EnableNetworkIsolation")                                                  |
| [HyperParameterRanges](#hyperparameterranges)                                   | `object` | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-parameterranges.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/HyperParameterTrainingJobDefinition/properties/HyperParameterRanges")                                                         |
| [InputDataConfig](#inputdataconfig)                                             | `array`  | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-hyperparametertrainingjobdefinition-properties-inputdataconfig.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/HyperParameterTrainingJobDefinition/properties/InputDataConfig")               |
| [OutputDataConfig](#outputdataconfig)                                           | `object` | Required | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-hyperparametertrainingjobdefinition-properties-outputdataconfig.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/HyperParameterTrainingJobDefinition/properties/OutputDataConfig")             |
| [ResourceConfig](#resourceconfig)                                               | `object` | Required | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-hyperparametertrainingjobdefinition-properties-resourceconfig.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/HyperParameterTrainingJobDefinition/properties/ResourceConfig")                 |
| [RetryStrategy](#retrystrategy)                                                 | `object` | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-hyperparametertrainingjobdefinition-properties-retrystrategy.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/HyperParameterTrainingJobDefinition/properties/RetryStrategy")                   |
| [RoleArn](#rolearn)                                                             | Merged   | Required | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/HyperParameterTrainingJobDefinition/properties/RoleArn")                                                                  |
| [StaticHyperParameters](#statichyperparameters)                                 | `object` | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-hyperparametertrainingjobdefinition-properties-statichyperparameters.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/HyperParameterTrainingJobDefinition/properties/StaticHyperParameters")   |
| [StoppingCondition](#stoppingcondition)                                         | `object` | Required | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-hyperparametertrainingjobdefinition-properties-stoppingcondition.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/HyperParameterTrainingJobDefinition/properties/StoppingCondition")           |
| [TuningObjective](#tuningobjective)                                             | `object` | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-hyperparametertrainingjobdefinition-properties-tuningobjective.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/HyperParameterTrainingJobDefinition/properties/TuningObjective")               |
| [VpcConfig](#vpcconfig)                                                         | `object` | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-hyperparametertrainingjobdefinition-properties-vpcconfig.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/HyperParameterTrainingJobDefinition/properties/VpcConfig")                           |

### DefinitionName



`DefinitionName`

*   is optional

*   Type: merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/HyperParameterTrainingJobDefinition/properties/DefinitionName")

#### DefinitionName Type

merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

one (and only one) of

*   [Untitled string in SageMaker Pipeline Definition](pipeline-definition-definitions-stringargumentvalue-oneof-0.md "check type definition")

*   [Untitled object in SageMaker Pipeline Definition](pipeline-definition-definitions-getfunction.md "check type definition")

### AlgorithmSpecification



`AlgorithmSpecification`

*   is required

*   Type: `object` ([Details](pipeline-definition-definitions-hyperparametertrainingjobdefinition-properties-algorithmspecification.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-hyperparametertrainingjobdefinition-properties-algorithmspecification.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/HyperParameterTrainingJobDefinition/properties/AlgorithmSpecification")

#### AlgorithmSpecification Type

`object` ([Details](pipeline-definition-definitions-hyperparametertrainingjobdefinition-properties-algorithmspecification.md))

### CheckpointConfig



`CheckpointConfig`

*   is optional

*   Type: `object` ([Details](pipeline-definition-definitions-hyperparametertrainingjobdefinition-properties-checkpointconfig.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-hyperparametertrainingjobdefinition-properties-checkpointconfig.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/HyperParameterTrainingJobDefinition/properties/CheckpointConfig")

#### CheckpointConfig Type

`object` ([Details](pipeline-definition-definitions-hyperparametertrainingjobdefinition-properties-checkpointconfig.md))

### EnableInterContainerTrafficEncryption



`EnableInterContainerTrafficEncryption`

*   is optional

*   Type: merged type ([Details](pipeline-definition-definitions-booleanargumentvalue.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-booleanargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/HyperParameterTrainingJobDefinition/properties/EnableInterContainerTrafficEncryption")

#### EnableInterContainerTrafficEncryption Type

merged type ([Details](pipeline-definition-definitions-booleanargumentvalue.md))

one (and only one) of

*   [Untitled boolean in SageMaker Pipeline Definition](pipeline-definition-definitions-booleanargumentvalue-oneof-0.md "check type definition")

*   [Untitled object in SageMaker Pipeline Definition](pipeline-definition-definitions-getfunction.md "check type definition")

### EnableManagedSpotTraining



`EnableManagedSpotTraining`

*   is optional

*   Type: merged type ([Details](pipeline-definition-definitions-booleanargumentvalue.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-booleanargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/HyperParameterTrainingJobDefinition/properties/EnableManagedSpotTraining")

#### EnableManagedSpotTraining Type

merged type ([Details](pipeline-definition-definitions-booleanargumentvalue.md))

one (and only one) of

*   [Untitled boolean in SageMaker Pipeline Definition](pipeline-definition-definitions-booleanargumentvalue-oneof-0.md "check type definition")

*   [Untitled object in SageMaker Pipeline Definition](pipeline-definition-definitions-getfunction.md "check type definition")

### EnableNetworkIsolation



`EnableNetworkIsolation`

*   is optional

*   Type: merged type ([Details](pipeline-definition-definitions-booleanargumentvalue.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-booleanargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/HyperParameterTrainingJobDefinition/properties/EnableNetworkIsolation")

#### EnableNetworkIsolation Type

merged type ([Details](pipeline-definition-definitions-booleanargumentvalue.md))

one (and only one) of

*   [Untitled boolean in SageMaker Pipeline Definition](pipeline-definition-definitions-booleanargumentvalue-oneof-0.md "check type definition")

*   [Untitled object in SageMaker Pipeline Definition](pipeline-definition-definitions-getfunction.md "check type definition")

### HyperParameterRanges



`HyperParameterRanges`

*   is optional

*   Type: `object` ([Details](pipeline-definition-definitions-parameterranges.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-parameterranges.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/HyperParameterTrainingJobDefinition/properties/HyperParameterRanges")

#### HyperParameterRanges Type

`object` ([Details](pipeline-definition-definitions-parameterranges.md))

### InputDataConfig



`InputDataConfig`

*   is optional

*   Type: `object[]` ([Details](pipeline-definition-definitions-hyperparametertrainingjobdefinition-properties-inputdataconfig-items.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-hyperparametertrainingjobdefinition-properties-inputdataconfig.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/HyperParameterTrainingJobDefinition/properties/InputDataConfig")

#### InputDataConfig Type

`object[]` ([Details](pipeline-definition-definitions-hyperparametertrainingjobdefinition-properties-inputdataconfig-items.md))

### OutputDataConfig



`OutputDataConfig`

*   is required

*   Type: `object` ([Details](pipeline-definition-definitions-hyperparametertrainingjobdefinition-properties-outputdataconfig.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-hyperparametertrainingjobdefinition-properties-outputdataconfig.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/HyperParameterTrainingJobDefinition/properties/OutputDataConfig")

#### OutputDataConfig Type

`object` ([Details](pipeline-definition-definitions-hyperparametertrainingjobdefinition-properties-outputdataconfig.md))

### ResourceConfig



`ResourceConfig`

*   is required

*   Type: `object` ([Details](pipeline-definition-definitions-hyperparametertrainingjobdefinition-properties-resourceconfig.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-hyperparametertrainingjobdefinition-properties-resourceconfig.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/HyperParameterTrainingJobDefinition/properties/ResourceConfig")

#### ResourceConfig Type

`object` ([Details](pipeline-definition-definitions-hyperparametertrainingjobdefinition-properties-resourceconfig.md))

### RetryStrategy



`RetryStrategy`

*   is optional

*   Type: `object` ([Details](pipeline-definition-definitions-hyperparametertrainingjobdefinition-properties-retrystrategy.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-hyperparametertrainingjobdefinition-properties-retrystrategy.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/HyperParameterTrainingJobDefinition/properties/RetryStrategy")

#### RetryStrategy Type

`object` ([Details](pipeline-definition-definitions-hyperparametertrainingjobdefinition-properties-retrystrategy.md))

### RoleArn



`RoleArn`

*   is required

*   Type: merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/HyperParameterTrainingJobDefinition/properties/RoleArn")

#### RoleArn Type

merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

one (and only one) of

*   [Untitled string in SageMaker Pipeline Definition](pipeline-definition-definitions-stringargumentvalue-oneof-0.md "check type definition")

*   [Untitled object in SageMaker Pipeline Definition](pipeline-definition-definitions-getfunction.md "check type definition")

### StaticHyperParameters



`StaticHyperParameters`

*   is optional

*   Type: `object` ([Details](pipeline-definition-definitions-hyperparametertrainingjobdefinition-properties-statichyperparameters.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-hyperparametertrainingjobdefinition-properties-statichyperparameters.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/HyperParameterTrainingJobDefinition/properties/StaticHyperParameters")

#### StaticHyperParameters Type

`object` ([Details](pipeline-definition-definitions-hyperparametertrainingjobdefinition-properties-statichyperparameters.md))

### StoppingCondition



`StoppingCondition`

*   is required

*   Type: `object` ([Details](pipeline-definition-definitions-hyperparametertrainingjobdefinition-properties-stoppingcondition.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-hyperparametertrainingjobdefinition-properties-stoppingcondition.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/HyperParameterTrainingJobDefinition/properties/StoppingCondition")

#### StoppingCondition Type

`object` ([Details](pipeline-definition-definitions-hyperparametertrainingjobdefinition-properties-stoppingcondition.md))

### TuningObjective



`TuningObjective`

*   is optional

*   Type: `object` ([Details](pipeline-definition-definitions-hyperparametertrainingjobdefinition-properties-tuningobjective.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-hyperparametertrainingjobdefinition-properties-tuningobjective.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/HyperParameterTrainingJobDefinition/properties/TuningObjective")

#### TuningObjective Type

`object` ([Details](pipeline-definition-definitions-hyperparametertrainingjobdefinition-properties-tuningobjective.md))

### VpcConfig



`VpcConfig`

*   is optional

*   Type: `object` ([Details](pipeline-definition-definitions-hyperparametertrainingjobdefinition-properties-vpcconfig.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-hyperparametertrainingjobdefinition-properties-vpcconfig.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/HyperParameterTrainingJobDefinition/properties/VpcConfig")

#### VpcConfig Type

`object` ([Details](pipeline-definition-definitions-hyperparametertrainingjobdefinition-properties-vpcconfig.md))

## Definitions group ProcessingArgs

Reference this group by using

```json
{"$ref":"https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ProcessingArgs"}
```

| Property                                          | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                             |
| :------------------------------------------------ | :------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [AppSpecification](#appspecification)             | `object` | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-processingargs-properties-appspecification.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ProcessingArgs/properties/AppSpecification")             |
| [Environment](#environment)                       | `object` | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-processingargs-properties-environment.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ProcessingArgs/properties/Environment")                       |
| [ExperimentConfig](#experimentconfig)             | `object` | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-processingargs-properties-experimentconfig.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ProcessingArgs/properties/ExperimentConfig")             |
| [NetworkConfig](#networkconfig)                   | `object` | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-processingargs-properties-networkconfig.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ProcessingArgs/properties/NetworkConfig")                   |
| [ProcessingInputs](#processinginputs)             | `array`  | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-processingargs-properties-processinginputs.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ProcessingArgs/properties/ProcessingInputs")             |
| [ProcessingOutputConfig](#processingoutputconfig) | `object` | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-processingargs-properties-processingoutputconfig.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ProcessingArgs/properties/ProcessingOutputConfig") |
| [ProcessingResources](#processingresources)       | `object` | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-processingargs-properties-processingresources.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ProcessingArgs/properties/ProcessingResources")       |
| [RoleArn](#rolearn-1)                             | Merged   | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ProcessingArgs/properties/RoleArn")                                             |
| [StoppingCondition](#stoppingcondition-1)         | `object` | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-processingargs-properties-stoppingcondition.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ProcessingArgs/properties/StoppingCondition")           |
| [Tags](#tags)                                     | `array`  | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-processingargs-properties-tags.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ProcessingArgs/properties/Tags")                                     |

### AppSpecification



`AppSpecification`

*   is optional

*   Type: `object` ([Details](pipeline-definition-definitions-processingargs-properties-appspecification.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-processingargs-properties-appspecification.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ProcessingArgs/properties/AppSpecification")

#### AppSpecification Type

`object` ([Details](pipeline-definition-definitions-processingargs-properties-appspecification.md))

### Environment



`Environment`

*   is optional

*   Type: `object` ([Details](pipeline-definition-definitions-processingargs-properties-environment.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-processingargs-properties-environment.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ProcessingArgs/properties/Environment")

#### Environment Type

`object` ([Details](pipeline-definition-definitions-processingargs-properties-environment.md))

### ExperimentConfig



`ExperimentConfig`

*   is optional

*   Type: `object` ([Details](pipeline-definition-definitions-processingargs-properties-experimentconfig.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-processingargs-properties-experimentconfig.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ProcessingArgs/properties/ExperimentConfig")

#### ExperimentConfig Type

`object` ([Details](pipeline-definition-definitions-processingargs-properties-experimentconfig.md))

### NetworkConfig



`NetworkConfig`

*   is optional

*   Type: `object` ([Details](pipeline-definition-definitions-processingargs-properties-networkconfig.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-processingargs-properties-networkconfig.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ProcessingArgs/properties/NetworkConfig")

#### NetworkConfig Type

`object` ([Details](pipeline-definition-definitions-processingargs-properties-networkconfig.md))

### ProcessingInputs



`ProcessingInputs`

*   is optional

*   Type: `object[]` ([Details](pipeline-definition-definitions-processingargs-properties-processinginputs-items.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-processingargs-properties-processinginputs.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ProcessingArgs/properties/ProcessingInputs")

#### ProcessingInputs Type

`object[]` ([Details](pipeline-definition-definitions-processingargs-properties-processinginputs-items.md))

### ProcessingOutputConfig



`ProcessingOutputConfig`

*   is optional

*   Type: `object` ([Details](pipeline-definition-definitions-processingargs-properties-processingoutputconfig.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-processingargs-properties-processingoutputconfig.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ProcessingArgs/properties/ProcessingOutputConfig")

#### ProcessingOutputConfig Type

`object` ([Details](pipeline-definition-definitions-processingargs-properties-processingoutputconfig.md))

### ProcessingResources



`ProcessingResources`

*   is optional

*   Type: `object` ([Details](pipeline-definition-definitions-processingargs-properties-processingresources.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-processingargs-properties-processingresources.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ProcessingArgs/properties/ProcessingResources")

#### ProcessingResources Type

`object` ([Details](pipeline-definition-definitions-processingargs-properties-processingresources.md))

### RoleArn



`RoleArn`

*   is optional

*   Type: merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ProcessingArgs/properties/RoleArn")

#### RoleArn Type

merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

one (and only one) of

*   [Untitled string in SageMaker Pipeline Definition](pipeline-definition-definitions-stringargumentvalue-oneof-0.md "check type definition")

*   [Untitled object in SageMaker Pipeline Definition](pipeline-definition-definitions-getfunction.md "check type definition")

### StoppingCondition



`StoppingCondition`

*   is optional

*   Type: `object` ([Details](pipeline-definition-definitions-processingargs-properties-stoppingcondition.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-processingargs-properties-stoppingcondition.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ProcessingArgs/properties/StoppingCondition")

#### StoppingCondition Type

`object` ([Details](pipeline-definition-definitions-processingargs-properties-stoppingcondition.md))

### Tags



`Tags`

*   is optional

*   Type: `object[]` ([Details](pipeline-definition-definitions-tag.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-processingargs-properties-tags.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ProcessingArgs/properties/Tags")

#### Tags Type

`object[]` ([Details](pipeline-definition-definitions-tag.md))

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
| [Arguments](#arguments-2)         | `object` | Required | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-processingargs.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ProcessingStep/properties/Arguments")                              |

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

*   Type: `object` ([Details](pipeline-definition-definitions-processingargs.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-processingargs.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ProcessingStep/properties/Arguments")

#### Arguments Type

`object` ([Details](pipeline-definition-definitions-processingargs.md))

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

## Definitions group ContainerDefinition

Reference this group by using

```json
{"$ref":"https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ContainerDefinition"}
```

| Property                                                  | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                           |
| :-------------------------------------------------------- | :------- | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [ContainerHostname](#containerhostname)                   | Merged   | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ContainerDefinition/properties/ContainerHostname")                            |
| [Environment](#environment-1)                             | `object` | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-containerdefinition-properties-environment.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ContainerDefinition/properties/Environment")           |
| [Image](#image)                                           | Merged   | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ContainerDefinition/properties/Image")                                        |
| [ImageConfig](#imageconfig)                               | `object` | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-containerdefinition-properties-imageconfig.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ContainerDefinition/properties/ImageConfig")           |
| [InferenceSpecificationName](#inferencespecificationname) | Merged   | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ContainerDefinition/properties/InferenceSpecificationName")                   |
| [Mode](#mode)                                             | `string` | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-containerdefinition-properties-mode.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ContainerDefinition/properties/Mode")                         |
| [ModelDataUrl](#modeldataurl)                             | `string` | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-containerdefinition-properties-modeldataurl.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ContainerDefinition/properties/ModelDataUrl")         |
| [ModelPackageName](#modelpackagename)                     | Merged   | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ContainerDefinition/properties/ModelPackageName")                             |
| [MultiModelConfig](#multimodelconfig)                     | `object` | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-containerdefinition-properties-multimodelconfig.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ContainerDefinition/properties/MultiModelConfig") |

### ContainerHostname



`ContainerHostname`

*   is optional

*   Type: merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ContainerDefinition/properties/ContainerHostname")

#### ContainerHostname Type

merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

one (and only one) of

*   [Untitled string in SageMaker Pipeline Definition](pipeline-definition-definitions-stringargumentvalue-oneof-0.md "check type definition")

*   [Untitled object in SageMaker Pipeline Definition](pipeline-definition-definitions-getfunction.md "check type definition")

### Environment



`Environment`

*   is optional

*   Type: `object` ([Details](pipeline-definition-definitions-containerdefinition-properties-environment.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-containerdefinition-properties-environment.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ContainerDefinition/properties/Environment")

#### Environment Type

`object` ([Details](pipeline-definition-definitions-containerdefinition-properties-environment.md))

### Image



`Image`

*   is optional

*   Type: merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ContainerDefinition/properties/Image")

#### Image Type

merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

one (and only one) of

*   [Untitled string in SageMaker Pipeline Definition](pipeline-definition-definitions-stringargumentvalue-oneof-0.md "check type definition")

*   [Untitled object in SageMaker Pipeline Definition](pipeline-definition-definitions-getfunction.md "check type definition")

### ImageConfig



`ImageConfig`

*   is optional

*   Type: `object` ([Details](pipeline-definition-definitions-containerdefinition-properties-imageconfig.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-containerdefinition-properties-imageconfig.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ContainerDefinition/properties/ImageConfig")

#### ImageConfig Type

`object` ([Details](pipeline-definition-definitions-containerdefinition-properties-imageconfig.md))

### InferenceSpecificationName



`InferenceSpecificationName`

*   is optional

*   Type: merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ContainerDefinition/properties/InferenceSpecificationName")

#### InferenceSpecificationName Type

merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

one (and only one) of

*   [Untitled string in SageMaker Pipeline Definition](pipeline-definition-definitions-stringargumentvalue-oneof-0.md "check type definition")

*   [Untitled object in SageMaker Pipeline Definition](pipeline-definition-definitions-getfunction.md "check type definition")

### Mode



`Mode`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-containerdefinition-properties-mode.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ContainerDefinition/properties/Mode")

#### Mode Type

`string`

#### Mode Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value           | Explanation |
| :-------------- | :---------- |
| `"SingleModel"` |             |
| `"MultiModel"`  |             |

### ModelDataUrl



`ModelDataUrl`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-containerdefinition-properties-modeldataurl.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ContainerDefinition/properties/ModelDataUrl")

#### ModelDataUrl Type

`string`

#### ModelDataUrl Constraints

**maximum length**: the maximum number of characters for this string is: `1024`

**minimum length**: the minimum number of characters for this string is: `0`

**pattern**: the string must match the following regular expression:&#x20;

```regexp
^(https|s3)://([^/]+)/?(.*)$
```

[try pattern](https://regexr.com/?expression=%5E\(https%7Cs3\)%3A%2F%2F\(%5B%5E%2F%5D%2B\)%2F%3F\(.*\)%24 "try regular expression with regexr.com")

### ModelPackageName



`ModelPackageName`

*   is optional

*   Type: merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ContainerDefinition/properties/ModelPackageName")

#### ModelPackageName Type

merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

one (and only one) of

*   [Untitled string in SageMaker Pipeline Definition](pipeline-definition-definitions-stringargumentvalue-oneof-0.md "check type definition")

*   [Untitled object in SageMaker Pipeline Definition](pipeline-definition-definitions-getfunction.md "check type definition")

### MultiModelConfig



`MultiModelConfig`

*   is optional

*   Type: `object` ([Details](pipeline-definition-definitions-containerdefinition-properties-multimodelconfig.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-containerdefinition-properties-multimodelconfig.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ContainerDefinition/properties/MultiModelConfig")

#### MultiModelConfig Type

`object` ([Details](pipeline-definition-definitions-containerdefinition-properties-multimodelconfig.md))

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

| Value     | Explanation |
| :-------- | :---------- |
| `"Model"` |             |

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

| Property                              | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                         |
| :------------------------------------ | :------- | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Name](#name-10)                      | `string` | Required | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-lambdastep-properties-name.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/LambdaStep/properties/Name")                         |
| [Type](#type-13)                      | `string` | Required | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-lambdastep-properties-type.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/LambdaStep/properties/Type")                         |
| [DependsOn](#dependson-6)             | `array`  | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-lambdastep-properties-dependson.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/LambdaStep/properties/DependsOn")               |
| [DisplayName](#displayname-6)         | `string` | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-lambdastep-properties-displayname.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/LambdaStep/properties/DisplayName")           |
| [Description](#description-10)        | `string` | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-lambdastep-properties-description.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/LambdaStep/properties/Description")           |
| [FunctionArn](#functionarn)           | `string` | Required | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-lambdastep-properties-functionarn.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/LambdaStep/properties/FunctionArn")           |
| [Arguments](#arguments-6)             | `object` | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-lambdastep-properties-arguments.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/LambdaStep/properties/Arguments")               |
| [OutputParameters](#outputparameters) | `array`  | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-lambdastep-properties-outputparameters.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/LambdaStep/properties/OutputParameters") |

### Name



`Name`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-lambdastep-properties-name.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/LambdaStep/properties/Name")

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

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-lambdastep-properties-type.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/LambdaStep/properties/Type")

#### Type Type

`string`

#### Type Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value      | Explanation |
| :--------- | :---------- |
| `"Lambda"` |             |

### DependsOn



`DependsOn`

*   is optional

*   Type: `string[]`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-lambdastep-properties-dependson.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/LambdaStep/properties/DependsOn")

#### DependsOn Type

`string[]`

### DisplayName



`DisplayName`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-lambdastep-properties-displayname.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/LambdaStep/properties/DisplayName")

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

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-lambdastep-properties-description.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/LambdaStep/properties/Description")

#### Description Type

`string`

#### Description Constraints

**maximum length**: the maximum number of characters for this string is: `4096`

**minimum length**: the minimum number of characters for this string is: `0`

### FunctionArn



`FunctionArn`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-lambdastep-properties-functionarn.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/LambdaStep/properties/FunctionArn")

#### FunctionArn Type

`string`

### Arguments



`Arguments`

*   is optional

*   Type: `object` ([Details](pipeline-definition-definitions-lambdastep-properties-arguments.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-lambdastep-properties-arguments.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/LambdaStep/properties/Arguments")

#### Arguments Type

`object` ([Details](pipeline-definition-definitions-lambdastep-properties-arguments.md))

### OutputParameters



`OutputParameters`

*   is optional

*   Type: `object[]` ([Details](pipeline-definition-definitions-lambdastep-properties-outputparameters-items.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-lambdastep-properties-outputparameters.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/LambdaStep/properties/OutputParameters")

#### OutputParameters Type

`object[]` ([Details](pipeline-definition-definitions-lambdastep-properties-outputparameters-items.md))

## Definitions group CallbackStep

Reference this group by using

```json
{"$ref":"https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/CallbackStep"}
```

| Property                                | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                             |
| :-------------------------------------- | :------- | :------- | :------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Name](#name-11)                        | `string` | Required | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-callbackstep-properties-name.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/CallbackStep/properties/Name")                         |
| [Type](#type-14)                        | `string` | Required | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-callbackstep-properties-type.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/CallbackStep/properties/Type")                         |
| [DependsOn](#dependson-7)               | `array`  | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-callbackstep-properties-dependson.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/CallbackStep/properties/DependsOn")               |
| [DisplayName](#displayname-7)           | `string` | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-callbackstep-properties-displayname.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/CallbackStep/properties/DisplayName")           |
| [Description](#description-11)          | `string` | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-callbackstep-properties-description.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/CallbackStep/properties/Description")           |
| [SqsQueueUrl](#sqsqueueurl)             | `string` | Required | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-callbackstep-properties-sqsqueueurl.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/CallbackStep/properties/SqsQueueUrl")           |
| [Arguments](#arguments-7)               | `object` | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-callbackstep-properties-arguments.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/CallbackStep/properties/Arguments")               |
| [OutputParameters](#outputparameters-1) | `array`  | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-callbackstep-properties-outputparameters.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/CallbackStep/properties/OutputParameters") |

### Name



`Name`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-callbackstep-properties-name.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/CallbackStep/properties/Name")

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

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-callbackstep-properties-type.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/CallbackStep/properties/Type")

#### Type Type

`string`

#### Type Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value        | Explanation |
| :----------- | :---------- |
| `"Callback"` |             |

### DependsOn



`DependsOn`

*   is optional

*   Type: `string[]`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-callbackstep-properties-dependson.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/CallbackStep/properties/DependsOn")

#### DependsOn Type

`string[]`

### DisplayName



`DisplayName`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-callbackstep-properties-displayname.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/CallbackStep/properties/DisplayName")

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

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-callbackstep-properties-description.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/CallbackStep/properties/Description")

#### Description Type

`string`

#### Description Constraints

**maximum length**: the maximum number of characters for this string is: `4096`

**minimum length**: the minimum number of characters for this string is: `0`

### SqsQueueUrl



`SqsQueueUrl`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-callbackstep-properties-sqsqueueurl.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/CallbackStep/properties/SqsQueueUrl")

#### SqsQueueUrl Type

`string`

### Arguments



`Arguments`

*   is optional

*   Type: `object` ([Details](pipeline-definition-definitions-callbackstep-properties-arguments.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-callbackstep-properties-arguments.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/CallbackStep/properties/Arguments")

#### Arguments Type

`object` ([Details](pipeline-definition-definitions-callbackstep-properties-arguments.md))

### OutputParameters



`OutputParameters`

*   is optional

*   Type: `object[]` ([Details](pipeline-definition-definitions-callbackstep-properties-outputparameters-items.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-callbackstep-properties-outputparameters.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/CallbackStep/properties/OutputParameters")

#### OutputParameters Type

`object[]` ([Details](pipeline-definition-definitions-callbackstep-properties-outputparameters-items.md))

## Definitions group TuningStep

Reference this group by using

```json
{"$ref":"https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TuningStep"}
```

| Property                          | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                   |
| :-------------------------------- | :------- | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Name](#name-12)                  | `string` | Required | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-tuningstep-properties-name.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TuningStep/properties/Name")                   |
| [Type](#type-15)                  | `string` | Required | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-tuningstep-properties-type.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TuningStep/properties/Type")                   |
| [DependsOn](#dependson-8)         | `array`  | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-tuningstep-properties-dependson.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TuningStep/properties/DependsOn")         |
| [DisplayName](#displayname-8)     | `string` | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-tuningstep-properties-displayname.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TuningStep/properties/DisplayName")     |
| [Description](#description-12)    | `string` | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-tuningstep-properties-description.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TuningStep/properties/Description")     |
| [RetryPolicies](#retrypolicies-5) | `array`  | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-tuningstep-properties-retrypolicies.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TuningStep/properties/RetryPolicies") |
| [Arguments](#arguments-8)         | `object` | Required | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-tuningstep-properties-arguments.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TuningStep/properties/Arguments")         |

### Name



`Name`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-tuningstep-properties-name.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TuningStep/properties/Name")

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

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-tuningstep-properties-type.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TuningStep/properties/Type")

#### Type Type

`string`

#### Type Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value      | Explanation |
| :--------- | :---------- |
| `"Tuning"` |             |

### DependsOn



`DependsOn`

*   is optional

*   Type: `string[]`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-tuningstep-properties-dependson.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TuningStep/properties/DependsOn")

#### DependsOn Type

`string[]`

### DisplayName



`DisplayName`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-tuningstep-properties-displayname.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TuningStep/properties/DisplayName")

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

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-tuningstep-properties-description.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TuningStep/properties/Description")

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

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-tuningstep-properties-retrypolicies.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TuningStep/properties/RetryPolicies")

#### RetryPolicies Type

`object[]` ([Details](pipeline-definition-definitions-retrypolicy.md))

### Arguments



`Arguments`

*   is required

*   Type: `object` ([Details](pipeline-definition-definitions-tuningstep-properties-arguments.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-tuningstep-properties-arguments.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/TuningStep/properties/Arguments")

#### Arguments Type

`object` ([Details](pipeline-definition-definitions-tuningstep-properties-arguments.md))

## Definitions group ClarifyCheckStep

Reference this group by using

```json
{"$ref":"https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ClarifyCheckStep"}
```

| Property                                                    | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                               |
| :---------------------------------------------------------- | :------- | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Name](#name-13)                                            | `string` | Required | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-clarifycheckstep-properties-name.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ClarifyCheckStep/properties/Name")                   |
| [Type](#type-16)                                            | `string` | Required | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-clarifycheckstep-properties-type.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ClarifyCheckStep/properties/Type")                   |
| [DependsOn](#dependson-9)                                   | `array`  | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-clarifycheckstep-properties-dependson.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ClarifyCheckStep/properties/DependsOn")         |
| [DisplayName](#displayname-9)                               | `string` | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-clarifycheckstep-properties-displayname.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ClarifyCheckStep/properties/DisplayName")     |
| [Description](#description-13)                              | `string` | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-clarifycheckstep-properties-description.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ClarifyCheckStep/properties/Description")     |
| [RetryPolicies](#retrypolicies-6)                           | `array`  | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-clarifycheckstep-properties-retrypolicies.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ClarifyCheckStep/properties/RetryPolicies") |
| [CheckType](#checktype)                                     | `string` | Required | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-clarifycheckstep-properties-checktype.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ClarifyCheckStep/properties/CheckType")         |
| [ModelPackageGroupName](#modelpackagegroupname)             | Merged   | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ClarifyCheckStep/properties/ModelPackageGroupName")               |
| [SuppliedBaselineConstraints](#suppliedbaselineconstraints) | Merged   | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ClarifyCheckStep/properties/SuppliedBaselineConstraints")         |
| [SkipCheck](#skipcheck)                                     | Merged   | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-booleanargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ClarifyCheckStep/properties/SkipCheck")                          |
| [RegisterNewBaseline](#registernewbaseline)                 | Merged   | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-booleanargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ClarifyCheckStep/properties/RegisterNewBaseline")                |
| [ModelName](#modelname)                                     | Merged   | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ClarifyCheckStep/properties/ModelName")                           |
| [Arguments](#arguments-9)                                   | `object` | Required | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-processingargs.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ClarifyCheckStep/properties/Arguments")                                |

### Name



`Name`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-clarifycheckstep-properties-name.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ClarifyCheckStep/properties/Name")

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

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-clarifycheckstep-properties-type.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ClarifyCheckStep/properties/Type")

#### Type Type

`string`

#### Type Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value            | Explanation |
| :--------------- | :---------- |
| `"ClarifyCheck"` |             |

### DependsOn



`DependsOn`

*   is optional

*   Type: `string[]`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-clarifycheckstep-properties-dependson.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ClarifyCheckStep/properties/DependsOn")

#### DependsOn Type

`string[]`

### DisplayName



`DisplayName`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-clarifycheckstep-properties-displayname.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ClarifyCheckStep/properties/DisplayName")

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

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-clarifycheckstep-properties-description.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ClarifyCheckStep/properties/Description")

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

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-clarifycheckstep-properties-retrypolicies.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ClarifyCheckStep/properties/RetryPolicies")

#### RetryPolicies Type

`object[]` ([Details](pipeline-definition-definitions-retrypolicy.md))

### CheckType



`CheckType`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-clarifycheckstep-properties-checktype.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ClarifyCheckStep/properties/CheckType")

#### CheckType Type

`string`

#### CheckType Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                    | Explanation |
| :----------------------- | :---------- |
| `"DATA_BIAS"`            |             |
| `"MODEL_BIAS"`           |             |
| `"MODEL_EXPLAINABILITY"` |             |

### ModelPackageGroupName



`ModelPackageGroupName`

*   is optional

*   Type: merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ClarifyCheckStep/properties/ModelPackageGroupName")

#### ModelPackageGroupName Type

merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

one (and only one) of

*   [Untitled string in SageMaker Pipeline Definition](pipeline-definition-definitions-stringargumentvalue-oneof-0.md "check type definition")

*   [Untitled object in SageMaker Pipeline Definition](pipeline-definition-definitions-getfunction.md "check type definition")

### SuppliedBaselineConstraints



`SuppliedBaselineConstraints`

*   is optional

*   Type: merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ClarifyCheckStep/properties/SuppliedBaselineConstraints")

#### SuppliedBaselineConstraints Type

merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

one (and only one) of

*   [Untitled string in SageMaker Pipeline Definition](pipeline-definition-definitions-stringargumentvalue-oneof-0.md "check type definition")

*   [Untitled object in SageMaker Pipeline Definition](pipeline-definition-definitions-getfunction.md "check type definition")

### SkipCheck



`SkipCheck`

*   is optional

*   Type: merged type ([Details](pipeline-definition-definitions-booleanargumentvalue.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-booleanargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ClarifyCheckStep/properties/SkipCheck")

#### SkipCheck Type

merged type ([Details](pipeline-definition-definitions-booleanargumentvalue.md))

one (and only one) of

*   [Untitled boolean in SageMaker Pipeline Definition](pipeline-definition-definitions-booleanargumentvalue-oneof-0.md "check type definition")

*   [Untitled object in SageMaker Pipeline Definition](pipeline-definition-definitions-getfunction.md "check type definition")

### RegisterNewBaseline



`RegisterNewBaseline`

*   is optional

*   Type: merged type ([Details](pipeline-definition-definitions-booleanargumentvalue.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-booleanargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ClarifyCheckStep/properties/RegisterNewBaseline")

#### RegisterNewBaseline Type

merged type ([Details](pipeline-definition-definitions-booleanargumentvalue.md))

one (and only one) of

*   [Untitled boolean in SageMaker Pipeline Definition](pipeline-definition-definitions-booleanargumentvalue-oneof-0.md "check type definition")

*   [Untitled object in SageMaker Pipeline Definition](pipeline-definition-definitions-getfunction.md "check type definition")

### ModelName



`ModelName`

*   is optional

*   Type: merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ClarifyCheckStep/properties/ModelName")

#### ModelName Type

merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

one (and only one) of

*   [Untitled string in SageMaker Pipeline Definition](pipeline-definition-definitions-stringargumentvalue-oneof-0.md "check type definition")

*   [Untitled object in SageMaker Pipeline Definition](pipeline-definition-definitions-getfunction.md "check type definition")

### Arguments



`Arguments`

*   is required

*   Type: `object` ([Details](pipeline-definition-definitions-processingargs.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-processingargs.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ClarifyCheckStep/properties/Arguments")

#### Arguments Type

`object` ([Details](pipeline-definition-definitions-processingargs.md))

## Definitions group QualityCheckStep

Reference this group by using

```json
{"$ref":"https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/QualityCheckStep"}
```

| Property                                                      | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                               |
| :------------------------------------------------------------ | :------- | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Name](#name-14)                                              | `string` | Required | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-qualitycheckstep-properties-name.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/QualityCheckStep/properties/Name")                   |
| [Type](#type-17)                                              | `string` | Required | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-qualitycheckstep-properties-type.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/QualityCheckStep/properties/Type")                   |
| [DependsOn](#dependson-10)                                    | `array`  | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-qualitycheckstep-properties-dependson.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/QualityCheckStep/properties/DependsOn")         |
| [DisplayName](#displayname-10)                                | `string` | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-qualitycheckstep-properties-displayname.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/QualityCheckStep/properties/DisplayName")     |
| [Description](#description-14)                                | `string` | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-qualitycheckstep-properties-description.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/QualityCheckStep/properties/Description")     |
| [RetryPolicies](#retrypolicies-7)                             | `array`  | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-qualitycheckstep-properties-retrypolicies.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/QualityCheckStep/properties/RetryPolicies") |
| [CheckType](#checktype-1)                                     | `string` | Required | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-qualitycheckstep-properties-checktype.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/QualityCheckStep/properties/CheckType")         |
| [ModelPackageGroupName](#modelpackagegroupname-1)             | Merged   | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/QualityCheckStep/properties/ModelPackageGroupName")               |
| [SuppliedBaselineConstraints](#suppliedbaselineconstraints-1) | Merged   | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/QualityCheckStep/properties/SuppliedBaselineConstraints")         |
| [SuppliedBaselineStatistics](#suppliedbaselinestatistics)     | Merged   | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/QualityCheckStep/properties/SuppliedBaselineStatistics")          |
| [SkipCheck](#skipcheck-1)                                     | Merged   | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-booleanargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/QualityCheckStep/properties/SkipCheck")                          |
| [RegisterNewBaseline](#registernewbaseline-1)                 | Merged   | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-booleanargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/QualityCheckStep/properties/RegisterNewBaseline")                |
| [Arguments](#arguments-10)                                    | `object` | Required | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-processingargs.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/QualityCheckStep/properties/Arguments")                                |

### Name



`Name`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-qualitycheckstep-properties-name.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/QualityCheckStep/properties/Name")

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

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-qualitycheckstep-properties-type.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/QualityCheckStep/properties/Type")

#### Type Type

`string`

#### Type Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value            | Explanation |
| :--------------- | :---------- |
| `"QualityCheck"` |             |

### DependsOn



`DependsOn`

*   is optional

*   Type: `string[]`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-qualitycheckstep-properties-dependson.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/QualityCheckStep/properties/DependsOn")

#### DependsOn Type

`string[]`

### DisplayName



`DisplayName`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-qualitycheckstep-properties-displayname.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/QualityCheckStep/properties/DisplayName")

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

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-qualitycheckstep-properties-description.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/QualityCheckStep/properties/Description")

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

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-qualitycheckstep-properties-retrypolicies.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/QualityCheckStep/properties/RetryPolicies")

#### RetryPolicies Type

`object[]` ([Details](pipeline-definition-definitions-retrypolicy.md))

### CheckType



`CheckType`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-qualitycheckstep-properties-checktype.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/QualityCheckStep/properties/CheckType")

#### CheckType Type

`string`

#### CheckType Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                    | Explanation |
| :----------------------- | :---------- |
| `"DATA_BIAS"`            |             |
| `"MODEL_BIAS"`           |             |
| `"MODEL_EXPLAINABILITY"` |             |

### ModelPackageGroupName



`ModelPackageGroupName`

*   is optional

*   Type: merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/QualityCheckStep/properties/ModelPackageGroupName")

#### ModelPackageGroupName Type

merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

one (and only one) of

*   [Untitled string in SageMaker Pipeline Definition](pipeline-definition-definitions-stringargumentvalue-oneof-0.md "check type definition")

*   [Untitled object in SageMaker Pipeline Definition](pipeline-definition-definitions-getfunction.md "check type definition")

### SuppliedBaselineConstraints



`SuppliedBaselineConstraints`

*   is optional

*   Type: merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/QualityCheckStep/properties/SuppliedBaselineConstraints")

#### SuppliedBaselineConstraints Type

merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

one (and only one) of

*   [Untitled string in SageMaker Pipeline Definition](pipeline-definition-definitions-stringargumentvalue-oneof-0.md "check type definition")

*   [Untitled object in SageMaker Pipeline Definition](pipeline-definition-definitions-getfunction.md "check type definition")

### SuppliedBaselineStatistics



`SuppliedBaselineStatistics`

*   is optional

*   Type: merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/QualityCheckStep/properties/SuppliedBaselineStatistics")

#### SuppliedBaselineStatistics Type

merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

one (and only one) of

*   [Untitled string in SageMaker Pipeline Definition](pipeline-definition-definitions-stringargumentvalue-oneof-0.md "check type definition")

*   [Untitled object in SageMaker Pipeline Definition](pipeline-definition-definitions-getfunction.md "check type definition")

### SkipCheck



`SkipCheck`

*   is optional

*   Type: merged type ([Details](pipeline-definition-definitions-booleanargumentvalue.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-booleanargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/QualityCheckStep/properties/SkipCheck")

#### SkipCheck Type

merged type ([Details](pipeline-definition-definitions-booleanargumentvalue.md))

one (and only one) of

*   [Untitled boolean in SageMaker Pipeline Definition](pipeline-definition-definitions-booleanargumentvalue-oneof-0.md "check type definition")

*   [Untitled object in SageMaker Pipeline Definition](pipeline-definition-definitions-getfunction.md "check type definition")

### RegisterNewBaseline



`RegisterNewBaseline`

*   is optional

*   Type: merged type ([Details](pipeline-definition-definitions-booleanargumentvalue.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-booleanargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/QualityCheckStep/properties/RegisterNewBaseline")

#### RegisterNewBaseline Type

merged type ([Details](pipeline-definition-definitions-booleanargumentvalue.md))

one (and only one) of

*   [Untitled boolean in SageMaker Pipeline Definition](pipeline-definition-definitions-booleanargumentvalue-oneof-0.md "check type definition")

*   [Untitled object in SageMaker Pipeline Definition](pipeline-definition-definitions-getfunction.md "check type definition")

### Arguments



`Arguments`

*   is required

*   Type: `object` ([Details](pipeline-definition-definitions-processingargs.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-processingargs.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/QualityCheckStep/properties/Arguments")

#### Arguments Type

`object` ([Details](pipeline-definition-definitions-processingargs.md))

## Definitions group EMRStep

Reference this group by using

```json
{"$ref":"https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/EMRStep"}
```

| Property                       | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                         |
| :----------------------------- | :------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Name](#name-15)               | `string` | Required | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-emrstep-properties-name.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/EMRStep/properties/Name")               |
| [Type](#type-18)               | `string` | Required | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-emrstep-properties-type.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/EMRStep/properties/Type")               |
| [DependsOn](#dependson-11)     | `array`  | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-emrstep-properties-dependson.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/EMRStep/properties/DependsOn")     |
| [DisplayName](#displayname-11) | `string` | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-emrstep-properties-displayname.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/EMRStep/properties/DisplayName") |
| [Description](#description-15) | `string` | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-emrstep-properties-description.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/EMRStep/properties/Description") |
| [Arguments](#arguments-11)     | `object` | Required | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-emrstep-properties-arguments.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/EMRStep/properties/Arguments")     |

### Name



`Name`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-emrstep-properties-name.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/EMRStep/properties/Name")

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

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-emrstep-properties-type.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/EMRStep/properties/Type")

#### Type Type

`string`

#### Type Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value   | Explanation |
| :------ | :---------- |
| `"EMR"` |             |

### DependsOn



`DependsOn`

*   is optional

*   Type: `string[]`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-emrstep-properties-dependson.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/EMRStep/properties/DependsOn")

#### DependsOn Type

`string[]`

### DisplayName



`DisplayName`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-emrstep-properties-displayname.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/EMRStep/properties/DisplayName")

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

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-emrstep-properties-description.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/EMRStep/properties/Description")

#### Description Type

`string`

#### Description Constraints

**maximum length**: the maximum number of characters for this string is: `4096`

**minimum length**: the minimum number of characters for this string is: `0`

### Arguments



`Arguments`

*   is required

*   Type: `object` ([Details](pipeline-definition-definitions-emrstep-properties-arguments.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-emrstep-properties-arguments.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/EMRStep/properties/Arguments")

#### Arguments Type

`object` ([Details](pipeline-definition-definitions-emrstep-properties-arguments.md))

## Definitions group FailStep

Reference this group by using

```json
{"$ref":"https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/FailStep"}
```

| Property                       | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                           |
| :----------------------------- | :------- | :------- | :------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Name](#name-16)               | `string` | Required | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-failstep-properties-name.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/FailStep/properties/Name")               |
| [Type](#type-19)               | `string` | Required | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-failstep-properties-type.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/FailStep/properties/Type")               |
| [DependsOn](#dependson-12)     | `array`  | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-failstep-properties-dependson.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/FailStep/properties/DependsOn")     |
| [DisplayName](#displayname-12) | `string` | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-failstep-properties-displayname.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/FailStep/properties/DisplayName") |
| [Description](#description-16) | `string` | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-failstep-properties-description.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/FailStep/properties/Description") |
| [Arguments](#arguments-12)     | `object` | Required | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-failstep-properties-arguments.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/FailStep/properties/Arguments")     |

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
