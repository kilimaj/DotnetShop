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

```zsh
dotnet --info
```

- To check for available commands do

```zsh
dotnet -h
```

- and available options for new type

```zsh
dotnet new list
```

- To create a dotnet gitignore file type

```zsh
dotnet new gitignore
```

- To create a new solution file

```zsh
dotnet new sln
```

- Then create a new api dotnet core project

```zsh
dotnet new webapi -n API
```

- Add the project to solutions file

```zsh
dotnet sln add API
```

- And lastly to see all available projects in solutions file

```zsh
dotnet sln list
```

## Running the app using dotnet run

- Go to terminal and type

```zsh
cd API
```

```zsh
dotnet run
```

- Then go to postman and GET request to https://localhost:5001/WeatherForecast
- Incase does not show then it may be an issue with cwertificate
  - First make sure that in postman preferences SSL certificate verification should be off
  - Then check the dev certificate if present

```zsh
  dotnet dev-certs https
```

- Second can use the following commands to refresh certificate, point to note may require password for priviledge issues.

```zsh
  dotnet dev-certs https --clean
```

```zsh
  dotnet dev-certs https --trust
```
