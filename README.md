
# ToDo List Web Application Backend

This is the backend for a ToDo list web application built using Django Rest Framework. This README provides an overview of the project, how to set it up, and some basic usage instructions.

## Table of Contents

- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)
- [Contributing](#contributing)
- [License](#license)

## Getting Started

### Prerequisites

Before you begin, make sure you have the following installed on your system:

- Python (version 3.9.13)
- Django (version 3.1.4)
- Django Rest Framework (version 3.11.1)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Evrz/ToDoList_Backend.git
2. Navigate to the project directory:
   ```bash
   cd ToDoList_Backend
3. Create a virtual environment and activate it (Recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate
4. Install the project dependencies:
    ```bash
   pip install -r requirements.txt
5. Apply database migrations:
   ```bash
   python manage.py migrate
6. Start the development server:
   ```bash
   python manage.py runserver
   ```
   Now your backend server should be up and running at http://localhost:8000/.

## Usage
To use this ToDo list backend, you can interact with it via API requests. You can use tools like curl or Postman to make HTTP requests to the API endpoints.

## API Endpoints
### The following API endpoints are available:

+ List all tasks: GET /api/tasks/
+ Create a new task: POST /api/tasks/
+ Retrieve a task: GET /api/tasks/<task_id>/
+ Update a task: PUT /api/tasks/<task_id>/
+ Delete a task: DELETE /api/tasks/<task_id>/
+ Please refer to the API documentation or code comments for more details on how to use these endpoints.

## Contributing
If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bugfix: git checkout -b feature-name.
3. Make your changes and commit them: git commit -m "Description of changes".
4. Push your changes to your fork: git push origin feature-name.
5. Create a pull request on the original repository.



