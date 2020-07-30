# Pronóstico de tendencia de productos financieros con series de tiempo y Google trends

[![lisence](https://img.shields.io/github/license/cbarros7/sentiment-analysis-banking-sector?style=plastic)](https://github.com/cbarros7/time_series_productos_financieros/blob/master/LICENSE)
[![Twitter Carlos](https://img.shields.io/twitter/follow/cbarros27?label=CarlosBarros&style=social)](https://twitter.com/cbarros27)

## Descripción :speech_balloon:
El pronóstico se considera un ingrediente clave de la toma de decisiones tanto en el sector público como en el privado. Es particularmente importante en el contexto de la banca, tanto por su gestión como por su supervisión.

**¿Cuál es el objetivo de este proyecto?**  El objetivo de este estudio es pronosticar a través de series de tiempo el número de búsquedas para el año 2021 de los principales productos financieros a partir de datos históricos semanales de 5 años, es decir, las fechas comprendidas desde el 19/07/2010 hasta el 12/07/2020.

## Herramientas :hammer:
The tools used to develop the project were:
 * Jupyter Notebook - Python
 * Google trends

## Project structure :notebook_with_decorative_cover:

### Adquisición de datos
#### Fuente de datos
El presente estudio tiene 7 conjuntos de datos totalmente diferentes, pertenecientes a cada categoría de productos definidos anteriormente. Los datos han sido descargados en Google trends con el filtro de búsquedas en Colombia desde el 2015 hasta el 2020.  

### Análisis exploratorio
#### Crédito hipotecario
El valor de la media de las búsquedas para este conjunto fue de 56 con una desviación estándar de 14, el primer cuartil Q1 se ubicó en 47 y el tercero Q3 en 66. Su distribución es mesocúrtica debido a que el valor de Kurtosis fue de 0.16, es decir, que la distribución tiene una concentración normal en su región central. En el gráfico 1 se puede observar la densidad comprobando lo anterior.

<p align="center">
  <img src="https://user-images.githubusercontent.com/60367519/88868311-720e4b00-d1d5-11ea-8797-12b3610777e2.png">
</p>
<p align="center"><strong>Gráfico 1</strong></p>
<br>

En primera instancia parece una distribución gaussiana, sin embargo, es una distribución normal ya que el valor de oblicuidad fue de 0.31 presentando presencia de valores atípicos en los máximos tal y como se puede observar en el diagrama de caja y bigotes.

<p align="center">
  <img src="https://user-images.githubusercontent.com/60367519/88868317-79cdef80-d1d5-11ea-946f-8367d9b628b1.png">
</p>
<p align="center"><strong>Gráfico 2</strong></p>
<br>

## Authors :black_nib:
**Carlos Barros** [Portfolio](https://carlosbarros.netlify.app/)
                  [Github](https://github.com/cbarros7)
                  [LinkdIn](https://www.linkedin.com/in/carlosbarros7/)
                  [Tableau Public](https://public.tableau.com/profile/carlos.barros#!/?newProfile=&activeTab=0)          
                  
**Hugo Santiago** [LinkedIn](https://www.linkedin.com/in/hugo-santiago-330b30145/) 
                  [Github](https://github.com/hfsantiago)                  
                  

