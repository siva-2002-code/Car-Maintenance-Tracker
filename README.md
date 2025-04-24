Project Name: 

Car Maintenance Tracker 

Description, Purpose, and Value: 

The Car Maintenance Tracker is a web application designed to help vehicle owners manage and track essential aspects of car care. It enables users to log and monitor their vehicle's maintenance history, including details about service types, costs, and dates. The platform also allows users to record fuel consumption, track mileage, and set reminders for car washes based on usage intervals. By providing detailed reports on maintenance expenses, fuel costs, and fuel efficiency, the application offers valuable insights that help users make informed decisions about vehicle maintenance and budgeting. The app aims to simplify car maintenance tasks, ensuring that users stay on top of their vehicle’s needs and optimize their overall vehicle management. 

Technologies Used: 

The application is built with Flask, a micro web framework, and utilizes Flask-SQLAlchemy for database interaction. Flask-Login is used for managing user authentication and sessions. The frontend is developed using HTML, CSS, and JavaScript, while the database is powered by SQLite, a lightweight, serverless database. The app also leverages Werkzeug for secure password hashing and Jinja2 for dynamic HTML rendering. For exporting service history, the app provides a CSV download functionality. 

Setup Instructions: 

Ensure Python is installed on your system, if Python is not yet installed, you can download it from the official site: https://www.python.org/downloads/. 

To verify if Python is already installed, run the following command in your terminal or command prompt: 

python --version 

Next to get started with the Car Maintenance Tracker, first clone the repository from GitHub: 

git clone https://github.com/siva-2002-code/Car-Maintenance-Tracker 

And then navigate into the project directory: 

cd Car-Maintenance-Tracker

cd src 

Now installing the required dependencies using: 

pip install -r requirements.txt 

Once the dependencies are set up, start the Flask application with: 

python app.py 

And the app will be available locally at: 

http://127.0.0.1:5000 

Now users can then register an account, log in, and begin adding vehicles, logging maintenance and fuel records, and tracking other vehicle-related activities. 

YouTube Video Link:
