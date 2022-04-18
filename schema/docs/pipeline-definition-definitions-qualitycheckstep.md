## 10 Type

`object` ([Details](pipeline-definition-definitions-qualitycheckstep.md))

# 10 Properties

| Property                                                    | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                      |
| :---------------------------------------------------------- | :------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [Name](#name)                                               | `string` | Required | cannot be null | [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-stepname.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/QualityCheckStep/properties/Name")                                           |
| [Type](#type)                                               | `string` | Required | cannot be null | [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-qualitycheckstep-properties-type.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/QualityCheckStep/properties/Type")                   |
| [DependsOn](#dependson)                                     | `array`  | Optional | cannot be null | [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-qualitycheckstep-properties-dependson.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/QualityCheckStep/properties/DependsOn")         |
| [DisplayName](#displayname)                                 | `string` | Optional | cannot be null | [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-stepname.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/QualityCheckStep/properties/DisplayName")                                    |
| [Description](#description)                                 | `string` | Optional | cannot be null | [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-parameterdescription.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/QualityCheckStep/properties/Description")                        |
| [RetryPolicies](#retrypolicies)                             | `array`  | Optional | cannot be null | [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-qualitycheckstep-properties-retrypolicies.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/QualityCheckStep/properties/RetryPolicies") |
| [CacheConfig](#cacheconfig)                                 | `object` | Optional | cannot be null | [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-cacheconfig.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/QualityCheckStep/properties/CacheConfig")                                 |
| [CheckType](#checktype)                                     | `string` | Required | cannot be null | [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-qualitycheckstep-properties-checktype.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/QualityCheckStep/properties/CheckType")         |
| [ModelPackageGroupName](#modelpackagegroupname)             | Merged   | Optional | cannot be null | [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/QualityCheckStep/properties/ModelPackageGroupName")               |
| [SuppliedBaselineConstraints](#suppliedbaselineconstraints) | Merged   | Optional | cannot be null | [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/QualityCheckStep/properties/SuppliedBaselineConstraints")         |
| [SuppliedBaselineStatistics](#suppliedbaselinestatistics)   | Merged   | Optional | cannot be null | [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/QualityCheckStep/properties/SuppliedBaselineStatistics")          |
| [SkipCheck](#skipcheck)                                     | Merged   | Optional | cannot be null | [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-booleanargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/QualityCheckStep/properties/SkipCheck")                          |
| [RegisterNewBaseline](#registernewbaseline)                 | Merged   | Optional | cannot be null | [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-booleanargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/QualityCheckStep/properties/RegisterNewBaseline")                |
| [Arguments](#arguments)                                     | `object` | Required | cannot be null | [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-processingargs.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/QualityCheckStep/properties/Arguments")                                |

## Name



`Name`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-stepname.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/QualityCheckStep/properties/Name")

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

*   defined in: [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-qualitycheckstep-properties-type.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/QualityCheckStep/properties/Type")

### Type Type

`string`

### Type Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value            | Explanation |
| :--------------- | :---------- |
| `"QualityCheck"` |             |

## DependsOn



`DependsOn`

*   is optional

*   Type: `string[]`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-qualitycheckstep-properties-dependson.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/QualityCheckStep/properties/DependsOn")

### DependsOn Type

`string[]`

## DisplayName



`DisplayName`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-stepname.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/QualityCheckStep/properties/DisplayName")

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

*   defined in: [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-parameterdescription.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/QualityCheckStep/properties/Description")

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

*   defined in: [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-qualitycheckstep-properties-retrypolicies.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/QualityCheckStep/properties/RetryPolicies")

### RetryPolicies Type

`object[]` ([Details](pipeline-definition-definitions-retrypolicy.md))

## CacheConfig



`CacheConfig`

*   is optional

*   Type: `object` ([Details](pipeline-definition-definitions-cacheconfig.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-cacheconfig.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/QualityCheckStep/properties/CacheConfig")

### CacheConfig Type

`object` ([Details](pipeline-definition-definitions-cacheconfig.md))

## CheckType



`CheckType`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-qualitycheckstep-properties-checktype.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/QualityCheckStep/properties/CheckType")

### CheckType Type

`string`

### CheckType Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value             | Explanation |
| :---------------- | :---------- |
| `"DATA_QUALITY"`  |             |
| `"MODEL_QUALITY"` |             |

## ModelPackageGroupName



`ModelPackageGroupName`

*   is optional

*   Type: merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/QualityCheckStep/properties/ModelPackageGroupName")

### ModelPackageGroupName Type

merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

one (and only one) of

*   [Untitled string in SageMaker Pipeline Definition Schema](pipeline-definition-definitions-stringargumentvalue-oneof-0.md "check type definition")

*   [Untitled object in SageMaker Pipeline Definition Schema](pipeline-definition-definitions-getfunction.md "check type definition")

## SuppliedBaselineConstraints



`SuppliedBaselineConstraints`

*   is optional

*   Type: merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/QualityCheckStep/properties/SuppliedBaselineConstraints")

### SuppliedBaselineConstraints Type

merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

one (and only one) of

*   [Untitled string in SageMaker Pipeline Definition Schema](pipeline-definition-definitions-stringargumentvalue-oneof-0.md "check type definition")

*   [Untitled object in SageMaker Pipeline Definition Schema](pipeline-definition-definitions-getfunction.md "check type definition")

## SuppliedBaselineStatistics



`SuppliedBaselineStatistics`

*   is optional

*   Type: merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-stringargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/QualityCheckStep/properties/SuppliedBaselineStatistics")

### SuppliedBaselineStatistics Type

merged type ([Details](pipeline-definition-definitions-stringargumentvalue.md))

one (and only one) of

*   [Untitled string in SageMaker Pipeline Definition Schema](pipeline-definition-definitions-stringargumentvalue-oneof-0.md "check type definition")

*   [Untitled object in SageMaker Pipeline Definition Schema](pipeline-definition-definitions-getfunction.md "check type definition")

## SkipCheck



`SkipCheck`

*   is optional

*   Type: merged type ([Details](pipeline-definition-definitions-booleanargumentvalue.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-booleanargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/QualityCheckStep/properties/SkipCheck")

### SkipCheck Type

merged type ([Details](pipeline-definition-definitions-booleanargumentvalue.md))

one (and only one) of

*   [Untitled boolean in SageMaker Pipeline Definition Schema](pipeline-definition-definitions-booleanargumentvalue-oneof-0.md "check type definition")

*   [Untitled object in SageMaker Pipeline Definition Schema](pipeline-definition-definitions-getfunction.md "check type definition")

## RegisterNewBaseline



`RegisterNewBaseline`

*   is optional

*   Type: merged type ([Details](pipeline-definition-definitions-booleanargumentvalue.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-booleanargumentvalue.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/QualityCheckStep/properties/RegisterNewBaseline")

### RegisterNewBaseline Type

merged type ([Details](pipeline-definition-definitions-booleanargumentvalue.md))

one (and only one) of

*   [Untitled boolean in SageMaker Pipeline Definition Schema](pipeline-definition-definitions-booleanargumentvalue-oneof-0.md "check type definition")

*   [Untitled object in SageMaker Pipeline Definition Schema](pipeline-definition-definitions-getfunction.md "check type definition")

## Arguments



`Arguments`

*   is required

*   Type: `object` ([Details](pipeline-definition-definitions-processingargs.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition Schema](pipeline-definition-definitions-processingargs.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/QualityCheckStep/properties/Arguments")

### Arguments Type

`object` ([Details](pipeline-definition-definitions-processingargs.md))
