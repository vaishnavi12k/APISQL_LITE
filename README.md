# APISQL_LITE
# 🍹 Drinks API (Django REST Framework)

A simple REST API built using Django and Django REST Framework to manage drinks data. This project demonstrates CRUD operations, serializers, and API views.

---

## 🚀 Features

- Create, Read, Update, Delete (CRUD) operations
- RESTful API design
- SQLite database
- Django Admin panel
- Organized app structure (drinks app)

---

## 🛠️ Tech Stack

- Python
- Django
- Django REST Framework
- SQLite

---

## 📁 Project Structure

APIRD/
│── APIRD/                # Main project settings  
│── drinks/               # App containing API logic  
│   ├── models.py         # Database models  
│   ├── serializers.py    # Data serialization  
│   ├── views.py          # API views  
│── db.sqlite3            # Database  
│── manage.py             # Django management script  

---

## ⚙️ Installation & Setup

### 1. Clone the repository
git clone <your-repo-link>  
cd APIRD  

### 2. Create virtual environment
python -m venv venv  
source venv/bin/activate   # On Windows: venv\Scripts\activate  

### 3. Install dependencies
pip install django djangorestframework  

### 4. Run migrations
python manage.py migrate  

### 5. Start server
python manage.py runserver  

---

## 🌐 API Endpoints

| Method | Endpoint        | Description         |
|--------|----------------|---------------------|
| GET    | /drinks/       | Get all drinks      |
| GET    | /drinks/<id>/  | Get single drink    |
| POST   | /drinks/       | Add new drink       |
| PUT    | /drinks/<id>/  | Update drink        |
| DELETE | /drinks/<id>/  | Delete drink        |

---

## 📦 Example JSON

{
  "id": 1,
  "name": "Coca Cola",
  "description": "Soft drink"
}

---

## 🧪 Running Tests

python manage.py test  

---

## 🧑‍💻 Author

- Your Name  

---

## 📌 Future Improvements

- Add authentication (JWT)  
- Deploy to cloud (AWS/Heroku)  
- Add pagination & filtering  
- Swagger API documentation  

---

## 📜 License

This project is open-source and free to use.
