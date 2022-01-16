[awesome-nestjs-boilerplate](../README.md) / [Exports](../modules.md) / PublicStrategy

# Class: PublicStrategy

## Hierarchy

- `Strategy`<`this`\> & `StrategyCreatedStatic`

  ↳ **`PublicStrategy`**

## Table of contents

### Constructors

- [constructor](PublicStrategy.md#constructor)

### Properties

- [name](PublicStrategy.md#name)

### Methods

- [authenticate](PublicStrategy.md#authenticate)
- [error](PublicStrategy.md#error)
- [fail](PublicStrategy.md#fail)
- [pass](PublicStrategy.md#pass)
- [redirect](PublicStrategy.md#redirect)
- [success](PublicStrategy.md#success)

## Constructors

### constructor

• **new PublicStrategy**()

#### Overrides

PassportStrategy(Strategy, &#x27;public&#x27;).constructor

#### Defined in

[src/modules/auth/public.strategy.ts:7](https://github.com/klub-deepak/poc_doc_generation_3/blob/a592bb2/src/modules/auth/public.strategy.ts#L7)

## Properties

### name

• `Optional` **name**: `string`

#### Inherited from

PassportStrategy(Strategy, 'public').name

#### Defined in

node_modules/@types/passport/index.d.ts:98

## Methods

### authenticate

▸ **authenticate**(): `void`

#### Returns

`void`

#### Overrides

PassportStrategy(Strategy, &#x27;public&#x27;).authenticate

#### Defined in

[src/modules/auth/public.strategy.ts:11](https://github.com/klub-deepak/poc_doc_generation_3/blob/a592bb2/src/modules/auth/public.strategy.ts#L11)

___

### error

▸ **error**(`err`): `void`

Internal error while performing authentication.

Strategies should call this function when an internal error occurs
during the process of performing authentication; for example, if the
user directory is not available.

#### Parameters

| Name | Type |
| :------ | :------ |
| `err` | `any` |

#### Returns

`void`

#### Inherited from

PassportStrategy(Strategy, 'public').error

#### Defined in

node_modules/@types/passport/index.d.ts:143

___

### fail

▸ **fail**(`challenge?`, `status?`): `void`

Fail authentication, with optional `challenge` and `status`, defaulting
to 401.

Strategies should call this function to fail an authentication attempt.

#### Parameters

| Name | Type |
| :------ | :------ |
| `challenge?` | `string` \| `number` |
| `status?` | `number` |

#### Returns

`void`

#### Inherited from

PassportStrategy(Strategy, 'public').fail

#### Defined in

node_modules/@types/passport/index.d.ts:120

___

### pass

▸ **pass**(): `void`

Pass without making a success or fail decision.

Under most circumstances, Strategies should not need to call this
function.  It exists primarily to allow previous authentication state
to be restored, for example from an HTTP session.

#### Returns

`void`

#### Inherited from

PassportStrategy(Strategy, 'public').pass

#### Defined in

node_modules/@types/passport/index.d.ts:135

___

### redirect

▸ **redirect**(`url`, `status?`): `void`

Redirect to `url` with optional `status`, defaulting to 302.

Strategies should call this function to redirect the user (via their
user agent) to a third-party website for authentication.

#### Parameters

| Name | Type |
| :------ | :------ |
| `url` | `string` |
| `status?` | `number` |

#### Returns

`void`

#### Inherited from

PassportStrategy(Strategy, 'public').redirect

#### Defined in

node_modules/@types/passport/index.d.ts:127

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

#### Parameters

| Name | Type |
| :------ | :------ |
| `user` | `User` |
| `info?` | `object` |

#### Returns

`void`

#### Inherited from

PassportStrategy(Strategy, 'public').success

#### Defined in

node_modules/@types/passport/index.d.ts:113
