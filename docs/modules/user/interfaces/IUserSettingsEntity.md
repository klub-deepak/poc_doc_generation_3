[awesome-nestjs-boilerplate](../README.md) / IUserSettingsEntity

# Interface: IUserSettingsEntity

## Hierarchy

- `IAbstractEntity`<`UserDto`\>

  ↳ **`IUserSettingsEntity`**

## Implemented by

- [`UserSettingsEntity`](../classes/UserSettingsEntity.md)

## Table of contents

### Properties

- [createdAt](IUserSettingsEntity.md#createdat)
- [id](IUserSettingsEntity.md#id)
- [isEmailVerified](IUserSettingsEntity.md#isemailverified)
- [isPhoneVerified](IUserSettingsEntity.md#isphoneverified)
- [updatedAt](IUserSettingsEntity.md#updatedat)
- [user](IUserSettingsEntity.md#user)

### Methods

- [toDto](IUserSettingsEntity.md#todto)

## Properties

### createdAt

• **createdAt**: `Date`

#### Inherited from

IAbstractEntity.createdAt

#### Defined in

[common/abstract.entity.ts:20](https://github.com/klub-deepak/poc_doc_generation_3/blob/afd7f83/src/common/abstract.entity.ts#L20)

___

### id

• **id**: `string`

#### Inherited from

IAbstractEntity.id

#### Defined in

[common/abstract.entity.ts:19](https://github.com/klub-deepak/poc_doc_generation_3/blob/afd7f83/src/common/abstract.entity.ts#L19)

___

### isEmailVerified

• `Optional` **isEmailVerified**: `boolean`

#### Defined in

[modules/user/user-settings.entity.ts:12](https://github.com/klub-deepak/poc_doc_generation_3/blob/afd7f83/src/modules/user/user-settings.entity.ts#L12)

___

### isPhoneVerified

• `Optional` **isPhoneVerified**: `boolean`

#### Defined in

[modules/user/user-settings.entity.ts:14](https://github.com/klub-deepak/poc_doc_generation_3/blob/afd7f83/src/modules/user/user-settings.entity.ts#L14)

___

### updatedAt

• **updatedAt**: `Date`

#### Inherited from

IAbstractEntity.updatedAt

#### Defined in

[common/abstract.entity.ts:21](https://github.com/klub-deepak/poc_doc_generation_3/blob/afd7f83/src/common/abstract.entity.ts#L21)

___

### user

• `Optional` **user**: `IUserEntity`

#### Defined in

[modules/user/user-settings.entity.ts:16](https://github.com/klub-deepak/poc_doc_generation_3/blob/afd7f83/src/modules/user/user-settings.entity.ts#L16)

## Methods

### toDto

▸ **toDto**(`options?`): `UserDto`

#### Parameters

| Name | Type |
| :------ | :------ |
| `options?` | `undefined` |

#### Returns

`UserDto`

#### Inherited from

IAbstractEntity.toDto

#### Defined in

[common/abstract.entity.ts:23](https://github.com/klub-deepak/poc_doc_generation_3/blob/afd7f83/src/common/abstract.entity.ts#L23)
