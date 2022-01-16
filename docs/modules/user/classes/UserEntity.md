[awesome-nestjs-boilerplate](../README.md) / [Exports](../modules.md) / UserEntity

# Class: UserEntity

## Hierarchy

- `AbstractEntity`<`UserDto`, `UserDtoOptions`\>

  ↳ **`UserEntity`**

## Implements

- [`IUserEntity`](../interfaces/IUserEntity.md)

## Table of contents

### Constructors

- [constructor](UserEntity.md#constructor)

### Properties

- [avatar](UserEntity.md#avatar)
- [createdAt](UserEntity.md#createdat)
- [email](UserEntity.md#email)
- [firstName](UserEntity.md#firstname)
- [fullName](UserEntity.md#fullname)
- [id](UserEntity.md#id)
- [lastName](UserEntity.md#lastname)
- [password](UserEntity.md#password)
- [phone](UserEntity.md#phone)
- [role](UserEntity.md#role)
- [settings](UserEntity.md#settings)
- [updatedAt](UserEntity.md#updatedat)

### Methods

- [toDto](UserEntity.md#todto)

## Constructors

### constructor

• **new UserEntity**()

#### Inherited from

AbstractEntity<UserDto, UserDtoOptions\>.constructor

## Properties

### avatar

• `Optional` **avatar**: `string`

#### Implementation of

[IUserEntity](../interfaces/IUserEntity.md).[avatar](../interfaces/IUserEntity.md#avatar)

#### Defined in

[modules/user/user.entity.ts:57](https://github.com/klub-deepak/poc_doc_generation_3/blob/a592bb2/src/modules/user/user.entity.ts#L57)

___

### createdAt

• **createdAt**: `Date`

#### Implementation of

[IUserEntity](../interfaces/IUserEntity.md).[createdAt](../interfaces/IUserEntity.md#createdat)

#### Inherited from

AbstractEntity.createdAt

#### Defined in

[common/abstract.entity.ts:37](https://github.com/klub-deepak/poc_doc_generation_3/blob/a592bb2/src/common/abstract.entity.ts#L37)

___

### email

• `Optional` **email**: `string`

#### Implementation of

[IUserEntity](../interfaces/IUserEntity.md).[email](../interfaces/IUserEntity.md#email)

#### Defined in

[modules/user/user.entity.ts:48](https://github.com/klub-deepak/poc_doc_generation_3/blob/a592bb2/src/modules/user/user.entity.ts#L48)

___

### firstName

• `Optional` **firstName**: `string`

#### Implementation of

[IUserEntity](../interfaces/IUserEntity.md).[firstName](../interfaces/IUserEntity.md#firstname)

#### Defined in

[modules/user/user.entity.ts:39](https://github.com/klub-deepak/poc_doc_generation_3/blob/a592bb2/src/modules/user/user.entity.ts#L39)

___

### fullName

• `Optional` **fullName**: `string`

#### Implementation of

[IUserEntity](../interfaces/IUserEntity.md).[fullName](../interfaces/IUserEntity.md#fullname)

#### Defined in

[modules/user/user.entity.ts:60](https://github.com/klub-deepak/poc_doc_generation_3/blob/a592bb2/src/modules/user/user.entity.ts#L60)

___

### id

• **id**: `string`

#### Implementation of

[IUserEntity](../interfaces/IUserEntity.md).[id](../interfaces/IUserEntity.md#id)

#### Inherited from

AbstractEntity.id

#### Defined in

[common/abstract.entity.ts:32](https://github.com/klub-deepak/poc_doc_generation_3/blob/a592bb2/src/common/abstract.entity.ts#L32)

___

### lastName

• `Optional` **lastName**: `string`

#### Implementation of

[IUserEntity](../interfaces/IUserEntity.md).[lastName](../interfaces/IUserEntity.md#lastname)

#### Defined in

[modules/user/user.entity.ts:42](https://github.com/klub-deepak/poc_doc_generation_3/blob/a592bb2/src/modules/user/user.entity.ts#L42)

___

### password

• `Optional` **password**: `string`

#### Implementation of

[IUserEntity](../interfaces/IUserEntity.md).[password](../interfaces/IUserEntity.md#password)

#### Defined in

[modules/user/user.entity.ts:51](https://github.com/klub-deepak/poc_doc_generation_3/blob/a592bb2/src/modules/user/user.entity.ts#L51)

___

### phone

• `Optional` **phone**: `string`

#### Implementation of

[IUserEntity](../interfaces/IUserEntity.md).[phone](../interfaces/IUserEntity.md#phone)

#### Defined in

[modules/user/user.entity.ts:54](https://github.com/klub-deepak/poc_doc_generation_3/blob/a592bb2/src/modules/user/user.entity.ts#L54)

___

### role

• **role**: `RoleType`

#### Implementation of

[IUserEntity](../interfaces/IUserEntity.md).[role](../interfaces/IUserEntity.md#role)

#### Defined in

[modules/user/user.entity.ts:45](https://github.com/klub-deepak/poc_doc_generation_3/blob/a592bb2/src/modules/user/user.entity.ts#L45)

___

### settings

• `Optional` **settings**: `UserSettingsEntity`

#### Implementation of

[IUserEntity](../interfaces/IUserEntity.md).[settings](../interfaces/IUserEntity.md#settings)

#### Defined in

[modules/user/user.entity.ts:63](https://github.com/klub-deepak/poc_doc_generation_3/blob/a592bb2/src/modules/user/user.entity.ts#L63)

___

### updatedAt

• **updatedAt**: `Date`

#### Implementation of

[IUserEntity](../interfaces/IUserEntity.md).[updatedAt](../interfaces/IUserEntity.md#updatedat)

#### Inherited from

AbstractEntity.updatedAt

#### Defined in

[common/abstract.entity.ts:42](https://github.com/klub-deepak/poc_doc_generation_3/blob/a592bb2/src/common/abstract.entity.ts#L42)

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

[IUserEntity](../interfaces/IUserEntity.md).[toDto](../interfaces/IUserEntity.md#todto)

#### Inherited from

AbstractEntity.toDto

#### Defined in

[common/abstract.entity.ts:46](https://github.com/klub-deepak/poc_doc_generation_3/blob/a592bb2/src/common/abstract.entity.ts#L46)
