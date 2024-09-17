# Todo Application

## Description

This is a Todo application built using the Fiber web framework in Go. It provides basic CRUD operations for managing todos.

## Features

- List all todos
- Create a new todo
- Update an existing todo
- Delete a todo

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/Jordilla08/tasks.git
   ```
2. Navigate to the project directory:
   ```sh
   cd todo-app
   ```
3. Install the dependencies:
   ```sh
   go get
   ```

## Usage

1. Set the environment variable for the port:
   ```sh
   export PORT=3000
   ```
   or on Windows:
   ```sh
   set PORT=3000
   ```
2. Run the application:
   ```sh
   go run main.go
   ```

## API Endpoints

- `GET /todos` - Retrieve all todos
- `POST /todos` - Create a new todo
- `PUT /todos/:id` - Update an existing todo
- `DELETE /todos/:id` - Delete a todo

## Contributing

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a pull request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgements

- [Fiber](https://gofiber.io/) - The web framework used
- [Go](https://golang.org/) - The programming language used
