Esercizio di oggi: DB First
nome repo: db-first
Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.
Per la consegna, potete inserire la vostra tabella in un file markdown come vi ho fatto vedere a lezione, oppure farla su Excel, Fogli Google ecc e fare uno screen.



Colonne|Tipo|Attributi|Index
---|---|---|---
id| bigint | AUTO_INCREMENT| PRIMARY_KEY
brand| varchar| NOTNULL
chassi| char(17)| Unique, NOTNULL
model| Varchar(20)| NOTNULL
plate| Varchar(10)| NULL, Unique
kms| Mediummint| NOTNULL
imm_year| Date| NOTNULL
price| float(9,1)| NULL
original_price| float(9,1)| NULL
prev_owners_num| Tinyint| NOTNULL, Default(1)
color| char(7)| NULL
power_supply| Char(4)| NOTNULL
prod_year| Year| NOTNULL
transmission| CHar(4)| NOTNULL
