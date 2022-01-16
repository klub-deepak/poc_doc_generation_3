[awesome-nestjs-boilerplate](../README.md) / [Exports](../modules.md) / TranslationService

# Class: TranslationService

## Table of contents

### Constructors

- [constructor](TranslationService.md#constructor)

### Methods

- [translate](TranslationService.md#translate)
- [translateNecessaryKeys](TranslationService.md#translatenecessarykeys)

## Constructors

### constructor

• **new TranslationService**(`i18n`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `i18n` | `I18nService` |

#### Defined in

[translation.service.ts:13](https://github.com/klub-deepak/poc_doc_generation_3/blob/a592bb2/src/shared/services/translation.service.ts#L13)

## Methods

### translate

▸ **translate**(`key`, `options?`): `Promise`<`string`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `key` | `string` |
| `options` | `translateOptions` |

#### Returns

`Promise`<`string`\>

#### Defined in

[translation.service.ts:15](https://github.com/klub-deepak/poc_doc_generation_3/blob/a592bb2/src/shared/services/translation.service.ts#L15)

___

### translateNecessaryKeys

▸ **translateNecessaryKeys**<`T`\>(`dto`): `Promise`<`T`\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `AbstractDto`<`T`\> |

#### Parameters

| Name | Type |
| :------ | :------ |
| `dto` | `T` |

#### Returns

`Promise`<`T`\>

#### Defined in

[translation.service.ts:22](https://github.com/klub-deepak/poc_doc_generation_3/blob/a592bb2/src/shared/services/translation.service.ts#L22)
