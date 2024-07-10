Todo Application with Django This project is a simple Todo application built using Django. It allows users to create, update, delete, and mark tasks as completed.

Features User authentication and authorization. CRUD operations for managing tasks. Mark tasks as completed. Filter tasks by status (completed/incomplete). Prerequisites Python 3.x installed on your system. Pipenv installed globally (pip install pipenv) or any other preferred virtual environment tool. Installation Clone the repository:

Setup virtual environment:

bash Copy code pipenv install pipenv shell Install dependencies:

bash Copy code pipenv install django pipenv install psycopg2-binary # For PostgreSQL database (optional) Apply database migrations:

bash Copy code python manage.py migrate Create a superuser (admin account):

bash Copy code python manage.py createsuperuser Run the development server:

bash Copy code python manage.py runserver Access the application: Open your web browser and go to http://localhost:8000

Usage Login: Use the admin account created in step 5 or register a new user. Create Tasks: Click on "Add Task" to create new tasks. Update Tasks: Click on a task to edit or update its details. Mark as Completed: Check the checkbox next to a task to mark it as completed. Delete Tasks: Click on the delete button to remove tasks. Contributing Contributions are welcome! Please fork the repository and create a pull request with your improvements.

License This project is licensed under the MIT License - see the LICENSE file for details.
