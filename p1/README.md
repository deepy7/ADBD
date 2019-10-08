# Instalación y prueba de postgresql

```
- Michael Brian Santana Mon
```
## Histórico de comandos

* Instalación de postgresql
  - sudo apt-get install postgresql

* Creación de usuario
  - sudo su postgres password: XXXXXXXXXX
  - createuser miusuario
  - alter role miusuario with password 'mipassword';
  
* Acceso y realización de las tareas
  - sudo su postgres
  - psql
  - \l
  - CREATE DATABASE pract1;
  - \c pract1
  - create table usuarios (nombre varchar(30),clave varchar(10));
  - insert into usuarios (nombre, clave) values ('Isa','asdf');
  - insert into usuarios (nombre, clave) values ('Pablo','jfx344');
  - insert into usuarios (nombre, clave) values ('Ana','tru3fal');
  - \dt
  - \d usuarios
  - SELECT * FROM usuarios;
  - \s
