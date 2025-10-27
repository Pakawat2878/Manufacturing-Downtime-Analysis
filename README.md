## Project Background

The data set present manufacturing production of electric baord which utilize in air conditioner.

The data set include significant manufacturing downtime causation, downtime minute and scrap units which generated in production. This project throughly analyzes this data in order to uncover critical insight that will improve production efficiency of electrice board production.

Insight and recommendations are provided on following key areas:
- _**Production Efficiency Analysis:**_ Evaluate production performance through finish good product quantity and scrap part to understand current situation of business.
  
- _**Downtime Analysis:**_ Specify contribution factor in downtime causation and downtime occurrence timing to scope target improvement action.
  
- _**Reccomendation:**_ provide proposal to improve process efficiency base on insign data analyst. 
  
An interactive Looker Studio dashboard can be download here.

The SQL queries utilized to inspect and perform quality check be download here.

The Python notebook to conduct data exporatory can be found here.


## Data Structure Overview
- picture of table diagram(show information linkage to each tabel)

## Executive summary
### Overview of Findings

**_WE RECCOMMEND stretegic_** to <ins>_improve +12% process efficiency and reduce -22% of system downtime_</ins> and  _<ins>by allocate high experience operator into afternoon shift</ins>_ and _<ins>increase actual productio minute(from 433 to 440 minutes)</ins>_

**Immediate action is required to resolve process efficiency and poor downtime management**. 
We recommend instantly allocation high experience operator into afternoon shift and increase production minute to reduce downtime minute. This strategic pivot will instantly improve.

**This plan targets the 15% surge in scrap costs and the frequent system downtime that has cost 188 lost labor hours.** While our high-cost phone support remains effective (92% resolution rate), the unmanaged 45% increase in chat volume, coupled with its low 78% resolution rate, is the primary driver of current inefficiency and customer dissatisfaction.


<ins>**_Accumulation of scrap and downtime minute cause business impact by xx% of total cost._**</ins>
As key performance indicator have shown _scrap unit by +x% and downtime minute by +x%_ during producttion period(Jan - Apr'24). Following section will explore contributing factor and highlight key opportunity area for improvement.

- picture of KPI dashboard

### Process Efficiency:
- <ins>**_Overall production efficiency has small fluctuate during Jan - Apr'24_**</ins> by +x%, average downtime minute xx and average scrap by xx.
However, accumulated downtime minute(xx mins) and scrap unit(xx pcs) as <ins>estimated loss xx% of production.</ins>
  
- <ins>_**XX% of downtime and xx% of scrap was perform under afternoon shift**_</ins> with the worst efficiency 76.51% along production period(Jan - Apr). This number has shown that shift assignment is influent to production performance.

![Alternative text for the image](https://github.com/Pakawat2878/Manufacturing-Downtime-Analysis/blob/main/Eff_produciton_shift.png)


### Downtime Analysis:
-  <ins>_35% of downtime causation come from solder clog_</ins> Then following by other factor 30%, 17%, 15% for 'component feed error', 'material shortage' and 'vision system issue' respectively.
  The highest scrap unit came from Solder clog causation also.

![Alternative text for the image](https://github.com/Pakawat2878/Manufacturing-Downtime-Analysis/blob/main/Picture1.png)

- _<ins>Lower average experience year was assigned in the aftrernoon shift</ins>_ when compare to other shift. Clearly lower than morning: -x years and Night -x years. As analsysis, there's strong correlation coefficient 0.59 between operators experience year and production efficiency, assumption is operator experience is influent.


### Reccomendation
- Temporary solution: allocate high experience year operator to afternoon shift to increase production efficiency.
- Reccomend to deep investigate into 'solder clog' machine to find root cause of issue.



