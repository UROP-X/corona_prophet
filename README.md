# Corona Prophet Prediction


[![GitHub stars](https://img.shields.io/github/stars/UROP-X/corona_prophet)](https://github.com/UROP-X/corona_prophet/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/UROP-X/corona_prophet)](https://github.com/UROP-X/corona_prophet/network)
[![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/)
[![GitHub license](https://img.shields.io/github/license/UROP-X/corona_prophet)](https://github.com/UROP-X/corona_prophet/LICENSE)

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/EXYNOS-999/corona_prophet/master)


[UPDATES]
- https://www.nature.com/articles/d41586-020-00154-w?utm_source=facebook&utm_medium=social&utm_content=organic&utm_campaign=NGMT_USG_JC01_GL_Nature&fbclid=IwAR3I1vxjD05wwXbGYzqt9jnXVPE6pUiQzbTjISHT6W-niFs5MistDkL2l80
- https://public.tableau.com/profile/ankit.grover4668#!/vizhome/COVID-19_15854929469350/Story1

2019-nCoV Global Cases by Johns Hopkins

https://gisanddata.maps.arcgis.com/apps/opsdashboard/index.html#/bda7594740fd40299423467b48e9ecf6
![Coronavirus 2019-nCoV Global Cases by Johns Hopkins CSSE](media/interactive_map.png)

>***Can we build an original, comprehensive solution to help handle the crisis?***

>***We are looking to predict, visualize and act to contain the 2019 n-Coron Virus, through the power of data science.***

With the objective of understanding and minimizing epidemic spread, we devloped an method to accuractely predict and visualize the necessary features relating to **n-Corona virus** using *Time Series Analysis* and *EDA*.

The following dataset has been taken from 
[Novel Corona Virus 2019 Dataset:](https://www.kaggle.com/sudalairajkumar/novel-corona-virus-2019-dataset) along with custom feature engineering by extracting data from web.

![](media/dataset_viz_0.png)

![](media/dataset_viz_1.png)



### Kernels 

* Mathematical Simulation of nCOV Transmission Model.
* Feature engineeing and analysis of their effects in predicting extent of the nCOV Virus.
* Prediction model for expected new cases in the Mainland China region. 
* Prediction model for expected new cases in the Mainland China region.

![](media/prophet.jpg)



## Mainland China* Death Trends

Following trend indicates **daily,weekly,monthly** trend in confirmed death rates in China .It was obtained using [Prophet](https://facebook.github.io/prophet/) an open source tool for Time Series analysis.

![](media/china/trend_chart_china.png)

*Mainland China includes SAR provinces and Hong Kong.

## Uncertainty in Prediction


![](media/china/uncerntainty_prediction.png)

## Prediction with uncertainty and changepoint  

![](media/prediction_with_uncertainty.png)


![](media/changepoint.png)

## Long-term forecast and trends

![](media/long_term_forecast.png)

![](media/trend.png)

## Correlation Matrix 

Features include  **StockPrice**,**Lowest/Highest Daily Temperature**, **Humidity(%)**, **Currency**, **related search terms** such as cold,etc.

![](media/Feature_Correlation_Matrix.png)


## Feature Relationships
We explore the relationship of various features with the spread of the disease  by plotting graphs.

- Stock Price Relationship

![Stock](media/StocksEU.png)


-  Humidity  Relationship

![Stock](media/Humidity.png)


-  Flights Search  Relation

![Stock](media/CDvsFlights.png)


-  Lowest Temperature  Relation

![Stock](media/CDvsFlights.png)

# Simulations

![](media/epidemic_simulation.gif)



![](media/infection_V6.gif)

<b>Data Sources:</b><br>

* World Health Organization (WHO): https://www.who.int/ <br>
* DXY.cn. Pneumonia. 2020. http://3g.dxy.cn/newh5/view/pneumonia.  <br>
* BNO News: https://bnonews.com/index.php/2020/02/the-latest-coronavirus-cases/  <br>
* National Health Commission of the People’s Republic of China (NHC): <br>
 http://www.nhc.gov.cn/xcs/yqtb/list_gzbd.shtml <br>
* China CDC (CCDC): http://weekly.chinacdc.cn/news/TrackingtheEpidemic.htm <br>
* Hong Kong Department of Health: https://www.chp.gov.hk/en/features/102465.html <br>
* Macau Government: https://www.ssm.gov.mo/portal/ <br>
* Taiwan CDC: https://sites.google.com/cdc.gov.tw/2019ncov/taiwan?authuser=0 <br>
* US CDC: https://www.cdc.gov/coronavirus/2019-ncov/index.html <br>
* Government of Canada: https://www.canada.ca/en/public-health/services/diseases/coronavirus.html <br>
* Australia Government Department of Health: https://www.health.gov.au/news/coronavirus-update-at-a-glance <br>
* European Centre for Disease Prevention and Control (ECDC): https://www.ecdc.europa.eu/en/geographical-distribution-2019-ncov-cases 
* Ministry of Health Singapore (MOH): https://www.moh.gov.sg/covid-19
* Italy Ministry of Health: http://www.salute.gov.it/nuovocoronavirus

# References and citations 

[1] https://www.kaggle.com/sudalairajkumar/novel-corona-virus-2019-dataset

[2] https://www.cdc.gov/coronavirus/2019-ncov/index.html

[3]https://gisanddata.maps.arcgis.com/apps/opsdashboard/index.html#/bda7594740fd40299423467b48e9ecf6

[4] https://www.who.int/emergencies/diseases/novel-coronavirus-2019/technical-guidance

[5]https://www.maa.org/press/periodicals/loci/joma/the-sir-model-for-spread-of-disease-the-differential-equation-model

[6]https://facebook.github.io/prophet/

[7]https://ai.googleblog.com/2017/07/facets-open-source-visualization-tool.html

[8]https://scikit-learn.org/stable/

[9]https://seaborn.pydata.org/

[10]https://colab.research.google.com/

[11]https://github.com/CSSEGISandData/COVID-19/




