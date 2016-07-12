# dotnetcore-todoapi
.NET Core v1 TODO Api example (Linux)

In order to start the API you'll need to do the following:

- cd into the src folder (src/TodoApi/)
- dotnet restore
- dotnet run

By default, this will start the API in port 5000, you can run this:

curl -XGET http://localhost:5000/api/todo

Here's the official link to expose this endpoint with nginx: https://docs.asp.net/en/latest/publishing/linuxproduction.html
