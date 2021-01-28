# Heart-Failure-Prediction

Cardiovascular diseases (CDVs) are the number 1 cause of death globally, taking an estimate of 17.9 million each year which counts for 31% of all deaths worldwide. Heart failure is a common cause of CVDs and can be prevented by addressing behavioral risk factors such as tabaco use, unhealthy diet, physical activity and alcohol use.

## Data Source

Origional data set is from Davide Chicco & Giuseppe Jurman from biomedcentral and can be accessed from there. 

### Python Modules

Libraries and modules used are

* Pandas
* Math
* Numpy
* Scipy
* Matplotlib
* Seaborn

### Data Downloading, Cleaning and Manipulating

 Data set is divided into 2 main categories

1.  Patients who died

2. Patients who survived

#### Hypothesis to Test
 
Ho: There is no significant difference between platelets distributed between patients who died vs those who survived.

Ha: There is a significant difference between platelets distributed between patients who died vs who survived.

#### Data Overview

![text](https://user-images.githubusercontent.com/68614187/106083250-c8efd100-60e1-11eb-8cbc-c2feecf24f49.png)

### MEthods

#### Histogram

![text](https://user-images.githubusercontent.com/68614187/106083413-1704d480-60e2-11eb-8ec0-aeec30809ebf.png)

#### t-test confirmation
stats.ttest_ind(death_data['platelets'], no_death_data['platelets'])
Ttest_indResult(statistic=-0.8478681784251544, pvalue=0.3971941540413678)


