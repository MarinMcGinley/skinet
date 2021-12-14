To run: Inside API:  `dotnet watch run`

Create a new project: Inside root: `dotnet new classlib -o [Project name]`

Add csproj file to project: `dotnet sln add [Project name]`

Inside API folder: `dotnet add reference ../Infrastructure`

Inside Infrastructure folder: `dotnet add reference ../Core`

Inside root folder register references to solution. If you have moved dependencies around: `dotnet restore`

Build project: `dotnet build`

Drop database in root: `dotnet ef database drop -p Infrastructure -s API`

Remove migrations in root: `dotnet ef migrations remove -p Infrastructure -s API`

Add migration in root: `dotnet ef migrations add InitiaCreate -p Infrastructure -s API -o Data/Migrations`

Suggestions: `.` + `control`

If Omnisharp stops suggesting: `https://stackoverflow.com/questions/29975152/intellisense-not-automatically-working-vscode`

Open a database: `command` + `shift` + `P` -> SQLite: Open database

Format on mac: `option` + `shift` + `F`