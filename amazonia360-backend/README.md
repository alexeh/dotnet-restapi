.NET backend

2 datasource connection conf:

1. appsettings.json
2. appsetting.Development.json

The second one overrides the first one, and the environment is set by:
``
ASPNETCORE_ENVIRONMENT
``
env var.


**Program.cs** is the entrypoint for the app
