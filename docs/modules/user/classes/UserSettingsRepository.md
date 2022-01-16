[awesome-nestjs-boilerplate](../README.md) / UserSettingsRepository

# Class: UserSettingsRepository

## Hierarchy

- `Repository`<`UserSettingsEntity`\>

  ↳ **`UserSettingsRepository`**

## Table of contents

### Constructors

- [constructor](UserSettingsRepository.md#constructor)

### Properties

- [manager](UserSettingsRepository.md#manager)
- [metadata](UserSettingsRepository.md#metadata)
- [queryRunner](UserSettingsRepository.md#queryrunner)

### Accessors

- [target](UserSettingsRepository.md#target)

### Methods

- [clear](UserSettingsRepository.md#clear)
- [count](UserSettingsRepository.md#count)
- [create](UserSettingsRepository.md#create)
- [createQueryBuilder](UserSettingsRepository.md#createquerybuilder)
- [decrement](UserSettingsRepository.md#decrement)
- [delete](UserSettingsRepository.md#delete)
- [find](UserSettingsRepository.md#find)
- [findAndCount](UserSettingsRepository.md#findandcount)
- [findByIds](UserSettingsRepository.md#findbyids)
- [findOne](UserSettingsRepository.md#findone)
- [findOneOrFail](UserSettingsRepository.md#findoneorfail)
- [getId](UserSettingsRepository.md#getid)
- [hasId](UserSettingsRepository.md#hasid)
- [increment](UserSettingsRepository.md#increment)
- [insert](UserSettingsRepository.md#insert)
- [merge](UserSettingsRepository.md#merge)
- [preload](UserSettingsRepository.md#preload)
- [query](UserSettingsRepository.md#query)
- [recover](UserSettingsRepository.md#recover)
- [remove](UserSettingsRepository.md#remove)
- [restore](UserSettingsRepository.md#restore)
- [save](UserSettingsRepository.md#save)
- [softDelete](UserSettingsRepository.md#softdelete)
- [softRemove](UserSettingsRepository.md#softremove)
- [update](UserSettingsRepository.md#update)
- [upsert](UserSettingsRepository.md#upsert)

## Constructors

### constructor

• **new UserSettingsRepository**()

#### Inherited from

Repository<UserSettingsEntity\>.constructor

## Properties

### manager

• `Readonly` **manager**: `EntityManager`

Entity Manager used by this repository.

#### Inherited from

Repository.manager

#### Defined in

node_modules/typeorm/repository/Repository.d.ts:25

___

### metadata

• `Readonly` **metadata**: `EntityMetadata`

Entity metadata of the entity current repository manages.

#### Inherited from

Repository.metadata

#### Defined in

node_modules/typeorm/repository/Repository.d.ts:29

___

### queryRunner

• `Optional` `Readonly` **queryRunner**: `QueryRunner`

Query runner provider used for this repository.

#### Inherited from

Repository.queryRunner

#### Defined in

node_modules/typeorm/repository/Repository.d.ts:33

## Accessors

### target

• `get` **target**(): `string` \| `Function`

Returns object that is managed by this repository.
If this repository manages entity from schema,
then it returns a name of that schema instead.

#### Returns

`string` \| `Function`

#### Inherited from

Repository.target

#### Defined in

node_modules/typeorm/repository/Repository.d.ts:43

## Methods

### clear

▸ **clear**(): `Promise`<`void`\>

Clears all the data from the given table/collection (truncates/drops it).

Note: this method uses TRUNCATE and may not work as you expect in transactions on some platforms.

**`see`** https://stackoverflow.com/a/5972738/925151

#### Returns

`Promise`<`void`\>

#### Inherited from

Repository.clear

#### Defined in

node_modules/typeorm/repository/Repository.d.ts:267

___

### count

▸ **count**(`options?`): `Promise`<`number`\>

Counts entities that match given options.

#### Parameters

| Name | Type |
| :------ | :------ |
| `options?` | `FindManyOptions`<`UserSettingsEntity`\> |

#### Returns

`Promise`<`number`\>

#### Inherited from

Repository.count

#### Defined in

node_modules/typeorm/repository/Repository.d.ts:197

▸ **count**(`conditions?`): `Promise`<`number`\>

Counts entities that match given conditions.

#### Parameters

| Name | Type |
| :------ | :------ |
| `conditions?` | `FindConditions`<`UserSettingsEntity`\> |

#### Returns

`Promise`<`number`\>

#### Inherited from

Repository.count

#### Defined in

node_modules/typeorm/repository/Repository.d.ts:201

___

### create

▸ **create**(): `UserSettingsEntity`

Creates a new entity instance.

#### Returns

`UserSettingsEntity`

#### Inherited from

Repository.create

#### Defined in

node_modules/typeorm/repository/Repository.d.ts:56

▸ **create**(`entityLikeArray`): `UserSettingsEntity`[]

Creates new entities and copies all entity properties from given objects into their new entities.
Note that it copies only properties that are present in entity schema.

#### Parameters

| Name | Type |
| :------ | :------ |
| `entityLikeArray` | `DeepPartial`<`UserSettingsEntity`\>[] |

#### Returns

`UserSettingsEntity`[]

#### Inherited from

Repository.create

#### Defined in

node_modules/typeorm/repository/Repository.d.ts:61

▸ **create**(`entityLike`): `UserSettingsEntity`

Creates a new entity instance and copies all entity properties from this object into a new entity.
Note that it copies only properties that are present in entity schema.

#### Parameters

| Name | Type |
| :------ | :------ |
| `entityLike` | `DeepPartial`<`UserSettingsEntity`\> |

#### Returns

`UserSettingsEntity`

#### Inherited from

Repository.create

#### Defined in

node_modules/typeorm/repository/Repository.d.ts:66

___

### createQueryBuilder

▸ **createQueryBuilder**(`alias?`, `queryRunner?`): `SelectQueryBuilder`<`UserSettingsEntity`\>

Creates a new query builder that can be used to build a sql query.

#### Parameters

| Name | Type |
| :------ | :------ |
| `alias?` | `string` |
| `queryRunner?` | `QueryRunner` |

#### Returns

`SelectQueryBuilder`<`UserSettingsEntity`\>

#### Inherited from

Repository.createQueryBuilder

#### Defined in

node_modules/typeorm/repository/Repository.d.ts:37

___

### decrement

▸ **decrement**(`conditions`, `propertyPath`, `value`): `Promise`<`UpdateResult`\>

Decrements some column by provided value of the entities matched given conditions.

#### Parameters

| Name | Type |
| :------ | :------ |
| `conditions` | `FindConditions`<`UserSettingsEntity`\> |
| `propertyPath` | `string` |
| `value` | `string` \| `number` |

#### Returns

`Promise`<`UpdateResult`\>

#### Inherited from

Repository.decrement

#### Defined in

node_modules/typeorm/repository/Repository.d.ts:275

___

### delete

▸ **delete**(`criteria`): `Promise`<`DeleteResult`\>

Deletes entities by a given criteria.
Unlike save method executes a primitive operation without cascades, relations and other operations included.
Executes fast and efficient DELETE query.
Does not check if entity exist in the database.

#### Parameters

| Name | Type |
| :------ | :------ |
| `criteria` | `string` \| `number` \| `Date` \| `ObjectID` \| `string`[] \| `number`[] \| `Date`[] \| `ObjectID`[] \| `FindConditions`<`UserSettingsEntity`\> |

#### Returns

`Promise`<`DeleteResult`\>

#### Inherited from

Repository.delete

#### Defined in

node_modules/typeorm/repository/Repository.d.ts:179

___

### find

▸ **find**(`options?`): `Promise`<`UserSettingsEntity`[]\>

Finds entities that match given options.

#### Parameters

| Name | Type |
| :------ | :------ |
| `options?` | `FindManyOptions`<`UserSettingsEntity`\> |

#### Returns

`Promise`<`UserSettingsEntity`[]\>

#### Inherited from

Repository.find

#### Defined in

node_modules/typeorm/repository/Repository.d.ts:205

▸ **find**(`conditions?`): `Promise`<`UserSettingsEntity`[]\>

Finds entities that match given conditions.

#### Parameters

| Name | Type |
| :------ | :------ |
| `conditions?` | `FindConditions`<`UserSettingsEntity`\> |

#### Returns

`Promise`<`UserSettingsEntity`[]\>

#### Inherited from

Repository.find

#### Defined in

node_modules/typeorm/repository/Repository.d.ts:209

___

### findAndCount

▸ **findAndCount**(`options?`): `Promise`<[`UserSettingsEntity`[], `number`]\>

Finds entities that match given find options.
Also counts all entities that match given conditions,
but ignores pagination settings (from and take options).

#### Parameters

| Name | Type |
| :------ | :------ |
| `options?` | `FindManyOptions`<`UserSettingsEntity`\> |

#### Returns

`Promise`<[`UserSettingsEntity`[], `number`]\>

#### Inherited from

Repository.findAndCount

#### Defined in

node_modules/typeorm/repository/Repository.d.ts:215

▸ **findAndCount**(`conditions?`): `Promise`<[`UserSettingsEntity`[], `number`]\>

Finds entities that match given conditions.
Also counts all entities that match given conditions,
but ignores pagination settings (from and take options).

#### Parameters

| Name | Type |
| :------ | :------ |
| `conditions?` | `FindConditions`<`UserSettingsEntity`\> |

#### Returns

`Promise`<[`UserSettingsEntity`[], `number`]\>

#### Inherited from

Repository.findAndCount

#### Defined in

node_modules/typeorm/repository/Repository.d.ts:221

___

### findByIds

▸ **findByIds**(`ids`, `options?`): `Promise`<`UserSettingsEntity`[]\>

Finds entities by ids.
Optionally find options can be applied.

#### Parameters

| Name | Type |
| :------ | :------ |
| `ids` | `any`[] |
| `options?` | `FindManyOptions`<`UserSettingsEntity`\> |

#### Returns

`Promise`<`UserSettingsEntity`[]\>

#### Inherited from

Repository.findByIds

#### Defined in

node_modules/typeorm/repository/Repository.d.ts:226

▸ **findByIds**(`ids`, `conditions?`): `Promise`<`UserSettingsEntity`[]\>

Finds entities by ids.
Optionally conditions can be applied.

#### Parameters

| Name | Type |
| :------ | :------ |
| `ids` | `any`[] |
| `conditions?` | `FindConditions`<`UserSettingsEntity`\> |

#### Returns

`Promise`<`UserSettingsEntity`[]\>

#### Inherited from

Repository.findByIds

#### Defined in

node_modules/typeorm/repository/Repository.d.ts:231

___

### findOne

▸ **findOne**(`id?`, `options?`): `Promise`<`undefined` \| `UserSettingsEntity`\>

Finds first entity that matches given options.

#### Parameters

| Name | Type |
| :------ | :------ |
| `id?` | `string` \| `number` \| `Date` \| `ObjectID` |
| `options?` | `FindOneOptions`<`UserSettingsEntity`\> |

#### Returns

`Promise`<`undefined` \| `UserSettingsEntity`\>

#### Inherited from

Repository.findOne

#### Defined in

node_modules/typeorm/repository/Repository.d.ts:235

▸ **findOne**(`options?`): `Promise`<`undefined` \| `UserSettingsEntity`\>

Finds first entity that matches given options.

#### Parameters

| Name | Type |
| :------ | :------ |
| `options?` | `FindOneOptions`<`UserSettingsEntity`\> |

#### Returns

`Promise`<`undefined` \| `UserSettingsEntity`\>

#### Inherited from

Repository.findOne

#### Defined in

node_modules/typeorm/repository/Repository.d.ts:239

▸ **findOne**(`conditions?`, `options?`): `Promise`<`undefined` \| `UserSettingsEntity`\>

Finds first entity that matches given conditions.

#### Parameters

| Name | Type |
| :------ | :------ |
| `conditions?` | `FindConditions`<`UserSettingsEntity`\> |
| `options?` | `FindOneOptions`<`UserSettingsEntity`\> |

#### Returns

`Promise`<`undefined` \| `UserSettingsEntity`\>

#### Inherited from

Repository.findOne

#### Defined in

node_modules/typeorm/repository/Repository.d.ts:243

___

### findOneOrFail

▸ **findOneOrFail**(`id?`, `options?`): `Promise`<`UserSettingsEntity`\>

Finds first entity that matches given options.

#### Parameters

| Name | Type |
| :------ | :------ |
| `id?` | `string` \| `number` \| `Date` \| `ObjectID` |
| `options?` | `FindOneOptions`<`UserSettingsEntity`\> |

#### Returns

`Promise`<`UserSettingsEntity`\>

#### Inherited from

Repository.findOneOrFail

#### Defined in

node_modules/typeorm/repository/Repository.d.ts:247

▸ **findOneOrFail**(`options?`): `Promise`<`UserSettingsEntity`\>

Finds first entity that matches given options.

#### Parameters

| Name | Type |
| :------ | :------ |
| `options?` | `FindOneOptions`<`UserSettingsEntity`\> |

#### Returns

`Promise`<`UserSettingsEntity`\>

#### Inherited from

Repository.findOneOrFail

#### Defined in

node_modules/typeorm/repository/Repository.d.ts:251

▸ **findOneOrFail**(`conditions?`, `options?`): `Promise`<`UserSettingsEntity`\>

Finds first entity that matches given conditions.

#### Parameters

| Name | Type |
| :------ | :------ |
| `conditions?` | `FindConditions`<`UserSettingsEntity`\> |
| `options?` | `FindOneOptions`<`UserSettingsEntity`\> |

#### Returns

`Promise`<`UserSettingsEntity`\>

#### Inherited from

Repository.findOneOrFail

#### Defined in

node_modules/typeorm/repository/Repository.d.ts:255

___

### getId

▸ **getId**(`entity`): `any`

Gets entity mixed id.

#### Parameters

| Name | Type |
| :------ | :------ |
| `entity` | `UserSettingsEntity` |

#### Returns

`any`

#### Inherited from

Repository.getId

#### Defined in

node_modules/typeorm/repository/Repository.d.ts:52

___

### hasId

▸ **hasId**(`entity`): `boolean`

Checks if entity has an id.
If entity composite compose ids, it will check them all.

#### Parameters

| Name | Type |
| :------ | :------ |
| `entity` | `UserSettingsEntity` |

#### Returns

`boolean`

#### Inherited from

Repository.hasId

#### Defined in

node_modules/typeorm/repository/Repository.d.ts:48

___

### increment

▸ **increment**(`conditions`, `propertyPath`, `value`): `Promise`<`UpdateResult`\>

Increments some column by provided value of the entities matched given conditions.

#### Parameters

| Name | Type |
| :------ | :------ |
| `conditions` | `FindConditions`<`UserSettingsEntity`\> |
| `propertyPath` | `string` |
| `value` | `string` \| `number` |

#### Returns

`Promise`<`UpdateResult`\>

#### Inherited from

Repository.increment

#### Defined in

node_modules/typeorm/repository/Repository.d.ts:271

___

### insert

▸ **insert**(`entity`): `Promise`<`InsertResult`\>

Inserts a given entity into the database.
Unlike save method executes a primitive operation without cascades, relations and other operations included.
Executes fast and efficient INSERT query.
Does not check if entity exist in the database, so query will fail if duplicate entity is being inserted.

#### Parameters

| Name | Type |
| :------ | :------ |
| `entity` | `QueryDeepPartialEntity`<`UserSettingsEntity`\> \| `QueryDeepPartialEntity`<`UserSettingsEntity`\>[] |

#### Returns

`Promise`<`InsertResult`\>

#### Inherited from

Repository.insert

#### Defined in

node_modules/typeorm/repository/Repository.d.ts:159

___

### merge

▸ **merge**(`mergeIntoEntity`, ...`entityLikes`): `UserSettingsEntity`

Merges multiple entities (or entity-like objects) into a given entity.

#### Parameters

| Name | Type |
| :------ | :------ |
| `mergeIntoEntity` | `UserSettingsEntity` |
| `...entityLikes` | `DeepPartial`<`UserSettingsEntity`\>[] |

#### Returns

`UserSettingsEntity`

#### Inherited from

Repository.merge

#### Defined in

node_modules/typeorm/repository/Repository.d.ts:70

___

### preload

▸ **preload**(`entityLike`): `Promise`<`undefined` \| `UserSettingsEntity`\>

Creates a new entity from the given plain javascript object. If entity already exist in the database, then
it loads it (and everything related to it), replaces all values with the new ones from the given object
and returns this new entity. This new entity is actually a loaded from the db entity with all properties
replaced from the new object.

Note that given entity-like object must have an entity id / primary key to find entity by.
Returns undefined if entity with given id was not found.

#### Parameters

| Name | Type |
| :------ | :------ |
| `entityLike` | `DeepPartial`<`UserSettingsEntity`\> |

#### Returns

`Promise`<`undefined` \| `UserSettingsEntity`\>

#### Inherited from

Repository.preload

#### Defined in

node_modules/typeorm/repository/Repository.d.ts:80

___

### query

▸ **query**(`query`, `parameters?`): `Promise`<`any`\>

Executes a raw SQL query and returns a raw database results.
Raw query execution is supported only by relational databases (MongoDB is not supported).

#### Parameters

| Name | Type |
| :------ | :------ |
| `query` | `string` |
| `parameters?` | `any`[] |

#### Returns

`Promise`<`any`\>

#### Inherited from

Repository.query

#### Defined in

node_modules/typeorm/repository/Repository.d.ts:260

___

### recover

▸ **recover**<`T`\>(`entities`, `options`): `Promise`<`T`[]\>

Recovers all given entities in the database.

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `DeepPartial`<`UserSettingsEntity`\> |

#### Parameters

| Name | Type |
| :------ | :------ |
| `entities` | `T`[] |
| `options` | `SaveOptions` & { `reload`: ``false``  } |

#### Returns

`Promise`<`T`[]\>

#### Inherited from

Repository.recover

#### Defined in

node_modules/typeorm/repository/Repository.d.ts:136

▸ **recover**<`T`\>(`entities`, `options?`): `Promise`<`T` & `UserSettingsEntity`[]\>

Recovers all given entities in the database.

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `DeepPartial`<`UserSettingsEntity`\> |

#### Parameters

| Name | Type |
| :------ | :------ |
| `entities` | `T`[] |
| `options?` | `SaveOptions` |

#### Returns

`Promise`<`T` & `UserSettingsEntity`[]\>

#### Inherited from

Repository.recover

#### Defined in

node_modules/typeorm/repository/Repository.d.ts:142

▸ **recover**<`T`\>(`entity`, `options`): `Promise`<`T`\>

Recovers a given entity in the database.

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `DeepPartial`<`UserSettingsEntity`\> |

#### Parameters

| Name | Type |
| :------ | :------ |
| `entity` | `T` |
| `options` | `SaveOptions` & { `reload`: ``false``  } |

#### Returns

`Promise`<`T`\>

#### Inherited from

Repository.recover

#### Defined in

node_modules/typeorm/repository/Repository.d.ts:146

▸ **recover**<`T`\>(`entity`, `options?`): `Promise`<`T` & `UserSettingsEntity`\>

Recovers a given entity in the database.

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `DeepPartial`<`UserSettingsEntity`\> |

#### Parameters

| Name | Type |
| :------ | :------ |
| `entity` | `T` |
| `options?` | `SaveOptions` |

#### Returns

`Promise`<`T` & `UserSettingsEntity`\>

#### Inherited from

Repository.recover

#### Defined in

node_modules/typeorm/repository/Repository.d.ts:152

___

### remove

▸ **remove**(`entities`, `options?`): `Promise`<`UserSettingsEntity`[]\>

Removes a given entities from the database.

#### Parameters

| Name | Type |
| :------ | :------ |
| `entities` | `UserSettingsEntity`[] |
| `options?` | `RemoveOptions` |

#### Returns

`Promise`<`UserSettingsEntity`[]\>

#### Inherited from

Repository.remove

#### Defined in

node_modules/typeorm/repository/Repository.d.ts:108

▸ **remove**(`entity`, `options?`): `Promise`<`UserSettingsEntity`\>

Removes a given entity from the database.

#### Parameters

| Name | Type |
| :------ | :------ |
| `entity` | `UserSettingsEntity` |
| `options?` | `RemoveOptions` |

#### Returns

`Promise`<`UserSettingsEntity`\>

#### Inherited from

Repository.remove

#### Defined in

node_modules/typeorm/repository/Repository.d.ts:112

___

### restore

▸ **restore**(`criteria`): `Promise`<`UpdateResult`\>

Restores entities by a given criteria.
Unlike save method executes a primitive operation without cascades, relations and other operations included.
Executes fast and efficient SOFT-DELETE query.
Does not check if entity exist in the database.

#### Parameters

| Name | Type |
| :------ | :------ |
| `criteria` | `string` \| `number` \| `Date` \| `ObjectID` \| `string`[] \| `number`[] \| `Date`[] \| `ObjectID`[] \| `FindConditions`<`UserSettingsEntity`\> |

#### Returns

`Promise`<`UpdateResult`\>

#### Inherited from

Repository.restore

#### Defined in

node_modules/typeorm/repository/Repository.d.ts:193

___

### save

▸ **save**<`T`\>(`entities`, `options`): `Promise`<`T`[]\>

Saves all given entities in the database.
If entities do not exist in the database then inserts, otherwise updates.

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `DeepPartial`<`UserSettingsEntity`\> |

#### Parameters

| Name | Type |
| :------ | :------ |
| `entities` | `T`[] |
| `options` | `SaveOptions` & { `reload`: ``false``  } |

#### Returns

`Promise`<`T`[]\>

#### Inherited from

Repository.save

#### Defined in

node_modules/typeorm/repository/Repository.d.ts:85

▸ **save**<`T`\>(`entities`, `options?`): `Promise`<`T` & `UserSettingsEntity`[]\>

Saves all given entities in the database.
If entities do not exist in the database then inserts, otherwise updates.

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `DeepPartial`<`UserSettingsEntity`\> |

#### Parameters

| Name | Type |
| :------ | :------ |
| `entities` | `T`[] |
| `options?` | `SaveOptions` |

#### Returns

`Promise`<`T` & `UserSettingsEntity`[]\>

#### Inherited from

Repository.save

#### Defined in

node_modules/typeorm/repository/Repository.d.ts:92

▸ **save**<`T`\>(`entity`, `options`): `Promise`<`T`\>

Saves a given entity in the database.
If entity does not exist in the database then inserts, otherwise updates.

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `DeepPartial`<`UserSettingsEntity`\> |

#### Parameters

| Name | Type |
| :------ | :------ |
| `entity` | `T` |
| `options` | `SaveOptions` & { `reload`: ``false``  } |

#### Returns

`Promise`<`T`\>

#### Inherited from

Repository.save

#### Defined in

node_modules/typeorm/repository/Repository.d.ts:97

▸ **save**<`T`\>(`entity`, `options?`): `Promise`<`T` & `UserSettingsEntity`\>

Saves a given entity in the database.
If entity does not exist in the database then inserts, otherwise updates.

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `DeepPartial`<`UserSettingsEntity`\> |

#### Parameters

| Name | Type |
| :------ | :------ |
| `entity` | `T` |
| `options?` | `SaveOptions` |

#### Returns

`Promise`<`T` & `UserSettingsEntity`\>

#### Inherited from

Repository.save

#### Defined in

node_modules/typeorm/repository/Repository.d.ts:104

___

### softDelete

▸ **softDelete**(`criteria`): `Promise`<`UpdateResult`\>

Records the delete date of entities by a given criteria.
Unlike save method executes a primitive operation without cascades, relations and other operations included.
Executes fast and efficient SOFT-DELETE query.
Does not check if entity exist in the database.

#### Parameters

| Name | Type |
| :------ | :------ |
| `criteria` | `string` \| `number` \| `Date` \| `ObjectID` \| `string`[] \| `number`[] \| `Date`[] \| `ObjectID`[] \| `FindConditions`<`UserSettingsEntity`\> |

#### Returns

`Promise`<`UpdateResult`\>

#### Inherited from

Repository.softDelete

#### Defined in

node_modules/typeorm/repository/Repository.d.ts:186

___

### softRemove

▸ **softRemove**<`T`\>(`entities`, `options`): `Promise`<`T`[]\>

Records the delete date of all given entities.

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `DeepPartial`<`UserSettingsEntity`\> |

#### Parameters

| Name | Type |
| :------ | :------ |
| `entities` | `T`[] |
| `options` | `SaveOptions` & { `reload`: ``false``  } |

#### Returns

`Promise`<`T`[]\>

#### Inherited from

Repository.softRemove

#### Defined in

node_modules/typeorm/repository/Repository.d.ts:116

▸ **softRemove**<`T`\>(`entities`, `options?`): `Promise`<`T` & `UserSettingsEntity`[]\>

Records the delete date of all given entities.

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `DeepPartial`<`UserSettingsEntity`\> |

#### Parameters

| Name | Type |
| :------ | :------ |
| `entities` | `T`[] |
| `options?` | `SaveOptions` |

#### Returns

`Promise`<`T` & `UserSettingsEntity`[]\>

#### Inherited from

Repository.softRemove

#### Defined in

node_modules/typeorm/repository/Repository.d.ts:122

▸ **softRemove**<`T`\>(`entity`, `options`): `Promise`<`T`\>

Records the delete date of a given entity.

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `DeepPartial`<`UserSettingsEntity`\> |

#### Parameters

| Name | Type |
| :------ | :------ |
| `entity` | `T` |
| `options` | `SaveOptions` & { `reload`: ``false``  } |

#### Returns

`Promise`<`T`\>

#### Inherited from

Repository.softRemove

#### Defined in

node_modules/typeorm/repository/Repository.d.ts:126

▸ **softRemove**<`T`\>(`entity`, `options?`): `Promise`<`T` & `UserSettingsEntity`\>

Records the delete date of a given entity.

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `DeepPartial`<`UserSettingsEntity`\> |

#### Parameters

| Name | Type |
| :------ | :------ |
| `entity` | `T` |
| `options?` | `SaveOptions` |

#### Returns

`Promise`<`T` & `UserSettingsEntity`\>

#### Inherited from

Repository.softRemove

#### Defined in

node_modules/typeorm/repository/Repository.d.ts:132

___

### update

▸ **update**(`criteria`, `partialEntity`): `Promise`<`UpdateResult`\>

Updates entity partially. Entity can be found by a given conditions.
Unlike save method executes a primitive operation without cascades, relations and other operations included.
Executes fast and efficient UPDATE query.
Does not check if entity exist in the database.

#### Parameters

| Name | Type |
| :------ | :------ |
| `criteria` | `string` \| `number` \| `Date` \| `ObjectID` \| `string`[] \| `number`[] \| `Date`[] \| `ObjectID`[] \| `FindConditions`<`UserSettingsEntity`\> |
| `partialEntity` | `QueryDeepPartialEntity`<`UserSettingsEntity`\> |

#### Returns

`Promise`<`UpdateResult`\>

#### Inherited from

Repository.update

#### Defined in

node_modules/typeorm/repository/Repository.d.ts:166

___

### upsert

▸ **upsert**(`entityOrEntities`, `conflictPathsOrOptions`): `Promise`<`InsertResult`\>

Inserts a given entity into the database, unless a unique constraint conflicts then updates the entity
Unlike save method executes a primitive operation without cascades, relations and other operations included.
Executes fast and efficient INSERT ... ON CONFLICT DO UPDATE/ON DUPLICATE KEY UPDATE query.

#### Parameters

| Name | Type |
| :------ | :------ |
| `entityOrEntities` | `QueryDeepPartialEntity`<`UserSettingsEntity`\> \| `QueryDeepPartialEntity`<`UserSettingsEntity`\>[] |
| `conflictPathsOrOptions` | `string`[] \| `UpsertOptions`<`UserSettingsEntity`\> |

#### Returns

`Promise`<`InsertResult`\>

#### Inherited from

Repository.upsert

#### Defined in

node_modules/typeorm/repository/Repository.d.ts:172
