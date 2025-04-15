# Library Management System

## Overview

The Library Management System is a Django-based web application designed for the efficient management of an online library. It allows administrators to manage authors, books, and borrow records with features such as user registration, pagination, and Excel data export. The application includes a clean and intuitive admin interface for managing the library resources, providing a seamless user experience.

---

## 🚀 Features

- *Dashboard*: Provides an overview page with motivational quotes, library statistics, and easy navigation.
- *Author Management*: Add, update, delete, and list authors with full CRUD functionality.
- *Book Management*: Manage the library's books by adding, updating, deleting, and listing them.
- *Borrow Record Management*: Add, update, delete, and list borrow records, including tracking borrow and return dates.
- *Export to Excel*: Export authors, books, and borrow records to Excel for data management and reporting.
- *Pagination*: Efficiently manage large datasets with easy-to-use pagination.
- *User Registration*: Allows admins to create accounts to manage the library.
- *Custom Template Filters*: Includes custom template filters for better form styling and UI enhancements.
- *Responsive Design*: Built with Bootstrap, the system is fully responsive and works well on mobile devices.

---

## 📊 Requirements

Ensure that your system meets the following prerequisites before setting up the project:

- *Python*: 3.8 or higher
- *Django*: 5.1.4
- *openpyxl*: For exporting data to Excel.
- *xlwt*: For older Excel file formats.

---

## 📖 Installation

Follow these steps to set up the project locally:

### Step 1: Clone the Repository

Clone the project repository using Git:

```bash
git clone https://github.com/Devilgaurav123/Hackerkernel
cd LiberaryManagement
```

### Step 2: Set Up a Virtual Environment 

python3 -m venv venv

### Step 3: Install Dependencies
pip install -r requirements.txt


### step 4 : Set Up the Database

python manage.py migrate

### Step 5: Create a Superuser
py manage.py createsuperuser

### Step 6: Run the Development Server

py manage.py runserver

### 📂 Project Structure
```bash
library/
├── library/
│   ├── _init_.py
│   ├── asgi.py
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
├── manager/
│   ├── migrations/
│   ├── templatetags/
│   │   ├── _init_.py
│   │   └── form_filters.py
│   ├── _init_.py
│   ├── admin.py
│   ├── apps.py
│   ├── forms.py
│   ├── models.py
│   ├── tests.py
│   ├── views.py
│   └── urls.py
├── templates/
│   └── manager/
│       ├── add_author.html
│       ├── add_book.html
│       ├── add_borrow.html
│       ├── author_confirm_delete.html
│       ├── author_form.html
│       ├── author_list.html
│       ├── base.html
│       ├── book_confirm_delete.html
│       ├── book_form.html
│       ├── book_list.html
│       ├── borrow_form.html
│       ├── borrow_list.html
│       ├── borrowrecord_confirm_delete.html
│       ├── dashboard.html
│       ├── edit_author.html
│       ├── edit_book.html
│       ├── edit_borrow.html
│       ├── pagination.html
│       └── register.html
├── static/css/style.css
├── db.sqlite3
├── manage.py
├── requirements.txt
└── README.md
```


✉ License

This project is licensed under the MIT License. See the LICENSE file for more details.
