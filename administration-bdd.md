# Administration d'une Bdd PostgrSQL

## 1. Creéation d'un fichier Backup de la base de données

A la racine de linux, se connecter en tant qu'utilisateur Postgres
`sudo -i -u postgres`

`pg_dump -d <database_name> -f <file_name.sql>`

## 2. Restoration d'une base de données à partir d'un fichier Backup (.sql)

`pg_restore -d <database_name> <file_name.sql> -c`


