# ToDo Project

This is a simple ToDo web application built using Python and Django.

## Features

- View a list of tasks
- Add new tasks
- Edit existing tasks
- Delete tasks

## Getting Started

### Prerequisites

- Python 3.x
- Django

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/dnazirzhanov/Neobis_ToDo_Project.git
    ```

2. Navigate to the project directory:

    ```bash
    cd Neobis_ToDo_Project
    ```

3. Create a virtual environment (optional but recommended):

    ```bash
    python -m venv venv
    ```

4. Activate the virtual environment:

    - On Windows:

        ```bash
        .\venv\Scripts\activate
        ```

    - On macOS/Linux:

        ```bash
        source venv/bin/activate
        ```


5. Apply database migrations:

    ```bash
    python manage.py migrate
    ```

6. Run the development server:

    ```bash
    python manage.py runserver
    ```

7. Access the application at [http://127.0.0.1:8000/](http://127.0.0.1:8000/)

## Usage

1. View the list of tasks at the homepage.
2. Add new tasks by clicking the "Add new task" button.
3. Edit tasks using the "Edit" button next to each task.
4. Delete tasks using the "Delete" button next to each task.

