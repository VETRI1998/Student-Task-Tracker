# 🎓 Student Task Tracker

A simple web app for students to track tasks using Django, MySQL, and Bootstrap.

## 💻 Tech Stack
- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Python, Django
- **Database**: MySQL

## 🧩 Features
- Student registration & login
- Add daily tasks with title & description
- Mark tasks as complete/incomplete
- Delete tasks
- Secure authentication system

## 🛠️ How to Run
1. Clone this repo
2. Set up virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # or venv\Scripts\activate (Windows)
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
4. Create MySQL DB named student_tracker
5. Configure settings.py with MySQL credentials
6. Run migrations:
    ```bash
    python manage.py makemigrations
    python manage.py migrate
7. Start server:
    ```bash
    python manage.py runserver

  
