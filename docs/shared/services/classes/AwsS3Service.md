[awesome-nestjs-boilerplate](../README.md) / [Exports](../modules.md) / AwsS3Service

# Class: AwsS3Service

## Table of contents

### Constructors

- [constructor](AwsS3Service.md#constructor)

### Properties

- [configService](AwsS3Service.md#configservice)
- [generatorService](AwsS3Service.md#generatorservice)
- [s3](AwsS3Service.md#s3)

### Methods

- [uploadImage](AwsS3Service.md#uploadimage)

## Constructors

### constructor

• **new AwsS3Service**(`configService`, `generatorService`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `configService` | `ApiConfigService` |
| `generatorService` | `GeneratorService` |

#### Defined in

[aws-s3.service.ts:13](https://github.com/klub-deepak/poc_doc_generation_3/blob/a592bb2/src/shared/services/aws-s3.service.ts#L13)

## Properties

### configService

• **configService**: `ApiConfigService`

___

### generatorService

• **generatorService**: `GeneratorService`

___

### s3

• `Private` `Readonly` **s3**: `S3`

#### Defined in

[aws-s3.service.ts:11](https://github.com/klub-deepak/poc_doc_generation_3/blob/a592bb2/src/shared/services/aws-s3.service.ts#L11)

## Methods

### uploadImage

▸ **uploadImage**(`file`): `Promise`<`string`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `file` | `IFile` |

#### Returns

`Promise`<`string`\>

#### Defined in

[aws-s3.service.ts:27](https://github.com/klub-deepak/poc_doc_generation_3/blob/a592bb2/src/shared/services/aws-s3.service.ts#L27)
