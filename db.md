# Consegna

- Modellare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.

## Struttura

Table Name : cars

- ID | Primary Key | INT | NOTNULL | UNIQUE | AUTO_INCREMENT
- Marca | VARCHAR(150) | NOTNULL
- Modello | VARCHAR(200) | NOTNULL
- Matricola | VARCHAR(15) | NOTNULL | UNIQUE
- Data di produzione | DATE | NOTNULL
- Colore | VARCHAR(20) | NULL
- Usata | BOOL | NOTNULL
- Venduta | BOOL | NOTNULL | DEFAULT(FALSE)
- Numero di proprietari | TINYINT | NULL | DEFAULT(0)
- Km | MEDIUM | NULL
- Prezzo | MEDIUM | NOTNULL
- Equipaggiamento | TEXT | NULL |
- Condizioni | TEXT | NULL

## Table

| ID  | Marca | Modello | Matricola | Data di produzione | Colore | Usata | Venduta | Numero di proprietari | KM  | Prezzo | Equipaggiamento | Condizioni |
| --- | ----- | ------- | --------- | ------------------ | ------ | ----- | ------- | --------------------- | --- | ------ | --------------- | ---------- |
