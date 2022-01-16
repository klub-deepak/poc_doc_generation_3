[awesome-nestjs-boilerplate](../README.md) / [Exports](../modules.md) / UserRepository

# Class: UserRepository

## Hierarchy

- `Repository`<`UserEntity`\>

  ↳ **`UserRepository`**

## Table of contents

### Constructors

- [constructor](UserRepository.md#constructor)

### Properties

- [manager](UserRepository.md#manager)
- [metadata](UserRepository.md#metadata)
- [queryRunner](UserRepository.md#queryrunner)

### Accessors

- [target](UserRepository.md#target)

### Methods

- [clear](UserRepository.md#clear)
- [count](UserRepository.md#count)
- [create](UserRepository.md#create)
- [createQueryBuilder](UserRepository.md#createquerybuilder)
- [decrement](UserRepository.md#decrement)
- [delete](UserRepository.md#delete)
- [find](UserRepository.md#find)
- [findAndCount](UserRepository.md#findandcount)
- [findByIds](UserRepository.md#findbyids)
- [findOne](UserRepository.md#findone)
- [findOneOrFail](UserRepository.md#findoneorfail)
- [getId](UserRepository.md#getid)
- [hasId](UserRepository.md#hasid)
- [increment](UserRepository.md#increment)
- [insert](UserRepository.md#insert)
- [merge](UserRepository.md#merge)
- [preload](UserRepository.md#preload)
- [query](UserRepository.md#query)
- [recover](UserRepository.md#recover)
- [remove](UserRepository.md#remove)
- [restore](UserRepository.md#restore)
- [save](UserRepository.md#save)
- [softDelete](UserRepository.md#softdelete)
- [softRemove](UserRepository.md#softremove)
- [update](UserRepository.md#update)
- [upsert](UserRepository.md#upsert)

## Constructors

### constructor

• **new UserRepository**()

#### Inherited from

Repository<UserEntity\>.constructor

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
| `options?` | `FindManyOptions`<`UserEntity`\> |

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
| `conditions?` | `FindConditions`<`UserEntity`\> |

#### Returns

`Promise`<`number`\>

#### Inherited from

Repository.count

#### Defined in

node_modules/typeorm/repository/Repository.d.ts:201

___

### create

▸ **create**(): `UserEntity`

Creates a new entity instance.

#### Returns

`UserEntity`

#### Inherited from

Repository.create

#### Defined in

node_modules/typeorm/repository/Repository.d.ts:56

▸ **create**(`entityLikeArray`): `UserEntity`[]

Creates new entities and copies all entity properties from given objects into their new entities.
Note that it copies only properties that are present in entity schema.

#### Parameters

| Name | Type |
| :------ | :------ |
| `entityLikeArray` | `DeepPartial`<`UserEntity`\>[] |

#### Returns

`UserEntity`[]

#### Inherited from

Repository.create

#### Defined in

node_modules/typeorm/repository/Repository.d.ts:61

▸ **create**(`entityLike`): `UserEntity`

Creates a new entity instance and copies all entity properties from this object into a new entity.
Note that it copies only properties that are present in entity schema.

#### Parameters

| Name | Type |
| :------ | :------ |
| `entityLike` | `DeepPartial`<`UserEntity`\> |

#### Returns

`UserEntity`

#### Inherited from

Repository.create

#### Defined in

node_modules/typeorm/repository/Repository.d.ts:66

___

### createQueryBuilder

▸ **createQueryBuilder**(`alias?`, `queryRunner?`): `SelectQueryBuilder`<`UserEntity`\>

Creates a new query builder that can be used to build a sql query.

#### Parameters

| Name | Type |
| :------ | :------ |
| `alias?` | `string` |
| `queryRunner?` | `QueryRunner` |

#### Returns

`SelectQueryBuilder`<`UserEntity`\>

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
| `conditions` | `FindConditions`<`UserEntity`\> |
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
| `criteria` | `string` \| `number` \| `Date` \| `ObjectID` \| `string`[] \| `number`[] \| `Date`[] \| `ObjectID`[] \| `FindConditions`<`UserEntity`\> |

#### Returns

`Promise`<`DeleteResult`\>

#### Inherited from

Repository.delete

#### Defined in

node_modules/typeorm/repository/Repository.d.ts:179

___

### find

▸ **find**(`options?`): `Promise`<`UserEntity`[]\>

Finds entities that match given options.

#### Parameters

| Name | Type |
| :------ | :------ |
| `options?` | `FindManyOptions`<`UserEntity`\> |

#### Returns

`Promise`<`UserEntity`[]\>

#### Inherited from

Repository.find

#### Defined in

node_modules/typeorm/repository/Repository.d.ts:205

▸ **find**(`conditions?`): `Promise`<`UserEntity`[]\>

Finds entities that match given conditions.

#### Parameters

| Name | Type |
| :------ | :------ |
| `conditions?` | `FindConditions`<`UserEntity`\> |

#### Returns

`Promise`<`UserEntity`[]\>

#### Inherited from

Repository.find

#### Defined in

node_modules/typeorm/repository/Repository.d.ts:209

___

### findAndCount

▸ **findAndCount**(`options?`): `Promise`<[`UserEntity`[], `number`]\>

Finds entities that match given find options.
Also counts all entities that match given conditions,
but ignores pagination settings (from and take options).

#### Parameters

| Name | Type |
| :------ | :------ |
| `options?` | `FindManyOptions`<`UserEntity`\> |

#### Returns

`Promise`<[`UserEntity`[], `number`]\>

#### Inherited from

Repository.findAndCount

#### Defined in

node_modules/typeorm/repository/Repository.d.ts:215

▸ **findAndCount**(`conditions?`): `Promise`<[`UserEntity`[], `number`]\>

Finds entities that match given conditions.
Also counts all entities that match given conditions,
but ignores pagination settings (from and take options).

#### Parameters

| Name | Type |
| :------ | :------ |
| `conditions?` | `FindConditions`<`UserEntity`\> |

#### Returns

`Promise`<[`UserEntity`[], `number`]\>

#### Inherited from

Repository.findAndCount

#### Defined in

node_modules/typeorm/repository/Repository.d.ts:221

___

### findByIds

▸ **findByIds**(`ids`, `options?`): `Promise`<`UserEntity`[]\>

Finds entities by ids.
Optionally find options can be applied.

#### Parameters

| Name | Type |
| :------ | :------ |
| `ids` | `any`[] |
| `options?` | `FindManyOptions`<`UserEntity`\> |

#### Returns

`Promise`<`UserEntity`[]\>

#### Inherited from

Repository.findByIds

#### Defined in

node_modules/typeorm/repository/Repository.d.ts:226

▸ **findByIds**(`ids`, `conditions?`): `Promise`<`UserEntity`[]\>

Finds entities by ids.
Optionally conditions can be applied.

#### Parameters

| Name | Type |
| :------ | :------ |
| `ids` | `any`[] |
| `conditions?` | `FindConditions`<`UserEntity`\> |

#### Returns

`Promise`<`UserEntity`[]\>

#### Inherited from

Repository.findByIds

#### Defined in

node_modules/typeorm/repository/Repository.d.ts:231

___

### findOne

▸ **findOne**(`id?`, `options?`): `Promise`<`undefined` \| `UserEntity`\>

Finds first entity that matches given options.

#### Parameters

| Name | Type |
| :------ | :------ |
| `id?` | `string` \| `number` \| `Date` \| `ObjectID` |
| `options?` | `FindOneOptions`<`UserEntity`\> |

#### Returns

`Promise`<`undefined` \| `UserEntity`\>

#### Inherited from

Repository.findOne

#### Defined in

node_modules/typeorm/repository/Repository.d.ts:235

▸ **findOne**(`options?`): `Promise`<`undefined` \| `UserEntity`\>

Finds first entity that matches given options.

#### Parameters

| Name | Type |
| :------ | :------ |
| `options?` | `FindOneOptions`<`UserEntity`\> |

#### Returns

`Promise`<`undefined` \| `UserEntity`\>

#### Inherited from

Repository.findOne

#### Defined in

node_modules/typeorm/repository/Repository.d.ts:239

▸ **findOne**(`conditions?`, `options?`): `Promise`<`undefined` \| `UserEntity`\>

Finds first entity that matches given conditions.

#### Parameters

| Name | Type |
| :------ | :------ |
| `conditions?` | `FindConditions`<`UserEntity`\> |
| `options?` | `FindOneOptions`<`UserEntity`\> |

#### Returns

`Promise`<`undefined` \| `UserEntity`\>

#### Inherited from

Repository.findOne

#### Defined in

node_modules/typeorm/repository/Repository.d.ts:243

___

### findOneOrFail

▸ **findOneOrFail**(`id?`, `options?`): `Promise`<`UserEntity`\>

Finds first entity that matches given options.

#### Parameters

| Name | Type |
| :------ | :------ |
| `id?` | `string` \| `number` \| `Date` \| `ObjectID` |
| `options?` | `FindOneOptions`<`UserEntity`\> |

#### Returns

`Promise`<`UserEntity`\>

#### Inherited from

Repository.findOneOrFail

#### Defined in

node_modules/typeorm/repository/Repository.d.ts:247

▸ **findOneOrFail**(`options?`): `Promise`<`UserEntity`\>

Finds first entity that matches given options.

#### Parameters

| Name | Type |
| :------ | :------ |
| `options?` | `FindOneOptions`<`UserEntity`\> |

#### Returns

`Promise`<`UserEntity`\>

#### Inherited from

Repository.findOneOrFail

#### Defined in

node_modules/typeorm/repository/Repository.d.ts:251

▸ **findOneOrFail**(`conditions?`, `options?`): `Promise`<`UserEntity`\>

Finds first entity that matches given conditions.

#### Parameters

| Name | Type |
| :------ | :------ |
| `conditions?` | `FindConditions`<`UserEntity`\> |
| `options?` | `FindOneOptions`<`UserEntity`\> |

#### Returns

`Promise`<`UserEntity`\>

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
| `entity` | `UserEntity` |

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
| `entity` | `UserEntity` |

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
| `conditions` | `FindConditions`<`UserEntity`\> |
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
| `entity` | `QueryDeepPartialEntity`<`UserEntity`\> \| `QueryDeepPartialEntity`<`UserEntity`\>[] |

#### Returns

`Promise`<`InsertResult`\>

#### Inherited from

Repository.insert

#### Defined in

node_modules/typeorm/repository/Repository.d.ts:159

___

### merge

▸ **merge**(`mergeIntoEntity`, ...`entityLikes`): `UserEntity`

Merges multiple entities (or entity-like objects) into a given entity.

#### Parameters

| Name | Type |
| :------ | :------ |
| `mergeIntoEntity` | `UserEntity` |
| `...entityLikes` | `DeepPartial`<`UserEntity`\>[] |

#### Returns

`UserEntity`

#### Inherited from

Repository.merge

#### Defined in

node_modules/typeorm/repository/Repository.d.ts:70

___

### preload

▸ **preload**(`entityLike`): `Promise`<`undefined` \| `UserEntity`\>

Creates a new entity from the given plain javascript object. If entity already exist in the database, then
it loads it (and everything related to it), replaces all values with the new ones from the given object
and returns this new entity. This new entity is actually a loaded from the db entity with all properties
replaced from the new object.

Note that given entity-like object must have an entity id / primary key to find entity by.
Returns undefined if entity with given id was not found.

#### Parameters

| Name | Type |
| :------ | :------ |
| `entityLike` | `DeepPartial`<`UserEntity`\> |

#### Returns

`Promise`<`undefined` \| `UserEntity`\>

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
| `T` | extends `DeepPartial`<`UserEntity`\> |

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

▸ **recover**<`T`\>(`entities`, `options?`): `Promise`<`T` & `UserEntity`[]\>

Recovers all given entities in the database.

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `DeepPartial`<`UserEntity`\> |

#### Parameters

| Name | Type |
| :------ | :------ |
| `entities` | `T`[] |
| `options?` | `SaveOptions` |

#### Returns

`Promise`<`T` & `UserEntity`[]\>

#### Inherited from

Repository.recover

#### Defined in

node_modules/typeorm/repository/Repository.d.ts:142

▸ **recover**<`T`\>(`entity`, `options`): `Promise`<`T`\>

Recovers a given entity in the database.

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `DeepPartial`<`UserEntity`\> |

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

▸ **recover**<`T`\>(`entity`, `options?`): `Promise`<`T` & `UserEntity`\>

Recovers a given entity in the database.

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `DeepPartial`<`UserEntity`\> |

#### Parameters

| Name | Type |
| :------ | :------ |
| `entity` | `T` |
| `options?` | `SaveOptions` |

#### Returns

`Promise`<`T` & `UserEntity`\>

#### Inherited from

Repository.recover

#### Defined in

node_modules/typeorm/repository/Repository.d.ts:152

___

### remove

▸ **remove**(`entities`, `options?`): `Promise`<`UserEntity`[]\>

Removes a given entities from the database.

#### Parameters

| Name | Type |
| :------ | :------ |
| `entities` | `UserEntity`[] |
| `options?` | `RemoveOptions` |

#### Returns

`Promise`<`UserEntity`[]\>

#### Inherited from

Repository.remove

#### Defined in

node_modules/typeorm/repository/Repository.d.ts:108

▸ **remove**(`entity`, `options?`): `Promise`<`UserEntity`\>

Removes a given entity from the database.

#### Parameters

| Name | Type |
| :------ | :------ |
| `entity` | `UserEntity` |
| `options?` | `RemoveOptions` |

#### Returns

`Promise`<`UserEntity`\>

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
| `criteria` | `string` \| `number` \| `Date` \| `ObjectID` \| `string`[] \| `number`[] \| `Date`[] \| `ObjectID`[] \| `FindConditions`<`UserEntity`\> |

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
| `T` | extends `DeepPartial`<`UserEntity`\> |

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

▸ **save**<`T`\>(`entities`, `options?`): `Promise`<`T` & `UserEntity`[]\>

Saves all given entities in the database.
If entities do not exist in the database then inserts, otherwise updates.

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `DeepPartial`<`UserEntity`\> |

#### Parameters

| Name | Type |
| :------ | :------ |
| `entities` | `T`[] |
| `options?` | `SaveOptions` |

#### Returns

`Promise`<`T` & `UserEntity`[]\>

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
| `T` | extends `DeepPartial`<`UserEntity`\> |

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

▸ **save**<`T`\>(`entity`, `options?`): `Promise`<`T` & `UserEntity`\>

Saves a given entity in the database.
If entity does not exist in the database then inserts, otherwise updates.

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `DeepPartial`<`UserEntity`\> |

#### Parameters

| Name | Type |
| :------ | :------ |
| `entity` | `T` |
| `options?` | `SaveOptions` |

#### Returns

`Promise`<`T` & `UserEntity`\>

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
| `criteria` | `string` \| `number` \| `Date` \| `ObjectID` \| `string`[] \| `number`[] \| `Date`[] \| `ObjectID`[] \| `FindConditions`<`UserEntity`\> |

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
| `T` | extends `DeepPartial`<`UserEntity`\> |

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

▸ **softRemove**<`T`\>(`entities`, `options?`): `Promise`<`T` & `UserEntity`[]\>

Records the delete date of all given entities.

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `DeepPartial`<`UserEntity`\> |

#### Parameters

| Name | Type |
| :------ | :------ |
| `entities` | `T`[] |
| `options?` | `SaveOptions` |

#### Returns

`Promise`<`T` & `UserEntity`[]\>

#### Inherited from

Repository.softRemove

#### Defined in

node_modules/typeorm/repository/Repository.d.ts:122

▸ **softRemove**<`T`\>(`entity`, `options`): `Promise`<`T`\>

Records the delete date of a given entity.

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `DeepPartial`<`UserEntity`\> |

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

▸ **softRemove**<`T`\>(`entity`, `options?`): `Promise`<`T` & `UserEntity`\>

Records the delete date of a given entity.

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `DeepPartial`<`UserEntity`\> |

#### Parameters

| Name | Type |
| :------ | :------ |
| `entity` | `T` |
| `options?` | `SaveOptions` |

#### Returns

`Promise`<`T` & `UserEntity`\>

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
| `criteria` | `string` \| `number` \| `Date` \| `ObjectID` \| `string`[] \| `number`[] \| `Date`[] \| `ObjectID`[] \| `FindConditions`<`UserEntity`\> |
| `partialEntity` | `QueryDeepPartialEntity`<`UserEntity`\> |

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
| `entityOrEntities` | `QueryDeepPartialEntity`<`UserEntity`\> \| `QueryDeepPartialEntity`<`UserEntity`\>[] |
| `conflictPathsOrOptions` | `string`[] \| `UpsertOptions`<`UserEntity`\> |

#### Returns

`Promise`<`InsertResult`\>

#### Inherited from

Repository.upsert

#### Defined in

node_modules/typeorm/repository/Repository.d.ts:172
