# Manipulations de tables avec PostgreSQL

## 1. Création d'une table

```SQL
CREATE TABLE <table_name (
 <champ_1> SERIAL PRIMARY KEY NOT NULL,  
 <champ_2> Type,
 etc...
 );
```

Note : 'SERIAL' est utilisé pour créer Id en un auto-incrément.

## 2. Insertion d'un enregistrement

```SQL
INSERT INTO <table_name (champ_1, champ_2, etc...) VALUES (value_1, value_2, etc...);

Note : Pour les formats DATE, saisir la valeur au format américain (YYYY/MM/DD).


