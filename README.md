# MyRecipeBook

API .NET para gerenciamento de receitas, estruturada em camadas (Clean Architecture / DDD).

## Estrutura

- `src/Backend` — Api, Application, Domain, Infrastructure
- `src/Shared` — Communication, Exception

## Requisitos

- [.NET SDK](https://dotnet.microsoft.com/download) (net10.0)

## Executar a API

```bash
dotnet run --project src/Backend/MyRecipeBook.Api/MyRecipeBook.Api.csproj
```

Swagger (Development): `https://localhost:7128/swagger`
