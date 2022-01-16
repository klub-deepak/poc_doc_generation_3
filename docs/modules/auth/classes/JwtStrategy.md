[awesome-nestjs-boilerplate](../README.md) / [Exports](../modules.md) / JwtStrategy

# Class: JwtStrategy

## Hierarchy

- `Strategy`<`this`\>

  ↳ **`JwtStrategy`**

## Table of contents

### Constructors

- [constructor](JwtStrategy.md#constructor)

### Properties

- [name](JwtStrategy.md#name)

### Methods

- [authenticate](JwtStrategy.md#authenticate)
- [error](JwtStrategy.md#error)
- [fail](JwtStrategy.md#fail)
- [pass](JwtStrategy.md#pass)
- [redirect](JwtStrategy.md#redirect)
- [success](JwtStrategy.md#success)
- [validate](JwtStrategy.md#validate)

## Constructors

### constructor

• **new JwtStrategy**(`configService`, `userService`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `configService` | `ApiConfigService` |
| `userService` | `UserService` |

#### Overrides

PassportStrategy(Strategy).constructor

#### Defined in

[src/modules/auth/jwt.strategy.ts:13](https://github.com/klub-deepak/poc_doc_generation_3/blob/a592bb2/src/modules/auth/jwt.strategy.ts#L13)

## Properties

### name

• **name**: `string`

#### Inherited from

PassportStrategy(Strategy).name

#### Defined in

node_modules/@types/passport-jwt/index.d.ts:19

## Methods

### authenticate

▸ **authenticate**(`req`, `options?`): `void`

Performs authentication for the request.
Note: Virtual function - re-implement in the strategy.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `req` | `Request`<`ParamsDictionary`, `any`, `any`, `ParsedQs`, `Record`<`string`, `any`\>\> | The request to authenticate. |
| `options?` | `any` | Options passed to the strategy. |

#### Returns

`void`

#### Inherited from

PassportStrategy(Strategy).authenticate

#### Defined in

node_modules/@types/passport-strategy/index.d.ts:26

___

### error

▸ **error**(`err`): `void`

Internal error while performing authentication.

Strategies should call this function when an internal error occurs
during the process of performing authentication; for example, if the
user directory is not available.

**`api`** public

#### Parameters

| Name | Type |
| :------ | :------ |
| `err` | `Error` |

#### Returns

`void`

#### Inherited from

PassportStrategy(Strategy).error

#### Defined in

node_modules/@types/passport-strategy/index.d.ts:96

___

### fail

▸ **fail**(`challenge`, `status`): `void`

Fail authentication, with optional `challenge` and `status`, defaulting
to 401.

Strategies should call this function to fail an authentication attempt.

**`api`** public

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `challenge` | `any` | (Can also be an object with 'message' and 'type' fields). |
| `status` | `number` |  |

#### Returns

`void`

#### Inherited from

PassportStrategy(Strategy).fail

#### Defined in

node_modules/@types/passport-strategy/index.d.ts:60

▸ **fail**(`status`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `status` | `number` |

#### Returns

`void`

#### Inherited from

PassportStrategy(Strategy).fail

#### Defined in

node_modules/@types/passport-strategy/index.d.ts:61

___

### pass

▸ **pass**(): `void`

Pass without making a success or fail decision.

Under most circumstances, Strategies should not need to call this
function.  It exists primarily to allow previous authentication state
to be restored, for example from an HTTP session.

**`api`** public

#### Returns

`void`

#### Inherited from

PassportStrategy(Strategy).pass

#### Defined in

node_modules/@types/passport-strategy/index.d.ts:84

___

### redirect

▸ **redirect**(`url`, `status?`): `void`

Redirect to `url` with optional `status`, defaulting to 302.

Strategies should call this function to redirect the user (via their
user agent) to a third-party website for authentication.

**`api`** public

#### Parameters

| Name | Type |
| :------ | :------ |
| `url` | `string` |
| `status?` | `number` |

#### Returns

`void`

#### Inherited from

PassportStrategy(Strategy).redirect

#### Defined in

node_modules/@types/passport-strategy/index.d.ts:73

___

### success

▸ **success**(`user`, `info?`): `void`

Authenticate `user`, with optional `info`.

Strategies should call this function to successfully authenticate a
user.  `user` should be an object supplied by the application after it
has been given an opportunity to verify credentials.  `info` is an
optional argument containing additional user information.  This is
useful for third-party authentication strategies to pass profile
details.

**`api`** public

#### Parameters

| Name | Type |
| :------ | :------ |
| `user` | `any` |
| `info?` | `any` |

#### Returns

`void`

#### Inherited from

PassportStrategy(Strategy).success

#### Defined in

node_modules/@types/passport-strategy/index.d.ts:48

___

### validate

▸ **validate**(`args`): `Promise`<`UserEntity`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `args` | `Object` |
| `args.role` | `RoleType` |
| `args.type` | `ACCESS_TOKEN` |
| `args.userId` | `string` |

#### Returns

`Promise`<`UserEntity`\>

#### Defined in

[src/modules/auth/jwt.strategy.ts:23](https://github.com/klub-deepak/poc_doc_generation_3/blob/a592bb2/src/modules/auth/jwt.strategy.ts#L23)
