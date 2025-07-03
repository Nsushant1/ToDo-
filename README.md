# ToDo List Application (PHP)

A simple ToDo List web application built with PHP that supports full CRUD (Create, Read, Update, Delete) operations.

## Features

- Add new tasks
- View all tasks
- Edit existing tasks
- Delete tasks
- Mark tasks as completed

## Requirements

- PHP 7.x or higher
- MySQL/MariaDB
- Web server (e.g., Apache, XAMPP)

## Installation

1. **Clone the repository:**
    ```bash
    git clone https://github.com/yourusername/todolist.git
    ```
2. **Import the database:**
    - Import `todo_list.sql` into your MySQL server.

3. **Configure database connection:**
    - Edit `config.php` with your database credentials.

4. **Run the application:**
    - Place the project in your web server's root directory.
    - Access via `http://localhost/todolist/`

## Usage

- **Add Task:** Fill the form and submit to add a new task.
- **Edit Task:** Click the edit button next to a task to update it.
- **Delete Task:** Click the delete button to remove a task.
- **Mark as Completed:** Click the checkbox to mark a task as done.

## Folder Structure

```
/todolist
  |-- index.php
  |-- add.php
  |-- edit.php
  |-- delete.php
  |-- config.php
  |-- todo_list.sql
  |-- README.md
```

## License

This project is open-source and available under the MIT License.
