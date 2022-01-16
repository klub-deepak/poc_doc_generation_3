[awesome-nestjs-boilerplate](../README.md) / [Exports](../modules.md) / UserDto

# Class: UserDto

## Hierarchy

- `AbstractDto`

  ↳ **`UserDto`**

## Table of contents

### Constructors

- [constructor](UserDto.md#constructor)

### Properties

- [avatar](UserDto.md#avatar)
- [createdAt](UserDto.md#createdat)
- [email](UserDto.md#email)
- [firstName](UserDto.md#firstname)
- [id](UserDto.md#id)
- [isActive](UserDto.md#isactive)
- [lastName](UserDto.md#lastname)
- [phone](UserDto.md#phone)
- [role](UserDto.md#role)
- [updatedAt](UserDto.md#updatedat)
- [username](UserDto.md#username)

## Constructors

### constructor

• **new UserDto**(`user`, `options?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `user` | `UserEntity` |
| `options?` | `Partial`<{ `isActive`: `boolean`  }\> |

#### Overrides

AbstractDto.constructor

#### Defined in

[modules/user/dto/user.dto.ts:35](https://github.com/klub-deepak/poc_doc_generation_3/blob/a592bb2/src/modules/user/dto/user.dto.ts#L35)

## Properties

### avatar

• `Optional` **avatar**: `string`

#### Defined in

[modules/user/dto/user.dto.ts:27](https://github.com/klub-deepak/poc_doc_generation_3/blob/a592bb2/src/modules/user/dto/user.dto.ts#L27)

___

### createdAt

• **createdAt**: `Date`

#### Inherited from

AbstractDto.createdAt

#### Defined in

[common/dto/abstract.dto.ts:10](https://github.com/klub-deepak/poc_doc_generation_3/blob/a592bb2/src/common/dto/abstract.dto.ts#L10)

___

### email

• `Optional` **email**: `string`

#### Defined in

[modules/user/dto/user.dto.ts:24](https://github.com/klub-deepak/poc_doc_generation_3/blob/a592bb2/src/modules/user/dto/user.dto.ts#L24)

___

### firstName

• `Optional` **firstName**: `string`

#### Defined in

[modules/user/dto/user.dto.ts:12](https://github.com/klub-deepak/poc_doc_generation_3/blob/a592bb2/src/modules/user/dto/user.dto.ts#L12)

___

### id

• **id**: `string`

#### Inherited from

AbstractDto.id

#### Defined in

[common/dto/abstract.dto.ts:7](https://github.com/klub-deepak/poc_doc_generation_3/blob/a592bb2/src/common/dto/abstract.dto.ts#L7)

___

### isActive

• `Optional` **isActive**: `boolean`

#### Defined in

[modules/user/dto/user.dto.ts:33](https://github.com/klub-deepak/poc_doc_generation_3/blob/a592bb2/src/modules/user/dto/user.dto.ts#L33)

___

### lastName

• `Optional` **lastName**: `string`

#### Defined in

[modules/user/dto/user.dto.ts:15](https://github.com/klub-deepak/poc_doc_generation_3/blob/a592bb2/src/modules/user/dto/user.dto.ts#L15)

___

### phone

• `Optional` **phone**: `string`

#### Defined in

[modules/user/dto/user.dto.ts:30](https://github.com/klub-deepak/poc_doc_generation_3/blob/a592bb2/src/modules/user/dto/user.dto.ts#L30)

___

### role

• **role**: `RoleType`

#### Defined in

[modules/user/dto/user.dto.ts:21](https://github.com/klub-deepak/poc_doc_generation_3/blob/a592bb2/src/modules/user/dto/user.dto.ts#L21)

___

### updatedAt

• **updatedAt**: `Date`

#### Inherited from

AbstractDto.updatedAt

#### Defined in

[common/dto/abstract.dto.ts:13](https://github.com/klub-deepak/poc_doc_generation_3/blob/a592bb2/src/common/dto/abstract.dto.ts#L13)

___

### username

• **username**: `string`

#### Defined in

[modules/user/dto/user.dto.ts:18](https://github.com/klub-deepak/poc_doc_generation_3/blob/a592bb2/src/modules/user/dto/user.dto.ts#L18)
