# koko
Flask, SQLAlchemy y Postgres

# Proyecto Flask, SQLAlchemy y Postgres
Generación de aplicación To Do implementado SQLAlchemy ORM con base de dato Postgres

## Instalación de Postgres y creación de base de dato
Entorno virtual para gestionar las dependencias de su proyecto.

```bash
$ brew install postgresql
$ pg_ctl -D /usr/local/var/postgres
$ sudo -u postgres -i
$ createdb todoapp
```

## Generación de tablas apartir del model con flask_migrate

```bash
$ flask db init 
$ flask db migrate 
$ flask db upgrade
```

## Ejecución 

```bash
FLASK_APP=app 
FLASK_DEBUG=true 
flask run 
```



