# Portafolio
<h1 align="center">Hi 👋, me llamo Erick Geovany Medina </h1>
<h3 align="center">Soy apasionado para analizar datos </h3>

- 🔭Estoy trabajando en Análisis de ingresos para la toma de decisión
  
# Data-Analyst-Portafolio
Los siguientes son mis proyectos en Excel y RStdio

Este repositorio contiene los proyectos de cobros por medio de tarjeta de la empresa ABC, S.A. Los proyectos estan modelados en docuemento en excel y el proyecto de Ingenieria de Datos por medio de webscraping desde RStudio.

## Tabla de Contenido
### Proyecto de Cobros por medio de la Tarjeta de la empresa ABC, S.A.
- Limpieza y Transformación de Datos
- Análisis de Datos
- Visualización de Datos
- Ciencia de datos
### Proyecto Medio de Webscraping (Películas)
- Ingenieria de datos
  
## Problemas de la empresa ABC, S.A. con relacion a los ingresos (EXCEL)
La empresa ABC tiene inconvenientes en los cobros por medio de tarjeta. Por lo que en el mes de septiembre 2022 decide contratar a dos personas para que ayuden a incrementar los ingresos por medio de tarjeta se pide que evalué el ingreso promedio del año 2018 año 2019 año 2020 y año 2021 para validar si la contratación ayudo al incremento de los ingresos.
Por ello se necesita lo siguiente:
- Realizar una limpieza y transformación de datos de los años descritos en la data.
- Realizar un análisis de los datos cobros anuales mínimo, cobro anaual máximo y promedio de cobros anual para los años al a 2018, 2019, 2020, 2021, 2023 asi como los ingresos mensuales de cada año.
- De acuerdo con el análisis de datos indicar si fue efectiva o no la contratación de dos personas y si represento un incremento en los ingresos para poder extender el contrato con la empresa 2 años más.

### Primer Paso
- Del docuemento en excel se toma la pestaña de datos recibos de caja, se eliminar columna A-W.
- Nombrar la columna "X" como tarjeta, la columna "Y" como anulados, la columna "Z" como recibos de caja, columna AA como la fecha.
- Se renombran las siguientes las columnas: AC (código de cliente), AD (nombre del cliente), AF (ingreso), AG (ruta) y AH (autorización).
- Se eliminan las siguientes columnas: AB, AE,  AI - AZ.
### Segundo Paso
- Por medio de un filtro seleccionar la columna de anulados y eliminar las filas letra A (recibos anulados).
- Por medio de un filtro ordenar la columna de recibo por correlativo (ingresos reales de la empresa).
- Eliminar la columna de anulados.
- Remplazar los valores de ingresos de GTQ.
- Columna de ingresos colocar la moneda quetzal.
- Aplicar formula de CONTAR.BLANCO en la columna de autorización.
- Seleccionar las columnas en blanco y sustituirlas con valor 0.
### Tercer Paso
- Seleccionar la columna A-H y crear una tabla dinámica donde se crea subdatos por año e ingresos mensuales.
- Aplicar formula MIN, MAX y PROMEDIO de los años 2018 al 2022.
- Realizar Anális#is.
#### Análsisi: De acuerdo a los datos la empresa ABC, S.A. se cuenta con un ingreso promedio mensual para del año 2018 al 2020  entre Q 205K y  328K sin embargo a raiz de la contratación los ingresos no han bajado de los Q 400k lo que si representa un aumento en los ingresos por medio de tarjeta por lo que si la empresa quiere mantener un ingreso promedio de Q 400K se recomienda extender el contrato de las 2 personas.

