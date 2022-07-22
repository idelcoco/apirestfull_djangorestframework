# apirestfull_djangorestframework
## _Api rest full_
### _Djangorestframework_


## Installation

Entorno virtual con python y django.

Debemos tener instalado python/pip y virtualevn "_pip install virtualenv_".
- en el directorio raiz: apirestfull_djangorestframework/

```sh
virtualenv env
env\Scripts\activate
pip install django==3.0.6
pip install django-mssql-backend
pip install djangorestframework
```

Ahora ejecutamos el projecto...
- en el directori: apirestfull_djangorestframework/rest/

_Nota: debes configurar la conexión a la base SQL Server desde:_ apirestfull_djangorestframework/rest/rest/settings.py

DATABASES = {
'default': {
'ENGINE': 'sql_server.pyodbc',
'NAME': 'DB0004',
'USER': 'sa',
'PASSWORD': 'qwe123/',
'HOST': 'PRACTICANTE4\localhost0001',
'OPTIONS': {
'driver': 'ODBC Driver 13 for SQL Server',
},
}
}

```sh
py manage.py migrate
py manage.py runserver
```
**Puerto del servidor en el loclahost**

```sh
127.0.0.1:8000/
```

## License

GitHub

**idelcoco**
