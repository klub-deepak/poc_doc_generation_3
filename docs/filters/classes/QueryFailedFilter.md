[awesome-nestjs-boilerplate](../README.md) / [Exports](../modules.md) / QueryFailedFilter

# Class: QueryFailedFilter

## Implements

- `ExceptionFilter`<`QueryFailedError`\>

## Table of contents

### Constructors

- [constructor](QueryFailedFilter.md#constructor)

### Properties

- [reflector](QueryFailedFilter.md#reflector)

### Methods

- [catch](QueryFailedFilter.md#catch)

## Constructors

### constructor

• **new QueryFailedFilter**(`reflector`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `reflector` | `Reflector` |

#### Defined in

[query-failed.filter.ts:12](https://github.com/klub-deepak/poc_doc_generation_3/blob/a592bb2/src/filters/query-failed.filter.ts#L12)

## Properties

### reflector

• **reflector**: `Reflector`

## Methods

### catch

▸ **catch**(`exception`, `host`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `exception` | `QueryFailedError` & { `constraint?`: `string`  } |
| `host` | `ArgumentsHost` |

#### Returns

`void`

#### Implementation of

ExceptionFilter.catch

#### Defined in

[query-failed.filter.ts:14](https://github.com/klub-deepak/poc_doc_generation_3/blob/a592bb2/src/filters/query-failed.filter.ts#L14)
