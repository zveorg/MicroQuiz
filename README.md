# MicroQuiz
Quiz Application on microservices.

- **Important:** This project is still in progress and hasn't many of necessary things. They will be added in the future.

## What is MicroQuiz?

It's version of implementation of a simple quiz application on microservices with .Net Core, CQRS, Clean Architecture and almost DDD. 

## Architecture:

- Clean architecture with Clean Code and SOLID
- Domain Driven Design (without logic in models)
- Domain Command/Queries/Events
- CQRS (but one database)

## Technologies implemented:

- ASP.NET Core 3.0 (with .NET Core 3.0)
- ASP.NET WebApi Core
- ASP.NET Identity Core
- ASP.NET Identity Server
- Entity Framework Core 3.0
- Dapper (with Dommel)
- .NET Core Native DI
- AutoMapper
- MediatR
- Ocelot
- Consul
- RabbitMq
- Docker
- Docker Compose
- Angular 8
- Angular CLI
- CoreUI (with Bootstrap)

will be added soon:
- Swagger
- Logging
- Tests (yes, it's not about TDD :-) )
- ...

## Which repositories should I clone?

Please clone the following repositories and put them into the same working directory:

- [MicroQuiz](https://github.com/zveorg/MicroQuiz)
- [MicroQuiz.Api](https://github.com/zveorg/MicroQuiz.Api)
- [MicroQuiz.Services.Auth](https://github.com/zveorg/MicroQuiz.Services.Auth)
- [MicroQuiz.Services.Operations](https://github.com/zveorg/MicroQuiz.Services.Operations)
- [MicroQuiz.Services.Quizzes](https://github.com/zveorg/MicroQuiz.Services.Quizzes)
- [MicroQuiz.Admin](https://github.com/zveorg/MicroQuiz.Admin) - this repository could be anywhere

## Development Environment
- Visual Studio 2019 Community
- Visual Studio Code 1.40.1 
- .NET Core SDK 3.0.100
- Docker 19.03.5
- Docker Compose 1.24.1
- Node.js 12.11.0
- Angular 8.2.12
- NPM 6.12.0

## How to start the solution?

**1.** Clone/Fork/Download the all repositories from the previously mentioned list.

**2.** Install Docker for Windows and Docker Compose if necessary.

**3.** Install Node.js and Angular CLI if necessary.

**4.** Open the `MicroQuiz.sln` solution in Visual Studio 2019 and set `docker-compose` project as startup project. Run it.
  - **Important:** This must be running on http://localhost:5100

**5.** Open the folder `MicroQuiz.Admin\src\microquiz-admin\` in Visual Studio Code (by example). Run `npm install` and `ng serve` for starting a dev server.
  - **Important:** This must be running on http://localhost:4200

**6.** Point a browser to `http://localhost:4200` to access the Admin dashboard.

## Related projects

These are some other repos for related projects:

* [MicroQuiz](https://github.com/zveorg/MicroQuiz)
* [MicroQuiz.Admin](https://github.com/zveorg/MicroQuiz.Admin)
* [MicroQuiz.Api](https://github.com/zveorg/MicroQuiz.Api)
* [MicroQuiz.Services.Auth](https://github.com/zveorg/MicroQuiz.Services.Auth)
* [MicroQuiz.Services.Operations](https://github.com/zveorg/MicroQuiz.Services.Operations)
* [MicroQuiz.Services.Quizzes](https://github.com/zveorg/MicroQuiz.Services.Quizzes)
