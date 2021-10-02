# real-time-chat-with-signalr
Simple real-time chat with .NET Core, ReactJS and SignalR


Create New Solution File
`dotnet new sln -n Chatty`

Create Web Api
`dotnet new webapi -o Chatty.Api`

Add csproj to the solution
`dotnet sln add ./Chatty.Api/Chatty.Api.csproj`

Update Https Certificate

`dotnet dev-certs https --clean`
`dotnet dev-certs https --trust`