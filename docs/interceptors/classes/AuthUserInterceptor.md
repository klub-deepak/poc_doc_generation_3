[awesome-nestjs-boilerplate](../README.md) / [Exports](../modules.md) / AuthUserInterceptor

# Class: AuthUserInterceptor

## Implements

- `NestInterceptor`

## Table of contents

### Constructors

- [constructor](AuthUserInterceptor.md#constructor)

### Methods

- [intercept](AuthUserInterceptor.md#intercept)

## Constructors

### constructor

• **new AuthUserInterceptor**()

## Methods

### intercept

▸ **intercept**(`context`, `next`): `Observable`<`any`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `context` | `ExecutionContext` |
| `next` | `CallHandler`<`any`\> |

#### Returns

`Observable`<`any`\>

#### Implementation of

NestInterceptor.intercept

#### Defined in

[auth-user-interceptor.service.ts:13](https://github.com/klub-deepak/poc_doc_generation_3/blob/a592bb2/src/interceptors/auth-user-interceptor.service.ts#L13)
