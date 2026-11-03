# 💰 Expense Tracker

A personal expense tracking web application built using **Flask and SQLite** to help users manage their daily expenses, monitor spending, and understand their financial habits.

## ✨ Features

- User registration and login authentication
- Secure password hashing
- Add, edit, view, and delete expenses
- Categorize expenses
- Search expenses by description
- Filter expenses by category
- Dashboard with expense summaries
- Category-wise spending visualization
- Monthly expense tracking
- Current month vs previous month comparison
- Responsive and user-friendly interface

## 🛠️ Technologies Used

- **Python**
- **Flask**
- **Flask-SQLAlchemy**
- **SQLite**
- **Flask-WTF**
- **HTML5**
- **CSS3**
- **JavaScript**
- **Chart.js**

## 📂 Project Structure

```text
expense-tracker/
│
├── app.py
├── forms.py
├── create_tables.py
├── requirements.txt
├── .gitignore
│
├── instance/
│   └── expenses.db
│
├── static/
│   ├── css/
│   │   └── style.css
│   └── js/
│       └── main.js
│
└── templates/
    ├── base.html
    ├── home.html
    ├── dashboard.html
    ├── login.html
    ├── register.html
    ├── expenses.html
    ├── add_expense.html
    ├── edit_expense.html
    └── single_expense.html
```

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/duwandcunha/expense-tracker.git
```

### 2. Navigate to the project directory

```bash
cd expense-tracker
```

### 3. Create a virtual environment

```bash
python -m venv venv
```

### 4. Activate the virtual environment

For Windows PowerShell:

```powershell
.\venv\Scripts\Activate.ps1
```

### 5. Install dependencies

```bash
pip install -r requirements.txt
```

### 6. Run the application

```bash
python app.py
```

Open your browser and visit:

```text
http://127.0.0.1:5000
```

## 📌 Purpose

This project was developed to practice Flask web development, database integration, authentication, and building a complete web application with a functional user interface.

## 👩‍💻 Author

**Duwan Judith Dcunha**

GitHub: [@duwandcunha](https://github.com/duwandcunha)

---

⭐ If you find this project interesting, feel free to explore the repository!
