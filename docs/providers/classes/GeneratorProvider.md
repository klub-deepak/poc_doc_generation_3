[awesome-nestjs-boilerplate](../README.md) / [Exports](../modules.md) / GeneratorProvider

# Class: GeneratorProvider

## Table of contents

### Constructors

- [constructor](GeneratorProvider.md#constructor)

### Methods

- [fileName](GeneratorProvider.md#filename)
- [generatePassword](GeneratorProvider.md#generatepassword)
- [generateRandomString](GeneratorProvider.md#generaterandomstring)
- [generateVerificationCode](GeneratorProvider.md#generateverificationcode)
- [getS3Key](GeneratorProvider.md#gets3key)
- [getS3PublicUrl](GeneratorProvider.md#gets3publicurl)
- [uuid](GeneratorProvider.md#uuid)

## Constructors

### constructor

• **new GeneratorProvider**()

## Methods

### fileName

▸ `Static` **fileName**(`ext`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ext` | `string` |

#### Returns

`string`

#### Defined in

[generator.provider.ts:10](https://github.com/klub-deepak/poc_doc_generation_3/blob/a592bb2/src/providers/generator.provider.ts#L10)

___

### generatePassword

▸ `Static` **generatePassword**(): `string`

#### Returns

`string`

#### Defined in

[generator.provider.ts:38](https://github.com/klub-deepak/poc_doc_generation_3/blob/a592bb2/src/providers/generator.provider.ts#L38)

___

### generateRandomString

▸ `Static` **generateRandomString**(`length`): `string`

generate random string

#### Parameters

| Name | Type |
| :------ | :------ |
| `length` | `number` |

#### Returns

`string`

#### Defined in

[generator.provider.ts:58](https://github.com/klub-deepak/poc_doc_generation_3/blob/a592bb2/src/providers/generator.provider.ts#L58)

___

### generateVerificationCode

▸ `Static` **generateVerificationCode**(): `string`

#### Returns

`string`

#### Defined in

[generator.provider.ts:34](https://github.com/klub-deepak/poc_doc_generation_3/blob/a592bb2/src/providers/generator.provider.ts#L34)

___

### getS3Key

▸ `Static` **getS3Key**(`publicUrl`): `Optional`<`string`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `publicUrl` | `string` |

#### Returns

`Optional`<`string`\>

#### Defined in

[generator.provider.ts:22](https://github.com/klub-deepak/poc_doc_generation_3/blob/a592bb2/src/providers/generator.provider.ts#L22)

___

### getS3PublicUrl

▸ `Static` **getS3PublicUrl**(`key`): `Optional`<`string`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `key` | `string` |

#### Returns

`Optional`<`string`\>

#### Defined in

[generator.provider.ts:14](https://github.com/klub-deepak/poc_doc_generation_3/blob/a592bb2/src/providers/generator.provider.ts#L14)

___

### uuid

▸ `Static` **uuid**(): `string`

#### Returns

`string`

#### Defined in

[generator.provider.ts:6](https://github.com/klub-deepak/poc_doc_generation_3/blob/a592bb2/src/providers/generator.provider.ts#L6)
