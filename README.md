# Little Lemon
Tt is a one stop application for food businesses offering various functionalities like bookings, offered menus and associated price listings typically offered by food businesses.




## Steps to run the app

### 1. Install `pipenv`

```bash
pip install pipenv
```

### 2. Create a `.env` file in the root folder

```bash
# .env
DATABASE = YOUR_MYSQL_DATABASE_NAME
USER     = YOUR_USERNAME             # default is root
PASSWORD = YOUR_MYSQL_PASSWORD
HOST     = localhost                 # or 127.0.0.1
PORT     = 3306
```

### 3. Install dependencies

```bash
pipenv install
```

### 4. Make migrations

```bash
py manage.py makemigrations
```

### 5. Migrate

```bash
py manage.py migrate
```

### 6. Run the app

```bash
py manage.py runserver
```

### To run tests

```bash
py manage.py test tests
```
