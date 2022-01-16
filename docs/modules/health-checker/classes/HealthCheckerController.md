[awesome-nestjs-boilerplate](../README.md) / [Exports](../modules.md) / HealthCheckerController

# Class: HealthCheckerController

## Table of contents

### Constructors

- [constructor](HealthCheckerController.md#constructor)

### Methods

- [check](HealthCheckerController.md#check)

## Constructors

### constructor

• **new HealthCheckerController**(`healthCheckService`, `ormIndicator`, `serviceIndicator`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `healthCheckService` | `HealthCheckService` |
| `ormIndicator` | `TypeOrmHealthIndicator` |
| `serviceIndicator` | `ServiceHealthIndicator` |

#### Defined in

[health-checker.controller.ts:13](https://github.com/klub-deepak/poc_doc_generation_3/blob/a592bb2/src/modules/health-checker/health-checker.controller.ts#L13)

## Methods

### check

▸ **check**(): `Promise`<`HealthCheckResult`\>

#### Returns

`Promise`<`HealthCheckResult`\>

#### Defined in

[health-checker.controller.ts:21](https://github.com/klub-deepak/poc_doc_generation_3/blob/a592bb2/src/modules/health-checker/health-checker.controller.ts#L21)
