# 💻 Cyber Hacking Breaches – Django Project

This is a Django-based web application built to analyze and manage cyber hacking breach data. The project may also include automation or desktop-related functionality using the Windows API (via `pywin32`), as seen in the `hello.py` script.

---

## 🚀 Features

- ✅ Django 3.x+ web framework
- ✅ MySQL or SQLite3 backend support
- ✅ Web interface for managing breach data
- ✅ Background image support with static assets
- ✅ Screenshot auto for Windows apps (Calculator) using Win32 API (`hello.py`)

## 🧰 Project Structure
Cyber_Hacking_Breaches/
├── manage.py
├── hello.py # Separate Win32 automation script
├── Cyber_Users/ # Django app with models/views/templates
├── assets/static/ # Static images (backgrounds)
├── templates/ # HTML templates
├── db.sqlite3 # Optional SQLite database
└── requirements.txt # Python dependencies

## 🛠 Installation

### 1. Clone the Repository

bash
git clone https://github.com/ManikantaReddy-13/cyber-hacking-breaches.git
cd cyber-hacking-breaches

### 2. Create and Activate Virtual Environment

python -m venv venv
source venv/Scripts/activate

### 3. Install Requirements

pip install -r requirements.txt

### 4. Apply Migrations

python manage.py makemigrations
python manage.py migrate

### 5. Run the Server

python manage.py runserver

Open your browser at: http://127.0.0.1:8000

⚙️ Optional – Run hello.py

python hello.py
This script uses Win32 API to screenshot the Calculator window. Make sure Calculator is open before running.

🛑 Requirements
Python 3.10 or 3.11 (avoid 3.13 for now)

pip

Git

MySQL (if using MySQL DB instead of SQLite)

🧪 Testing
You can add unit tests inside the app's tests/ folder and run them with:

python manage.py test

👨‍💻 Author
Manikanta Reddy
