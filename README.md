
GHOSTMODE 🕵️‍♂️
GHOSTMODE is a web application designed as part of a Git and GitHub workflow project. It helps demonstrate web development fundamentals using Flask and SQLite, featuring a lightweight and modular design for building, testing, and scaling simple applications.

🚀 Features
User Authentication: Secure login and session handling (if implemented).

Activity Tracker: Basic functionality for tracking and managing entries (placeholder for feature expansion).

Database Integration: Uses SQLite for lightweight data management.

Modular Design: Built using Flask with clear separation of templates, static assets, and backend logic.

Development-Ready: Easily expandable for future features like user profiles, dynamic analytics, etc.

🛠 Technologies Used
Python (Flask): Backend logic and routing.

SQLite: Lightweight file-based database system.

HTML/CSS: Frontend templates and styling.

Bootstrap (optional): For responsive, mobile-friendly UI.

Jinja2: Flask’s built-in templating engine.

📦 How to Clone and Run the Project
1. Clone the Repository
bash
Copy
Edit
git clone https://github.com/manasa309/GHOSTMODE.git
cd GHOSTMODE
2. Set Up Virtual Environment (Recommended)
bash
Copy
Edit
python -m venv venv
# Activate:
# On Windows:
venv\Scripts\activate
# On macOS/Linux:
source venv/bin/activate
3. Install Dependencies
bash
Copy
Edit
pip install -r requirements.txt
4. Run Database Migrations (If Applicable)
bash
Copy
Edit
python manage.py db upgrade
Note: If not using Flask-Migrate, ensure db.sqlite3 exists or is created via your app logic.

5. Run the Flask Server
bash
Copy
Edit
python manage.py runserver
Or, if not using a custom manage.py, run:

bash
Copy
Edit
flask run
🌐 Access the Application
Once the server is running, open your browser and go to:

cpp
Copy
Edit
http://127.0.0.1:5000/
📁 Project Structure
php
Copy
Edit
GHOSTMODE/
├── static/          # CSS and other static files
│   └── css/
├── templates/       # HTML templates
├── tracker/         # (Optional) App logic, routes
├── venv/            # Virtual environment
├── db.sqlite3       # SQLite database
├── manage.py        # Flask app runner
└── requirements.txt # Project dependencies
