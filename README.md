# NetCoreSwagger
Creating a .Net Core web API with Swagger. 

## Technologies

- [.Net Core 3](https://docs.microsoft.com/pt-br/dotnet/core/whats-new/dotnet-core-3-0)
- [Visual Studio 2019](https://visualstudio.microsoft.com/pt-br/vs/)
- [Swagger](https://docs.microsoft.com/pt-br/aspnet/core/tutorials/getting-started-with-swashbuckle?view=aspnetcore-3.0&tabs=visual-studio)

### Swagger

Inside the Visual Studio 2019, open the Package Manager Console and run the following commands to install the Swashbuckle version compatible with .Net Core 3:

```bash
Install-Package Swashbuckle.AspNetCore -Version 5.0.0-rc3
Install-Package Swashbuckle.AspNetCore.Filters -Version 5.0.0-rc3
Install-Package Swashbuckle.AspNetCore.Annotations -Version 5.0.0-rc3
```

### Run

```bash
http://localhost:<API-PORT>/swagger/index.html
```