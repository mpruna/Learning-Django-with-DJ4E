### Learning Django with DJ4E

MOOC to Learn Django Web site programming
[Charles Severance](http://www.dr-chuck.com/) the instructor has other free materials, check it out!

* Free Courses / Educational Material:
* Coursera: Python for Everybody (Python)
* Coursera: Web Applications for Everybody (PHP/SQL)
* Coursera: Internet History, Technnology and Security
* See also www.py4e.com, www.wa4e.com and www.dj4e.com

### Project setup

1) Install python --v 3.6.0

**Python 3.6.0** found [here](https://www.python.org/downloads/release/python-360/)
**Older Python Versions** available on [Python Software Foundation](https://www.python.org/downloads/)

Check available python installed versions:

```
py -0p
Installed Pythons found by py Launcher for Windows
 -3.7-64        C:\Users\pruna\AppData\Local\Programs\Python\Python37\python.exe *
 -3.6-64        C:\Users\pruna\AppData\Local\Programs\Python\Python36\python.exe
 -3.5-64        C:\Users\pruna\AppData\Local\Programs\Python\Python35\python.exe
 -2.7-64        C:\Python27\python.exe
```

2) Setup project env

```
C:\Users\pruna\AppData\Local\Programs\Python\Python36\python.exe -m venv project_
env
```

3) Activate environment & install/upgrade pip:

```
project_env\Scripts\activate.bat
python -m pip install --upgrade pip
```

4) Clone Django skeleton site & pip requirements

```
git clone https://github.com/csev/dj4e-samples
cd dj4es-samples
pip install -r requirements.txt
```

5) Checkout and run server

```
python manage.py migrate            # Makemigrations is already in git
python manage.py createsuperuser
python manage.py runscript gview_load
python manage.py runscript many_load

python manage.py runserver
```






