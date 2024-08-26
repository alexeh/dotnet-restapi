# dotnet-restapi
Basic REST API with SQL Server using .NET8

SQL Server docker run:

```
docker run -e "ACCEPT_EULA=Y" -e "SA_PASSWORD=YourStrong!Passw0rd" -p 1433:1433 --name sqlserver -d mcr.microsoft.com/azure-sql-edge
```

**ACCEPT_EULA**: Terms of use

**TEST PASSWORD**: Dotnetrestapi360

Default database schema for the app is: `dbo`