# Online Shopping Backend

A minimal Django + DRF backend for an online shop, featuring Customer, Category, Item, and Order CRUD APIs, with Celery tasks.

1. **Prerequisites**

Make sure you have installed:

- Python 3.8+  
- PostgreSQL  
- Redis  
- Git  

## 🛠️ Installation

1. *Clone the repo*  
   ```bash
   git clone git@github.com:<your-username>/online-shopping-website-backend.git
   cd online-shop-backend

2. Create a virtual environment and activate it.    
    ```python3 -m venv env ```
    ```source env/bin/activate```  
3. Install the dependencies.
    ```pip install django djangorestframework psycopg2-binary celery redis```
4. Freeze Dependencies
    pip freeze > requirements.txt
4. Run the migrations.    