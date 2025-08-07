# TaskMaster

A simple task management app using Django.

## Features
- User registration/login
- Task CRUD with priority & completion filter
- Bootstrap UI
- Overdue task highlighting
- Message feedback

## Setup Instructions

```bash
git clone https://github.com/sojibhasan5800/TaskMaster_Assignment.git
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
