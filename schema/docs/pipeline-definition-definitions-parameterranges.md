## HyperParameterRanges Type

`object` ([Details](pipeline-definition-definitions-parameterranges.md))

# HyperParameterRanges Properties

| Property                                                  | Type    | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                       |
| :-------------------------------------------------------- | :------ | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [CategoricalParameterRanges](#categoricalparameterranges) | `array` | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-parameterranges-properties-categoricalparameterranges.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ParameterRanges/properties/CategoricalParameterRanges") |
| [IntegerParameterRanges](#integerparameterranges)         | `array` | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-parameterranges-properties-integerparameterranges.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ParameterRanges/properties/IntegerParameterRanges")         |
| [ContinuousParameterRanges](#continuousparameterranges)   | `array` | Optional | cannot be null | [SageMaker Pipeline Definition](pipeline-definition-definitions-parameterranges-properties-continuousparameterranges.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ParameterRanges/properties/ContinuousParameterRanges")   |

## CategoricalParameterRanges



`CategoricalParameterRanges`

*   is optional

*   Type: `object[]` ([Details](pipeline-definition-definitions-parameterranges-properties-categoricalparameterranges-items.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-parameterranges-properties-categoricalparameterranges.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ParameterRanges/properties/CategoricalParameterRanges")

### CategoricalParameterRanges Type

`object[]` ([Details](pipeline-definition-definitions-parameterranges-properties-categoricalparameterranges-items.md))

### CategoricalParameterRanges Constraints

**maximum number of items**: the maximum number of items for this array is: `20`

**minimum number of items**: the minimum number of items for this array is: `0`

## IntegerParameterRanges



`IntegerParameterRanges`

*   is optional

*   Type: `object[]` ([Details](pipeline-definition-definitions-parameterranges-properties-integerparameterranges-items.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-parameterranges-properties-integerparameterranges.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ParameterRanges/properties/IntegerParameterRanges")

### IntegerParameterRanges Type

`object[]` ([Details](pipeline-definition-definitions-parameterranges-properties-integerparameterranges-items.md))

### IntegerParameterRanges Constraints

**maximum number of items**: the maximum number of items for this array is: `20`

**minimum number of items**: the minimum number of items for this array is: `0`

## ContinuousParameterRanges



`ContinuousParameterRanges`

*   is optional

*   Type: `object[]` ([Details](pipeline-definition-definitions-parameterranges-properties-continuousparameterranges-items.md))

*   cannot be null

*   defined in: [SageMaker Pipeline Definition](pipeline-definition-definitions-parameterranges-properties-continuousparameterranges.md "https://github.com/jerrypeng7773/sagemaker-model-building-pipeline-definition-JSON-schema/schema/#/definitions/ParameterRanges/properties/ContinuousParameterRanges")

### ContinuousParameterRanges Type

`object[]` ([Details](pipeline-definition-definitions-parameterranges-properties-continuousparameterranges-items.md))

### ContinuousParameterRanges Constraints

**maximum number of items**: the maximum number of items for this array is: `20`

**minimum number of items**: the minimum number of items for this array is: `0`
