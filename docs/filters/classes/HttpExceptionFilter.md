[awesome-nestjs-boilerplate](../README.md) / [Exports](../modules.md) / HttpExceptionFilter

# Class: HttpExceptionFilter

## Implements

- `ExceptionFilter`<`UnprocessableEntityException`\>

## Table of contents

### Constructors

- [constructor](HttpExceptionFilter.md#constructor)

### Properties

- [reflector](HttpExceptionFilter.md#reflector)

### Methods

- [catch](HttpExceptionFilter.md#catch)
- [validationFilter](HttpExceptionFilter.md#validationfilter)

## Constructors

### constructor

• **new HttpExceptionFilter**(`reflector`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `reflector` | `Reflector` |

#### Defined in

[bad-request.filter.ts:12](https://github.com/klub-deepak/poc_doc_generation_3/blob/a592bb2/src/filters/bad-request.filter.ts#L12)

## Properties

### reflector

• **reflector**: `Reflector`

## Methods

### catch

▸ **catch**(`exception`, `host`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `exception` | `UnprocessableEntityException` |
| `host` | `ArgumentsHost` |

#### Returns

`void`

#### Implementation of

ExceptionFilter.catch

#### Defined in

[bad-request.filter.ts:14](https://github.com/klub-deepak/poc_doc_generation_3/blob/a592bb2/src/filters/bad-request.filter.ts#L14)

___

### validationFilter

▸ `Private` **validationFilter**(`validationErrors`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `validationErrors` | `ValidationError`[] |

#### Returns

`void`

#### Defined in

[bad-request.filter.ts:26](https://github.com/klub-deepak/poc_doc_generation_3/blob/a592bb2/src/filters/bad-request.filter.ts#L26)
