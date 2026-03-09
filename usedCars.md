## Auto usate

| Nome colonna             | Tipo di Dato | Attributi                      | Indice      |
| ------------------------ | ------------ | ------------------------------ | ----------- |
| Id                       | BIGINT       | NOT NULL, UNIQUE, UNSIGNED, AI | PRIMARY KEY |
| Marca                    | VARCHAR(40)  | NOT NULL                       | INDEX       |
| Modello                  | VARCHAR(80)  | NOT NULL                       |             |
| Anno di immatricolazione | YEAR         | NOT NULL, UNSIGNED             |             |
| Numero di Telaio         | CHAR(17)     | NOT NULL, UNSIGNED, UNIQUE     |             |
| Chilometraggio           | FLOAT(6,3)   | NOT NULL, UNSIGNED             |             |
| Alimentazione            | VARCHAR(40)  | NOT NULL                       |             |
| Tipo di cambio           | VARCHAR(40)  | NOT NULL                       |             |
| Classe ambientale        | VARCHAR(20)  | NOT NULL                       |             |
| Numero ex-proprietari    | TINYINT      | NOT NULL, UNSIGNED             |             |
| Prezzo                   | FLOAT(6,3)   | NOT NULL, UNSIGNED             | INDEX       |
