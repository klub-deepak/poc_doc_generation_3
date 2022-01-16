[awesome-nestjs-boilerplate](../README.md) / [Modules](../modules.md) / [common/abstract.entity](../modules/common_abstract_entity.md) / AbstractEntity

# Class: AbstractEntity<DTO, O\>

[common/abstract.entity](../modules/common_abstract_entity.md).AbstractEntity

## Type parameters

| Name | Type |
| :------ | :------ |
| `DTO` | extends [`AbstractDto`](common_dto_abstract_dto.AbstractDto.md) = [`AbstractDto`](common_dto_abstract_dto.AbstractDto.md) |
| `O` | `never` |

## Implements

- [`IAbstractEntity`](../interfaces/common_abstract_entity.IAbstractEntity.md)<`DTO`, `O`\>

## Table of contents

### Constructors

- [constructor](common_abstract_entity.AbstractEntity.md#constructor)

### Properties

- [createdAt](common_abstract_entity.AbstractEntity.md#createdat)
- [dtoClass](common_abstract_entity.AbstractEntity.md#dtoclass)
- [id](common_abstract_entity.AbstractEntity.md#id)
- [updatedAt](common_abstract_entity.AbstractEntity.md#updatedat)

### Methods

- [toDto](common_abstract_entity.AbstractEntity.md#todto)

## Constructors

### constructor

• **new AbstractEntity**<`DTO`, `O`\>()

#### Type parameters

| Name | Type |
| :------ | :------ |
| `DTO` | extends [`AbstractDto`](common_dto_abstract_dto.AbstractDto.md)<`DTO`\> = [`AbstractDto`](common_dto_abstract_dto.AbstractDto.md) |
| `O` | `never` |

## Properties

### createdAt

• **createdAt**: `Date`

#### Implementation of

[IAbstractEntity](../interfaces/common_abstract_entity.IAbstractEntity.md).[createdAt](../interfaces/common_abstract_entity.IAbstractEntity.md#createdat)

#### Defined in

common/abstract.entity.ts:37

___

### dtoClass

• `Private` **dtoClass**: `Constructor`<`DTO`, [[`AbstractEntity`](common_abstract_entity.AbstractEntity.md)<[`AbstractDto`](common_dto_abstract_dto.AbstractDto.md), `never`\>, O?]\>

#### Defined in

common/abstract.entity.ts:44

___

### id

• **id**: `string`

#### Implementation of

[IAbstractEntity](../interfaces/common_abstract_entity.IAbstractEntity.md).[id](../interfaces/common_abstract_entity.IAbstractEntity.md#id)

#### Defined in

common/abstract.entity.ts:32

___

### updatedAt

• **updatedAt**: `Date`

#### Implementation of

[IAbstractEntity](../interfaces/common_abstract_entity.IAbstractEntity.md).[updatedAt](../interfaces/common_abstract_entity.IAbstractEntity.md#updatedat)

#### Defined in

common/abstract.entity.ts:42

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

[IAbstractEntity](../interfaces/common_abstract_entity.IAbstractEntity.md).[toDto](../interfaces/common_abstract_entity.IAbstractEntity.md#todto)

#### Defined in

common/abstract.entity.ts:46
