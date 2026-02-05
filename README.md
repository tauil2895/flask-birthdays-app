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
git clone https://github.com/your-username/flask-birthdays-app.git
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
- **Description:** Users can browse featured products and navigate the store.
- **Screenshot:**  
![Index Page](static/images/index.png)  

### 2️⃣ Product Page
- **Description:** Each product shows image, price, and “Add to Cart” button.  
- **Screenshot:**  
![Product Page](static/images/product_index.png)

### 3️⃣ Shopping cart
- **Description:** Users can update quantities or remove items before checkout. 
- **Screenshot:**  
![Shopping cart](static/images/shopping-cart.png)

### 4️⃣ Checkout
- **Description:** Users can review their order and place it securely.
- **Screenshot:**  
![Checkout](static/images/checkout.png)  

### 5️⃣ Admin Dashboard
- **Description:** Admins can add/update new users, manage roles, and view users.
- **Also:** Admins can add/update products, manage categories, and view orders.
- **Screenshot:**  
![Admin Dashboard](static/screenshots/admin_users.png)  

