# 💰 Expense Tracker

A simple and user-friendly **Expense Tracker Web Application** built using Python Flask and SQLite.

The application allows users to add, view, edit, delete, search, and filter their daily expenses. It also provides a dashboard with useful spending statistics.

---

## 📌 Features

- ➕ Add new expenses
- 👁️ View all expenses
- ✏️ Edit existing expenses
- 🗑️ Delete expenses
- 🔍 Search expenses
- 🏷️ Filter expenses by category
- 📈 Monthly spending trend chart (last 6 months)\n- 🥧 Category-wise doughnut/pie chart with amounts\n- 💡 Top spending category and average expense insights\n- 📊 View total spending
- 📅 View current month's spending
- 💰 View highest expense
- 📱 Responsive and user-friendly UI
- 💾 SQLite database for storing expenses

---

## 🛠️ Technologies Used

### Backend
- Python
- Flask
- Flask-SQLAlchemy
- SQLAlchemy

### Frontend
- HTML5
- CSS3
- Bootstrap 5
- Jinja2

### Database
- SQLite

---

## 📁 Project Structure

```text
ExpenseTracker/
│
├── app.py
├── requirements.txt
├── README.md
├── .gitignore
│
├── static/
│   └── css/
│       └── style.css
│
└── templates/
    ├── base.html
    ├── index.html
    ├── add_expense.html
    └── edit_expense.html# expense-tracker
