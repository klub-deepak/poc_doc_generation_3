[awesome-nestjs-boilerplate](../README.md) / UserController

# Class: UserController

## Table of contents

### Constructors

- [constructor](UserController.md#constructor)

### Methods

- [admin](UserController.md#admin)
- [getUser](UserController.md#getuser)
- [getUsers](UserController.md#getusers)

## Constructors

### constructor

• **new UserController**(`userService`, `translationService`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `userService` | `UserService` |
| `translationService` | `TranslationService` |

#### Defined in

[user.controller.ts:23](https://github.com/klub-deepak/poc_doc_generation_3/blob/afd7f83/src/modules/user/user.controller.ts#L23)

## Methods

### admin

▸ **admin**(`user`): `Promise`<`string`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `user` | `UserEntity` |

#### Returns

`Promise`<`string`\>

#### Defined in

[user.controller.ts:31](https://github.com/klub-deepak/poc_doc_generation_3/blob/afd7f83/src/modules/user/user.controller.ts#L31)

___

### getUser

▸ **getUser**(`userId`): `Promise`<`UserDto`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `userId` | `string` |

#### Returns

`Promise`<`UserDto`\>

#### Defined in

[user.controller.ts:65](https://github.com/klub-deepak/poc_doc_generation_3/blob/afd7f83/src/modules/user/user.controller.ts#L65)

___

### getUsers

▸ **getUsers**(`pageOptionsDto`): `Promise`<`PageDto`<`UserDto`\>\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `pageOptionsDto` | `UsersPageOptionsDto` |

#### Returns

`Promise`<`PageDto`<`UserDto`\>\>

#### Defined in

[user.controller.ts:50](https://github.com/klub-deepak/poc_doc_generation_3/blob/afd7f83/src/modules/user/user.controller.ts#L50)
