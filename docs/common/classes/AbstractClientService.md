[awesome-nestjs-boilerplate](../README.md) / [Exports](../modules.md) / AbstractClientService

# Class: AbstractClientService<ActionType\>

## Type parameters

| Name |
| :------ |
| `ActionType` |

## Table of contents

### Constructors

- [constructor](AbstractClientService.md#constructor)

### Methods

- [send](AbstractClientService.md#send)

## Constructors

### constructor

• **new AbstractClientService**<`ActionType`\>(`client`)

#### Type parameters

| Name |
| :------ |
| `ActionType` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `client` | `ClientProxy` |

#### Defined in

[abstract-client.service.ts:10](https://github.com/klub-deepak/poc_doc_generation_3/blob/a592bb2/src/common/abstract-client.service.ts#L10)

## Methods

### send

▸ **send**<`R`, `I`\>(`pattern`, `data`, `returnDataOptions`, `isType?`): `Promise`<`PageDto`<`R`\>\>

#### Type parameters

| Name |
| :------ |
| `R` |
| `I` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `pattern` | `ActionType` |
| `data` | `I` |
| `returnDataOptions` | `Object` |
| `returnDataOptions.class` | `Constructor`<`R`, `undefined`[]\> |
| `returnDataOptions.isPage` | ``true`` |
| `isType?` | ``false`` |

#### Returns

`Promise`<`PageDto`<`R`\>\>

#### Defined in

[abstract-client.service.ts:12](https://github.com/klub-deepak/poc_doc_generation_3/blob/a592bb2/src/common/abstract-client.service.ts#L12)

▸ **send**<`R`, `I`\>(`pattern`, `data`, `returnDataOptions`): `Promise`<`R`\>

#### Type parameters

| Name |
| :------ |
| `R` |
| `I` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `pattern` | `ActionType` |
| `data` | `I` |
| `returnDataOptions` | { `class`: `Constructor`<`R`, `undefined`[]\> ; `isPage?`: ``false``  } \| { `isPage?`: ``false`` ; `isType`: ``true``  } |

#### Returns

`Promise`<`R`\>

#### Defined in

[abstract-client.service.ts:19](https://github.com/klub-deepak/poc_doc_generation_3/blob/a592bb2/src/common/abstract-client.service.ts#L19)

▸ **send**<`R`, `I`\>(`pattern`, `data`): `Promise`<`void`\>

#### Type parameters

| Name |
| :------ |
| `R` |
| `I` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `pattern` | `ActionType` |
| `data` | `I` |

#### Returns

`Promise`<`void`\>

#### Defined in

[abstract-client.service.ts:27](https://github.com/klub-deepak/poc_doc_generation_3/blob/a592bb2/src/common/abstract-client.service.ts#L27)
