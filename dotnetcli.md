# DotNet CLI

More details can be found on (docs.microsoft.com)[https://docs.microsoft.com/en-us/dotnet/core/tools/]

Below is a list of the most commonly used commands:

```sh
# cd to the directory you want the solution file in

# add a gitignore file
dotnet new gitignore

# create a new solution
dotnet new sln

# create a project and add it to the sln
dotnet new project_template -o project_name
dotnet sln add project_name

# build all projects in the solution
dotnet build
# for project
dotnet build project_name

# Run a project
dotnet run project_name

# get all dependencies for the solution
dotnet restore
# for project
dotnet restore project_name

# run unit tests for solution
dotnet test
# for project
dotnet test project_name

# publish a solution to a folder for deployment
dotnet publish
# for project
dotnet publish project_name

# adding a razorcomponent
# name must start with a capital letter
dotnet new razorcomponent -n name -o Pages


# rnning in watch mode
dotnet watch run
```