# Todo List API

## Task Overview

Your task is to create a RESTful API for a todo list application. This API will allow users to manage their todo items.

## Setup

1. Clone this repository.
2. Run `composer install` to install the project dependencies.
3. Copy `.env.example` to `.env` and configure your environment settings, including the database connection.
4. Run `php artisan key:generate` to generate the application key.
5. Setup your database and run `php artisan migrate` to create the tables.

## Requirements

1. **Database Models and Migrations:**
   - Create migrations and models for `Todo` items. Each todo should have an `id`, `title`, `description`, `due_date`, and `status`.

2. **API Endpoints:**
   - Implement routes and controllers for the following actions:
     - Registering and authenticating users.
     - CRUD operations for todo items for authenticated users.

3. **Authentication:**
   - Use Laravel Sanctum for API token authentication.

## Submission Instructions

1. Make sure the application runs correctly and all endpoints function as expected.
2. Push your code to a new branch named after your name (e.g., `feature/jane-doe`).
3. Create a pull request against the `main` branch with a summary of your work.

## Evaluation Criteria

- Functionality: All specified endpoints should be implemented and working.
- Code Quality: Your code should be clean, well-commented, and follow Laravel best practices.
- Security: Apply best practices to ensure the API is secure.
- Documentation: Include clear instructions on how to set up and test your application.

Best of luck!