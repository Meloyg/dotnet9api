# Dotnet 9 Web Api

## Description
This is a simple web API built with .NET 9. It serves as a template for creating RESTful services. The API is designed to be easy to use and extend, making it suitable for various applications.

- Clean architecture

## How to run

1. use db.sql to initialize the database

﻿To check the installed Entity Framework (EF) versions on your machine, you can use the following steps:

Open a command prompt (cmd) or PowerShell window.
Use the following command to list all installed EF packages for all .NET Core/.NET projects on your machine:

To install latest EF use
dotnet tool install --global dotnet-ef

To un install
dotnet tool uninstall --global dotnet-ef

*********************************

To Scaffold database as model to local project use below cmd.


use this for locally installed SQL Express Dev DB
dotnet ef dbcontext scaffold "Server=localhost\SQLEXPRESS;Initial Catalog=SmartCertify;Integrated Security=SSPI; MultipleActiveResultSets=true;TrustServerCertificate=True;" Microsoft.EntityFrameworkCore.SqlServer -o Entities -d

### API Endpoints

once you run the project, you can view the API endpoints in the browser at: http://localhost:5065/scalar/v1