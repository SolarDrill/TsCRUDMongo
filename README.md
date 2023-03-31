### BackendAternaNet is a RESTful API built using ASP.NET Core for managing a table of characters for the AternaNet game. This project includes a controller for managing CRUD operations, a database context for interacting with the database, and a model for defining the structure of the character data.

## Prerequisites
.NET 7 SDK
Microsoft SQL Server

## Installation
Clone this repository.
Open the project in Visual Studio or Visual Studio Code.
In the appsettings.json file, replace the connection string with your own SQL Server connection string.
Open the Package Manager Console and run update-database to create the database and apply migrations.
Run the project.

### Usage
The API has endpoints for retrieving all characters, retrieving a character by id, retrieving a character by alter ego, creating a new character, updating a character, and deleting a character.

## Endpoints
GET /api/personaje
Retrieves all characters.

GET /api/personaje/{id}
Retrieves a character by id.

GET /api/personaje/{alte}
Retrieves a character by alter ego.

POST /api/personaje
Creates a new character.

PUT /api/personaje/{id}
Updates a character by id.

DELETE /api/personaje/{id}
Deletes a character by id.

