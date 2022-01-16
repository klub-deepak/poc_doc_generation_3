[awesome-nestjs-boilerplate](../README.md) / [Exports](../modules.md) / ApiConfigService

# Class: ApiConfigService

## Table of contents

### Constructors

- [constructor](ApiConfigService.md#constructor)

### Accessors

- [appConfig](ApiConfigService.md#appconfig)
- [authConfig](ApiConfigService.md#authconfig)
- [awsS3Config](ApiConfigService.md#awss3config)
- [documentationEnabled](ApiConfigService.md#documentationenabled)
- [fallbackLanguage](ApiConfigService.md#fallbacklanguage)
- [isDevelopment](ApiConfigService.md#isdevelopment)
- [isProduction](ApiConfigService.md#isproduction)
- [isTest](ApiConfigService.md#istest)
- [natsConfig](ApiConfigService.md#natsconfig)
- [natsEnabled](ApiConfigService.md#natsenabled)
- [nodeEnv](ApiConfigService.md#nodeenv)
- [postgresConfig](ApiConfigService.md#postgresconfig)

### Methods

- [get](ApiConfigService.md#get)
- [getBoolean](ApiConfigService.md#getboolean)
- [getNumber](ApiConfigService.md#getnumber)
- [getString](ApiConfigService.md#getstring)

## Constructors

### constructor

• **new ApiConfigService**(`configService`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `configService` | `ConfigService`<`Record`<`string`, `unknown`\>, ``false``\> |

#### Defined in

[api-config.service.ts:11](https://github.com/klub-deepak/poc_doc_generation_3/blob/a592bb2/src/shared/services/api-config.service.ts#L11)

## Accessors

### appConfig

• `get` **appConfig**(): `Object`

#### Returns

`Object`

| Name | Type |
| :------ | :------ |
| `port` | `string` |

#### Defined in

[api-config.service.ts:138](https://github.com/klub-deepak/poc_doc_generation_3/blob/a592bb2/src/shared/services/api-config.service.ts#L138)

___

### authConfig

• `get` **authConfig**(): `Object`

#### Returns

`Object`

| Name | Type |
| :------ | :------ |
| `jwtExpirationTime` | `number` |
| `jwtSecret` | `string` |

#### Defined in

[api-config.service.ts:131](https://github.com/klub-deepak/poc_doc_generation_3/blob/a592bb2/src/shared/services/api-config.service.ts#L131)

___

### awsS3Config

• `get` **awsS3Config**(): `Object`

#### Returns

`Object`

| Name | Type |
| :------ | :------ |
| `bucketApiVersion` | `string` |
| `bucketName` | `string` |
| `bucketRegion` | `string` |

#### Defined in

[api-config.service.ts:108](https://github.com/klub-deepak/poc_doc_generation_3/blob/a592bb2/src/shared/services/api-config.service.ts#L108)

___

### documentationEnabled

• `get` **documentationEnabled**(): `boolean`

#### Returns

`boolean`

#### Defined in

[api-config.service.ts:116](https://github.com/klub-deepak/poc_doc_generation_3/blob/a592bb2/src/shared/services/api-config.service.ts#L116)

___

### fallbackLanguage

• `get` **fallbackLanguage**(): `string`

#### Returns

`string`

#### Defined in

[api-config.service.ts:55](https://github.com/klub-deepak/poc_doc_generation_3/blob/a592bb2/src/shared/services/api-config.service.ts#L55)

___

### isDevelopment

• `get` **isDevelopment**(): `boolean`

#### Returns

`boolean`

#### Defined in

[api-config.service.ts:13](https://github.com/klub-deepak/poc_doc_generation_3/blob/a592bb2/src/shared/services/api-config.service.ts#L13)

___

### isProduction

• `get` **isProduction**(): `boolean`

#### Returns

`boolean`

#### Defined in

[api-config.service.ts:17](https://github.com/klub-deepak/poc_doc_generation_3/blob/a592bb2/src/shared/services/api-config.service.ts#L17)

___

### isTest

• `get` **isTest**(): `boolean`

#### Returns

`boolean`

#### Defined in

[api-config.service.ts:21](https://github.com/klub-deepak/poc_doc_generation_3/blob/a592bb2/src/shared/services/api-config.service.ts#L21)

___

### natsConfig

• `get` **natsConfig**(): `Object`

#### Returns

`Object`

| Name | Type |
| :------ | :------ |
| `host` | `string` |
| `port` | `number` |

#### Defined in

[api-config.service.ts:124](https://github.com/klub-deepak/poc_doc_generation_3/blob/a592bb2/src/shared/services/api-config.service.ts#L124)

___

### natsEnabled

• `get` **natsEnabled**(): `boolean`

#### Returns

`boolean`

#### Defined in

[api-config.service.ts:120](https://github.com/klub-deepak/poc_doc_generation_3/blob/a592bb2/src/shared/services/api-config.service.ts#L120)

___

### nodeEnv

• `get` **nodeEnv**(): `string`

#### Returns

`string`

#### Defined in

[api-config.service.ts:51](https://github.com/klub-deepak/poc_doc_generation_3/blob/a592bb2/src/shared/services/api-config.service.ts#L51)

___

### postgresConfig

• `get` **postgresConfig**(): `TypeOrmModuleOptions`

#### Returns

`TypeOrmModuleOptions`

#### Defined in

[api-config.service.ts:59](https://github.com/klub-deepak/poc_doc_generation_3/blob/a592bb2/src/shared/services/api-config.service.ts#L59)

## Methods

### get

▸ `Private` **get**(`key`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `key` | `string` |

#### Returns

`string`

#### Defined in

[api-config.service.ts:144](https://github.com/klub-deepak/poc_doc_generation_3/blob/a592bb2/src/shared/services/api-config.service.ts#L144)

___

### getBoolean

▸ `Private` **getBoolean**(`key`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `key` | `string` |

#### Returns

`boolean`

#### Defined in

[api-config.service.ts:35](https://github.com/klub-deepak/poc_doc_generation_3/blob/a592bb2/src/shared/services/api-config.service.ts#L35)

___

### getNumber

▸ `Private` **getNumber**(`key`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `key` | `string` |

#### Returns

`number`

#### Defined in

[api-config.service.ts:25](https://github.com/klub-deepak/poc_doc_generation_3/blob/a592bb2/src/shared/services/api-config.service.ts#L25)

___

### getString

▸ `Private` **getString**(`key`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `key` | `string` |

#### Returns

`string`

#### Defined in

[api-config.service.ts:45](https://github.com/klub-deepak/poc_doc_generation_3/blob/a592bb2/src/shared/services/api-config.service.ts#L45)
