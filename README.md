# django-install
easy guide to how install django

## 1.- INSTALAR PYTHON<br>
https://www.python.org/downloads/

## 2.- INSTALAR PIP<br>
sudo easy_install pip

## 3.- INSTALAR ENTORNO VIRTUAL<br>
pip install virtualenv


## 4.- CREAR ENTORNO VIRTUAL<br>
virtualenv trirotaryenv -p python3.8


## 6.- ACTIVAR ENTORNO VIRTAL
source trirotaryenv/bin/activate


## 7.- ACTUALIZAR PIP<br>
pip install --upgrade pip


## 8.- INSTALAR DJANGO<br>
pip install Django==3.0.8


## 9.- INSTALAR REQUERIMIENTOS
pip install -r requierement.txt


## 10.- CREAR PROYECTO EN DJANGO
django-admin.py startproject trirotaryenv


## 11.- CREAR MIGRACIONES
Python3.8 manage.py migrate  


## 12.- APLICAR MIGRACIONES
Python3.8 manage.py makemigrations  


## 13.- CREAR SUPERUSUARIO
python3.8 manage.py createsuperuser


## 14.- CORRER SERVIDOR
python3.8 manage.py runserver
