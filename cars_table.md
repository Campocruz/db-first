# Cars Table

  - id                    BIGINT            Auto_Increment, Not_Null, 
  - marca                 VARCHAR(100)      Not_Null
  - modelo                VARCHAR(150)      Not_Null
  - data_vendita          DATETIME          Null
  - anno                  YEAR              Not_Null
  - prezzo_netto          DECIMAL(10,2)     Null
  - descrizione           TEXT              Null
  - foto_principale       VARCHAR(255)      Null, Default
  - stato                 VARCHAR(50)       Null