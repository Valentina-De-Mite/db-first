Tabella auto usate di un concessionario

Nome Tabella:
Used_Cars

Colonne Tabella:

- id | BIGINT | PK AI

- marca_auto | VARCHAR(30) | NOTNULL
- modello | CHAR(20) | NOTNULL
- venditore | VARCHAR(100) | NOTNULL
- info_venditore | TEXT | NULL
- prezzo | DECIMAL(7,2) | DEFAULT(0)
- immatricolazione | CHAR(2) | NULL
- colore | VARCHAR(20) | NULL
