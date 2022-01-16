[awesome-nestjs-boilerplate](../README.md) / [Exports](../modules.md) / FileNotImageException

# Class: FileNotImageException

## Hierarchy

- `BadRequestException`

  ↳ **`FileNotImageException`**

## Table of contents

### Constructors

- [constructor](FileNotImageException.md#constructor)

### Properties

- [message](FileNotImageException.md#message)
- [name](FileNotImageException.md#name)
- [stack](FileNotImageException.md#stack)
- [prepareStackTrace](FileNotImageException.md#preparestacktrace)
- [stackTraceLimit](FileNotImageException.md#stacktracelimit)

### Methods

- [getResponse](FileNotImageException.md#getresponse)
- [getStatus](FileNotImageException.md#getstatus)
- [initMessage](FileNotImageException.md#initmessage)
- [initName](FileNotImageException.md#initname)
- [captureStackTrace](FileNotImageException.md#capturestacktrace)
- [createBody](FileNotImageException.md#createbody)

## Constructors

### constructor

• **new FileNotImageException**(`error?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `error?` | `string` |

#### Overrides

BadRequestException.constructor

#### Defined in

[src/exceptions/file-not-image.exception.ts:4](https://github.com/klub-deepak/poc_doc_generation_3/blob/a592bb2/src/exceptions/file-not-image.exception.ts#L4)

## Properties

### message

• **message**: `string`

#### Inherited from

BadRequestException.message

#### Defined in

node_modules/typescript/lib/lib.es5.d.ts:1023

___

### name

• **name**: `string`

#### Inherited from

BadRequestException.name

#### Defined in

node_modules/typescript/lib/lib.es5.d.ts:1022

___

### stack

• `Optional` **stack**: `string`

#### Inherited from

BadRequestException.stack

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

BadRequestException.prepareStackTrace

#### Defined in

node_modules/@types/node/globals.d.ts:11

___

### stackTraceLimit

▪ `Static` **stackTraceLimit**: `number`

#### Inherited from

BadRequestException.stackTraceLimit

#### Defined in

node_modules/@types/node/globals.d.ts:13

## Methods

### getResponse

▸ **getResponse**(): `string` \| `object`

#### Returns

`string` \| `object`

#### Inherited from

BadRequestException.getResponse

#### Defined in

node_modules/@nestjs/common/exceptions/http.exception.d.ts:40

___

### getStatus

▸ **getStatus**(): `number`

#### Returns

`number`

#### Inherited from

BadRequestException.getStatus

#### Defined in

node_modules/@nestjs/common/exceptions/http.exception.d.ts:41

___

### initMessage

▸ **initMessage**(): `void`

#### Returns

`void`

#### Inherited from

BadRequestException.initMessage

#### Defined in

node_modules/@nestjs/common/exceptions/http.exception.d.ts:38

___

### initName

▸ **initName**(): `void`

#### Returns

`void`

#### Inherited from

BadRequestException.initName

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

BadRequestException.captureStackTrace

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

BadRequestException.createBody

#### Defined in

node_modules/@nestjs/common/exceptions/http.exception.d.ts:42
