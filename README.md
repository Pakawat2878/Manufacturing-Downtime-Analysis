## Project Background

The data set present manufacturing production of Air Conditioner company in part of assembly process.

The data set include significant manufacturing downtime causation, minute amount and operation efficiency. This project throughly analyzes this data in order to uncover critical insight that will improve production efficiency of Air Condition product.

Insight and recommendations are provided on followig key areas:
- Downtime Analysis:
  - Evaluate historical downtime, focusing on total accumulate minute of downtime and timing of downtime occurence.
  - Determine severity level of downtime impact to business.
  - Identify contribution factor to prioritize decision making on urgent point.

- Production efficiency:
  - Evaluate overall process efficiency and process performance as indiviaul model product.
  - Evaluate operator performance efficiency.

An interactive Looker Studio dashboard can be download here.

The SQL queries utilized to inspect and perform quality check be download here.

The Python notebook to conduct data exporatory can be found here.


## Data Structure Overview
- picture of table diagram(show information linkage to each tabel)

## Executive summary
### Overview of Findings

- Production efficiency of production is 85% with total downtime minute is 11291 or equals to number of electric board 6272 pieces that loss in production.

- Most highest contribution factor came from solder clog issue(35% of total causation) with scraping rate at 2.8%(highest value when compare to other factor).

- As correlation analysis, there's weak correlation between downtime minute and process efficiency. So, decrease downtime doesn't significantly improve process efficiency.

- Found downtime occurence as seansonal in each idividual factor. Prioritize investigation on most severe factor 'solder clog'

### Reccomendation
- Reccomend to deep investigate into 'solder clog' machine to find root cause of issue.



