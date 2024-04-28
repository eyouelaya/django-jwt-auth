## Django Auth rest API with JWT Token and Mysql Database

The project is a rest api that has a JWT authentication built into it with a configuration of MySQL for the database the following applicaitons

To run the project

### Step 1

create a virtual environment:

```
python3 -m venv myenv
```

### Step 2 Activate the virtual environment

# On Windows

```
myenv\Scripts\activate

# On Unix or MacOS

source myenv/bin/activate
```

### Setp 3 install dependancies

```
pip install -r requirements.txt
```

### Step 4 set up environment varialbes

duplicate .env-example file rename to .env and provide values for the attributes

### Step 5 Database setup

```
python manage.py migrate
python manage.py createsuperuser
```

### Step 6 run the django file

```
python manage.py runserver
```
