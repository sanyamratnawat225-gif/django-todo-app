README.md
# Django TODO App

A simple and user-friendly TODO application built with Django.

## Features

* Create tasks
* View all tasks
* Edit tasks
* Delete tasks
* Mark tasks as completed/uncompleted
* Tasks are ordered by creation date

## Tech Stack

* Python
* Django
* HTML
* CSS
* SQLite

## Project Structure

```text
todoproject/
├── manage.py
├── todo/
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   └── templates/
│       └── todo/
├── todoproject/
│   ├── settings.py
│   └── urls.py
└── README.md
```

## How to Run

### 1. Clone the repository

```bash
git clone git@github.com:sanyamratnawat225-gif/django-todo-app.git
cd django-todo-app
```

### 2. Create a virtual environment

```bash
python -m venv venv
```

### 3. Activate the virtual environment

Windows:

```powershell
venv\Scripts\activate
```

### 4. Install Django

```bash
pip install django
```

### 5. Run migrations

```bash
python manage.py migrate
```

### 6. Start the development server

```bash
python manage.py runserver
```

Open:

```text
http://127.0.0.1:8000/
```

## Future Improvements

* User authentication
* Due dates and reminders
* Task priorities
* Search and filtering
* Responsive UI
