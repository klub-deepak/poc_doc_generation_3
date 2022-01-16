[awesome-nestjs-boilerplate](README.md) / Exports

# awesome-nestjs-boilerplate

## Table of contents

### Functions

- [generateHash](modules.md#generatehash)
- [getVariableName](modules.md#getvariablename)
- [validateHash](modules.md#validatehash)

## Functions

### generateHash

▸ **generateHash**(`password`): `string`

generate hash from password or string

#### Parameters

| Name | Type |
| :------ | :------ |
| `password` | `string` |

#### Returns

`string`

#### Defined in

[utils.ts:10](https://github.com/klub-deepak/poc_doc_generation_3/blob/a592bb2/src/common/utils.ts#L10)

___

### getVariableName

▸ **getVariableName**<`TResult`\>(`getVar`): `string`

#### Type parameters

| Name |
| :------ |
| `TResult` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `getVar` | () => `TResult` |

#### Returns

`string`

#### Defined in

[utils.ts:31](https://github.com/klub-deepak/poc_doc_generation_3/blob/a592bb2/src/common/utils.ts#L31)

___

### validateHash

▸ **validateHash**(`password`, `hash`): `Promise`<`boolean`\>

validate text with hash

#### Parameters

| Name | Type |
| :------ | :------ |
| `password` | `Optional`<`string`\> |
| `hash` | `Optional`<`string`\> |

#### Returns

`Promise`<`boolean`\>

#### Defined in

[utils.ts:20](https://github.com/klub-deepak/poc_doc_generation_3/blob/a592bb2/src/common/utils.ts#L20)
