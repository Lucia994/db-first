# db-first
Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario
Cosa consegnare?
create un file readme come fatto stamattina in classe con la struttura della tabella.

## Table name : Used_vehicle 
-id | BIGINT - PRIMARY_KEY AUTO_INCREMENT NOTNULL UNIQUE
-plate|(CHAR 7) NOTNULL
-brand_car | VARCHAR (20) NOTNULL
-car_model| VARCHAR (20)  NOTNULL
-number_of_ car_chassis |VARCHAR (20) NOTNULL
-car_power_supply |VARCHAR (20) NULL
-year_of_car_registration | YEAR (YYYY) NULL
-car_mileage | MEDIUMINT  NULL
-maintenance_work_carried_out_on_cars | TEXT (1000) NULL
-information_on_possible_car_accidents | TEXT (1000) NULL
-market_value | DECIMAL (7, 2) NULL
-purchase_value | DECIMAL (7, 2) NOTNULL


+----+-------+-------+-------+-----------------+---------------+------+----------+------------------+---------------+---------+-------+
| id | plate | brand | model | number_chassis  | power_supply  | year | mileage  | maintenance_work | info_accident | m_value | p_val |
+----+-------+-------+-------+-----------------+---------------+------+----------+------------------+---------------+---------+--------
|    |       |       |       |                 |               |      |          |                  |               |         |       |
|    |       |       |       |                 |               |      |          |                  |               |         |       |
|    |       |       |       |                 |               |      |          |                  |               |         |       |
|    |       |       |       |                 |               |      |          |                  |               |         |       |
|    |       |       |       |                 |               |      |          |                  |               |         |       |
|    |       |       |       |                 |               |      |          |                  |               |         |       |
|    |       |       |       |                 |               |      |          |                  |               |         |       |
|    |       |       |       |                 |               |      |          |                  |               |         |       |
+----+-------+-------+-------+-----------------+---------------+------+----------+------------------+---------------+---------+-------+