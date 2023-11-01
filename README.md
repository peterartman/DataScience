# Data Science Y4 Project Portfolio 

Piotr Artman <br>
Final Year Bsc Student SETU <br>
<img src='portrait.jpg' width='400'>

# Find more information about me here:
* [GitHub](https://github.com/peterartman)
* [LinkedIn](https://www.linkedin.com/in/piotr-artman-22105815/)

# Technical expertise:

* programming languages - Java, C++, Python, HTML, CSS, JavaScript, Git
* database/storage - local: MySQL, MongoDB,
* database/remote - (Amazon Web Services, Google Cloud)
* UI/UX design - draw.io, Figma

# Education:

* BSc. H. in Computer Science
* High Certyficate in Business

# Projects:

## Project 1: Predicting trends in price of gold bullion <br>
<br>
**Introduction**
<br>
This project aims to determine price trends for gold bullion and create a machine learning model to predict these prices in the future.
<br>
**Data sets and data sources**
<br>
**Infrastrucutre for data**
<br>
**APIs and libraries utlilised**
<br>
**Work plan**
<br>
Work plan:    1. Download bullion gold prices from NASDAQ.    https://data.nasdaq.com          DONE
              2. Download data from ECB                       https://data.ecb.europa.eu
              3. Download data from FED                       https://fred.stlouisfed.org
              4. Download data from OECD                      https://data.oecd.org
              5. Download data from EU.                       https://data.europa.eu/en
              6. Download data from Frankfurt Stock Exchange                  
              7. Import data from NASDAQ into memory 
                 and calculate moving average and use it to predict price of gold bullion.
              8. Import remaining data into memory
                 and use random forest algorithm to improve predictions. 
                 <br>
                 <br>
<!-- <br>
**Algorithms / ML models utilised**
<br>
**Other tools utilised**
<br>
**Visualisation of the project**
<br>
Verification of the project - this section contains how the accuracy of the model(s) was checked.
<br>
Outcome/result/challenges - what were the results or outcomes of the project, what challenges were faced during the project, and how were they overcome.
<br> -->
** Sample of data downloaded from NASDAQ** 

            USD (AM)  USD (PM)  GBP (AM)  GBP (PM)  EURO (AM)  EURO (PM)
Date                                                                    
1968-01-02     35.18       NaN    14.641       NaN        NaN        NaN
1968-01-03     35.16       NaN    14.617       NaN        NaN        NaN
1968-01-04     35.14       NaN    14.603       NaN        NaN        NaN
1968-01-05     35.14       NaN    14.597       NaN        NaN        NaN
1968-01-08     35.14       NaN    14.586       NaN        NaN        NaN
...              ...       ...       ...       ...        ...        ...
2023-10-24   1967.40   1963.65  1605.990   1610.78    1848.18    1849.95
2023-10-25   1970.15   1983.30  1625.180   1635.03    1864.16    1876.20
2023-10-26   1991.45   1975.00  1647.130   1630.96    1888.09    1874.67
2023-10-27   1987.60   1982.90  1636.990   1631.93    1881.26    1873.64
2023-10-30   1996.15   1997.60  1645.830   1644.82    1886.56    1883.14

** Visualisation of data downloaded **
<br>
<br>
<img src='/pictures/LBMA.png' width='580'>