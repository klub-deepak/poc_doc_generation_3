[awesome-nestjs-boilerplate](../README.md) / AuthController

# Class: AuthController

## Table of contents

### Constructors

- [constructor](AuthController.md#constructor)

### Methods

- [getCurrentUser](AuthController.md#getcurrentuser)
- [userLogin](AuthController.md#userlogin)
- [userRegister](AuthController.md#userregister)

## Constructors

### constructor

• **new AuthController**(`userService`, `authService`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `userService` | `UserService` |
| `authService` | `AuthService` |

#### Defined in

[auth.controller.ts:29](https://github.com/klub-deepak/poc_doc_generation_3/blob/afd7f83/src/modules/auth/auth.controller.ts#L29)

## Methods

### getCurrentUser

▸ **getCurrentUser**(`user`): `UserDto`

#### Parameters

| Name | Type |
| :------ | :------ |
| `user` | `UserEntity` |

#### Returns

`UserDto`

#### Defined in

[auth.controller.ts:77](https://github.com/klub-deepak/poc_doc_generation_3/blob/afd7f83/src/modules/auth/auth.controller.ts#L77)

___

### userLogin

▸ **userLogin**(`userLoginDto`): `Promise`<`LoginPayloadDto`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `userLoginDto` | `UserLoginDto` |

#### Returns

`Promise`<`LoginPayloadDto`\>

#### Defined in

[auth.controller.ts:41](https://github.com/klub-deepak/poc_doc_generation_3/blob/afd7f83/src/modules/auth/auth.controller.ts#L41)

___

### userRegister

▸ **userRegister**(`userRegisterDto`, `file`): `Promise`<`UserDto`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `userRegisterDto` | `UserRegisterDto` |
| `file` | `IFile` |

#### Returns

`Promise`<`UserDto`\>

#### Defined in

[auth.controller.ts:58](https://github.com/klub-deepak/poc_doc_generation_3/blob/afd7f83/src/modules/auth/auth.controller.ts#L58)
