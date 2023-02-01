# Covid-Analysis
# Covid-19 Highlights, California 2019-2020

__Coronavirus disease (COVID-19) is an infectious disease caused by the SARS-CoV-2 virus.__

Infected humans experience mild to moderate respiratory illness, some humans become seriously ill and require medical attention. Anyone can get sick with COVID-19, become seriously ill, and die at any age. 

Protection from the virus is gained by maintaining distance from other individuals, wearing a mask, and washing your hands or using an alcohol-based rub frequently. Vaccination for COVID-19 is available. 

Infection spreads through small liquid particles expelled through mouth and nose of infected
Human beings. Infecting particles range from larger respiratory droplets to smaller aerosols.

Fig.1 


#### COVID-19 Death Visual State Comparison
This map compares the maximum daily reported hospital COVID deaths
per 1,000,000 people in each state of the United States of America

__Question 1__

### How were hospitals affected by COVID-19 deaths?

fig.2 Graph Question 1A
<img src="https://github.com/Project-1-Team-9/Covid-Analysis/blob/dd_branch/images/COVID19.daily.hospital.reported.deaths.over.2020.2021.png" width="50%" height="50%">

#### COVID-19 Daily Hospital-Reported Deaths Over 2020-2021 CA
The graph spikes during summer months as COVID-19 spread through California. COVID-19 safety protocols decreased deaths.  A COVID-19 death surge became evident during the holiday season.

fig.3 Graph Question 1B
<img src="https://github.com/Project-1-Team-9/Covid-Analysis/blob/dd_branch/images/Deaths.vs.ICU.Bed.Utilization.png">

#### Deaths vs ICU Bed Utilization & Staffing Shortage vs Daily Death Correlation
COVID-19 deaths directly affected ICU bed occupancy. The graph exhibits an exponential relationship. As the COVID-19 ICU bed occupancy increase, the number of deaths increased.

fig.4 Graph Question 1C.1 of 2 

<img src="https://github.com/Project-1-Team-9/Covid-Analysis/blob/dd_branch/images/staffing.shortage.vs.daily.death.correlation.png">

#### Staffing Shortage vs Daily Death Correlation

fig.5 Graph Question 1C.2 of 2
<img src="https://github.com/Project-1-Team-9/Covid-Analysis/blob/dd_branch/images/no.staffing.shortage.vs.daily.death.correlation.png">

#### No Staffing Shortage vs Daily Death Correlation

There is some positive correlation between the number of hospitals reporting staffing shortage and the number of daily deaths reported. The number of shortages reported increased, and the number of deaths skyrocketed, suggesting that hospitals could not provide adequate treatment. There is not a correlation between the number of hospitals not reporting a shortage and the number of daily deaths.

__Question 2__

### How did COVID-19 impact hospital occupancy?

fig.6 Graph Question 2A
<img src="https://github.com/Project-1-Team-9/Covid-Analysis/blob/dd_branch/images/covid.hospital.bed.occupancy.png">

#### COVID-19 Hospital Bed Occupancy

This stacked bar graph shows the total COVID-19 inpatient beds compared to the number of ICU beds occupied by COVID-19 positive patients over time. Notice that the number of ICU beds in the Junaray 2021 does not seem to increase as much as you might think it would. The max number of ICU COVID-19 beds is 4939 while the max number of COVID-19 inpatient beds is 30,334.

fig.7 Graph Question 2B
<img src="https://github.com/Project-1-Team-9/Covid-Analysis/blob/dd_branch/images/covid.icu.bed.utilization.over.time.png">

#### COVID-19 ICU Bed Utilization Over Time
This scatter plot shows the COVID-19 ICU bed utilization as a percent over time. It is calculated by dividing the number of COVID-19 ICU patients by the total number of ICU patients. The maximum COVID-19 ICU utilization is 55.37% on January 8, 2021. The first spike is relatively small compared to the first spike in other charts. This means hospitals had to reserve ICU beds for other treatments to the detriment of COVID patients.

__Question 3__

### Which age group had the highest rate of COVID-19 hospital admissions?

Fig.8 Graph Question 3A
<img src="https://github.com/Project-1-Team-9/Covid-Analysis/blob/dd_branch/images/Screenshot%202023-01-31%20162437.png">

#### Confirmed COVID-19 Hospital Admissions by Age Group

The pie chart describes the age breakdown of COVID-19 hospital admissions. Hospitals were impacted by older aged covid patients. 71.6% of hospital admissions were comprised of adults 50 and older. The largest single demographic of hospital admissions were adults aged 60-69.

Fig.9 Graph Question 3B
<img src="https://github.com/Project-1-Team-9/Covid-Analysis/blob/dd_branch/images/suspected.vs.confirmed.at.admission.png">

### Suspected vs Confirmed at Admission

The stacked bar graph displays the total number of COVID-19 related hospital admissions based on confirmed or suspected status. Majority of admissions were from previously confirmed COVID-19 patients. The age group most affected ranged from 60-69.

### Summary
The biggest spike in hospital deaths was after the 2020 holidays. During this spike, ICU bed utilization was high for COVID, and there was a spike in staffing shortages reported. There was likely insufficient treatment available for all the patients, leading to higher-than-expected deaths. Over 70% of hospitalizations for COVID were for patients 50 and older. The age group 60-69 had the highest number of admissions during this time period.
### Challenges
1.The data called did not come in the format that was listed in the documentation
2.Some of the columns did not come with much information.
3.The dataset does not contain deaths broken down by age, so we were limited to only hospitalizations while trying to understand the impact by demographics.
4.The dataset is an aggregated report for states so there is no hospital, city or county identifier to perform more specific analyses
### Next Steps

We still have a few more questions that we would like to answer. To address those, we would like to connect this dataset with a couple of others:

1 Government policies put in place to determine how hospitals were impacted

1.1 Which type of policies were most effective?

1.2 How much policy is too much policy?

2 General population COVID data
2.1 Can hospitals anticipate shortages by understanding what is happening outside?

2.2 What benchmarks can be set to initiate certain procedures or protocols at the hospitals?


