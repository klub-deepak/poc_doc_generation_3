[awesome-nestjs-boilerplate](../README.md) / ServiceHealthIndicator

# Class: ServiceHealthIndicator

## Hierarchy

- `HealthIndicator`

  ↳ **`ServiceHealthIndicator`**

## Table of contents

### Constructors

- [constructor](ServiceHealthIndicator.md#constructor)

### Methods

- [getStatus](ServiceHealthIndicator.md#getstatus)
- [isHealthy](ServiceHealthIndicator.md#ishealthy)

## Constructors

### constructor

• **new ServiceHealthIndicator**(`clientProxy`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `clientProxy` | `ClientProxy` |

#### Overrides

HealthIndicator.constructor

#### Defined in

[src/modules/health-checker/health-indicators/service.indicator.ts:10](https://github.com/klub-deepak/poc_doc_generation_3/blob/afd7f83/src/modules/health-checker/health-indicators/service.indicator.ts#L10)

## Methods

### getStatus

▸ `Protected` **getStatus**(`key`, `isHealthy`, `data?`): `HealthIndicatorResult`

Generates the health indicator result object

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `key` | `string` | The key which will be used as key for the result object |
| `isHealthy` | `boolean` | Whether the health indicator is healthy |
| `data?` | `Object` | Additional data which will get appended to the result object |

#### Returns

`HealthIndicatorResult`

#### Inherited from

HealthIndicator.getStatus

#### Defined in

node_modules/@nestjs/terminus/dist/health-indicator/health-indicator.d.ts:35

___

### isHealthy

▸ **isHealthy**(`eventName`): `Promise`<`HealthIndicatorResult`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `eventName` | `string` |

#### Returns

`Promise`<`HealthIndicatorResult`\>

#### Defined in

[src/modules/health-checker/health-indicators/service.indicator.ts:18](https://github.com/klub-deepak/poc_doc_generation_3/blob/afd7f83/src/modules/health-checker/health-indicators/service.indicator.ts#L18)
