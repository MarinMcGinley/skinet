To run: Inside API:  `dotnet watch run`

Create a new project: Inside root: dotnet new classlib -o [Project name]

Add csproj file to project: dotnet sln add [Project name]

Inside API folder: dotnet add reference ../Infrastructure

Inside Infrastructure folder: dotnet add reference ../Core

Inside root folder register references to solution. If you have moved dependencies around: dotnet restore

Build project: dotnet build
