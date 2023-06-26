# Manipulations de base de données avec PostgreSQL

## 1. Création d'un utilisateur

`CREATE USER <user_name> WITH PASSWORD '<password>';`

## 2. Vérifier la liste des utilisateurs

`\du`

## 3. Création d'une base de données avec PostgreSQL

`CREATE DATABASE <database_name> WITH OWNER <username>;`

## 4. Vérifier la liste des bases de données

`\l`

## 5. Attibution des droits à l'utilisateur sur la base de données

`GRANT ALL PRIVILEGES ON DATABASE <db_name> TO <user_name>;`

## 6. Connexion à la base de données avec l'utilisateur

`pgcli -h localhost -p 5432 -U <user_name> <database_name>`

