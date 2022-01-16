[awesome-nestjs-boilerplate](../README.md) / UserSettingsEntity

# Class: UserSettingsEntity

## Hierarchy

- `AbstractEntity`<`UserDto`, `UserDtoOptions`\>

  ↳ **`UserSettingsEntity`**

## Implements

- [`IUserSettingsEntity`](../interfaces/IUserSettingsEntity.md)

## Table of contents

### Constructors

- [constructor](UserSettingsEntity.md#constructor)

### Properties

- [createdAt](UserSettingsEntity.md#createdat)
- [id](UserSettingsEntity.md#id)
- [isEmailVerified](UserSettingsEntity.md#isemailverified)
- [isPhoneVerified](UserSettingsEntity.md#isphoneverified)
- [updatedAt](UserSettingsEntity.md#updatedat)
- [user](UserSettingsEntity.md#user)
- [userId](UserSettingsEntity.md#userid)

### Methods

- [toDto](UserSettingsEntity.md#todto)

## Constructors

### constructor

• **new UserSettingsEntity**()

#### Inherited from

AbstractEntity<UserDto, UserDtoOptions\>.constructor

## Properties

### createdAt

• **createdAt**: `Date`

#### Implementation of

[IUserSettingsEntity](../interfaces/IUserSettingsEntity.md).[createdAt](../interfaces/IUserSettingsEntity.md#createdat)

#### Inherited from

AbstractEntity.createdAt

#### Defined in

[common/abstract.entity.ts:37](https://github.com/klub-deepak/poc_doc_generation_3/blob/afd7f83/src/common/abstract.entity.ts#L37)

___

### id

• **id**: `string`

#### Implementation of

[IUserSettingsEntity](../interfaces/IUserSettingsEntity.md).[id](../interfaces/IUserSettingsEntity.md#id)

#### Inherited from

AbstractEntity.id

#### Defined in

[common/abstract.entity.ts:32](https://github.com/klub-deepak/poc_doc_generation_3/blob/afd7f83/src/common/abstract.entity.ts#L32)

___

### isEmailVerified

• `Optional` **isEmailVerified**: `boolean`

#### Implementation of

[IUserSettingsEntity](../interfaces/IUserSettingsEntity.md).[isEmailVerified](../interfaces/IUserSettingsEntity.md#isemailverified)

#### Defined in

[modules/user/user-settings.entity.ts:26](https://github.com/klub-deepak/poc_doc_generation_3/blob/afd7f83/src/modules/user/user-settings.entity.ts#L26)

___

### isPhoneVerified

• `Optional` **isPhoneVerified**: `boolean`

#### Implementation of

[IUserSettingsEntity](../interfaces/IUserSettingsEntity.md).[isPhoneVerified](../interfaces/IUserSettingsEntity.md#isphoneverified)

#### Defined in

[modules/user/user-settings.entity.ts:29](https://github.com/klub-deepak/poc_doc_generation_3/blob/afd7f83/src/modules/user/user-settings.entity.ts#L29)

___

### updatedAt

• **updatedAt**: `Date`

#### Implementation of

[IUserSettingsEntity](../interfaces/IUserSettingsEntity.md).[updatedAt](../interfaces/IUserSettingsEntity.md#updatedat)

#### Inherited from

AbstractEntity.updatedAt

#### Defined in

[common/abstract.entity.ts:42](https://github.com/klub-deepak/poc_doc_generation_3/blob/afd7f83/src/common/abstract.entity.ts#L42)

___

### user

• `Optional` **user**: `UserEntity`

#### Implementation of

[IUserSettingsEntity](../interfaces/IUserSettingsEntity.md).[user](../interfaces/IUserSettingsEntity.md#user)

#### Defined in

[modules/user/user-settings.entity.ts:36](https://github.com/klub-deepak/poc_doc_generation_3/blob/afd7f83/src/modules/user/user-settings.entity.ts#L36)

___

### userId

• `Optional` **userId**: `string`

#### Defined in

[modules/user/user-settings.entity.ts:32](https://github.com/klub-deepak/poc_doc_generation_3/blob/afd7f83/src/modules/user/user-settings.entity.ts#L32)

## Methods

### toDto

▸ **toDto**(`options?`): `UserDto`

#### Parameters

| Name | Type |
| :------ | :------ |
| `options?` | `Partial`<{ `isActive`: `boolean`  }\> |

#### Returns

`UserDto`

#### Implementation of

[IUserSettingsEntity](../interfaces/IUserSettingsEntity.md).[toDto](../interfaces/IUserSettingsEntity.md#todto)

#### Inherited from

AbstractEntity.toDto

#### Defined in

[common/abstract.entity.ts:46](https://github.com/klub-deepak/poc_doc_generation_3/blob/afd7f83/src/common/abstract.entity.ts#L46)
