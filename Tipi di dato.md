# Tipi di dato
## Database 1
### Gestione di una biblioteca.
- Entità 1: Libri

| #   | nome               | tipo di dato in java | tipo di data in SQL |
| --- | ------------------ | -------------------- | ------------------- |
| 1   | codice_libro       | byte(11)             | tinyint(11)         |
| 2   | titolo             | string(255)          | varchar(255)        |
| 3   | numero_pagine      | int                  | int                 |
| 4   | prezzo             | double               | double              |
| 5   | data_pubblicazione | localdate            | date                |

- Entità 2: Membri

| #   | nome            | tipo di dato in java | tipo di data in SQL |
| --- | --------------- | -------------------- | ------------------- |
| 1   | id_membro       | byte(11)             | tinyint(11)         |
| 2   | nome            | string(255)          | varchar(255)        |
| 3   | cognome         | string(255)          | varchar(255)        |
| 4   | data di nascita | localdate            | date                |
| 5   | indirizzo       | string(255)          | varchar(255)        |

- Entità 3: Prestiti

| #   | nome         | tipo di dato in java | tipo di dato in SQL |
| --- | ------------ | -------------------- | ------------------- |
| 1   | n_prestito   | short                | smallint            |
| 2   | data_inizio  | localdate            | datetime            |
| 3   | data_fine    | localdate            | datetime            |
| 4   | id_membro    | byte(11)             | tinyint(11)         |
| 5   | codice_libro | byte(11)             | tinyint(11)         |
## Database 2
### Gestione di un ristorante.
- Entità 1: Piatti

| #   | nome_attributo | tipo di dato in java | tipo di data in SQL |
| --- | -------------- | -------------------- | ------------------- |
| 1   | numero_menù    | byte(11)             | tinyint(11)         |
| 2   | nome_piatto    | string(255)          | varchar(255)        |
| 3   | prezzo         | double               | double              |

- Entità 2: Clienti

| #   | nome_attributo      | tipo di dato in java | tipo di data in SQL |
| --- | ------------------- | -------------------- | ------------------- |
| 1   | numero_prenotazione | byte(11)             | tinyint(11)         |
| 2   | nome                | string(255)          | varchar(255)        |
| 3   | cognome             | string(255)          | varchar(255)        |
| 4   | prenotazione        | localdate            | datetime            |

- Entità 3: Ingredienti

| #   | nome_attributo | tipo di dato in java | tipo di dato in SQL |
| --- | -------------- | -------------------- | ------------------- |
| 1   | id_ingrediente | byte(11)             | tinyint(11)         |
| 2   | nome           | string(255)          | varchar(255)        |
| 3   | composizione   | string(255)          | varchar(255)        |
| 4   | allergeni      | string(255)          | varchar(255)        |
| 5   | numero_menù    | byte(11)             | tinyint(11)         |

## Database 3
### Gestione di un negozio di fiori.
- Entità 1: Fiori

| #   | nome_attributo | tipo di dato in java | tipo di data in SQL |
| --- | -------------- | -------------------- | ------------------- |
| 1   | id_fiore       | byte(11)             | tinyint(11)         |
| 2   | nome           | string(255)          | varchar(255)        |
| 3   | descrizione    | string(255)          | varchar(255)        |
| 4   | prezzo         | double               | double              |

- Entità 2: Clienti

| #   | nome_attributo | tipo di dato in java | tipo di data in SQL |
| --- | -------------- | -------------------- | ------------------- |
| 1   | numero_tessera | byte(11)             | tinyint(11)         |
| 2   | nome           | string(255)          | varchar(255)        |
| 3   | cognome        | string(255)          | varchar(255)        |
| 4   | data_nascita   | localdate            | date                |
| 5   | indirizzo      | string(255)          | varchar(255)        |

- Entità 3: Fornitori

| #   | nome_attributo | tipo di dato in java | tipo di dato in SQL |
| --- | -------------- | -------------------- | ------------------- |
| 1   | id_fornitore   | byte(11)             | tinyint(11)         |
| 2   | nome           | string(255)          | varchar(255)        |
| 3   | locazione      | string(255)          | varchar(255)        |
| 4   | id_fiore       | byte(11)             | tinyint(11)         |


