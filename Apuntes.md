# Power BI

## Carga de datos

• Evitar la dinamización de columnas me permite evitar redundancia de columnas, por ejemplo se tiene una columna por cada región (4 regiones) al usar la dinamización se crea una única columna llamda región y se crean 4 registros con los valores de región.

• Para las columnas que tengan únicamente años se puede utilizar el tipo de dato "texto"

## Aplicar filtros para todos los reportes

Es posible bloquear o filtrar valores a partir de controladores, para todas las visualizaciones, 
podemos hacerlo por página o por proyecto. Los filtros no son manipulables tras la publicación del reporte 

## Ejemplos Dax

> **Calcular edad**
>> Edad = INT(YEARFRAC('Tabla Empleados'[Nacimiento], TODAY()))
>>> INT redondea al entero inferior más cercano