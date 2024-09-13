RealWorld Example App
ASP.NET Core codebase containing real world examples (CRUD, auth, advanced patterns, etc) that adheres to the RealWorld spec and API.

RealWorld
This codebase was created to demonstrate a fully fledged fullstack application built with ASP.NET Core (with Feature orientation) including CRUD operations, authentication, routing, pagination, and more.

We've gone to great lengths to adhere to the ASP.NET Core community styleguides & best practices.

For more information on how to this works with other frontends/backends, head over to the RealWorld repo.

How it works
This is using ASP.NET Core with:

CQRS and MediatR
Simplifying Development and Separating Concerns with MediatR
CQRS with MediatR and AutoMapper
Thin Controllers with CQRS and MediatR
AutoMapper
Fluent Validation
Feature folders and vertical slices
Entity Framework Core on SQLite for demo purposes. Can easily be anything else EF Core supports. Open to porting to other ORMs/DBs.
Built-in Swagger via Swashbuckle.AspNetCore
Bullseye for building!
JWT authentication using ASP.NET Core JWT Bearer Authentication.
Use dotnet-format for style checking
.editorconfig to enforce some usage patterns
This basic architecture is based on this reference architecture: https://github.com/jbogard/ContosoUniversityCore

Getting started
Install the .NET Core SDK and lots of documentation: https://www.microsoft.com/net/download/core

Documentation for ASP.NET Core: https://docs.microsoft.com/en-us/aspnet/core/

Docker Build
There is a 'Makefile' for OS X and Linux:

make build executes docker-compose build
make run executes docker-compose up
The above might work for Docker on Windows

Local building
It's just another C# file! dotnet run -p build/build.csproj
Swagger URL
http://localhost:5000/swagger
GitHub Actions build
Build and Test
