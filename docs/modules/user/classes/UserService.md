[awesome-nestjs-boilerplate](../README.md) / [Exports](../modules.md) / UserService

# Class: UserService

## Table of contents

### Constructors

- [constructor](UserService.md#constructor)

### Methods

- [createSettings](UserService.md#createsettings)
- [createUser](UserService.md#createuser)
- [findByUsernameOrEmail](UserService.md#findbyusernameoremail)
- [findOne](UserService.md#findone)
- [getUser](UserService.md#getuser)
- [getUsers](UserService.md#getusers)

## Constructors

### constructor

• **new UserService**(`userRepository`, `validatorService`, `awsS3Service`, `commandBus`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `userRepository` | `UserRepository` |
| `validatorService` | `ValidatorService` |
| `awsS3Service` | `AwsS3Service` |
| `commandBus` | `CommandBus`<`ICommand`\> |

#### Defined in

[user.service.ts:24](https://github.com/klub-deepak/poc_doc_generation_3/blob/a592bb2/src/modules/user/user.service.ts#L24)

## Methods

### createSettings

▸ **createSettings**(`userId`, `createSettingsDto`): `Promise`<`UserSettingsEntity`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `userId` | `string` |
| `createSettingsDto` | `CreateSettingsDto` |

#### Returns

`Promise`<`UserSettingsEntity`\>

#### Defined in

[user.service.ts:109](https://github.com/klub-deepak/poc_doc_generation_3/blob/a592bb2/src/modules/user/user.service.ts#L109)

___

### createUser

▸ **createUser**(`userRegisterDto`, `file`): `Promise`<`UserEntity`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `userRegisterDto` | `UserRegisterDto` |
| `file` | `IFile` |

#### Returns

`Promise`<`UserEntity`\>

#### Defined in

[user.service.ts:59](https://github.com/klub-deepak/poc_doc_generation_3/blob/a592bb2/src/modules/user/user.service.ts#L59)

___

### findByUsernameOrEmail

▸ **findByUsernameOrEmail**(`options`): `Promise`<`Optional`<`UserEntity`\>\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `options` | `Partial`<{ `email`: `string` ; `username`: `string`  }\> |

#### Returns

`Promise`<`Optional`<`UserEntity`\>\>

#### Defined in

[user.service.ts:38](https://github.com/klub-deepak/poc_doc_generation_3/blob/a592bb2/src/modules/user/user.service.ts#L38)

___

### findOne

▸ **findOne**(`findData`): `Promise`<`Optional`<`UserEntity`\>\>

Find single user

#### Parameters

| Name | Type |
| :------ | :------ |
| `findData` | `FindConditions`<`UserEntity`\> |

#### Returns

`Promise`<`Optional`<`UserEntity`\>\>

#### Defined in

[user.service.ts:34](https://github.com/klub-deepak/poc_doc_generation_3/blob/a592bb2/src/modules/user/user.service.ts#L34)

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

[user.service.ts:95](https://github.com/klub-deepak/poc_doc_generation_3/blob/a592bb2/src/modules/user/user.service.ts#L95)

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

[user.service.ts:86](https://github.com/klub-deepak/poc_doc_generation_3/blob/a592bb2/src/modules/user/user.service.ts#L86)
