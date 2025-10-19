# 📝 Django TODO App - Backend Exercise

A practical web development exercise focused on building a complete Django backend for a TODO application. The frontend templates are provided, allowing students to concentrate on models, views, forms, and Django architecture.

## 🎯 Learning Objectives

By completing this exercise, students will practice:

- Creating Django models with various field types
- Implementing CRUD operations (Create, Read, Update, Delete)
- Working with Django views (Function-Based or Class-Based)
- Handling forms and form validation
- Setting up URL routing
- Working with Django ORM for database operations
- Understanding the Django MVT (Model-View-Template) architecture

## 📋 Project Requirements

### Features to Implement

Your TODO app must support the following operations:

1. **Create a Task**
   - Title (required)
   - Description (optional)
   - Due Date (optional)
   - Due Time (optional)

2. **Display All Tasks**
   - List view with all tasks
   - Show completion status
   - Display task metadata

3. **Display Single Task**
   - Detailed view of individual task
   - Show all task information

4. **Update a Task**
   - Edit existing task details
   - Update completion status

5. **Delete a Task**
   - Remove task from database

6. **Mark Task as Complete/Incomplete**
   - Toggle completion status
   - Visual indication of completed tasks

## 🗂️ Project Structure

```
todo_project/
│
├── todo_app/
│   ├── migrations/
│   ├── templates/
│   │   ├── base.html
│   │   ├── task_list.html
│   │   ├── task_detail.html
│   │   └── task_form.html
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── models.py          # ← YOU IMPLEMENT THIS
│   ├── views.py           # ← YOU IMPLEMENT THIS
│   ├── forms.py           # ← YOU IMPLEMENT THIS
│   ├── urls.py            # ← YOU IMPLEMENT THIS
│   └── tests.py           # ← BONUS: Write tests
│
├── todo_project/
│   ├── __init__.py
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
│
├── manage.py
└── README.md
```

## 🚀 Getting Started

### Prerequisites

- Python 3.8+
- uv (Python package installer)
- Git
- GitHub account

### Getting the Project

1. **Fork this repository**
   - Click the "Fork" button at the top right of this repository
   - This creates a copy of the project in your GitHub account

2. **Clone your forked repository**
   ```bash
   git clone https://github.com/YOUR_USERNAME/student_todo_app.git
   cd student_todo_app
   ```
   Replace `YOUR_USERNAME` with your GitHub username and `student_todo_app` with the actual repository name.

### Installation

1. **Install uv** (if not already installed)
   ```bash
   # On macOS and Linux
   curl -LsSf https://astral.sh/uv/install.sh | sh

   # On Windows
   powershell -c "irm https://astral.sh/uv/install.ps1 | iex"
   ```

2. **Create a virtual environment with uv**
   ```bash
   uv venv
   ```

3. **Activate the virtual environment**
   - Windows:
     ```bash
     .venv\Scripts\activate
     ```
   - Mac/Linux:
     ```bash
     source .venv/bin/activate
     ```

4. **Install Django**
   ```bash
   uv add django
   ```

5. **Install Django**
   ```bash
   uv pip install django
   ```

6. **Create Django project** (if not already created)
   ```bash
   django-admin startproject todo_project .
   ```

6. **Create Django app**
   ```bash
   python manage.py startapp todo_app
   ```

7. **Add templates to the app**
   - Create a `templates` folder inside `todo_app`
   - Add the provided HTML files (base.html, task_list.html, task_detail.html, task_form.html)


## Resources

- https://docs.djangoproject.com/en/4.2/ref/templates/language/
- https://docs.djangoproject.com/en/4.2/topics/templates/
- https://docs.djangoproject.com/en/4.2/topics/forms/

## 🎉 Good Luck!

Remember: The goal is to learn Django architecture and best practices. Don't hesitate to experiment and try different approaches. Happy coding! 🚀
