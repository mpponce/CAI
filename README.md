# CAI
Captura y Almacenamiento de Información 2021

Por el peso no se pudo agregar el dataset NYPD_Complaint_Data_Historic.csv

Bajarlo de:
https://data.cityofnewyork.us/Public-Safety/NYPD-Complaint-Data-Historic/qgea-i56i

Mediante la opción Export-->CSV

Renombrarlo a "nypd_crimes.csv" y modificar su ubicación en el archivo de configuración de Logstash "crimes.elastic.logstash.conf" de ser necesario.

También subimos un archivo con menos registros como demostración "nypd_tail.csv"
