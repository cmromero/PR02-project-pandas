<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>

# Data Cleaning and Manipulation with Pandas to find out where Fonzie jumped the shark
*[Carlos Romero]*

*[DATA PT SEP 2021, Ironhack Barcelona 2021-10-30]*

## Content
- [Overview](#overview)
- [Checklist to start](#checklist-to-start)
- [Fases](#fases)
- [Links](#links)

## Overview

El objetivo de este proyecto era combinar todo lo que he aprendido sobre la manipulación, la limpieza y la manipulación de datos con Pandas para poder ver cómo funciona todo en conjunto. Para este proyecto, comenzaré con este desordenado conjunto de datos [Shark Attack](https://www.kaggle.com/teajay/global-shark-attacks/version/1). Tengo que importarlo, usar mis habilidades de manejo de datos para limpiarlo, prepararlo para ser analizado y luego exportarlo como un archivo de datos CSV limpio.

## Checklist to start
- Examinar base de datos
- Eliminar columnas innecesarias
- Eliminar valores nulos
- Arreglar tipos de datos
- Eliminar años y lugares imposibles
- Substituir valores erroneos por el correcto o, en su caso, poner valor como desconocido

## Fases

El notebook se encuentra dividido por fases en las que se ha intentado agrupar las diferentes acciones llevadas a cabo para limpiar la base de datos
- 1  Fase de importación: Aquí se reserva una celda para importar las librerías necesarias y otra para importar el archivo csv.
- 2  Fase de exploración de columnas u observaciones: Aquí exploramos el dataset y procuramos detectar las columnas con valores innecesarios o conflictivos.
- 3  Fase limpieza: Aquí agrupamos todas las acciones de transformación de los datos.
	- 3.1  Eliminar columnas y filas innecesarias o conflictivas: hacemos drop con las columnas detectadas anteriormente.
	- 3.2  Depurar y eliminar valores nulos de la columna href
	- 3.3  Substituimos valores nulos por string 'Unknown' en columnas que no usaremos
	- 3.4  Depurar y eliminar valores nulos de la columna 'Fatal (Y/N)'
	- 3.5  Depurar y completar los valores de las columnas 'Area', 'Country' y 'Location'
	- 3.6  Depurar los valores del campo 'Sex '
	- 3.7  Informar com John/Jane Doe a los nombres que estén vacios pero con sexo determinado
	- 3.8  Depurar campo 'Activity' y agrupar actividades en un campo adicional
	- 3.9  Depuramos la columna 'year' a partir de la columna 'Date'
	- 3.10  Agrupamos los países en una nueva columna llamada 'Territories'
- 4  Fase final de exportación: Aquí hacemos los último retoques y exportamos el dataset a un archivo csv.
- 5  Fase de consulta: Where did Fonzie jump de shark??? Aquí vamos filtrando el dataframe haciéndole preguntas hasta que obtenemos el caso buscado.


## Links
[Repository]( https://github.com/ironhack-bcn-data-pt/PR02-project-pandas/pull/22)
[Slides in html](https://drive.google.com/file/d/1Ulhpb53ksjjvWVtfaXYcwjeXQRHaNBfR/view?usp=sharing)
[Slide in pdf](https://drive.google.com/file/d/1Ygw8E27ZZPEKNguXSGmjhkQEXZPoCWjO/view?usp=sharing)






	



