# Used Cars

| Colonna               | Tipo         | Attributi                  |
| --------------------- | ------------ | -------------------------- |
| id                    | BigInt       | Primary_key Auto_Increment |
| proprietari           | TinyInt      | Not Null                   |
| chilometri            | MediumInt    | Not Null                   |
| marca                 | VarChar(25)  | Not Null                   |
| modello               | VarChar(25)  | Not Null                   |
| anno_immatricolazione | Year         | Not Null                   |
| mese_immatricolazione | Char(2)      | Not Null                   |
| tipo_di_cambio        | VarChar(25)  | Not Null                   |
| potenza_kw            | SmallInt     | Not Null                   |
| potenza_cv            | SmallInt     | Not Null                   |
| tipo_carburante       | VarChar(25)  | Not Null                   |
| numeri_porte          | Char(1)      | Not Null                   |
| marce                 | Char(1)      | Not Null                   |
| emissioni_co_2        | VarChar(25)  | Null                       |
| colore                | VarChar(25)  | Not Null                   |
| valutazione_prezzo    | Float(9,2)   | Null                       |
| descrizione_veicolo   | VarChar      | Null                       |
| peso_a_vuoto          | SmallInt     | Null                       |
| classe_emissione      | VarChart(25) | Not Null                   |
| optional              | VarChar      | Null                       |
| comfort               | VarChar      | Null                       |
| intrattenimento       | VarChar      | Null                       |
| sicurezza             | VarChar      | Null                       |
| extra                 | VarChar      | Null                       |
