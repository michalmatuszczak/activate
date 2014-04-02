# Index

## [Get started](/docs/get-started.md)

Activate is a framework to persist objects in Scala.

## [Persistence Context](/docs/migration.md)

To use Activate, first you have to define a Persistence Context.

## [Entity](/docs/migration.md)

To define a persistent entity you just have to extend the Entity trait.

## [Transaction](/docs/transaction.md)

All entity creation, modification, read or query must be executed inside a transaction, otherwise a RequiredTransactionException will be thrown.

## [Validation](/docs/migration.md)

Activate provides a Design by Contract (DbC) mechanism to achieve validation.

## [Query](/docs/migration.md)

Activate queries are consistent, even with entities created in the current transaction, so a new entity can be returned in a query.

## [Migration](/docs/migration.md)

Migration is the storage schema evolution mechanism provided by Activate.

## [Multiple VMs](/docs/migration.md)

Activate uses memory efficiently by maintaining soft references for the entities that are loaded from the storage.

## [Mass statement](/docs/migration.md)

Activate supports mass update/delete statements.

## [Play framework](/docs/migration.md)

The “activate-play” component has some classes to facilitate the Activate usage with the Play Framework 2.2.

## [Lift framework](/docs/migration.md)

The “activate-lift” module has the EntityForm that provides a easy way to handle lift entity forms.

## [Spray Json](/docs/migration.md)

The spray-json integration is a easy way to manipulate entities from/to json.

## [Architecture](/docs/migration.md)

Activate is a Software Transactional Memory with efficient memory usage and pluggable persistence.
