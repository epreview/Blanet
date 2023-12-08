## Blanet | .NET 8 with Razor 

> So commits are not arbitrary when pushing the developer version, it is hoped to follow this urge.


1. Clone the source code or create new project :

```shell
git clone https://github.com/epreview/blanet.git
```

2. Installing / DB update with ef core tools

```shell
dotnet new blazor -au Individual | dotnet ef database update -- --environment Production
```
