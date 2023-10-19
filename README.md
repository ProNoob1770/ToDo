# Todo APP
#### This project is a basic representation of the backend structure for an Todo application.
## Technologies Used
- Java
- Spring Boot
- Hibernate (JPA)
- MySQL (or any other database of your choice)
### Todo Model

The Todo Model represents the structure of a todo item. It includes the properties of a todo, such as its title, description, completion status, and creation date.

#### Todo Model Fields

- `id` (integer): Unique identifier for the todo.
- `title` (string): Title of the todo.
- `description` (string): Description of the todo.
- `completed` (boolean): Indicates whether the todo is completed.
- `createdDate` (string): Date and time when the todo was created
## API Endpoints
Here are the available API endpoints:

- GET todos: Get a list of all todos.
- GET todo/{id}: Get a single todo by ID.
- POST todos: Create a new todo.
- PUT todo/{id}: Update an existing todo.
- DELETE todo/{id}: Delete a todo by ID.
## Validation
The controller enforces validation rules for creating and updating todos. Validation includes checks for required fields, data types, and other constraints. Invalid requests will receive a 400 Bad Request response.
## Project Summary
- This Todo App is built using Spring Boot and Java.
- It allows users to perform CRUD operations.
- The project follows a structured architecture with controllers, services, and repositories.