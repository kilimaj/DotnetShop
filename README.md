# Creating the project

- Simply install the dotnet core from [microsoft](https://dotnet.microsoft.com/en-us/)
- Then download vscode
  - Extensions to be installed
    - Material Icon Theme
    - C# by Microsoft
    - C# Extensions by JosKreativ
    - SQLite by alexcvzz
- Install postman from [postman](https://www.postman.com/)

## API setup

- Create an empty folder or clone an empty repo
- go to commandline check if dotnet is properly installed by typing

```cmd
dotnet --info
```

- To check for available commands do

```cmd
dotnet -h
```

- and available options for new type

```cmd
dotnet new list
```

- To create a dotnet gitignore file type

```cmd
dotnet new gitignore
```

- To create a new solution file

```cmd
dotnet new sln
```

- Then create a new api dotnet core project

```cmd
dotnet new webapi -n API
```

- Add the project to solutions file

```cmd
dotnet sln add API
```

- And lastly to see all available projects in solutions file

```cmd
dotnet sln list
```
