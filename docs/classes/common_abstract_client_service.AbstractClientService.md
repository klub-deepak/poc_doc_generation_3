[awesome-nestjs-boilerplate](../README.md) / [Modules](../modules.md) / [common/abstract-client.service](../modules/common_abstract_client_service.md) / AbstractClientService

# Class: AbstractClientService<ActionType\>

[common/abstract-client.service](../modules/common_abstract_client_service.md).AbstractClientService

## Type parameters

| Name |
| :------ |
| `ActionType` |

## Table of contents

### Constructors

- [constructor](common_abstract_client_service.AbstractClientService.md#constructor)

### Methods

- [send](common_abstract_client_service.AbstractClientService.md#send)

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

common/abstract-client.service.ts:10

## Methods

### send

▸ **send**<`R`, `I`\>(`pattern`, `data`, `returnDataOptions`, `isType?`): `Promise`<[`PageDto`](common_dto_page_dto.PageDto.md)<`R`\>\>

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

`Promise`<[`PageDto`](common_dto_page_dto.PageDto.md)<`R`\>\>

#### Defined in

common/abstract-client.service.ts:12

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

common/abstract-client.service.ts:19

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

common/abstract-client.service.ts:27
