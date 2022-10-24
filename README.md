# Bank security console

Bank security console - website to view remote database, containing pass cards of bank
"Sirena" employees.
It shows who is inside the "storage" and how long.
It shows all visits of employees to "storage"

### How to install

Python3 should be already installed. 
Then use `pip` (or `pip3`, if there is a conflict with Python2) to install dependencies:
```
pip install -r requirements.txt
```
Access to database should be written in project/settings.py

Create ".env" file and write database access parameters and Debug mode:

    STORAGE_DB_HOST=
    STORAGE_DB_USER=
    STORAGE_DB_PASSWORD=
    SECRET_KEY=
    DEBUG=False/True

## Getting Started
Run server:
```
py manage.py runserver
```
### Usage
Open a link "Starting development server at http://0.0.0.0:8000/" or "http://127.0.0.1:8000/" 

## Authors
* **Evgeny Melnikov** - *Initial work* - [Evgeny Melnikov](https://github.com/MelnikovEI)

## Acknowledgments
* Inspired by [Devman](https://dvmn.org/)
