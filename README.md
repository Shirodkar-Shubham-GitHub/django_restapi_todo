# To-Do List Application

This is a simple To-Do List application built using Django REST Framework. It supports basic CRUD (Create, Read, Update, Delete) operations, with APIs implemented using Django REST Framework's generic views.

## Features

- **Create To-Do**: Add a new to-do item.
- **Read To-Do**: Retrieve the list of all to-do items or a single item.
- **Update To-Do**: Edit the details of an existing to-do item.
- **Delete To-Do**: Remove a to-do item from the list.

## API Endpoints

### 1. List and Create To-Do
- **Endpoint**: `/api/tasks/`
- **Methods**: 
  - `GET`: List all to-do items.
  - `POST`: Create a new to-do item.
  
### 2. Retrieve, Update, and Delete To-Do
- **Endpoint**: `/api/tasks/<id>/`
- **Methods**: 
  - `GET`: Retrieve a specific to-do item by ID.
  - `PUT`: Update an existing to-do item by ID.
  - `DELETE`: Delete a to-do item by ID.

## Installation and Setup

1. Clone the repository:
    ```sh
    git clone https://github.com/Shirodkar-Shubham-GitHub/django_restapi_todo
    cd api_todo-list
    ```

2. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

3. Run the migrations:
    ```sh
    python manage.py migrate
    ```

4. Start the development server:
    ```sh
    python manage.py runserver
    ```

5. The API is now accessible at `http://127.0.0.1:8000/api/tasks/`.

## User Interface Endpoints

1. The API is now accessible at `http://127.0.0.1:8000/`.


## Technologies Used

- JavaScript
- Django
- Django REST Framework
- MySQL

## License

This project is licensed under the MIT License.

## Author

- Shubham Ashok Shirodkar (shubhamshirodkar90@gmail.com)
- [My GitHub Profile](https://github.com/Shirodkar-Shubham-GitHub)
