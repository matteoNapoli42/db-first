# Car Database

## Table Name

Cars

## Table Columns

- id | PK, UNIQUE,BIGINT,NOT NULL
- company | VARCHAR(50), NOT NULL
- model | VARCHAR(50), NOT NULL
- year | NOT NULL, DATE 
- engine | VARCHAR(10) , NOT NULL
- price | DECIMAL(8,2) //da una veloce ricerca su internet, la macchina più costosa Bugatti La Voiture Noire costa 16.800.000,00 milioni di euro
- is_used | TINYBIT, NOT NULL
- km | DOUBLE(6,2), NULL 
- internal_condition | TEXT, NULL
- external_condition | TEXT, NULL
- horsepower | VARCHAR(20), NULL
- seats | TINYINT, NULL
- optionals | TEXT, NULL
- img | VARCHAR,NULL
- color | VARCHAR (15), NULL
- description | TEXT, NULL
- accelleration| FLOAT(2,2), NULL
- max_vel | SMALLINT, NULL
- is_aviable | TINYINT, NULL
- plate_number | VARCHAR(10), NOT NULL, UNIQUE