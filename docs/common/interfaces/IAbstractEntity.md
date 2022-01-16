[awesome-nestjs-boilerplate](../README.md) / [Exports](../modules.md) / IAbstractEntity

# Interface: IAbstractEntity<DTO, O\>

Abstract Entity

**`author`** Narek Hakobyan <narek.hakobyan.07@gmail.com>

**`description`** This class is an abstract class for all entities.
It's experimental and recommended using it only in microservice architecture,
otherwise just delete and use your own entity.

## Type parameters

| Name | Type |
| :------ | :------ |
| `DTO` | extends `AbstractDto` |
| `O` | `never` |

## Implemented by

- [`AbstractEntity`](../classes/AbstractEntity.md)

## Table of contents

### Properties

- [createdAt](IAbstractEntity.md#createdat)
- [id](IAbstractEntity.md#id)
- [updatedAt](IAbstractEntity.md#updatedat)

### Methods

- [toDto](IAbstractEntity.md#todto)

## Properties

### createdAt

• **createdAt**: `Date`

#### Defined in

[abstract.entity.ts:20](https://github.com/klub-deepak/poc_doc_generation_3/blob/a592bb2/src/common/abstract.entity.ts#L20)

___

### id

• **id**: `string`

#### Defined in

[abstract.entity.ts:19](https://github.com/klub-deepak/poc_doc_generation_3/blob/a592bb2/src/common/abstract.entity.ts#L19)

___

### updatedAt

• **updatedAt**: `Date`

#### Defined in

[abstract.entity.ts:21](https://github.com/klub-deepak/poc_doc_generation_3/blob/a592bb2/src/common/abstract.entity.ts#L21)

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

[abstract.entity.ts:23](https://github.com/klub-deepak/poc_doc_generation_3/blob/a592bb2/src/common/abstract.entity.ts#L23)
