Esercizio di oggi: DB First

nome repo: db-first

Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.

COLONNA         | TIPI       | ATTRIBUTO 
---             |---         |---
id              | INT        | PRIMARY_KEY, AUTO_INCREMENT
marca           | VARCHAR    | NONULL
modello         | VARCHAR    | NONULL
codice_carroz   | CHAR(2)    | NONULL
colore          | VARCHAR    | NULL
km_fatti        | MEDIUMINT  | NONULL
data_produzione | DATE       | NONULL
cilindrata      | VARCHAR    | NONULL
potenza massima | VARCHAR    | NONULL
lunghezza       | FLOAT(4,1) | NONULL
larghezza       | FLOAT(4,1) | NONULL
altezza         | FLOAT(4,1) | NONULL
passo           | FLOAT(4,1) | NONULL
massa           | SMALLINT   | NONULL
tipo_motore     | CHAR       | NONULL
tipo_carburante | CHAR       | NONULL
cambio_manuale  | TINYINT(1) | NONULL
consumo medio   | FLOAT(3,1) | NONULL
prev_owner      | VARCHAR    | NULL