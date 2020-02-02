![Urban vs Rural](Images/IntroSlide.png)

# Do urban counties have better health outcomes in Texas?

Our hypothesis is:

## Urban counties have a better health outcome than rural counties in Texas.


The first two questions that immediately follow are:
* How do you define Urban and Rural?
* What measure do you use for a Health Outcome?


# Urban vs Rural

### How do you define Urban and Rural?

We used the Texas Health Professions Resource Center (HPRC) ![Definitions of County Designations](https://dshs.texas.gov/chs/hprc/counties.shtm) to imported an excel file
![Urban Rural Excel File](data/county_status.xlsx)

After reading more on the subject we found a system to classify Urban and Rural into six subcategories
at the ![CDC NCHS Urban Rural Classification System](https://www.cdc.gov/nchs/data_access/urban_rural.htm#Data_Files_and_Documentation)
The deeper classification splits up urban into four groups making a distinction between inner-city large population counties and suburb large population counties. You can see the clusters on a map from their website.
![US Map of URCS](URCS_usaMap.png)

# What measure do we use for 'Health Outcome'?

We used the ![County Health rankings Texas 2019 dataset](https://www.countyhealthrankings.org/app/texas/2019/downloads) and chose Age-Adjusted Mortality rate (deaths <75yrs of age / 100k population (age-adjusted)

# Research questions to answer

* Do urban counties have a better age-adjusted mortality rate (AAMR) than rural counties?
* What factors correlate with AAMR?
*   health behavior
*   clinical care 
*   social and economic 
*   physical environment 
* What are the five top and bottom counties measured by AAMR?




which county you live in has no impact on your health outcome. Next we will explore the factors that influence the differences between urban and rural counties in Texas. Finally we will give a ranking of the statistically top 5 and bottom 5 counties regarding health outcomes (as measured by the Age-Adjusted Mortality Rate).


Project Description/Outline
We will merge health and demographic data to find correlated factors that have an impact on health outcomes compared by counties. 
Rough Breakdown of Tasks
Acquire datasets: APIs, csv, xlsx and potentially database queries will be used to obtain datasets. Shane Livingston
Cleaning of Datasets: Data will be cleaned for incomplete rows, incorrect datatypes, and outliers. Kip Madden
Merging Datasets: Some Datasets will be merged into a single set.
Analysis of Data: Data will be statistically analyzed, plotted and correlated. Hopefully we will find significant trends to report on.
Presentation: We will present NO more than 10 minutes on our findings and create Jupyter notebooks with tables and figures.


## File & Directory Structure

* Urban_Rural_Health_Texas.ipynb : Data wrangling and analysis notebook
* [Urban_Rural_Health_Texas.pptx](output/Urban_Rural_Health_Texas.pptx)  : Presentation power point slides 

* data/       Excel & csv files for data importing
* Resources/  NCHS Urban Rural classfication scheme
* output/     Correlation matrix and dataframe exports

We will seek to reject the null hypothesis:

#### There is no difference to health outcome as measured by Age-Adjusted Mortality Rate (Deaths of under age 75 per 100,000 population (age-adjusted) ) between urban and rural county residents in Texas.

# Do urban counties have better health outcomes in Texas?

Using the [Count Health rankings](https://www.countyhealthrankings.org/app/texas/2019/downloads) Texas 2019 dataset and the [CDC NCHS Urban Rural Classification System](https://www.cdc.gov/nchs/data_access/urban_rural.htm#Data_Files_and_Documentation) we will seek to reject the null hypothesis that which county you live in has no impact on your health outcome. Next we will explore the factors that influence the differences between urban and rural counties in Texas. Finally we will give a ranking of the statistically top 5 and bottom 5 counties regarding health outcomes (as measured by the Age-Adjusted Mortality Rate).

