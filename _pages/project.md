---
layout: page
title: Projects
# subtitle: I am a smart heading.
desc: My portfolio projects.
permalink: /project/
---

<div class="pretty-links">

    
<div class="lead lead-about">There are three classes of people: those who see, those who see when shown, and those that do not see.<br>
<div style="text-align: right"> Leonardo Da Vinci
<div style="text-align: left">
    
<!-- {::nomarkdown} 
<figure class="site-profile">
    <img src="{{ site.baseurl }}/assets/img/profile.png">
</figure>
{:/} -->

---
<div>
### [Customer Segmentation with K-means](https://github.com/deawyk/Customer-Segmentation-via-KMeans/blob/main/CS_KMeans.ipynb)
**Customer segmentation and cohort analysis on real retail data using k-means clustering.**<br>
I cleaned and explored over 500k records of retail data from an UK based online store. Prices in GBP was dynamically converted based on currency rate ([currency converter](https://pypi.org/project/CurrencyConverter/)) at date of purchase. Behavioural analysis was conducted on each cohort; average purchase value, customer value, CLV, were determined to draw further insights. My heuristic approach to segmentation using RFM was compared to the definitive k-means algorithm (minimizes within cluster variances). Tellingly, the unsupervised ML output had 69% congruence to the heuristic approach. Presentation was visual heavy and intended for business-oriented audience.
<i class='fa fa-file-text'></i>[Presentation](/assets/pdf/git.customerseg.pdf)
<img src="{{ site.baseurl }}/assets/img/git.cs1.png">
<img src="{{ site.baseurl }}/assets/img/git.cs2.png">
    
### [Automated Trading System with APIs](https://github.com/deawyk/Automated-Trading-System-via-APIs/blob/main/automated%20trading%20tda%20api.py)
**A trading bot that trades stocks for you using TD Ameritrade API in Python.**<br>
I used [tda-api](https://pypi.org/project/tda-api/) for most trading actions. The stock and time interval to trade at is determined by user input. Investment strategies are altered accordingly. Here, I bought and sold stocks by setting RSI ([ta](https://technical-analysis-library-in-python.readthedocs.io/en/latest/) for financial ratios) thresholds to trigger action. I automated the process end-to-end by importing Selenium and Chrome Driver for automatic login.
<img src="{{ site.baseurl }}/assets/img/git.tb1.png">

### [Google BigQuery ETL and KPI Dashboard](https://github.com/deawyk/Google-Analytics-KPIs-via-Google-BigQuery/blob/main/BigQuery%20Script.sql)
**A high-level to granular dashboard in Tableau using Google BigQuery ETL from Google Analytics Sample data.**<br>
I wrote SQL-like queries for the metrics: Total Pageviews, Total Unique Pageviews, Total Entrances, Total Exits, Total Time on Page, Total Sessions, and Total Bounces.
    
### [Comprehensive Webscraping with Regex](https://github.com/deawyk/Webscraping-Three-Ways/blob/main/pipeline.py)
**Webscraping using Regex, Selenium, BeautifulSoup to download financial data into workable dataframes.**<br>
I built three data pipelines for diversely formatted sites to compile stock market data via [yfinance](https://pypi.org/project/yfinance/), with an emphasis on learning regex.
<img src="{{ site.baseurl }}/assets/img/git.ws2.png">
---
    
### Conclusion
<p> As a data analyst, the goal is simply *to see*. Amongst an inordinate amount of KPIs, my goal is to identify the disproportionately valuable ones which drive the biggest impact. Often, they are the ones to get the most pushback cross-departments. They are also the most difficult and stubborn KPIs to move.<br>
    
I like to lay groundwork by learning from and interviewing subject-matter experts to get a clear definition of the business problem. Then, data become my solutions book. I'll iterate, incrementally improve, and apply creativity in pursuit of a resolve, having some _Aha_ moments along the way.<br>
    
The beauty of data is that it is falseless and fair. How well data help businesses grow largely depend on the application.</p>

