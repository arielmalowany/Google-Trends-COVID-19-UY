# Google-Trends-COVID-19-UY
### Autor: Ariel Malowany
### Fecha: 20-8-2020

Sin dudas, Google Trends es una herramienta muy útil para realizar proyectos entretenidos. En esta ocasión, exploré la popularidad en Uruguay de los términos de búsqueda: coronavirus y covid.
¿Será que los uruguayos estamos menos preocupados por el coronavirus que en Mayo? ¿O utilizamos otros términos que búsqueda diferentes de coronavirus para estar actualizados sobre las noticias de la enfermedad?

Para responder a la pregunta realicé una exploración de los datos de Google Trends mediante una animación gráfica de la evolución de la popularidad de los términos de búsqueda coronavirus y covid.

El proyecto se realizó en R y los paquetes utilizados fueron: 

* tidyverse
* stringr
* knitr
* lubridate
* tinytex
* ggrepel
* gganimate
* showtext
* gifski

Para los gráficos individuales, el código estaría pronto para ejecutar luego de hacer la consulta en Google Trends y nombrar los archivos. Para la comparación de los términos coronavirus y COVID, se descarga la consulta directamente, pero el código es un poco menos flexible (por ejemplo supone que se consultó covid vs coronavirus y no coronavirus vs covid). De todos modos, es un código de práctica.
