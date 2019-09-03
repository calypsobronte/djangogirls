# djangogirls
Tutorial de Django Girls

# Entorno virtual

## Creamos la carpeta
```bash
$ mkdir djangogirls
$ cd djangogirls
```

Haremos un virtualenv llamado myvenv. El comando general estará en el formato:
```bash
$ python3 -m venv myvenv
```
Inicia el entorno virtual ejecutando:
```bash
$ source myvenv/bin/activate
```

Instalar Django
```bash
$ pip install django
```

Vamos a crear un blog sencillo!
```bash
$ django-admin startproject mysite .
```
Ahora deberías tener una estructura de directorios parecida a esta:

djangogirls
├───manage.py
├───mysite
│        settings.py
│        urls.py
│        wsgi.py
│        __init__.py
└───requirements.txt

## Configurar una base de datos

```bash
$ python manage.py migrate
```

## Iniciar el servidor
```bash
$ python manage.py runserver
```
http://127.0.0.1:8000/

![servidor]

[servidor]: https://live.staticflickr.com/65535/48669586708_064ac331f3_b.jpg

