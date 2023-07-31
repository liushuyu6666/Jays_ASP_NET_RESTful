# Overview
ASP.NET has primarily two types of web APIs: RESTful APIs and Minimal APIs. This is based on RESTful APIs.

# Start

1. .NET Environment Setup: Install `dotnet-sdk` instead of `dotnet`.
2. Initialize the project:
   1. Create a new folder for your project.
   2. Navigate to the newly created folder using the command line or terminal.
   3. Check the installed .NET SDK versions with `dotnet --list-sdks`.
   4. Create a basic web API project with controllers using the latest .NET version (e.g., .NET 6) by running:
        ```shell
        dotnet new webapi -f net6.0
        ```
   5. Generate a default .gitignore file for version control:
        ```shell
        dotnet new gitignore
        ```
3. To build and run the project, use `dotnet build` and `dotnet run`, respectively.