## Project Background

The data set present manufacturing production of electric baord which utilize in air conditioner.

The data set include significant manufacturing downtime causation, downtime minute and scrap units which generated in production. This project throughly analyzes this data in order to uncover critical insight that will improve production efficiency of electrice board production.

Insight and recommendations are provided on following key areas:
- Production efficiency:
  - Evaluate production performance through finish good product quantity and scrap part to understand current situation of business.
- Downtime Analysis:
  - Specify contribution factor in downtime causation and downtime occurrence timing to scope and target action priority.
- Reccomendation:
  - Provide proposal to improve process efficiency base on insign data analyst. 
  
An interactive Looker Studio dashboard can be download here.

The SQL queries utilized to inspect and perform quality check be download here.

The Python notebook to conduct data exporatory can be found here.


## Data Structure Overview
- picture of table diagram(show information linkage to each tabel)

## Executive summary
### Overview of Findings

- Overall production efficiency is 85%, with generated downtime minute x% of total production minutes, equals to loss of ~6000 electric boards.

-  Solder clog is the most contribution factor of downtime(35% of total causation) with scraping rate 2.64%.

- The afternoon shift is the worst performance efficiency(76.51%) along production month period(Jan - Apr'24) and downtime factor also.

- Average experiece year of operator in afternoon shift(5 years) is clearly lower than other shift(morning: 7 years, night: 8 years).

- Strong correlation found between operators experience year and production efficiency(coefficient factor: 0.59).

### Reccomendation
- Reccomend to deep investigate into 'solder clog' machine to find root cause of issue.



