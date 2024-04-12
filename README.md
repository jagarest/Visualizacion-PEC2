# PEC2 - Visualización de datos
## Descripción
**Título de la PEC2**: Estudio de técnicas de visualización de datos

Esta PEC se ha realizado bajo el contexto de la asignatura Visualización de datos, perteneciente al Máster en Ciencia de Datos de la Universitat Oberta de Catalunya. En ella, se han creado tres pequeñas visualizaciones usando técnicas diferentes.
## Integrantes de la PEC
Esta PEC ha sido realizada por un único integrante:
+ Javier García Esteban
## Archivos del repositorio
Las carpetas y archivos disponibles en el repositorio son:
+ Carpeta **main/source**: Contiene el código R implementado para la obtención de los datos y generación de las visualizaciones, además de los ficheros necesarios para ejecutar el script.
+ Archivo **main/README.md**: documento que contiene toda la información relevante del repositorio y para ejecutar la PEC.
+ Archivo **main/Garcia_Esteban_Diagramas.html**: archivo con las visualizaciones generadas en código HTML.
## Cómo ver las visualizaciones
Acceder al siguiente enlace:
+ [3 Ejemplos Gráficos de Visualización de datos](https://htmlpreview.github.io/?https://github.com/jagarest/Visualizacion-PEC2/blob/main/Garcia_Esteban_Diagramas.html)

## Cómo usar el código generado en R
Para usar el código fuente, hay que abrir en RStudio el siguiente código fuente:
+ **main/source/Garcia_Esteban_Diagramas.rmd**: Fichero ejecutable en R. Inicia el proceso de generación de gráficos.

El código tiene las siguientes librerías que se Instalarán, en caso de que no estén instaladas ya:
```{r}
library(ggplot2)
library(dplyr)
library(hrbrthemes)
library(devtools)
library(arcdiagram)
library(igraph)
library(sf)
library(mapSpain)
library(cartogram)
library(RColorBrewer)
```
Para ejecutar el script, basta con ejecutar en R el archivo, que generará un fichero Garcia_Esteban_Diagramas.html con las visualizaciones resultantes.
## Recursos y Bibliografía
Incluimos en este apartado una lista de recursos de programación y bibliografía empleada para realizar esta PEC2 de la asignatura de Visualización de datos:
  + [Material teórico del aula: Visualización de datos](https://aula.uoc.edu/courses/35558)
  + [Espacio de recursos UOC para ciencia de datos](http://datascience.recursos.uoc.edu/es/)
  + [Buscador de código R](https://rseek.org/)  
  + [Colección de cheatsheets en R](https://www.rstudio.com/resources/cheatsheets/)  
  + [Cartogramas en ggplot2](https://r-charts.com/es/espacial/cartograma-ggplot2/) 
  + [Arcdiagram en R](https://github.com/gastonstat/arcdiagram)
  + [Connected scatterplot with R and ggplot2](https://r-graph-gallery.com/connected_scatterplot_ggplot2.html)
  + [Dataviz catalogue](https://datavizcatalogue.com/)
  + [Dataviz Project](https://datavizproject.com)
  + [Data to Viz](https://www.data-to-viz.com/)
