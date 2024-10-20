## Comandos básicos de Django

### Instalación e inicio

1. Crear entorno virtual: `python3 -m venv {nombre de entorno virtual}`
2. Activar entorno virtual: `source {ruta entorno virtual}/bin/activate`
3. Desactivar entorno virtual: `deactivate`
4. Instalar librerias: `pip3 install django`
5. Verificar que paquetes tiene el entorno virtual: `pip3 freeze`

### Django

1. Crear proyecto Django: `django-admin startproject {nombre proyecto con pisos}`
2. Correr proyecto Django: `python3 manage.py runserver`
3. Aplicar migraciones (Crear tablas en BD): `python3 manage.py migrate`
4. Crear superusuarios (Para el admin): `manage.py createsuperuser`
5. Crear app: `python3 manage.py startapp {nombre de aplicacion`
6. Crear migraciones a partir de los modelos: `python3 manage.py makemigrations`

#### Recordar de agregar los requeriments en la raiz del proyecto al nivel de manage.py. Guiarse del comando pip3 freeze para sacar las versiones correctas, para instalarlas se hace con: `pip3 install -r requirements.txt`

### DjangoRestFramework

1. Instalar DjangoRest: `pip3 install djangorestframework`