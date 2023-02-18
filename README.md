# .Net + Microsoft SQL Server + Angular 15 CRUD Application Example

# After completing this tutorial what we will build? 
We will build a full-stack web application that is a basic User Management Application with CRUD features: 

• Create User 

• List User 

• Update User 

• Delete User 

• View User

<img src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEjTYfm7flqG-rYemvKotqsuaHTXF6fuWHvlxfYGxxw_ZakYpwNDZrpevEPhrKFwrIz7ceL8yssdsYz9G7VcELNog-nMX2mA0KP8yEb3ua4tmWadzLdh9nueI3CGC3KDEJOi-H2U1BcM5PN3J8nA2jfxXEWEGUWgf7SdBSL7PzNhco2SFLUvcjxuUct5Mw/s1295/angulardotnetsqlcrud.png">


# Local Setup and Run the application

<h2>Create database and table</h2>

```CREATE DATABASE testdb;```

```
CREATE TABLE users (
  id              INT           NOT NULL    IDENTITY    PRIMARY KEY,
  first_name      VARCHAR(100)  NOT NULL,
  last_name       VARCHAR(100),
  email           VARCHAR(100)  NOT NULL,
);

```

<h2> Download or clone the source code from GitHub to the local machine</h2>

<h2> Backend</h2>

You can start the api by running ```dotnet run``` from the command line in the project root folder (where the WebApi.csproj file is located)

OR

You can also start the application in debug mode in Visual Studio by opening the project root folder in Visual Studio and pressing F5 or by selecting Debug -> Start Debugging from the top menu, running in debug mode.

<h2>Frontend</h2>

```npm install```

```ng serve```

<h2>From the browser call the endpoint http://localhost:4200</h2>
