


## How to set up the project to run on your local machine?

#### Download the code to your PC, unpack the zip and move inside the folder.

#### Create a new Python Virtual Environment:
```
python3 -m venv venv
```

#### Activate the environment and install all the Python/Django dependencies:

```
source ./venv/bin/activate
pip install -r ./requirements.txt
```

#### Apply the migrations as usual.

#### Run Django's development server:
```
python manage.py runserver
```

#### Open up Chrome and go to 127.0.0.1:8000 and the app is now running in development mode!
> Developed By : Bisheshwor Neupane
