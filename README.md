# Convertoo Backend Coding Test

> Congratulation on making it to the coding test section of the interview process, this coding test will consist of showing your skills in creating a simple CRUD REST api for TODO tasks.

## API Endpoints

The API should provide the following endpoints:

* GET /api/todos: Retrieve a list of all todos.
* GET /api/todos/{id}: Retrieve a single todo by ID.
* POST /api/todos: Create a new todo.
* PUT /api/todos/{id}: Update an existing todo by ID.
* DELETE /api/todos/{id}: Delete a todo by ID.

The GET endpoints should return a JSON response containing the requested todo or todos. The POST and PUT endpoints should accept a JSON payload containing the todo data in the request body. The DELETE endpoint should return a 204 No Content response on success.

## Todo Data Structure

Each todo should have the following fields:

* `id`: A unique identifier for the todo.
* `title`: A short description of the todo.
* `completed`: A boolean value indicating whether the todo has been completed.
* `created_at`: The date and time the todo was created.
* `updated_at`: The date and time the todo was last updated.

## Additional Requirements

In addition to the basic CRUD functionality, there are a few additional requirements for this project:

* The API should support pagination and filtering of the todo list.
* The POST and PUT endpoints should validate the input data to ensure that the title field is not empty.
* The PUT endpoint should return a 404 Not Found response if the requested todo does not exist.

## Conclusion

That's it! You now have all the information you need to complete the Laravel Todo CRUD REST API coding test. Good luck!