## Project Background

The data set present manufacturing production of electric baord which utilize in air conditioner.

The data set include significant manufacturing downtime causation, downtime minute and scrap units which generated in production. This project throughly analyzes this data in order to uncover critical insight that will improve production efficiency of electrice board production.

Insight and recommendations are provided on following key areas:
- _**Production Efficiency Analysis:**_ Evaluate production performance through finish good product quantity and scrap part to understand current situation of business.
  
- _**Downtime Analysis:**_ Specify contribution factor in downtime causation and downtime occurrence timing to scope target improvement action.
  
- _**Conclusion & Reccomendation:**_ provide proposal to improve process efficiency base on insign data analyst. 
  
An interactive Looker Studio dashboard can be download here.

The SQL queries utilized to inspect and perform quality check be download here.

The Python notebook to conduct data exporatory can be found here.


## Data Structure Overview
- picture of table diagram(show information linkage to each tabel)

## Executive summary

_**Reccommend Strategic**_ to <ins>_increase +12% process efficiency and reduce -22% of system downtime_</ins>  _<ins>by allocate high experience operator into afternoon shift</ins>_ and _<ins>increase actual productio minute</ins>_. This strategic pivot will instantly improve.

_**Impact Business Cost**_ _<ins>lost 9% of total production(188 labuor hours)</ins>_ from frequent system downtime and part scrap. 
Even overall performace of downtime decrease -6% and scrap slighly increase +0.8% over period but accumulation amount cause a huge impact cost. The primary driver of current inefficiency.

_Analysis confirm_ that experience year of operator and production time usage are influential to process efficiency and frequent of downtime occurence. Assumption is operator with high experience able handle machine and manage error situation better than low experience person.

![Alternative text for the image](https://github.com/Pakawat2878/Manufacturing-Downtime-Analysis/blob/main/Manufacturing%20KPI.png)

## Deep Insign Analysis

### Process Efficiency:
- **_Overall Production Efficiency has slightly change by +1.3%_**. The system downtime minute -6.05 and scrap unit by +0.77%. By the way, accumulation of downtime and scrap unit cause <ins>_estimated lost 9% of production_</ins>.
  
![Alternative text for the image]()


#### Product Model Performance
- **_47% of product volume contributed By model-x_**, 32% and 20% for model-y and z respectively. interm of downtime minute and scrap unit also according to production volume.
  
- **Product volume trends:** average production volume is _<ins>**up trend for all model since January to April**</ins>_.
- **Downtime minutes trends:** sum of downtime minutes _<ins>end up with down trend in product-y and z ( -10% and -17% change respectively) </ins>_ for product x a bit increase 5%(comparison between Jan and Apr).
  
- **Downtime minute swing direction**: _<ins>Product-z has opposite trend direction from model-x and y</ins>_.
- **Reccommend** to <ins>investigate production process and part structure different between product model-x,y and z-pro.</ins>

![Alternative text for the image](Dashboard which show overall KPI)


### Downtime Analysis:
#### Overall Trend Analysis
- _**There small change in downtime minute in Feb'24 average downtime increase around 6%**_(30 to 32 mins), _**after Feb'24 trends to decrease to same level as Jan'24**_ at end of Apr'24(29 mins)
- Average Scrap rate a bit increase during Jan - Feb(0.1%) after Feb'24 scrap unit quite constant at 1.5%.

#### Shift Assignment Analysis
- _**The lowest performance was conducted in afternoon shift**_(process efficiency: 77%) and low number of operator experience year(average 5 years).
  
- _Assumption is_ operator with _<ins>high experience able to manage error in production better than operator with less experience.</ins>_. Analysis result confirm _<ins>strong correlation between operator experience and process efficiency</ins>_ (coeff: 0.71).
  
- **Reccomend:** <ins>_allocate operator with high service years to afternoon shift_</ins> to increase efficiency of process.

  
![Alternative text for the image](Lind graph which show prcess efficiency in Afternoon shift)

#### Downtime Causation Analysis
- **_<ins>Reccomend prioritize investigate on 'Solder clog' and 'Compoenet feed error'</ins>_** issue first** becaue of high severity level in downtime minute and scraping rate 2.9.

- **_35% of downtime minute_** was contributed by **_Solder clog_**. Then follow by _**component feed error 30%**_. Material shortage(17%) and vision system issue 15%.

- **_Compoenent feed error issue is the highest average downtime minutes(37 mins)_**. Follow by Vission system(36 mins), compoent feed error(35 mins) and solder clog(33 mins). <ins>Overview, there's no much different in each causation</ins>.

![Alternative text for the image](bar graph which show ratio of downtime causation)
  
- **Downtime causation trends:** <ins>sum of downtime minute is **up trends in 'Solder Clog' and 'Material Shortage'** for +16% and +7%</ins> respectively since January month while <ins>**'Vission system issue' and 'Component feed error' are opposite with down trends**</ins> since January.
  
**_Interpret trends:_ frequency of 'Solder clog' and 'Material Shortage' increase during period**. Confirm by <ins> **sum of downtime increase while average downtime reduce**</ins>.

![Alternative text for the image](bar graph which show +/- %change of overall downtime minute over period)

- **_Strong Negative Correlation_** was found between _**downtime minute and actual production minute**_(corr coeff = -0.85).Same correlation pattern as individaul downtime causation(less than - 0.80). Assumpation:

![Alternative text for the image](bar graph which show correlation graph between Eff vs Exp
![Alternative text for the image](box graph which show range of experience years in each shift assignment)


### **Conclusion & Reccomendation**
1. _**Quick action approach:**_ Allocate high exeperience to afternoon shift to improve process efficiency.
2. _**Mid term plan of root cause analysis:**_ Deep investigate root cause of downtime minute, focus high contributing factor(Solder Clog & Component Feed Error) by ask support from facility team to analyze data record of machine.



