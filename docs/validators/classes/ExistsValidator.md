[awesome-nestjs-boilerplate](../README.md) / [Exports](../modules.md) / ExistsValidator

# Class: ExistsValidator

## Implements

- `ValidatorConstraintInterface`

## Table of contents

### Constructors

- [constructor](ExistsValidator.md#constructor)

### Methods

- [defaultMessage](ExistsValidator.md#defaultmessage)
- [validate](ExistsValidator.md#validate)

## Constructors

### constructor

• **new ExistsValidator**(`connection`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `connection` | `Connection` |

#### Defined in

[exists.validator.ts:15](https://github.com/klub-deepak/poc_doc_generation_3/blob/a592bb2/src/validators/exists.validator.ts#L15)

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

[exists.validator.ts:35](https://github.com/klub-deepak/poc_doc_generation_3/blob/a592bb2/src/validators/exists.validator.ts#L35)

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
| `args` | `IExistsValidationArguments`<`E`\> |

#### Returns

`Promise`<`boolean`\>

#### Implementation of

ValidatorConstraintInterface.validate

#### Defined in

[exists.validator.ts:17](https://github.com/klub-deepak/poc_doc_generation_3/blob/a592bb2/src/validators/exists.validator.ts#L17)
