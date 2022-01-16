[awesome-nestjs-boilerplate](../README.md) / ContextProvider

# Class: ContextProvider

## Table of contents

### Constructors

- [constructor](ContextProvider.md#constructor)

### Properties

- [authUserKey](ContextProvider.md#authuserkey)
- [languageKey](ContextProvider.md#languagekey)
- [nameSpace](ContextProvider.md#namespace)

### Methods

- [get](ContextProvider.md#get)
- [getAuthUser](ContextProvider.md#getauthuser)
- [getKeyWithNamespace](ContextProvider.md#getkeywithnamespace)
- [getLanguage](ContextProvider.md#getlanguage)
- [set](ContextProvider.md#set)
- [setAuthUser](ContextProvider.md#setauthuser)
- [setLanguage](ContextProvider.md#setlanguage)

## Constructors

### constructor

• **new ContextProvider**()

## Properties

### authUserKey

▪ `Static` `Private` `Readonly` **authUserKey**: ``"user_key"``

#### Defined in

[context.provider.ts:8](https://github.com/klub-deepak/poc_doc_generation_3/blob/afd7f83/src/providers/context.provider.ts#L8)

___

### languageKey

▪ `Static` `Private` `Readonly` **languageKey**: ``"language_key"``

#### Defined in

[context.provider.ts:10](https://github.com/klub-deepak/poc_doc_generation_3/blob/afd7f83/src/providers/context.provider.ts#L10)

___

### nameSpace

▪ `Static` `Private` `Readonly` **nameSpace**: ``"request"``

#### Defined in

[context.provider.ts:6](https://github.com/klub-deepak/poc_doc_generation_3/blob/afd7f83/src/providers/context.provider.ts#L6)

## Methods

### get

▸ `Static` `Private` **get**<`T`\>(`key`): `T`

#### Type parameters

| Name |
| :------ |
| `T` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `key` | `string` |

#### Returns

`T`

#### Defined in

[context.provider.ts:12](https://github.com/klub-deepak/poc_doc_generation_3/blob/afd7f83/src/providers/context.provider.ts#L12)

___

### getAuthUser

▸ `Static` **getAuthUser**(): `UserEntity`

#### Returns

`UserEntity`

#### Defined in

[context.provider.ts:37](https://github.com/klub-deepak/poc_doc_generation_3/blob/afd7f83/src/providers/context.provider.ts#L37)

___

### getKeyWithNamespace

▸ `Static` `Private` **getKeyWithNamespace**(`key`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `key` | `string` |

#### Returns

`string`

#### Defined in

[context.provider.ts:21](https://github.com/klub-deepak/poc_doc_generation_3/blob/afd7f83/src/providers/context.provider.ts#L21)

___

### getLanguage

▸ `Static` **getLanguage**(): `string`

#### Returns

`string`

#### Defined in

[context.provider.ts:33](https://github.com/klub-deepak/poc_doc_generation_3/blob/afd7f83/src/providers/context.provider.ts#L33)

___

### set

▸ `Static` `Private` **set**(`key`, `value`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `key` | `string` |
| `value` | `any` |

#### Returns

`void`

#### Defined in

[context.provider.ts:17](https://github.com/klub-deepak/poc_doc_generation_3/blob/afd7f83/src/providers/context.provider.ts#L17)

___

### setAuthUser

▸ `Static` **setAuthUser**(`user`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `user` | `UserEntity` |

#### Returns

`void`

#### Defined in

[context.provider.ts:25](https://github.com/klub-deepak/poc_doc_generation_3/blob/afd7f83/src/providers/context.provider.ts#L25)

___

### setLanguage

▸ `Static` **setLanguage**(`language`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `language` | `string` |

#### Returns

`void`

#### Defined in

[context.provider.ts:29](https://github.com/klub-deepak/poc_doc_generation_3/blob/afd7f83/src/providers/context.provider.ts#L29)
