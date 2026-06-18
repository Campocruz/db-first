# Cars Table

  - id                    BIGINT            Auto_Increment, Not_Null, 
  - marca                 VARCHAR(255)      Not_Null
  - anno_vendita          YEAR              Not_Null
  - prezzo_netto          DECIMAL(10,2)     Null
  - prezzo_iva            DECIMAL(10,2)     Null
  - codice_vettura        VARCHAR(255)      Not_Null, Unique
  - descrizione           TEXT              Null
  - foto_principale       VARCHAR(255)      Null
  - stato                 VARCHAR(50)       Null
  - data_creazione        DATETIME          Not_Null