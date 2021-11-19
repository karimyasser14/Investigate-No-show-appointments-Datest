# Investigate-No-show-appointments-Datest

This dataset collects information from 100k medical appointments in Brazil and is focused on the question of whether or not patients show up for their appointment. A number of characteristics about the patient are included in each row:
```
‘ScheduledDay’ tells us on what day the patient set up their appointment.
‘Neighborhood’ indicates the location of the hospital.
‘Scholarship’ indicates whether or not the patient is enrolled in Brasilian welfare program Bolsa Família.
Be careful about the encoding of the last column: it says ‘No’ if the patient showed up to their appointment, and ‘Yes’ if they did not show up.
```
## Dataset
The data including and the dataset can be found in the [at this provided URL] ( https://d17h27t6h515a5.cloudfront.net/topher/2017/October/59dd2e9a_noshowappointments-kagglev2-may-2016/noshowappointments-kagglev2-may-2016.csv.).


## Summary of findings
- Neighbourhood is a major sector which can effect on No. of patiants who showing up
- patiant in the 0-10 age showed more than any ages then 30-75, when they get older, they have less show up for their scheduled appointment
- Gender of Female who showed and did not show more than male
- More patients showed up without receive SMS as unusual, scholarship not major in showing up or not ### Limitation
- couldn't find direct relation between patiants which sowing up or not and many characteristics such as scholarship, Hipertension, Diabetes, Alcoholism and Handcap
- scholarship, Hipertension, Diabetes, Alcoholism and Handcap aren't major sector which can not effect on No. of patiants which showing up**


## Key Insights

 1. What are factors in order to predict if a patient will show up for their scheduled appointment?

2. what are a majors sectors which can effect on No. of patiants who showing up/ not showing up?

3. can you find direct relation between patiants which sowing up or not and many characteristics such as (Age, Neighbourhood, scholarship, Hipertension, Diabetes, Alcoholism and Handcap)?

## Tech Stack

These are the following packages I used throughout this project.

```
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
%matplotlib inline

```
