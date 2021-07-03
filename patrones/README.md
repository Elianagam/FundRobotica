# ¿Y dónde está Messi?

La manera más simple de buscar algo en una imagen es si conocemos de antemano lo que estamos buscando. La manera de buscar entonces es, definida una plantilla, realizar la cross-correlación de esa plantilla en la imagen y mediante algún estimador (como el error cuadrático medio) definir dónde es que estuvo más cerca de coincidir. Muchas veces es necesario buscar estos patrones a distinta resolución o escala, por lo que se presenta el concepto de pirámides y de transformaciones geométricas.

## Objetivo de la semana

A partir del patrón de la cara de Messi (el cual debe ser seleccionado de entre las imágenes) encontrarlo en cada una de las imágenes en las que Messi aparece. Se pide un algoritmo automático que frente a la lectura sucesiva de estas imágenes (y si quieren, pueden probar con imágenes que encuentren ustedes) devuelva la posición de la cara de Messi dentro de la imagen y el nivel de confianza con el que fue hallada (deben definir también el nivel de confianza propuesto).