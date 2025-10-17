# Open API Demo

This repository showcases how to setup an ASP .NET Core Web API project with
OpenAPI.

## Steps

### Setting up a new Dotnet Web API Project

Create a new directory for your project and navigate into it:

```bash
mkdir open-api-demo
cd open-api-demo
dotnet new webapi
```

The application exposes the OpenAPI documentation at:

```bash
http://localhost:5193/openapi/v1.json
```
