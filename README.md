# Awesome Dapper

[![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

[Dapper](https://github.com/StackExchange/Dapper) is a simple object mapper for .NET and own the title of King of Micro ORM in terms of speed and is virtually as fast as using a raw ADO.NET data reader.

A curated list of awesome dapper libraries, packages, and documentation.

### Contributing

Suggestions and contributions are always welcome! Make sure to read the [contribution guidelines](https://github.com/zzzprojects/awesome-dapper/blob/master/CONTRIBUTING.md) for more information before submitting a pull request.

### Contents

- [Awesome Dapper](#awesome-dapper)
   - [Documentation and Learning](#documentation-and-learning)
   - [Popular Packages](#popular-packages)
   - [Supported Packages](#supported-packages)
   - [Unsupported Packages](#supported-packages)
   - [Providers](#providers)

## Documentation and Learning

- [Dapper Tutorial](https://dapper-tutorial.net/) - Basic learning material for Dapper.
- [Knowledge Base](https://dapper-tutorial.net/knowledge-base) - Translated posts from Stack Overflow
- [RIP Tutorial](https://riptutorial.com/dapper) - Archived Stack Overflow Documentation (Multi-Language)
- [Google](http://www.letmegooglethat.com/?q=dapper) - Up-and-coming search engine ;) 

## Popular Packages
- [Z.Dapper.Plus](http://dapper-plus.net/) - Dapper Plus extends your IDbConnection with high-performance bulk operations: BulkInsert, BulkUpdate, BulkDelete, BulkMerge, and more.
- [Dapper.Contrib](https://www.nuget.org/packages/Dapper.Contrib/) - The official collection of get, insert, update and delete helpers for Dapper.net. Also handles lists of entities and optional "dirty" tracking of interface-based entities.
- [Dapper.SimpleCRUD](https://github.com/ericdc1/Dapper.SimpleCRUD/) - Basic read/insert/update/delete statements? SimpleCRUD provides simple CRUD helpers for Dapper.
helpers.
- [Dapper.SqlBuilder](https://www.nuget.org/packages/Dapper.SqlBuilder/) - The Dapper SqlBuilder component, for building SQL queries dynamically.

## Supported Packages
- [Dommel](https://github.com/henkmollema/Dommel) - Simple CRUD operations for Dapper.
- [Dapper.Abstractions](https://github.com/Tazmainiandevil/Dapper.Abstractions) - A simple abstraction atop the Dapper extension methods and TransactionScope for testability.
- [Dapper.Compose](https://github.com/naasking/Dapper.Compose) - Typed multi query composition for Dapper.
- [Dapper.Database](https://github.com/dallasbeek/Dapper.Database) - Dapper.Database contains a number of helper methods for inserting, getting, updating and deleting records.
- [Dapper.Rainbow](https://www.nuget.org/packages/Dapper.Rainbow/) - Trivial micro-orm implemented on Dapper, provides with CRUD 
- [LiteLib](https://unosquare.github.io/litelib/) - A cool little wrapper for SQLite based on Dapper from Unosquare Labs -- It's also free and MIT-licensed.
- [MicroOrm.Dapper.Repositories](https://github.com/phnx47/MicroOrm.Dapper.Repositories) - CRUD for Dapper

## Unsupported Packages
- [Dapper.ColumnMapper](https://github.com/dturkenk/Dapper.ColumnMapper) - Simple extension to Dapper to allow arbitrary column to property mapping.
- [Dapper.Data](https://github.com/mkonstan/Dapper.Data) - Micro-orm implemented on Dapper, streamlines connection and transaction management while preserving flexibility and usability of Dapper.
- [Dapper.DataRepositories](https://github.com/ElNinjaGaiden/Dapper.DataRepositories) - Base structures to implement Data Repository pattern upon Dapper as MicroOrm.
- [Dapper.DynamicReportGenerator](https://github.com/kvnallen/Dapper.DynamicReportGenerator) - A dynamic report generator for Dapper. Can be used to return generic data in CSV (currently) format.
- [Dapper.Extension](https://github.com/m98proxy/Dapper.Extension) - CRUD extension methods for Dapper (WIP).
- [Dapper.Extensions.Linq](https://github.com/ryanwatson/Dapper.Extensions.Linq) - Dapper.Extensions.Linq builds on this providing advanced DB access through Linq queries.
- [Dapper.Extensions.Repository](https://github.com/symondev/dapper-extensions-repository) - Dapper.Extensions.Repository is an extension to integration with dapper-dot-net and MicroOrm.Dapper.Repositories.
- [Dapper.FastCrud](https://github.com/MoonStorm/Dapper.FastCRUD) - The fastest micro-orm extension for Dapper.
- [Dapper.Fluent](https://github.com/beardeddev/dapper-fluent) - Dapper.Fluent is a small and easy library that supports fluent API for query construction and execution over database connection using [Dapper.Net](https://github.com/StackExchange/Dapper).
- [Dapper.FluentColumnMapping](https://github.com/alexander-87/Dapper.FluentColumnMapping) - Fluent Object-Column Mappings for use with Dapper.
 - [Dapper.FluentMap](https://github.com/henkmollema/Dapper-FluentMap) - Provides a simple API to fluently map POCO properties to database columns when using Dapper.
 - [Dapper.FluentMap.Dommel](https://github.com/henkmollema/Dapper-FluentMap) - Provides a simple API to fluently map POCO properties to database columns when using Dapper.
- [Dapper.Mapper](https://github.com/dotarj/Dapper.Mapper) - A extension to Dapper multi mapping which figures out the relationships between the returned objects and automatically assigns them. 
- [Dapper.MicroCRUD](https://github.com/berkeleybross/PeregrineDb) - CRUD Extensions for Dapper.Net
- [Dapper.MoqTests](https://github.com/laingsimon/Dapper.MoqTests) - Assemblies to assist testing dapper database invocations.
- [Dapper.SimpleLoad](https://github.com/Paymentsense/Dapper.SimpleLoad) - Dapper.SimpleLoad simplifies Dapper multi-mapping to load complex objects from a relational database. It's the companion to [Dapper.SimpleSave](https://github.com/Paymentsense/Dapper.SimpleSave).
- [Dapper.SimpleSave](https://github.com/Paymentsense/Dapper.SimpleSave/) - Dapper.SimpleSave makes it easy to save complex object hierarchies to a relational database.
- [Dapper.TableValuedParameter](https://github.com/ayberkcanturk/Dapper.TableValuedParameter) - An extension to provide Table-Valued Parameters to Dapper. .NET Core support available!
- [Dapper.Tvp](https://www.nuget.org/packages/Dapper.Tvp/) - A couple of helper classes to make using TVP parameters with Dapper easier.
- [DapperExtensions](https://github.com/tmsmith/Dapper-Extensions) - A small library that complements Dapper by adding basic CRUD operations (Get, Insert, Update, Delete) for your POCOs.
- [DapperWrappe](https://github.com/half-ogre/dapper-wrapper) - DA simple abstraction atop the Dapper extension methods and TransactionScope for testability.
- [Dashing](https://github.com/Polylytics/dashing) - Dashing is a simple to use mini ORM built on top of Dapper.
- [DeclarativeSql.Dapper](https://github.com/xin9le/DeclarativeSql) - This library provides attribute-based table mapping and simple database access.
- [SQLinq.Dapper](https://www.nuget.org/packages/SQLinq.Dapper) - Allows for SQLinq to be more easily used with a little help from "Dapper dot net".
- [Stove.Dapper](https://www.nuget.org/packages/Stove.Dapper) - Dapper integration for Stove.
 
## Providers

- [Dapper.Rainbow.MySql](https://www.nuget.org/packages/Dapper.Rainbow.MySql/) - Trivial micro-orm implemented on Dapper, provides with CRUD helpers specialize to handle MySql.
- [Dapper.Rainbow.SQLite](https://www.nuget.org/packages/Dapper.Rainbow.SQLite/) - Trivial micro-orm implemented on Dapper, provides with CRUD helpers. specialize to handle SQLite.
- [Dapper.Rainbow.PostgreSql](https://www.nuget.org/packages/Dapper.Rainbow.PostgreSql) - Trivial micro-orm implemented on Dapper, provides with CRUD helpers.
- [Dapper.Oracle](https://www.nuget.org/packages/Dapper.Oracle/) - Oracle support for Dapper Micro ORM.


