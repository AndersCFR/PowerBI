# Power BI DAX


## Ejemplos Dax

> **Calcular edad**
>> Edad = INT(YEARFRAC('Tabla Empleados'[Nacimiento], TODAY()))
>>> INT redondea al entero inferior más cercano