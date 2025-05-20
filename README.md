
## ✈️ CS50W Airline Project

A Django web application built as part of the CS50 Web Programming with Python and JavaScript course. The project simulates a basic airline booking system where users can log in, view flights, and book seats as passengers.

---

### 📌 Features

* View available flights (origin → destination)
* View flight details including passengers
* Book passengers onto flights
* User login and logout system
* Admin panel to manage airports, flights, and passengers

---

### 🛠️ Technologies Used

* **Python 3**
* **Django 5.2.1**
* **SQLite** (default database)
* HTML, CSS (basic templates)
* Django admin panel

---

### 🚀 How to Run Locally

1. **Clone the repository**:

   ```bash
   git clone https://github.com/YOUR_USERNAME/cs50w-airline.git
   cd cs50w-airline
   ```

2. **(Optional) Create virtual environment**:

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**:

   ```bash
   pip install -r requirements.txt
   ```

   If you don't have `requirements.txt`, install manually:

   ```bash
   pip install django
   ```

4. **Apply migrations**:

   ```bash
   python manage.py migrate
   ```

5. **Create a superuser (admin account)**:

   ```bash
   python manage.py createsuperuser
   ```

6. **Run the server**:

   ```bash
   python manage.py runserver
   ```

7. Open your browser and go to:
   [http://127.0.0.1:8000/](http://127.0.0.1:8000/)

---

### 👩‍💻 Admin Panel

* URL: [http://127.0.0.1:8000/admin/](http://127.0.0.1:8000/admin/)
* Use your superuser credentials
* You can add:

  * Airports
  * Flights (with duration and destination)
  * Passengers (and assign them to flights)

---

### 📂 Project Structure

```
airline/
├── flights/             # Flight-related models, views, templates
├── users/               # Login, logout, user pages
├── templates/           # Shared templates
├── db.sqlite3           # Database
├── manage.py            # Django CLI entry point
└── requirements.txt     # (optional) Python dependencies
```

---

### ✅ Status

✔️ Fully working local Django project
✔️ Matches CS50W Lecture 4 content
🧪 Can be extended with unit tests, user registration, seat limit, etc.

---

### 👤 Author

Created by **Nataliia Petrychuk** as part of the [CS50W](https://cs50.harvard.edu/web/) course
📍 Sydney, Australia
✉️ [nataliia.petrychuk@gmail.com](mailto:nataliia.petrychuk@gmail.com)



