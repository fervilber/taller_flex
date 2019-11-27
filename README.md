---
output:
  pdf_document: 
    fig_crop: no
  html_document: default
---

![enRdados logo](imag/Logo_enrdados_blanco.png.png)

# Taller: Shiny fácil con flexdashboard


Cómo hacer aplicaciones web dinámicas con R.

## DESCRIPCION DEL TALLER
[flexdashboard](https://rmarkdown.rstudio.com/flexdashboard/)  es una extensión de *RMarkdown* para realizar informes web que denominados genéricamente tableros o paneles.

En el taller empezaremos por explorar esta librería decubrir su uso y ver las enormes posibilidades que tiene.

Haremos varios ejercicios empezando por crear nuestro primer tablero simple y estático al que añadiremos complejidad y reactividad según avancemos conceptos y recursos.

Exploraremos entre otras cosas: cómo visualizar datos, gráficos y mapas de forma interactiva, cómo dotar a nuestra aplicación de reactividad a las acciones que realice el usuario, la introduccion dinámica de datos y parámetros mediante botones, selectores, barras slide o clicks en *htmlwidgets*... así como a personalizar la apariencia y formato de la web final.

Después del taller tendrás las herramientas y la base para crear aplicaciones web con R y presentar tus informes, trabajos, modelos o análisis de una forma atractiva, dinámica y con funcionalidad en tiempo real. Un mundo de posibilidades para mostrar tus ideas y creacciones por Internet. 

## REQUERIMIENTOS
Se requiere un conocimiento básico de R y el entorno RSTUDIO para trabajar.

Por favor, traiga su propio portátil con R, RSTUDIO así como las siguientes librerías instaladas si quiere realizar los ejercicios activamente durante el taller:

-	flexdashboard
- Shiny
- crosstalk
-	leaflet
- plotly
-	DT
- ggplot2
- dygraphs
- crosstalk
- purrr
- magick
- quantmod
- forecast

Para instalar los paquetes puedes usar este script:

```YAML
paquetes<-c("flexdashboard", "Shiny", "crosstalk",	"leaflet", "plotly",	"DT", "ggplot2", ,"dygraphs", "crosstalk", "purrr", "magick", "quantmod", "forecast")
install.packages(paquetes)

```

## CÓDIGO DE CONDUCTA
Esperamos que todos los asistentes cumplan con nuestro Código de conducta UMUR.
Este grupo fue creado para que quienes se identifican como usuarios de R tengan un lugar  para aprender y disfrutar.
