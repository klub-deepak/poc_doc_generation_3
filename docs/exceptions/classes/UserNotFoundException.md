[awesome-nestjs-boilerplate](../README.md) / [Exports](../modules.md) / UserNotFoundException

# Class: UserNotFoundException

## Hierarchy

- `NotFoundException`

  ↳ **`UserNotFoundException`**

## Table of contents

### Constructors

- [constructor](UserNotFoundException.md#constructor)

### Properties

- [message](UserNotFoundException.md#message)
- [name](UserNotFoundException.md#name)
- [stack](UserNotFoundException.md#stack)
- [prepareStackTrace](UserNotFoundException.md#preparestacktrace)
- [stackTraceLimit](UserNotFoundException.md#stacktracelimit)

### Methods

- [getResponse](UserNotFoundException.md#getresponse)
- [getStatus](UserNotFoundException.md#getstatus)
- [initMessage](UserNotFoundException.md#initmessage)
- [initName](UserNotFoundException.md#initname)
- [captureStackTrace](UserNotFoundException.md#capturestacktrace)
- [createBody](UserNotFoundException.md#createbody)

## Constructors

### constructor

• **new UserNotFoundException**(`error?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `error?` | `string` |

#### Overrides

NotFoundException.constructor

#### Defined in

[src/exceptions/user-not-found.exception.ts:4](https://github.com/klub-deepak/poc_doc_generation_3/blob/a592bb2/src/exceptions/user-not-found.exception.ts#L4)

## Properties

### message

• **message**: `string`

#### Inherited from

NotFoundException.message

#### Defined in

node_modules/typescript/lib/lib.es5.d.ts:1023

___

### name

• **name**: `string`

#### Inherited from

NotFoundException.name

#### Defined in

node_modules/typescript/lib/lib.es5.d.ts:1022

___

### stack

• `Optional` **stack**: `string`

#### Inherited from

NotFoundException.stack

#### Defined in

node_modules/typescript/lib/lib.es5.d.ts:1024

___

### prepareStackTrace

▪ `Static` `Optional` **prepareStackTrace**: (`err`: `Error`, `stackTraces`: `CallSite`[]) => `any`

#### Type declaration

▸ (`err`, `stackTraces`): `any`

Optional override for formatting stack traces

**`see`** https://v8.dev/docs/stack-trace-api#customizing-stack-traces

##### Parameters

| Name | Type |
| :------ | :------ |
| `err` | `Error` |
| `stackTraces` | `CallSite`[] |

##### Returns

`any`

#### Inherited from

NotFoundException.prepareStackTrace

#### Defined in

node_modules/@types/node/globals.d.ts:11

___

### stackTraceLimit

▪ `Static` **stackTraceLimit**: `number`

#### Inherited from

NotFoundException.stackTraceLimit

#### Defined in

node_modules/@types/node/globals.d.ts:13

## Methods

### getResponse

▸ **getResponse**(): `string` \| `object`

#### Returns

`string` \| `object`

#### Inherited from

NotFoundException.getResponse

#### Defined in

node_modules/@nestjs/common/exceptions/http.exception.d.ts:40

___

### getStatus

▸ **getStatus**(): `number`

#### Returns

`number`

#### Inherited from

NotFoundException.getStatus

#### Defined in

node_modules/@nestjs/common/exceptions/http.exception.d.ts:41

___

### initMessage

▸ **initMessage**(): `void`

#### Returns

`void`

#### Inherited from

NotFoundException.initMessage

#### Defined in

node_modules/@nestjs/common/exceptions/http.exception.d.ts:38

___

### initName

▸ **initName**(): `void`

#### Returns

`void`

#### Inherited from

NotFoundException.initName

#### Defined in

node_modules/@nestjs/common/exceptions/http.exception.d.ts:39

___

### captureStackTrace

▸ `Static` **captureStackTrace**(`targetObject`, `constructorOpt?`): `void`

Create .stack property on a target object

#### Parameters

| Name | Type |
| :------ | :------ |
| `targetObject` | `object` |
| `constructorOpt?` | `Function` |

#### Returns

`void`

#### Inherited from

NotFoundException.captureStackTrace

#### Defined in

node_modules/@types/node/globals.d.ts:4

___

### createBody

▸ `Static` **createBody**(`objectOrError`, `description?`, `statusCode?`): `object`

#### Parameters

| Name | Type |
| :------ | :------ |
| `objectOrError` | `string` \| `object` |
| `description?` | `string` |
| `statusCode?` | `number` |

#### Returns

`object`

#### Inherited from

NotFoundException.createBody

#### Defined in

node_modules/@nestjs/common/exceptions/http.exception.d.ts:42
