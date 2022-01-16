[awesome-nestjs-boilerplate](../README.md) / [Exports](../modules.md) / CreateSettingsHandler

# Class: CreateSettingsHandler

## Implements

- `ICommandHandler`<[`CreateSettingsCommand`](CreateSettingsCommand.md), `UserSettingsEntity`\>

## Table of contents

### Constructors

- [constructor](CreateSettingsHandler.md#constructor)

### Methods

- [execute](CreateSettingsHandler.md#execute)

## Constructors

### constructor

• **new CreateSettingsHandler**(`userSettingsRepository`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `userSettingsRepository` | `UserSettingsRepository` |

#### Defined in

[create-settings.command.ts:19](https://github.com/klub-deepak/poc_doc_generation_3/blob/a592bb2/src/modules/user/commands/create-settings.command.ts#L19)

## Methods

### execute

▸ **execute**(`command`): `Promise`<`UserSettingsEntity`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `command` | [`CreateSettingsCommand`](CreateSettingsCommand.md) |

#### Returns

`Promise`<`UserSettingsEntity`\>

#### Implementation of

ICommandHandler.execute

#### Defined in

[create-settings.command.ts:21](https://github.com/klub-deepak/poc_doc_generation_3/blob/a592bb2/src/modules/user/commands/create-settings.command.ts#L21)
