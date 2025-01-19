This is a simple bootstrap project, demonstrating the use of the
`dotnet new` command.

The `.gitignore` file was created using `dotnet new gitignore`.

The `HelloWorld` project is a simple command-line application that
writes "Hello, World!" to the console. The `HelloWorld.sln` and project
were created using the following commands:

```shell
dotnet new sln --name HelloWorld --output HelloWorld
dotnet new console --name HelloWorld --output HelloWorld/HelloWorld
dotnet sln HelloWorld/HelloWorld.sln add HelloWorld/HelloWorld/HelloWorld.csproj
```
