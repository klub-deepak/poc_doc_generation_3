[awesome-nestjs-boilerplate](../README.md) / UserSubscriber

# Class: UserSubscriber

## Implements

- `EntitySubscriberInterface`<`UserEntity`\>

## Table of contents

### Constructors

- [constructor](UserSubscriber.md#constructor)

### Methods

- [beforeInsert](UserSubscriber.md#beforeinsert)
- [beforeUpdate](UserSubscriber.md#beforeupdate)
- [listenTo](UserSubscriber.md#listento)

## Constructors

### constructor

• **new UserSubscriber**()

## Methods

### beforeInsert

▸ **beforeInsert**(`event`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `event` | `InsertEvent`<`UserEntity`\> |

#### Returns

`void`

#### Implementation of

EntitySubscriberInterface.beforeInsert

#### Defined in

[user-subscriber.ts:17](https://github.com/klub-deepak/poc_doc_generation_3/blob/afd7f83/src/entity-subscribers/user-subscriber.ts#L17)

___

### beforeUpdate

▸ **beforeUpdate**(`event`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `event` | `UpdateEvent`<`UserEntity`\> |

#### Returns

`void`

#### Implementation of

EntitySubscriberInterface.beforeUpdate

#### Defined in

[user-subscriber.ts:23](https://github.com/klub-deepak/poc_doc_generation_3/blob/afd7f83/src/entity-subscribers/user-subscriber.ts#L23)

___

### listenTo

▸ **listenTo**(): typeof `UserEntity`

#### Returns

typeof `UserEntity`

#### Implementation of

EntitySubscriberInterface.listenTo

#### Defined in

[user-subscriber.ts:13](https://github.com/klub-deepak/poc_doc_generation_3/blob/afd7f83/src/entity-subscribers/user-subscriber.ts#L13)
