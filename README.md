# Task-Queue-Celery

This is Djnago webapp made using Celery to queue your tasks.

## How to use

1. Install "requirements.txt".
2. Run the command "python manage.py migrate".
3. Run the command "python manage.py shell".
4. Import the task from tasks.py.
5. Run the command "task_name.delay(x,y)".
6. Open another terminal and run the command "celery -A proj worker -l INFO"
