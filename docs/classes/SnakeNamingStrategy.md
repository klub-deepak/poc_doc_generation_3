[awesome-nestjs-boilerplate](../README.md) / SnakeNamingStrategy

# Class: SnakeNamingStrategy

## Hierarchy

- `DefaultNamingStrategy`

  ↳ **`SnakeNamingStrategy`**

## Implements

- `NamingStrategyInterface`

## Table of contents

### Constructors

- [constructor](SnakeNamingStrategy.md#constructor)

### Properties

- [materializedPathColumnName](SnakeNamingStrategy.md#materializedpathcolumnname)
- [nestedSetColumnNames](SnakeNamingStrategy.md#nestedsetcolumnnames)

### Methods

- [checkConstraintName](SnakeNamingStrategy.md#checkconstraintname)
- [classTableInheritanceParentColumnName](SnakeNamingStrategy.md#classtableinheritanceparentcolumnname)
- [closureJunctionTableName](SnakeNamingStrategy.md#closurejunctiontablename)
- [columnName](SnakeNamingStrategy.md#columnname)
- [defaultConstraintName](SnakeNamingStrategy.md#defaultconstraintname)
- [eagerJoinRelationAlias](SnakeNamingStrategy.md#eagerjoinrelationalias)
- [exclusionConstraintName](SnakeNamingStrategy.md#exclusionconstraintname)
- [foreignKeyName](SnakeNamingStrategy.md#foreignkeyname)
- [indexName](SnakeNamingStrategy.md#indexname)
- [joinColumnName](SnakeNamingStrategy.md#joincolumnname)
- [joinTableColumnDuplicationPrefix](SnakeNamingStrategy.md#jointablecolumnduplicationprefix)
- [joinTableColumnName](SnakeNamingStrategy.md#jointablecolumnname)
- [joinTableInverseColumnName](SnakeNamingStrategy.md#jointableinversecolumnname)
- [joinTableName](SnakeNamingStrategy.md#jointablename)
- [prefixTableName](SnakeNamingStrategy.md#prefixtablename)
- [primaryKeyName](SnakeNamingStrategy.md#primarykeyname)
- [relationConstraintName](SnakeNamingStrategy.md#relationconstraintname)
- [relationName](SnakeNamingStrategy.md#relationname)
- [tableName](SnakeNamingStrategy.md#tablename)
- [uniqueConstraintName](SnakeNamingStrategy.md#uniqueconstraintname)

## Constructors

### constructor

• **new SnakeNamingStrategy**()

#### Inherited from

DefaultNamingStrategy.constructor

## Properties

### materializedPathColumnName

• **materializedPathColumnName**: `string`

#### Implementation of

NamingStrategyInterface.materializedPathColumnName

#### Inherited from

DefaultNamingStrategy.materializedPathColumnName

#### Defined in

node_modules/typeorm/naming-strategy/DefaultNamingStrategy.d.ts:48

___

### nestedSetColumnNames

• **nestedSetColumnNames**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `left` | `string` |
| `right` | `string` |

#### Implementation of

NamingStrategyInterface.nestedSetColumnNames

#### Inherited from

DefaultNamingStrategy.nestedSetColumnNames

#### Defined in

node_modules/typeorm/naming-strategy/DefaultNamingStrategy.d.ts:44

## Methods

### checkConstraintName

▸ **checkConstraintName**(`tableOrName`, `expression`, `isEnum?`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `tableOrName` | `string` \| `Table` |
| `expression` | `string` |
| `isEnum?` | `boolean` |

#### Returns

`string`

#### Implementation of

NamingStrategyInterface.checkConstraintName

#### Inherited from

DefaultNamingStrategy.checkConstraintName

#### Defined in

node_modules/typeorm/naming-strategy/DefaultNamingStrategy.d.ts:29

___

### classTableInheritanceParentColumnName

▸ **classTableInheritanceParentColumnName**(`parentTableName`, `parentTableIdPropertyName`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `parentTableName` | `string` |
| `parentTableIdPropertyName` | `string` |

#### Returns

`string`

#### Defined in

[src/snake-naming.strategy.ts:57](https://github.com/klub-deepak/poc_doc_generation_3/blob/afd7f83/src/snake-naming.strategy.ts#L57)

___

### closureJunctionTableName

▸ **closureJunctionTableName**(`originalClosureTableName`): `string`

Creates a table name for a junction table of a closure table.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `originalClosureTableName` | `string` | Name of the closure table which owns this junction table. |

#### Returns

`string`

#### Implementation of

NamingStrategyInterface.closureJunctionTableName

#### Inherited from

DefaultNamingStrategy.closureJunctionTableName

#### Defined in

node_modules/typeorm/naming-strategy/DefaultNamingStrategy.d.ts:20

___

### columnName

▸ **columnName**(`propertyName`, `customName`, `embeddedPrefixes`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `propertyName` | `string` |
| `customName` | `string` |
| `embeddedPrefixes` | `string`[] |

#### Returns

`string`

#### Implementation of

NamingStrategyInterface.columnName

#### Overrides

DefaultNamingStrategy.columnName

#### Defined in

[src/snake-naming.strategy.ts:13](https://github.com/klub-deepak/poc_doc_generation_3/blob/afd7f83/src/snake-naming.strategy.ts#L13)

___

### defaultConstraintName

▸ **defaultConstraintName**(`tableOrName`, `columnName`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `tableOrName` | `string` \| `Table` |
| `columnName` | `string` |

#### Returns

`string`

#### Implementation of

NamingStrategyInterface.defaultConstraintName

#### Inherited from

DefaultNamingStrategy.defaultConstraintName

#### Defined in

node_modules/typeorm/naming-strategy/DefaultNamingStrategy.d.ts:26

___

### eagerJoinRelationAlias

▸ **eagerJoinRelationAlias**(`alias`, `propertyPath`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `alias` | `string` |
| `propertyPath` | `string` |

#### Returns

`string`

#### Implementation of

NamingStrategyInterface.eagerJoinRelationAlias

#### Inherited from

DefaultNamingStrategy.eagerJoinRelationAlias

#### Defined in

node_modules/typeorm/naming-strategy/DefaultNamingStrategy.d.ts:43

___

### exclusionConstraintName

▸ **exclusionConstraintName**(`tableOrName`, `expression`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `tableOrName` | `string` \| `Table` |
| `expression` | `string` |

#### Returns

`string`

#### Implementation of

NamingStrategyInterface.exclusionConstraintName

#### Inherited from

DefaultNamingStrategy.exclusionConstraintName

#### Defined in

node_modules/typeorm/naming-strategy/DefaultNamingStrategy.d.ts:30

___

### foreignKeyName

▸ **foreignKeyName**(`tableOrName`, `columnNames`, `_referencedTablePath?`, `_referencedColumnNames?`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `tableOrName` | `string` \| `Table` |
| `columnNames` | `string`[] |
| `_referencedTablePath?` | `string` |
| `_referencedColumnNames?` | `string`[] |

#### Returns

`string`

#### Implementation of

NamingStrategyInterface.foreignKeyName

#### Inherited from

DefaultNamingStrategy.foreignKeyName

#### Defined in

node_modules/typeorm/naming-strategy/DefaultNamingStrategy.d.ts:27

___

### indexName

▸ **indexName**(`tableOrName`, `columnNames`, `where?`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `tableOrName` | `string` \| `Table` |
| `columnNames` | `string`[] |
| `where?` | `string` |

#### Returns

`string`

#### Implementation of

NamingStrategyInterface.indexName

#### Inherited from

DefaultNamingStrategy.indexName

#### Defined in

node_modules/typeorm/naming-strategy/DefaultNamingStrategy.d.ts:28

___

### joinColumnName

▸ **joinColumnName**(`relationName`, `referencedColumnName`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `relationName` | `string` |
| `referencedColumnName` | `string` |

#### Returns

`string`

#### Implementation of

NamingStrategyInterface.joinColumnName

#### Overrides

DefaultNamingStrategy.joinColumnName

#### Defined in

[src/snake-naming.strategy.ts:28](https://github.com/klub-deepak/poc_doc_generation_3/blob/afd7f83/src/snake-naming.strategy.ts#L28)

___

### joinTableColumnDuplicationPrefix

▸ **joinTableColumnDuplicationPrefix**(`columnName`, `index`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `columnName` | `string` |
| `index` | `number` |

#### Returns

`string`

#### Implementation of

NamingStrategyInterface.joinTableColumnDuplicationPrefix

#### Inherited from

DefaultNamingStrategy.joinTableColumnDuplicationPrefix

#### Defined in

node_modules/typeorm/naming-strategy/DefaultNamingStrategy.d.ts:33

___

### joinTableColumnName

▸ **joinTableColumnName**(`tableName`, `propertyName`, `columnName?`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `tableName` | `string` |
| `propertyName` | `string` |
| `columnName?` | `string` |

#### Returns

`string`

#### Implementation of

NamingStrategyInterface.joinTableColumnName

#### Overrides

DefaultNamingStrategy.joinTableColumnName

#### Defined in

[src/snake-naming.strategy.ts:47](https://github.com/klub-deepak/poc_doc_generation_3/blob/afd7f83/src/snake-naming.strategy.ts#L47)

___

### joinTableInverseColumnName

▸ **joinTableInverseColumnName**(`tableName`, `propertyName`, `columnName?`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `tableName` | `string` |
| `propertyName` | `string` |
| `columnName?` | `string` |

#### Returns

`string`

#### Implementation of

NamingStrategyInterface.joinTableInverseColumnName

#### Inherited from

DefaultNamingStrategy.joinTableInverseColumnName

#### Defined in

node_modules/typeorm/naming-strategy/DefaultNamingStrategy.d.ts:35

___

### joinTableName

▸ **joinTableName**(`firstTableName`, `secondTableName`, `firstPropertyName`, `_secondPropertyName`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `firstTableName` | `string` |
| `secondTableName` | `string` |
| `firstPropertyName` | `string` |
| `_secondPropertyName` | `string` |

#### Returns

`string`

#### Implementation of

NamingStrategyInterface.joinTableName

#### Overrides

DefaultNamingStrategy.joinTableName

#### Defined in

[src/snake-naming.strategy.ts:32](https://github.com/klub-deepak/poc_doc_generation_3/blob/afd7f83/src/snake-naming.strategy.ts#L32)

___

### prefixTableName

▸ **prefixTableName**(`prefix`, `tableName`): `string`

Adds globally set prefix to the table name.
This method is executed no matter if prefix was set or not.
Table name is either user's given table name, either name generated from entity target.
Note that table name comes here already normalized by #tableName method.

#### Parameters

| Name | Type |
| :------ | :------ |
| `prefix` | `string` |
| `tableName` | `string` |

#### Returns

`string`

#### Implementation of

NamingStrategyInterface.prefixTableName

#### Inherited from

DefaultNamingStrategy.prefixTableName

#### Defined in

node_modules/typeorm/naming-strategy/DefaultNamingStrategy.d.ts:42

___

### primaryKeyName

▸ **primaryKeyName**(`tableOrName`, `columnNames`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `tableOrName` | `string` \| `Table` |
| `columnNames` | `string`[] |

#### Returns

`string`

#### Implementation of

NamingStrategyInterface.primaryKeyName

#### Inherited from

DefaultNamingStrategy.primaryKeyName

#### Defined in

node_modules/typeorm/naming-strategy/DefaultNamingStrategy.d.ts:23

___

### relationConstraintName

▸ **relationConstraintName**(`tableOrName`, `columnNames`, `where?`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `tableOrName` | `string` \| `Table` |
| `columnNames` | `string`[] |
| `where?` | `string` |

#### Returns

`string`

#### Implementation of

NamingStrategyInterface.relationConstraintName

#### Inherited from

DefaultNamingStrategy.relationConstraintName

#### Defined in

node_modules/typeorm/naming-strategy/DefaultNamingStrategy.d.ts:25

___

### relationName

▸ **relationName**(`propertyName`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `propertyName` | `string` |

#### Returns

`string`

#### Implementation of

NamingStrategyInterface.relationName

#### Overrides

DefaultNamingStrategy.relationName

#### Defined in

[src/snake-naming.strategy.ts:24](https://github.com/klub-deepak/poc_doc_generation_3/blob/afd7f83/src/snake-naming.strategy.ts#L24)

___

### tableName

▸ **tableName**(`className`, `customName`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `className` | `string` |
| `customName` | `string` |

#### Returns

`string`

#### Implementation of

NamingStrategyInterface.tableName

#### Overrides

DefaultNamingStrategy.tableName

#### Defined in

[src/snake-naming.strategy.ts:9](https://github.com/klub-deepak/poc_doc_generation_3/blob/afd7f83/src/snake-naming.strategy.ts#L9)

___

### uniqueConstraintName

▸ **uniqueConstraintName**(`tableOrName`, `columnNames`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `tableOrName` | `string` \| `Table` |
| `columnNames` | `string`[] |

#### Returns

`string`

#### Implementation of

NamingStrategyInterface.uniqueConstraintName

#### Inherited from

DefaultNamingStrategy.uniqueConstraintName

#### Defined in

node_modules/typeorm/naming-strategy/DefaultNamingStrategy.d.ts:24
