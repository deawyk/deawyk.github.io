---
layout: page
title: Projects
# subtitle: I am a smart heading.
desc: My portfolio projects.
permalink: /project/
---

<div class="pretty-links">

    
<div class="lead lead-about">There are three classes of people: those who see, those who see when shown, and those that do not see.<br></div>
<div style="text-align: right">- Leonardo Da Vinci</div>

<!-- {::nomarkdown} 
<figure class="site-profile">
    <img src="{{ site.baseurl }}/assets/img/profile.png">
</figure>
{:/} -->


---
<div>
### [Automated Trading System with APIs](https://github.com/deawyk/Automated-Trading-System-via-APIs/blob/main/automated%20trading%20tda%20api.py)
***A trading bot that trades stocks for you using the TD Ameritrade API in Python.***
*I used [tda-api](https://pypi.org/project/tda-api/) for most trading actions. The stock and time interval to trade at is determined by user input. Investment strategies are altered accordingly. Here, I bought and sold stocks by setting RSI ([ta](https://technical-analysis-library-in-python.readthedocs.io/en/latest/) for financial ratios) thresholds to trigger action. I automated the process end-to-end by importing Selenium and Chrome Driver for automatic login.*
    
### [Customer Segmentation using K-Means](https://github.com/deawyk/Customer-Segmentation-via-KMeans)
***Customer segmentation and cohort analysis on real retail data using k-means clustering.***
*I cleaned and explored over 500k records of retail data from an UK based online store. Behavioural analysis was conducted on each cohort; average purchase value, customer value, CLV, were determined to draw further insights. My heuristic approach to segmentation using RFM was compared to the definitive k-means algorithm (minimizes within cluster variances). Tellingly, the unsupervised ML output had 69% congruence to the heuristic approach. Presentation was visual heavy and intended for a business-oriented audience. Also, I dynamically converted price based on the currency rate at the date of purchase using [Currency Converter](https://pypi.org/project/CurrencyConverter/).*

### [Google BigQuery ETL and KPI Dashboard](https://github.com/deawyk/Google-Analytics-KPIs-via-Google-BigQuery/blob/main/BigQuery%20Script.sql)
***A high-level to granular dashboard in Tableau using data extracted via Google BigQuery from Google Analytics Sample data.***
*I wrote SQL-like queries for the metrics: Total Pageviews, Total Unique Pageviews, Total Entrances, Total Exits, Total Time on Page, Total Sessions, and Total Bounces.*
    
### [Comprehensive Webscraping with Regex](https://github.com/deawyk/Webscraping-Three-Ways)
***Comprehensive Webscraping using Regex, Selenium, BeautifulSoup to download financial data into workable dataframes.***
*I built three data pipelines for diversely formatted sites to compile stock market data via [yfinance](https://pypi.org/project/yfinance/), with an emphasis on learning regex.*

---
    
<div>
### Conclusion
    In all my projects, the goal is simply _to see_. Amongst an inordinate amount of KPIs, I want to identify the disproportionately valuable ones which drive the greatest impact. Usually, they are the ones that get the most pushback cross-departments, because they are the most difficult and stubborn KPIs to move. 
    I like to lay groundwork by learning from and interviewing subject-matter experts to get a clear definition of the business problem. Data then becomes my solutions book. I spend most of my time iterating, incrementally improving, and applying some creativity to the answer. I love having _Aha_ moments throughout the process. 
    The beauty of data is that it is falseless and fair (the truth). How well data can help businesses grow depends solely on its application.

