[awesome-nestjs-boilerplate](../README.md) / IUserEntity

# Interface: IUserEntity

## Hierarchy

- `IAbstractEntity`<`UserDto`\>

  ↳ **`IUserEntity`**

## Implemented by

- [`UserEntity`](../classes/UserEntity.md)

## Table of contents

### Properties

- [avatar](IUserEntity.md#avatar)
- [createdAt](IUserEntity.md#createdat)
- [email](IUserEntity.md#email)
- [firstName](IUserEntity.md#firstname)
- [fullName](IUserEntity.md#fullname)
- [id](IUserEntity.md#id)
- [lastName](IUserEntity.md#lastname)
- [password](IUserEntity.md#password)
- [phone](IUserEntity.md#phone)
- [role](IUserEntity.md#role)
- [settings](IUserEntity.md#settings)
- [updatedAt](IUserEntity.md#updatedat)

### Methods

- [toDto](IUserEntity.md#todto)

## Properties

### avatar

• `Optional` **avatar**: `string`

#### Defined in

[modules/user/user.entity.ts:25](https://github.com/klub-deepak/poc_doc_generation_3/blob/afd7f83/src/modules/user/user.entity.ts#L25)

___

### createdAt

• **createdAt**: `Date`

#### Inherited from

IAbstractEntity.createdAt

#### Defined in

[common/abstract.entity.ts:20](https://github.com/klub-deepak/poc_doc_generation_3/blob/afd7f83/src/common/abstract.entity.ts#L20)

___

### email

• `Optional` **email**: `string`

#### Defined in

[modules/user/user.entity.ts:19](https://github.com/klub-deepak/poc_doc_generation_3/blob/afd7f83/src/modules/user/user.entity.ts#L19)

___

### firstName

• `Optional` **firstName**: `string`

#### Defined in

[modules/user/user.entity.ts:13](https://github.com/klub-deepak/poc_doc_generation_3/blob/afd7f83/src/modules/user/user.entity.ts#L13)

___

### fullName

• `Optional` **fullName**: `string`

#### Defined in

[modules/user/user.entity.ts:27](https://github.com/klub-deepak/poc_doc_generation_3/blob/afd7f83/src/modules/user/user.entity.ts#L27)

___

### id

• **id**: `string`

#### Inherited from

IAbstractEntity.id

#### Defined in

[common/abstract.entity.ts:19](https://github.com/klub-deepak/poc_doc_generation_3/blob/afd7f83/src/common/abstract.entity.ts#L19)

___

### lastName

• `Optional` **lastName**: `string`

#### Defined in

[modules/user/user.entity.ts:15](https://github.com/klub-deepak/poc_doc_generation_3/blob/afd7f83/src/modules/user/user.entity.ts#L15)

___

### password

• `Optional` **password**: `string`

#### Defined in

[modules/user/user.entity.ts:21](https://github.com/klub-deepak/poc_doc_generation_3/blob/afd7f83/src/modules/user/user.entity.ts#L21)

___

### phone

• `Optional` **phone**: `string`

#### Defined in

[modules/user/user.entity.ts:23](https://github.com/klub-deepak/poc_doc_generation_3/blob/afd7f83/src/modules/user/user.entity.ts#L23)

___

### role

• **role**: `RoleType`

#### Defined in

[modules/user/user.entity.ts:17](https://github.com/klub-deepak/poc_doc_generation_3/blob/afd7f83/src/modules/user/user.entity.ts#L17)

___

### settings

• `Optional` **settings**: `IUserSettingsEntity`

#### Defined in

[modules/user/user.entity.ts:29](https://github.com/klub-deepak/poc_doc_generation_3/blob/afd7f83/src/modules/user/user.entity.ts#L29)

___

### updatedAt

• **updatedAt**: `Date`

#### Inherited from

IAbstractEntity.updatedAt

#### Defined in

[common/abstract.entity.ts:21](https://github.com/klub-deepak/poc_doc_generation_3/blob/afd7f83/src/common/abstract.entity.ts#L21)

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
