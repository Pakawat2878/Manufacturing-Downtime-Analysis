## Project Background

The data set present manufacturing production of electric baord which utilize in air conditioner.

The data set include significant manufacturing downtime causation, downtime minute and scrap units which generated in production. This project throughly analyzes this data in order to uncover critical insight that will improve production efficiency of electrice board production.

Insight and recommendations are provided on following key areas:
- Production Efficiency Analysis: Evaluate production performance through finish good product quantity and scrap part to understand current situation of business.
- Downtime Analysis: Specify contribution factor in downtime causation and downtime occurrence timing to scope target improvement action.
- Reccomendation: provide proposal to improve process efficiency base on insign data analyst. 
  
An interactive Looker Studio dashboard can be download here.

The SQL queries utilized to inspect and perform quality check be download here.

The Python notebook to conduct data exporatory can be found here.


## Data Structure Overview
- picture of table diagram(show information linkage to each tabel)

## Executive summary
### Overview of Findings
Overall production has small change performance along production period. Key performance indicator have shown a bit change in process efficiency by -x%, scrap unit by +x% and downtime minute by +x%. However, accumulation in scrap quantity and downtime minute provide huge impact to business cost. Following section will explore contributing factor and highlight key opportunity area for improvement.

- picture of KPI dashboard


### Process Efficiency:
- Overall production efficiency is 85%, with small change during production period Jan - Apr'24 with total downtime minute xx mins and total scrap unit xx pcs.
- Business impact from scrap unit and downtime can be estimated as  xx% of total product loss.
- Along production period Jan - Apr'24, the lowest production efficiency was occured in afternoon shift by average 75.6% compare to other shift assignment.
- picture of line graph show performance level of each production shift



### Downtime Analysis:
- Accumulation of downtime munite xx cause business impact by equals to ~6000 pieces of electric board loss.
-  35% of downtime causation come from solder clog with the highest percentage of scrap rate by 2.64%.

- Average experience year of operator in afternoon shift(5 years) is clearly lower than other shift(morning: 7 years, night: 8 years).

- Strong correlation found between operators experience year and production efficiency(coefficient factor: 0.59).

### Reccomendation
- Temporary solution: allocate high experience year operator to afternoon shift to increase production efficiency.
- Reccomend to deep investigate into 'solder clog' machine to find root cause of issue.



