# DJANGO-CRUD
Microsoft Windows [Version 10.0.19045.2130]
(c) Microsoft Corporation. All rights reserved.

C:\Users\25473>desktop
'desktop' is not recognized as an internal or external command,
operable program or batch file.

C:\Users\25473>python --version
Python 3.10.8

C:\Users\25473>cd desktop

C:\Users\25473\Desktop>cd songcrud

C:\Users\25473\Desktop\songcrud>python manage.py startapp musicapp
python: can't open file 'C:\\Users\\25473\\Desktop\\songcrud\\manage.py': [Errno 2] No such file or directory

C:\Users\25473\Desktop\songcrud>my_env\scripts\activate
The system cannot find the path specified.

C:\Users\25473\Desktop\songcrud>pip --version
pip 22.2.2 from C:\Users\25473\AppData\Local\Programs\Python\Python310\lib\site-packages\pip (python 3.10)

C:\Users\25473\Desktop\songcrud>myproject\Scripts\activate.bat

(myproject) C:\Users\25473\Desktop\songcrud>py -m pip install Django
Collecting Django
  Downloading Django-4.1.2-py3-none-any.whl (8.1 MB)
     ---------------------------------------- 8.1/8.1 MB 1.0 MB/s eta 0:00:00
Collecting sqlparse>=0.2.2
  Downloading sqlparse-0.4.3-py3-none-any.whl (42 kB)
     ---------------------------------------- 42.8/42.8 kB 516.3 kB/s eta 0:00:00
Collecting tzdata
  Downloading tzdata-2022.5-py2.py3-none-any.whl (336 kB)
     ---------------------------------------- 336.7/336.7 kB 995.2 kB/s eta 0:00:00
Collecting asgiref<4,>=3.5.2
  Downloading asgiref-3.5.2-py3-none-any.whl (22 kB)
Installing collected packages: tzdata, sqlparse, asgiref, Django
Successfully installed Django-4.1.2 asgiref-3.5.2 sqlparse-0.4.3 tzdata-2022.5

[notice] A new release of pip available: 22.2.2 -> 22.3
[notice] To update, run: python.exe -m pip install --upgrade pip

(myproject) C:\Users\25473\Desktop\songcrud>python.exe m pip install --upgrade pip
C:\Users\25473\AppData\Local\Programs\Python\Python310\python.exe: can't open file 'C:\\Users\\25473\\Desktop\\songcrud\\m': [Errno 2] No such file or directory

(myproject) C:\Users\25473\Desktop\songcrud>django-admin --version
4.1.2

(myproject) C:\Users\25473\Desktop\songcrud>django-admin startproject myworld

(myproject) C:\Users\25473\Desktop\songcrud>django-admin startproject songcrud

(myproject) C:\Users\25473\Desktop\songcrud>py manage.py runserver
C:\Users\25473\AppData\Local\Programs\Python\Python310\python.exe: can't open file 'C:\\Users\\25473\\Desktop\\songcrud\\manage.py': [Errno 2] No such file or directory

(myproject) C:\Users\25473\Desktop\songcrud>pip install django
Requirement already satisfied: django in c:\users\25473\desktop\songcrud\myproject\lib\site-packages (4.1.2)
Requirement already satisfied: sqlparse>=0.2.2 in c:\users\25473\desktop\songcrud\myproject\lib\site-packages (from django) (0.4.3)
Requirement already satisfied: tzdata in c:\users\25473\desktop\songcrud\myproject\lib\site-packages (from django) (2022.5)
Requirement already satisfied: asgiref<4,>=3.5.2 in c:\users\25473\desktop\songcrud\myproject\lib\site-packages (from django) (3.5.2)

[notice] A new release of pip available: 22.2.2 -> 22.3
[notice] To update, run: python.exe -m pip install --upgrade pip

(myproject) C:\Users\25473\Desktop\songcrud>django-admin startapp musicapp

(myproject) C:\Users\25473\Desktop\songcrud>manage.py runserver
'manage.py' is not recognized as an internal or external command,
operable program or batch file.

(myproject) C:\Users\25473\Desktop\songcrud>python manage.py runserver
C:\Users\25473\AppData\Local\Programs\Python\Python310\python.exe: can't open file 'C:\\Users\\25473\\Desktop\\songcrud\\manage.py': [Errno 2] No such file or directory

(myproject) C:\Users\25473\Desktop\songcrud>python manage.py migrate
C:\Users\25473\AppData\Local\Programs\Python\Python310\python.exe: can't open file 'C:\\Users\\25473\\Desktop\\songcrud\\manage.py': [Errno 2] No such file or directory

(myproject) C:\Users\25473\Desktop\songcrud>py manage.py runserver
C:\Users\25473\AppData\Local\Programs\Python\Python310\python.exe: can't open file 'C:\\Users\\25473\\Desktop\\songcrud\\manage.py': [Errno 2] No such file or directory

(myproject) C:\Users\25473\Desktop\songcrud>from django.db import models
'from' is not recognized as an internal or external command,
operable program or batch file.

(myproject) C:\Users\25473\Desktop\songcrud>
(myproject) C:\Users\25473\Desktop\songcrud>class Members(models.Model):
'class' is not recognized as an internal or external command,
operable program or batch file.

(myproject) C:\Users\25473\Desktop\songcrud>  firstname = models.CharField(max_length=255)
'firstname' is not recognized as an internal or external command,
operable program or batch file.

(myproject) C:\Users\25473\Desktop\songcrud>  lastname = models.CharField(max_length=255)
'lastname' is not recognized as an internal or external command,
operable program or batch file.

(myproject) C:\Users\25473\Desktop\songcrud>cd models.py
The system cannot find the path specified.

(myproject) C:\Users\25473\Desktop\songcrud>cd musicapp

(myproject) C:\Users\25473\Desktop\songcrud\musicapp>cd models.py
The directory name is invalid.

(myproject) C:\Users\25473\Desktop\songcrud\musicapp>cd models
The system cannot find the path specified.

(myproject) C:\Users\25473\Desktop\songcrud\musicapp>artiste/model.py
'artiste' is not recognized as an internal or external command,
operable program or batch file.

(myproject) C:\Users\25473\Desktop\songcrud\musicapp>cd artiste/models.py
The system cannot find the path specified.

(myproject) C:\Users\25473\Desktop\songcrud\musicapp>cd models
The system cannot find the path specified.

(myproject) C:\Users\25473\Desktop\songcrud\musicapp>class artiste(models.Model)
'class' is not recognized as an internal or external command,
operable program or batch file.

(myproject) C:\Users\25473\Desktop\songcrud\musicapp>startclass artiste
'startclass' is not recognized as an internal or external command,
operable program or batch file.

(myproject) C:\Users\25473\Desktop\songcrud\musicapp>
