
## Car(ogetto)

## table name: Used Cars

## table columns:

- id | BIGINT PK AI NOTNULL UNIQUE
- marca | VARCHAR(255) | NOTNULL
- targa | CHAR(7) | NOTNULL UNIQUE
- modello | VARCHAR(255) | NOTNULL
- cambio | VARCHAR(30) | NULL
- alimentazione | VARCHAR(30) | NULL
- trazione | VARCHAR(30) | NULL
- potenza | SMALLINT | NULL
- cilindrata | SMALLINT | NULL
- colore | VARCHAR(30) 
- prezzo | DECIMAL(9,2) | NOTNULL
- immagine | VARCHAR(255) | NULL 
- chilometraggio | MEDIUMINT | NULL
- immatricolazione | DATE | NULL
- descrizione | TEXT | NULL
- ultimo_proprietario | VARCHAR(30) | NOTNULL