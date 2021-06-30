# Database auto usate

## (table) Auto
- id                                    BINGINT PRIMARY KEY UNIQUE NOTNULL INDEX
- targa                                 CHAR(7) NOTNULL UNIQUE
- marca                                 VARCHAR(100) NOTNULL
- modello                               VARCHAR(200) NOTNULL
- anno                                  YEAR NOTNULL
- posti                                 SMALLINT NOTNULL
- numero porte                          SMALLINT NOT NULL
- dimensione                            VARCHAR(25) NULL
- peso                                  FLOAT(9,2) NULL
- potenza                               VARCHAR(5) NOTNULL
- carburante                            VARCHAR(10) NOTNULL
- cilindri                              VARCHAR(10) NOTNULL
- cerchi                                VARCHAR(100) NULL
- pneumatici                            VARCHAR(255) NULL
- numero di marce                       SMALLINT NULL
- iipo di sterzo                        VARCHAR(20) NULL
- sistemi di assistenza                 VARCHAR(50) NULL
- capacità del serbatoio                VARCHAR(10) NULL
- tipo di carrozzeria                   VARCHAR(20) NULL
- modifica (motore)                     VARCHAR(20) NOTNULL
- sistemi di motori                     VARCHAR(50) NULL
- classe di emissione gas di scarico    VARCHAR(10) NOTNULL
- spazio bagagliaio                     VARCHAR(20) NOTNULL