# Caso Práctico Python

## Contexto

El Informe Mundial de la Felicidad es una encuesta histórica sobre el estado de la felicidad global. El primer informe se publicó en 2012, el segundo en 2013, el tercero en 2015 y el cuarto en la actualización de 2016. El World Happiness 2017, que clasifica a 155 países según sus niveles de felicidad, se lanzó en las Naciones Unidas en un evento que celebra el día internacional de la felicidad el 20 de marzo. El informe continúa ganando reconocimiento mundial a medida que los gobiernos, las organizaciones y la sociedad civil utilizan cada vez más los indicadores de felicidad para informar de sus decisiones de formulación de políticas. Los principales expertos en todos los campos (economía, psicología, análisis de encuestas, estadísticas nacionales, salud, políticas públicas y más) describen cómo las mediciones de bienestar se pueden usar de manera efectiva para evaluar el progreso de las naciones.

## Contenido 

Los puntajes y clasificaciones de felicidad utilizan datos de la encuesta mundial Gallup. Las puntuaciones se basan en las respuestas a la pregunta principal de evaluación de la vida formulada en la encuesta. Esta pregunta, conocida como la escalera de Cantril, les pide a los encuestados que piensen en una escalera con la mejor vida posible para ellos con un 10 y la peor vida posible con un 0 y que califiquen sus propias vidas actuales en esa escala. Las puntuaciones provienen de muestras representativas a nivel nacional para los años 2013-2016 y utilizan los pesos de Gallup para hacer que las estimaciones sean representativas. Las columnas que siguen la puntuación de felicidad estiman el grado en que cada uno de los seis factores (producción económica, apoyo social, esperanza de vida, libertad, ausencia de corrupción y generosidad) contribuyen a que las evaluaciones de vida sean más altas en cada país que en la distopía, un país hipotético que tiene valores iguales a los promedios nacionales más bajos del mundo para cada uno de los seis factores. No tienen impacto en el puntaje total reportado para cada país, pero sí explican por qué algunos países tienen una clasificación más alta que otros.

## ¿Qué es la distopía?

La distopía es un país imaginario que tiene las personas menos felices del mundo. El propósito de establecer la distopía es tener un punto de referencia con el que todos los países puedan ser comparados favorablemente (ningún país tiene un desempeño más pobre que la distopía) en términos de cada una de las seis variables clave, lo que permite que cada barra sea de ancho positivo. Las puntuaciones más bajas observadas para las seis variables clave, por lo tanto, caracterizan la distopía. La vida sería muy desagradable en un país con los ingresos más bajos del mundo, la esperanza de vida más baja, la generosidad más baja, la mayoría de la corrupción, la menor libertad y el menor apoyo social, en contraste con la utopía.

Toda la información del dataset puede ser ampliada desde el siguiente enlace: https://www.kaggle.com/unsdsn/world-happiness

## Se pide

Sobre los informes de felicidad de 2015 y 2016, realizar las siguientes exploraciones:

* Cargar los dos CSV como datasets.
* Identificra las columnas de ambos datasets: ¿hay diferencias entre ambos?
* Une ambos dataframes, sin importar que los dos compartan las mismas diferencias.
* Revisa el número de nulos que hay por cada columna, así como su porcentaje.
* Cambia los valores nulos de las columnas "Lower Confidence Interval" y "Upper Confidence Interval" por un número aleatorio entre el valor mínimo y máximo de la misma columna (un único número, no es necesario uno diferente para cada fila con valor nulo).
* Cambia los valores nulos de la columna "Standard Error" por su media al cuadrado.
* Obtén un resumen estadístico del dataframe sin valores nulos.
* Muestra de forma gráfica la relación entre la familia y la salud.
* Muestra de forma gráfica la relación entre la puntuación de felicidad y la confianza (corrupción del gobierno).
* Muestra la matriz de correlación del daframe.
* Tras unir los dataframes, los países aparecerán más de una vez. Muestra agrupado el dataframe por país con el valor máximo de felicidad, sin importar el año.
* ¿Tiene relación la felicidad con la generosidad? Muéstralo gráficamente a través de la puntuación de libertad.
* Muestra la distribución del grado de distopía en función de la región.
