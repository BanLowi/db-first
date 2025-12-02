## Table name: used_cars (entity name: used_car)

Columns:

- id : PK, INT, AUTO_INCREMENT
- model : VARCHAR(20)
- brand : VARCHAR(10)
- registration_year : YEAR
- milage : INT
- color : VARCHAR(20)
- plate : VARCHAR(20) UNIQUE
- price : DECIMAL(8, 2)
- description : TEXT NULL
- posted : DATE
