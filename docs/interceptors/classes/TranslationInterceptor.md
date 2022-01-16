[awesome-nestjs-boilerplate](../README.md) / [Exports](../modules.md) / TranslationInterceptor

# Class: TranslationInterceptor

## Implements

- `NestInterceptor`

## Table of contents

### Constructors

- [constructor](TranslationInterceptor.md#constructor)

### Methods

- [intercept](TranslationInterceptor.md#intercept)

## Constructors

### constructor

• **new TranslationInterceptor**(`translationService`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `translationService` | `TranslationService` |

#### Defined in

[translation-interceptor.service.ts:15](https://github.com/klub-deepak/poc_doc_generation_3/blob/a592bb2/src/interceptors/translation-interceptor.service.ts#L15)

## Methods

### intercept

▸ **intercept**(`_context`, `next`): `Observable`<`AbstractDto`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `_context` | `ExecutionContext` |
| `next` | `CallHandler`<`any`\> |

#### Returns

`Observable`<`AbstractDto`\>

#### Implementation of

NestInterceptor.intercept

#### Defined in

[translation-interceptor.service.ts:17](https://github.com/klub-deepak/poc_doc_generation_3/blob/a592bb2/src/interceptors/translation-interceptor.service.ts#L17)
