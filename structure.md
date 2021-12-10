# Concessionario

## (Table) cars:

- id | BIGINT - PRIMARY_KEY UNIQUE AUTO INCREMENT NOTNULL
- marca | VARCHAR(20) - NOTNULL 
- modello | VARCHAR(20) - NOTNULL
- versione | VARCHAR(10) - NULL
- carrozzeria | VARCHAR(20) - NOTNULL
- anno | YEAR - NOTNULL
- prezzo | MEDIUMINT - NOTNULL
- chilometraggio | MEDIUMINT - NOTNULL
- potenza | VARCHAR(15) - NOTNULL
- cilindrata | VARCHAR(10) - NULL
- cilindri | TINYINT - NULL
- peso | VARCHAR(15) - NULL
- cambio | VARCHAR(15) - NOTNULL
- marce | TINYINT - NULL
- numero_di_porte | TINYINT - NOTNULL
- condizione | CHAR(5) - NOTNULL
- colore | VARCHAR(15) - NOTNULL
- classe_emissione | VARCHAR(15) - NULL
- Alimentazione | VARCHAR(20) - NOTNULL
- numero_di_posti | TINYINT - NOTNULL
- rivestimento | VARCHAR(20) - NULL
- trazione | VARCHAR(10) - NULL
- descrizione | VARCHAR(255) - NULL
- immagine | VARCHAR(50) - NULL
