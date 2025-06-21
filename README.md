# Online Shopping Backend

A minimal Django + DRF backend for an online shop, featuring Customer, Category, Item, and Order CRUD APIs, with Celery tasks.

## Prerequisites

Make sure you have installed:

- Python 3.8+
- PostgreSQL
- Redis
- Git

## 🛠️ Setup & Installation

1. **Clone the repo**
   ```bash
   git clone git@github.com:<your-username>/online-shopping-website-backend.git
   cd online-shopping-website-backend/online-shopping-website-backend
   ```

2. **Create a virtual environment and activate it**
   ```bash
   python3 -m venv env
   source env/bin/activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Configure your database and environment variables as needed.**

5. **Run migrations**
   ```bash
   python online_shopping/manage.py migrate
   ```

6. **(Optional) Initialize test data**
   ```bash
   python online_shopping/manage.py init_test_data
   ```

## 🚀 Running the Application

Start the development server:
```bash
python online_shopping/manage.py runserver
```

## 🧪 Running Tests

Run all tests:
```bash
python online_shopping/manage.py test
```

## 📝 Notes

- Make sure PostgreSQL and Redis are running before starting the application.
- Adjust settings as needed in `online_shopping/settings.py`.