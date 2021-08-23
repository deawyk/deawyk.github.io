---
layout: page
title: Projects
# subtitle: I am a smart heading.
desc: My portfolio projects.
permalink: /project/
---

<div class="pretty-links">

    
<div class="lead lead-about">Have patience. <br>
    Leonardo Da Vinci called it "sfumato" (smoke). It's the idea that not everything is clear, and the desire to have an answer can lead someone into error. Intelligence is signified by having patience with difficult, dense, or even ambiguous or vague subjects, and showing resilience when presented with unclear, indefinite questions or answers. 
<div style="text-align: left">
    
<!-- {::nomarkdown} 
<figure class="site-profile">
    <img src="{{ site.baseurl }}/assets/img/profile.png">
</figure>
{:/} -->

---

### [Automated Trading System with APIs](https://github.com/deawyk/Automated-Trading-System-via-APIs/blob/main/automated%20trading%20tda%20api.py)
**A trading bot that trades stocks for you using TD Ameritrade API in Python.**
    
I wrote multiple Classes for trading actions using [tda-api](https://pypi.org/project/tda-api/). User could determine choice of stock, trading interval, and investment strategy. In the example I used RSI or EMA thresholds ([ta](https://technical-analysis-library-in-python.readthedocs.io/en/latest/) for financial ratios) to trigger actions. Process was automated end-to-end by importing Selenium and Chrome Driver to login.
<img src="{{ site.baseurl }}/assets/img/git.tb1.png">
    
    
### [Customer Segmentation with K-means](https://github.com/deawyk/Customer-Segmentation-via-KMeans/blob/main/CS_KMeans.ipynb)
**Customer segmentation and cohort analysis on real retail data using k-means clustering.**
    
Cleaned and explored over 500k records of retail data from an UK based online store. Dynamically converted prices in GBP based on fx rate at date of purchase ([currency converter](https://pypi.org/project/CurrencyConverter/)); conducted behavioural analysis on each cohort; calculated CLV and success metrics. My heuristic approach using RFM segmentation was analyzed against outputs from k-means algorithm (minimizes within cluster variances), which resulted in 69% congruence. I explained business implications and recommended best practice in my presentation to a business-oriented audience.<br>
<i class='fa fa-file-text'></i>[Customer Segmentation Presentation](/assets/pdf/git.customerseg.pdf)
<img src="{{ site.baseurl }}/assets/img/git.cs1.png">

    
### [Google BigQuery ETL and KPI Dashboard](https://github.com/deawyk/Google-Analytics-KPIs-via-Google-BigQuery/blob/main/BigQuery%20Script.sql)
**A high-level to granular dashboard in Tableau using Google BigQuery ETL from Google Analytics Sample data.**
    
I wrote SQL-like queries for the metrics: Total Pageviews, Total Unique Pageviews, Total Entrances, Total Exits, Total Time on Page, Total Sessions, and Total Bounces. Presented business intelligence using Tableau. <br>
[Google Merchandise Store Dashboard](https://public.tableau.com/views/gms_16221492319430/1?:language=en-US&:display_count=n&:origin=viz_share_link)
<img src="{{ site.baseurl }}/assets/img/git.ga1.png">          

    
### [Comprehensive Webscraping with Regex](https://github.com/deawyk/Webscraping-Three-Ways/blob/main/pipeline.py)
**Webscraping using Regex, Selenium, BeautifulSoup to download financial data into workable dataframes.**
    
Built data pipelines for three diversely formatted sites to compile data via [yfinance](https://pypi.org/project/yfinance/), with emphasis on regex.
<img src="{{ site.baseurl }}/assets/img/git.ws2.png">
    
---
    
### Conclusion
<p> As an analyst, the goal is simply *to see*. Amongst an inordinate amount of KPIs, my goal is to identify the disproportionately valuable ones which drive the biggest impact. Often, they are the ones to get the most pushback interdepartments. They are also the most difficult and stubborn KPIs to move.<br>
    
In my everyday work, I lay groundwork by interviewing and learning from subject-matter experts to get a clear definition of the business problem. Then, data become my solutions book. I'll iterate, incrementally improve, and apply creativity on my endeavor to a resolve, providing _Aha_ moments along the way.<br>
    
The beauty of data is that it is falseless and fair. How well data help businesses grow largely depend on their application.</p>

