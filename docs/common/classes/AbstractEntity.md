[awesome-nestjs-boilerplate](../README.md) / AbstractEntity

# Class: AbstractEntity<DTO, O\>

## Type parameters

| Name | Type |
| :------ | :------ |
| `DTO` | extends `AbstractDto` = `AbstractDto` |
| `O` | `never` |

## Implements

- [`IAbstractEntity`](../interfaces/IAbstractEntity.md)<`DTO`, `O`\>

## Table of contents

### Constructors

- [constructor](AbstractEntity.md#constructor)

### Properties

- [createdAt](AbstractEntity.md#createdat)
- [dtoClass](AbstractEntity.md#dtoclass)
- [id](AbstractEntity.md#id)
- [updatedAt](AbstractEntity.md#updatedat)

### Methods

- [toDto](AbstractEntity.md#todto)

## Constructors

### constructor

• **new AbstractEntity**<`DTO`, `O`\>()

#### Type parameters

| Name | Type |
| :------ | :------ |
| `DTO` | extends `AbstractDto`<`DTO`\> = `AbstractDto` |
| `O` | `never` |

## Properties

### createdAt

• **createdAt**: `Date`

#### Implementation of

[IAbstractEntity](../interfaces/IAbstractEntity.md).[createdAt](../interfaces/IAbstractEntity.md#createdat)

#### Defined in

[abstract.entity.ts:37](https://github.com/klub-deepak/poc_doc_generation_3/blob/afd7f83/src/common/abstract.entity.ts#L37)

___

### dtoClass

• `Private` **dtoClass**: `Constructor`<`DTO`, [[`AbstractEntity`](AbstractEntity.md)<`AbstractDto`, `never`\>, O?]\>

#### Defined in

[abstract.entity.ts:44](https://github.com/klub-deepak/poc_doc_generation_3/blob/afd7f83/src/common/abstract.entity.ts#L44)

___

### id

• **id**: `string`

#### Implementation of

[IAbstractEntity](../interfaces/IAbstractEntity.md).[id](../interfaces/IAbstractEntity.md#id)

#### Defined in

[abstract.entity.ts:32](https://github.com/klub-deepak/poc_doc_generation_3/blob/afd7f83/src/common/abstract.entity.ts#L32)

___

### updatedAt

• **updatedAt**: `Date`

#### Implementation of

[IAbstractEntity](../interfaces/IAbstractEntity.md).[updatedAt](../interfaces/IAbstractEntity.md#updatedat)

#### Defined in

[abstract.entity.ts:42](https://github.com/klub-deepak/poc_doc_generation_3/blob/afd7f83/src/common/abstract.entity.ts#L42)

## Methods

### toDto

▸ **toDto**(`options?`): `DTO`

#### Parameters

| Name | Type |
| :------ | :------ |
| `options?` | `O` |

#### Returns

`DTO`

#### Implementation of

[IAbstractEntity](../interfaces/IAbstractEntity.md).[toDto](../interfaces/IAbstractEntity.md#todto)

#### Defined in

[abstract.entity.ts:46](https://github.com/klub-deepak/poc_doc_generation_3/blob/afd7f83/src/common/abstract.entity.ts#L46)
