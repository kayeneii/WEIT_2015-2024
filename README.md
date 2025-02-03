# WEIT_2015-2024
This is a report on the analysis of world energy investment data obtained from the International Energy Agency (IEA) and a prediction of future energy investment trends.

[Overview](#overview)
[Dataset](#dataset)
[Objectives](#objectives)
[Methods](#methods)
[Insights](#insights)
[Visualizations](#visualizations)
[Predictions](#predictions)
[Conclusion](#conclusion)

# World Energy Investment Trends 2015-2024
![WEIT PNG](https://github.com/kayeneii/WEIT_2015-2024/blob/main/WEIT.png)

## Overview
This project was built to analyze and predict energy investment trends worldwide with the aid of the World Energy Investment 2024 Datafile by the IEA. The major goal was to identify key metrics and trends that help understand energy investment patterns globally, track energy typology, and identify key regions driving energy investment. Additionally, the findings of the data was used to predict future trends to ascertain probability of meeting SDG 2030 Goal.

**Disclaimer:** This is a work derived by [Adebayo Favour](https://www.linkedin.com/in/kayeneii/) from IEA material and Adebayo Favour is solely responsible for this derived work. The derived work is not endorsed by the IEA in any manner.


## Dataset
A data frame with 112 observations on 10 (numeric) variables was created from the World Energy Investment 2024 Datafile.xlsx provided by the _International Energy Agency_ (IEA). You can find it at [IEA](https://www.iea.org/data-and-statistics/data-product/world-energy-investment-2024-datafile).
![WEIT Data frame](https://github.com/kayeneii/WEIT_2015-2024/blob/main/dataframe.png)


## Objectives
To derive answers to the following questions:
  - What is the annual energy investment in:
       * Africa
       * Asia Pacific
       * Central and South America
       * Eurasia
       * Europe
       * Middle East
       * North America
  and what percentage was spent on energy generation and storage?
  - Which region recorded the highest investment in energy since 2020?
  - What was the percentage difference in energy investment across all seven regions between 2019 and 2020? Was it an increase or decrease?
  - What 3 regions had the highest investment in Clean Energy as at 2024? (Clean Energy includes: Clean Fuels, Transitional fossil fuels, Nuclear, Renewables, Storage, Electricity networks, Fossil  fuels: with CCUS and End-use.) 
  - What is the future investment trend for the next five years in:
       * Africa
       * Asia Pacific
       * Central and South America
       * Eurasia
       * Europe
       * Middle East
       * North America
  - What is the probability of each region meeting the SDG 7 [2030 Agenda for Sustainable Development](https://sdgs.un.org/2030agenda)?

    
## Methods
The following tools were used in the creation of this report.
1. **Microsoft Excel:** For data exploration, cleaning and preparation.
  * Data Cleaning and Preparation:
    - Data loading and inspection
    - Data cleaning

  * Foresight & Data Prediction: The FORECAST function was used to predict the energy investment of each region from 2025-2030.
       
2. **Microsoft Power BI:** For,
  * Further Data Processing:
    - Data loading and quality inspection
    - Data transformation and formatting

  * Data Analysis: During the analysis, the following measures were created in the Power Query to calculate the percentage of the region with the highest investment in clean energy. {i.e., Total energy investment / Asia-Pacific clean energy investment * 100}

     ```DAX Percentage = 859136000000 / 1661000000000 * 100 ```

  * Data Visualizations: Cards, Column and Line Charts were used to visually plot out the annual investment rates,  clean energy investment, energy investment profile of each region, and other summarized data.

  * Report Creation

3. **GitHUb:** For portfolio building

4. **LinkedIn:** For communication.


## Insights
Insights gotten from the data analysis include:
- Annual energy investment per region and percentage total invested in energy generation and storage.
  * Africa: $26.529 Billion was spent on energy generation and storage, making up % of her total investment of in 2024 
  * Asia Pacific: $551.036 Billion was spent on energy generation and storage, making up % of her total investment of in 2024
  * Central and South America: $44.786 Billion (USD) was spent on energy generation and storage, making up % of her total investment of in 2024
  * Eurasia: $20.29 Billion (USD) was spent on energy generation and storage, making up % of her total investment of in 2024
  * Europe: $194.43 Billion (USD) was spent on energy generation and storage, making up % of her total investment of in 2024
  * Middle East: $18.901 Billion (USD) was spent on energy generation and storage, making up % of her total investment of in 2024
  * North America: $127.593 Billion (USD) was spent on energy generation and storage, making up % of her total investment of in 2024

- The Asia-Pacific region recorded the highest investment in energy since 2020 at a total value of $895 Billion (USD) in 2020, marking its all-time lowest, and 1.29 Trillion in 2024.

- Percentage difference between 2019 and 2020 in all seven regions
   * Africa realized a 28% difference between 2019 and 2020, coming in at a **24.5% decrease** from $106 Billion (USD) in 2019 to $60 Billion USD in 2020
   * Asia-Pacific realized a 4.2% difference between 2019 and 2020, coming in at a **4% decrease** from $933.66 Billion (USD) in 2019 to $894.93 Billion USD in 2020
   * Central and South America realized a 19.4% difference between 2019 and 2020, coming in at an **18% decrease** from $114 Billion (USD) in 2019 to $94 Billion USD in 2020
   * Eurasia realized a 14% difference between 2019 and 2020, coming in at a **13% decrease** from $125.34 Billion (USD) in 2019 to $109 Billion USD in 2020
   * Europe realized a 3.8% difference between 2019 and 2020, coming in at a **3.8% increase** from $374 Billion (USD) in 2019 to $388.47 Billion USD in 2020
   * Middle East realized a 15.7% difference between 2019 and 2020, coming in at a **14.5% decrease** from $147.28 Billion (USD) in 2019 to $125.88 Billion USD in 2020
   * North America realized a 17.3% difference between 2019 and 2020, coming in at a **16% decrease** from $506.73 Billion (USD) in 2019 to $426 Billion USD in 2020
 
*Europe was the only region to record a percentage increase in energy investment between 2019 and 2020*

- The 3 regions that had the highest investment in Clean Energy as at 2024 were Asia-Pacific, Europe, and North America.


## Predictions
The future investment trend for all regions in 2025-2030 is predicted to be:
  * Africa

![WEITAfrica](https://github.com/kayeneii/WEIT_2015-2024/blob/main/Africa.png)
    
  * Asia Pacific 
    
![WEITAP](https://github.com/kayeneii/WEIT_2015-2024/blob/main/AP.png)
    
  * Central and South America 
    
![WEITCaS](https://github.com/kayeneii/WEIT_2015-2024/blob/main/CaS.png)
    
  * Eurasia

![WEITEurasia](https://github.com/kayeneii/WEIT_2015-2024/blob/main/Eurasia.png)

  * Europe

![WEITEurope](https://github.com/kayeneii/WEIT_2015-2024/blob/main/Europe.png)
   
  * Middle East

![WEITME](https://github.com/kayeneii/WEIT_2015-2024/blob/main/ME.png)

  * North America

![WEITNA](https://github.com/kayeneii/WEIT_2015-2024/blob/main/NA.png)

The United Nations Sustainable Development Goal (SDG) 7.3 Agenda states that all countries and stakeholders are required to double the global rate of improvement in energy efficiency by 2030. In 2024, the global investment in energy efficiency stood at $354.54 Billion (USD) worldwide. Therefore by 2030, this figure should have increased to at least $709 Billion (USD). The probability of this happening


## Visualizations
![WEIT1](https://github.com/kayeneii/WEIT_2015-2024/blob/main/WEIT_1.png)
![WEIT2](https://github.com/kayeneii/WEIT_2015-2024/blob/main/WEIT_2.png)
![WEIT3](https://github.com/kayeneii/WEIT_2015-2024/blob/main/WEIT_3.png)


## Conclusion
Thank you for reading my report!🥳 You may find me on [LinkedIn](https://www.linkedin.com/in/kayeneii/) for collaborations, I look forward to hearing from you.😄
