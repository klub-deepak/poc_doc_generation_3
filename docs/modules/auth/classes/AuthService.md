[awesome-nestjs-boilerplate](../README.md) / AuthService

# Class: AuthService

## Table of contents

### Constructors

- [constructor](AuthService.md#constructor)

### Methods

- [createAccessToken](AuthService.md#createaccesstoken)
- [validateUser](AuthService.md#validateuser)

## Constructors

### constructor

• **new AuthService**(`jwtService`, `configService`, `userService`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `jwtService` | `JwtService` |
| `configService` | `ApiConfigService` |
| `userService` | `UserService` |

#### Defined in

[auth.service.ts:16](https://github.com/klub-deepak/poc_doc_generation_3/blob/afd7f83/src/modules/auth/auth.service.ts#L16)

## Methods

### createAccessToken

▸ **createAccessToken**(`data`): `Promise`<`TokenPayloadDto`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `Object` |
| `data.role` | `RoleType` |
| `data.userId` | `string` |

#### Returns

`Promise`<`TokenPayloadDto`\>

#### Defined in

[auth.service.ts:22](https://github.com/klub-deepak/poc_doc_generation_3/blob/afd7f83/src/modules/auth/auth.service.ts#L22)

___

### validateUser

▸ **validateUser**(`userLoginDto`): `Promise`<`UserEntity`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `userLoginDto` | `UserLoginDto` |

#### Returns

`Promise`<`UserEntity`\>

#### Defined in

[auth.service.ts:36](https://github.com/klub-deepak/poc_doc_generation_3/blob/afd7f83/src/modules/auth/auth.service.ts#L36)
