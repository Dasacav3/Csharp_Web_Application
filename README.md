# Dotnet MVC Application

This is a example to learn about dotnet and start to build full stack apps with this great technology

# Features
- Dotnet 6.0
- C# 10
- MVC App
- Docker

# How to run

You can use Docker to run the app. Only you need run the next command (it's necessary that you have docker installed)

`
docker build --tag dotenv-mvc-app .
docker run --publish 49153:80 --name dotenv-app dotenv-mvc-app
`