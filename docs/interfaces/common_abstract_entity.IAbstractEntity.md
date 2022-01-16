[awesome-nestjs-boilerplate](../README.md) / [Modules](../modules.md) / [common/abstract.entity](../modules/common_abstract_entity.md) / IAbstractEntity

# Interface: IAbstractEntity<DTO, O\>

[common/abstract.entity](../modules/common_abstract_entity.md).IAbstractEntity

Abstract Entity

**`author`** Narek Hakobyan <narek.hakobyan.07@gmail.com>

**`description`** This class is an abstract class for all entities.
It's experimental and recommended using it only in microservice architecture,
otherwise just delete and use your own entity.

## Type parameters

| Name | Type |
| :------ | :------ |
| `DTO` | extends [`AbstractDto`](../classes/common_dto_abstract_dto.AbstractDto.md) |
| `O` | `never` |

## Implemented by

- [`AbstractEntity`](../classes/common_abstract_entity.AbstractEntity.md)

## Table of contents

### Properties

- [createdAt](common_abstract_entity.IAbstractEntity.md#createdat)
- [id](common_abstract_entity.IAbstractEntity.md#id)
- [updatedAt](common_abstract_entity.IAbstractEntity.md#updatedat)

### Methods

- [toDto](common_abstract_entity.IAbstractEntity.md#todto)

## Properties

### createdAt

• **createdAt**: `Date`

#### Defined in

common/abstract.entity.ts:20

___

### id

• **id**: `string`

#### Defined in

common/abstract.entity.ts:19

___

### updatedAt

• **updatedAt**: `Date`

#### Defined in

common/abstract.entity.ts:21

## Methods

### toDto

▸ **toDto**(`options?`): `DTO`

#### Parameters

| Name | Type |
| :------ | :------ |
| `options?` | `O` |

#### Returns

`DTO`

#### Defined in

common/abstract.entity.ts:23
