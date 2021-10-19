---
layout: page
title: Projects
# subtitle: I am a smart heading.
desc: My portfolio projects.
permalink: /projects/
---

<div class="pretty-links">

    
<div class="lead lead-about">

I generally spend 1-2 weeks working on each project (My bandwidth for long-term projects is strictly reserved for work). The ideation process is spontaneous, usually whenever personal interest, time, and an learning opportunity align.

I veer toward human problems that often deal with dense, ambiguous subjects; and present indefinite answers and even more questions. Working through them has made me more comfortable with uncertainty.
    
<div style="text-align: left">
    
<!-- {::nomarkdown} 
<figure class="site-profile">
    <img src="{{ site.baseurl }}/assets/img/profile.png">
</figure>
{:/} -->

---
## [Talent Migration and Time Series Forecasting](https://public.tableau.com/app/profile/dea.wang/viz/WorldBankLinkedInInsights/StoryInsights)
**A storyboard and predictive model that explains and forecasts country, industry, and skills migration of talents globally.** 

<img src="{{ site.baseurl }}/assets/img/git.talentmigration1.png">

**Forecasting Model Demo**
<img src="{{ site.baseurl }}/assets/img/git.talentmigration2.png">    
<br>  
    
## <i class='fa fa-file-text'></i>[Return-to-Office Recommender](/assets/pdf/git.o2analytics.pdf)
**Building a recommender system to classify and predict workplace health & safety and exigency of return-to-office admist the pandemic.**

**Prototype Pitch Draft**
<img src="{{ site.baseurl }}/assets/img/git.office.png">
<br>  

## [Automated Trading System with APIs](https://github.com/deawyk/Automated-Trading-System-via-APIs/blob/main/automated%20trading%20tda%20api.py)
**A trading bot that trades stocks for you using TD Ameritrade API in Python.**
    
I wrote multiple Classes for trading actions using [tda-api](https://pypi.org/project/tda-api/). The stock, trading interval, and investment strategy of choice is user-determined. In the example, I used RSI or EMA thresholds ([ta](https://technical-analysis-library-in-python.readthedocs.io/en/latest/) for financial ratios) to trigger actions. Process was automated end-to-end with Selenium.
<br>    
    
    
## [Customer Segmentation with Heurisitics and K-means](https://github.com/deawyk/Customer-Segmentation-via-KMeans/blob/main/CS_KMeans.ipynb)
**Customer segmentation and cohort analysis on real retail data using k-means clustering.**
    
Cleaned and explored over 500k records of real retail data from an UK based online store. Dynamically converted prices in GBP based on fx rate at date of purchase ([currency converter](https://pypi.org/project/CurrencyConverter/)); conducted behavioural analysis (CLV etc.) on each cohort. My heuristic approach using RFM segmentation was analyzed against outputs from k-means algorithm (minimizes within cluster variances), which resulted in 69% congruence. I focused my presentation on defining the busines problem and giving recommendations for action.<br>
<i class='fa fa-file-text'></i>[Customer Segmentation Presentation](/assets/pdf/git.customerseg.pdf)
<img src="{{ site.baseurl }}/assets/img/git.cs1.png">
<br>
    
    
## [Google Cloud Platform ETL and BI Reporting](https://github.com/deawyk/Google-Analytics-KPIs-via-Google-BigQuery/blob/main/BigQuery%20Script.sql)
**Tableau report composed of three dashboards outlining high-level, ad-hoc, and KPI needs.**
    
Amongst the inordinate amount of KPIs, I tried to identify the disproportionately valuable ones which drive the biggest impact. Using Google BigQuery and Google Analytics Sample data, I wrote SQL-like queries for the metrics: Total Pageviews, Total Unique Pageviews, Total Entrances, Total Exits, Total Time on Page, Total Sessions, and Total Bounces.<br>
[Google Merchandise Store Dashboard](https://public.tableau.com/views/gms_16221492319430/1?:language=en-US&:display_count=n&:origin=viz_share_link)
<img src="{{ site.baseurl }}/assets/img/git.ga1.png">          
<br>
    
    
## [Webscraping Three Ways](https://github.com/deawyk/Webscraping-Three-Ways/blob/main/pipeline.py)
**Webscraping using Regex, Selenium, BeautifulSoup to download financial data into workable dataframes.**
    
Built data pipelines for three diversely formatted sites to compile data via [yfinance](https://pypi.org/project/yfinance/), with emphasis on regex.
    
---

