# Financial product trend forecasting with time series and Google trends

[![lisence](https://img.shields.io/github/license/cbarros7/sentiment-analysis-banking-sector?style=plastic)](https://github.com/cbarros7/time_series_productos_financieros/blob/master/LICENSE)
[![Twitter Carlos](https://img.shields.io/twitter/follow/cbarros27?label=CarlosBarros&style=social)](https://twitter.com/cbarros27)

## Description :speech_balloon:
Forecasting is considered a key ingredient of decision making in both the public and private sectors. It is particularly important in the context of banking, both in terms of management and supervision.

The objective of this study is to forecast through time series the number of searches for the year 2021 of the main financial products based on weekly historical data of 5 years, that is, the dates from 19/07/2010 to 12/07/2020.

## Tools :hammer:
The tools used to develop the project were:
 * Jupyter Notebook - Python
 * Google trends

## Project structure :notebook_with_decorative_cover:

### Data
This study has 7 different data sets, belonging to each category of products defined above. The data has been downloaded in **[Google trends](https://trends.google.com/trends/?geo=US)** with the filter of searches in Colombia from 2015 to 2020. 


### Exploratory analysis
#### Mortgage credit
The average value of the searches for this set was 56 with a standard deviation of 14, the first quartile Q1 was located at 47, and the third quartile Q3 at 66. Its distribution is mesocuric because the value of Kurtosis was 0.16, that is, the distribution has a normal concentration in its central region. In graph 1, the density can be seen by checking the above.


<p align="center">
  <img src="https://user-images.githubusercontent.com/60367519/88868311-720e4b00-d1d5-11ea-8797-12b3610777e2.png">
</p>
<p align="center"><strong>Graph 1</strong></p>
<br>

In the first instance, it looks like a Gaussian distribution, however, it is a normal distribution since the obliquity value was 0.31 presenting the presence of outliers in the maxima as can be seen in the box and whiskers diagram.

<p align="center">
  <img src="https://user-images.githubusercontent.com/60367519/88868317-79cdef80-d1d5-11ea-946f-8367d9b628b1.png">
</p>
<p align="center"><strong>Graph 2</strong></p>
<br>

## Authors :black_nib:
**Carlos Barros** [Portfolio](https://carlosbarros.netlify.app/)
                  [Github](https://github.com/cbarros7)
                  [LinkdIn](https://www.linkedin.com/in/carlosbarros7/)
                  [Tableau Public](https://public.tableau.com/profile/carlos.barros#!/?newProfile=&activeTab=0)          
                  
**Hugo Santiago** [LinkedIn](https://www.linkedin.com/in/hugo-santiago-330b30145/) 
                  [Github](https://github.com/hfsantiago)                  
                  

