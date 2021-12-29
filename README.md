MINETSHOP
===

# Quick start
**Run API**
```shell
cd API
dotnet run

// run watch
dotnet watch run
```

# Migration

```shell
// drop database
dotnet ef database drop -p Infrastructure -s API

// remove migrations
dotnet ef migrations remove -p Infrastructure -s API

// add migration
dotnet ef migrations add InitialCreate -p Infrastructure -s API -o Data/Migrations
```

