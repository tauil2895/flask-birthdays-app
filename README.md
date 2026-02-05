# Flask Birthdays App

[![Python](https://img.shields.io/badge/python-3.11-blue?logo=python&logoColor=white)](https://www.python.org/)  
[![Flask](https://img.shields.io/badge/Flask-2.3.6-orange?logo=flask&logoColor=white)](https://flask.palletsprojects.com/)  

A simple **Flask web application** to track birthdays. Users can add names and birthdays, and view all entries in a clean, user-friendly interface. Inspired by **CS50’s “Birthdays” problem set**.  

---

## 🔹 Features

- Add a person's name and birthday.
- View all birthdays in a table.
- Simple, responsive UI with CSS.
- Uses **SQLite** database via **CS50 Python Library**.
- Fully local and lightweight (no heavy frameworks required).

---

## 📁 Project Structure

flask-birthdays-app/
├── app.py # Main Flask application

├── README.md

├── static/

│ ├── styles.css

│ └── images/

└── templates/

└── index.html

---

## Installation

1. Clone the repository:

bash
git clone https://github.com/tauil2895/flask-birthdays-app.git
cd flask-birthdays-app

2. Install dependencies:

pip install -r requirements.txt

3. Run the application:

python app.py

4. Open your browser and go to the right location

## Usage

1. Enter a name, month, and day in the form.
2. Click Add Birthday.
3. See all added birthdays appear in the table below.

---

## 📸 Screenshots & Page Descriptions

### 1️⃣ Index Page (Dashboard)
- **Description:** Shows a form to add new birthdays and a table listing all birthdays.  
- **Screenshot:**  
![Login Page](statics/images/add-birthday.png)

### 2️⃣ Birthday Table
- **Description:** Lists all added birthdays in a simple table. Can be expanded with future features like sorting or deleting.  
- **Screenshot:**  
![Birthday Table](statics/images/birthday-table.png)

