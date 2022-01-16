[awesome-nestjs-boilerplate](../README.md) / [Exports](../modules.md) / UniqueValidator

# Class: UniqueValidator

## Implements

- `ValidatorConstraintInterface`

## Table of contents

### Constructors

- [constructor](UniqueValidator.md#constructor)

### Methods

- [defaultMessage](UniqueValidator.md#defaultmessage)
- [validate](UniqueValidator.md#validate)

## Constructors

### constructor

• **new UniqueValidator**(`connection`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `connection` | `Connection` |

#### Defined in

[unique.validator.ts:15](https://github.com/klub-deepak/poc_doc_generation_3/blob/a592bb2/src/validators/unique.validator.ts#L15)

## Methods

### defaultMessage

▸ **defaultMessage**(`args`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `args` | `ValidationArguments` |

#### Returns

`string`

#### Implementation of

ValidatorConstraintInterface.defaultMessage

#### Defined in

[unique.validator.ts:35](https://github.com/klub-deepak/poc_doc_generation_3/blob/a592bb2/src/validators/unique.validator.ts#L35)

___

### validate

▸ **validate**<`E`\>(`value`, `args`): `Promise`<`boolean`\>

#### Type parameters

| Name |
| :------ |
| `E` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | `string` |
| `args` | `IUniqueValidationArguments`<`E`\> |

#### Returns

`Promise`<`boolean`\>

#### Implementation of

ValidatorConstraintInterface.validate

#### Defined in

[unique.validator.ts:17](https://github.com/klub-deepak/poc_doc_generation_3/blob/a592bb2/src/validators/unique.validator.ts#L17)
