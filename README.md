# django-install
easy guide to how install django

## 1.- INSTALAR PYTHON<br>
https://www.python.org/downloads/
<br>
<br>

## 2.- INSTALAR PIP<br>
sudo easy_install pip
<br>
<br>

## 3.- INSTALAR ENTORNO VIRTUAL<br>
pip install virtualenv
<br>
<br>

## 4.- CREAR ENTORNO VIRTUAL<br>
virtualenv trirotaryenv -p python3.8
<br>
<br>

## 6.- ACTIVAR ENTORNO VIRTAL
source trirotaryenv/bin/activate
<br>
<br>

## 7.- ACTUALIZAR PIP<br>
pip install --upgrade pip
<br>
<br>

## 8.- INSTALAR DJANGO<br>
pip install Django==3.0.8
<br>
<br>

## 9.- INSTALAR REQUERIMIENTOS
pip install -r requierement.txt
<br>
<br>

## 10.- CREAR PROYECTO EN DJANGO
django-admin.py startproject trirotaryenv
<br>
<br>

## 11.- CREAR MIGRACIONES
Python3.8 manage.py migrate  
<br>
<br>

## 12.- APLICAR MIGRACIONES
Python3.8 manage.py makemigrations  
<br>
<br>

## 13.- CREAR SUPERUSUARIO
python3.8 manage.py createsuperuser
<br>
<br>

## 14.- CORRER SERVIDOR
python3.8 manage.py runserver
<br>
<br>
