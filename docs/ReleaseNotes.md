# Release Notes

## WeihanLi.EntityFramework

### [WeihanLi.EntityFramework 1.7.0](https://www.nuget.org/packages/WeihanLi.EntityFramework/1.7.0)

- update `AuditEntry`
- optimize auto audit with aop

### [WeihanLi.EntityFramework 1.6.0](https://www.nuget.org/packages/WeihanLi.EntityFramework/1.6.0)

- add auto audit support
- add `dbContext.GetTableName<TEntity>()` extensions
- add `QueryWithNoLockInterceptor`

### [WeihanLi.EntityFramework 1.5.0](https://www.nuget.org/packages/WeihanLi.EntityFramework/1.5.0)

- update EF core to 3.1(drop support EF core 2.x)
- update `EFRepository.FindAsync` to return `ValueTask`
- update `IsRelationalDatabase` extension

### [WeihanLi.EntityFramework 1.4.2](https://www.nuget.org/packages/WeihanLi.EntityFramework/1.4.2)

- update `IEFUnitOfWork`/`IEFRepository`
- add `Update`/`UpdateWithout` extension methods for dbContext
- add `GetTableName`/`GetColumnName` extension method
- add `dbContext.Database.IsRelational`
- add auto audit support

### [WeihanLi.EntityFramework 1.3.0](https://www.nuget.org/packages/WeihanLi.EntityFramework/1.3.0)

- add `IEFUnitOfWork`
- optimize `EFRepositoryQueryBuilder` set default predict to null

### [WeihanLi.EntityFramework 1.2.0](https://www.nuget.org/packages/WeihanLi.EntityFramework/1.2.0)

- add `IEFRepositoryFactory`

### [WeihanLi.EntityFramework 1.1.0](https://www.nuget.org/packages/WeihanLi.EntityFramework/1.1.0)

- add `Query` for `IEFRepository` return raw `IQueryable<TEntity>`

### [WeihanLi.EntityFramework 1.0.9](https://www.nuget.org/packages/WeihanLi.EntityFramework/1.0.9)

- add `Delete`/`Any` for `IEFRepository`
- update pagedList extension
- add `DbContextBase`

### [WeihanLi.EntityFramework 1.0.8](https://www.nuget.org/packages/WeihanLi.EntityFramework/1.0.8)

- rename Get with selector method name => `GetResult`/`FirstOrDefaultResult`/`GetPagedListResult`

### [WeihanLi.EntityFramework 1.0.7](https://www.nuget.org/packages/WeihanLi.EntityFramework/1.0.7)

- update `Update` for `EFRepository`
- add `UpdateWithout`
- remove none `QueryBuilder` extensions

### [WeihanLi.EntityFramework 1.0.6](https://www.nuget.org/packages/WeihanLi.EntityFramework/1.0.6)

- add `FirstOrDefault` for `EFRepository`

### [WeihanLi.EntityFramework 1.0.5](https://www.nuget.org/packages/WeihanLi.EntityFramework/1.0.5)

- add `CancellationToken` support for async operations
- add `IEFRepositoryGenerator`
- add `EFRepositoryQueryBuilder` for `EFRepository`
- add [`sourceLink`](https://github.com/dotnet/sourcelink) support

### [WeihanLi.EntityFramework 1.0.3](https://www.nuget.org/packages/WeihanLi.EntityFramework/1.0.3)

- add `EFRepositoryGenerator`
