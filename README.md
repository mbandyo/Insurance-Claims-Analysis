# Insurance Claims Analysis
This project includes analyzing vehicle accident insurance claims in multiple US states for period covering January 01 - March 01 2015. The analysis involves building a model to flag potential fraudulant claims.
## Motivation
Almost all (49 of 50) US state make auto insurance mandatory. 
Auto insurance is a major expense for car owners in the United States. Not only is insurance expensive, it’s almost always necessary. 49 out of the country's 50 states make car insurance compulsory for every road user, with only New Hampshire making the possession of auto insurance optional and allowing drivers the choice of driving uninsured. 
The following statistics is sourced from policygenius.com website.
### Car insurance statistics: by the numbers
* $239 billion (The amount the auto industry generated in 2019 in written premiums).

* $1,652 per year (The average annual cost of auto insurance in the U.S. for drivers aged 30 to 45, according to Policygenius).

* 12.6% (The share of all U.S. drivers who were uninsured in 2019).
* 29.4% (The percentage of drivers without car insurance in Mississippi, the state with the highest percentage of uninsured drivers in 2019).

* 3.9% (The average percent per year that the cost of insurance has increased during the last decade, according to the Consumer Price Index).
* $200.1 billion (The total premium amount of all policies the 15 largest insurers issued in 2020).

#### Auto insurance premium trends
From 2015 to 2019 (the most recent year for available data), the entire auto insurance industry took in $1.1 trillion in premiums, before losses. In 2019, insurers took in a total of $238.7 billion in auto insurance premiums before losses — up 27% from the $189.5 billion in combined value in 2015.

During this period, 61% of this value came from liability coverage, including both bodily injury and property damage liability, as well as medical payments coverage, underinsured and uninsured motorist coverage, and more. For comparison, collision premiums accounted for 27% of the combined $1.1 trillion, and comprehensive coverage made up a 13% share.

|Year|Total premiums written|Liability|Comprehensive|Collision|
|----|----------------------|---------|-------------|---------|
|2015|$188,541,093,697|$114,155,468,085|$24,210,502,017|$50,175,123,595|
|2016|$202,684,436,433|$122,637,763,709|$25,610,241,516|$54,436,431,208|
|2017|$217,518,449,804|$132,332,049,280|$26,972,361,714|$58,214,038,810|
|2018|$232,846,787,082|$142,027,256,699|$28,968,030,655|$61,851,499,728|
|Total|$1,080,330,842,997|$656,195,440,221|$135,921,175,215|$288,214,227,561|

#### Average car insurance premiums by coverage type
Car insurance premiums vary depending on the amount of coverage as well as the types of car insurance coverage. 

From 2015 to 2019 the cost of liability coverage increased by an average of 20%. During the same period, comprehensive coverage went up by 16% and collision coverage went up by 18%. The average insurance premiums (for all levels of coverage) was $1,123 during this period.

|Year|Liability|Comprehensive|Collision|
|----|---------|-------------|---------|
|2015|$543|$148|$323|
|2016|$572|$152|$342|
|2017|$614|$160|$364|
|2018|$646|$168|$378|
|2019|$650|$172|$381|

Rates provided by Quadrant Information Services. Rates provided are a sample of costs. 

#### Auto insurance premiums by car type
In part, the kind of car affects what you pay for insurance. According to our analysis of public rate data, the most expensive type of car to insure is a sedan, followed by an electric sedan. On the other hand, the cheapest to insure is an SUV at $1,886 per year.

Auto insurers determine the cost to insure a car by checking the number of claims, accidents, and theft risk for similar cars. Pricey vehicles are also more expensive to insure than cheaper cars, which would be less expensive to replace after an accident.

|Type|Cost|
|----|----|
|Sedan|$2,231|
|Sedan - electric|$2,063|
|Small SUV|$2,025|
|Pickup|$1,890|
|SUV|$1,886|

Cost of auto insurance premiums compared to other goods
Auto insurance has gotten more expensive over the course of the last decade. The Consumer Price Index, a measurement that the U.S. Bureau of Labor Statistics uses to track the average change over time in consumer prices, shows that the cost of car insurance has gone up by an average of 3.9% per year since 2011.

The largest year over year change came in 2017, when the CPI shows that the cost of auto coverage increased by 7.7% nationwide. Only in 2020, when drivers stayed off the roads during the height of the COVID-19 pandemic, were prices lower compared to the previous year.

For comparison, according to the CPI the prices of all goods rose by an average of 2% per year during this time. 

|Year|Price change|Price change - all goods|
|----|------------|------------------------|
|2011|3.6%|3.2%|
|2012|3.6%|2.1%|
|2013|4.2%|1.5%|
|2014|4.2%|1.6%|
|2015|5.4%|0.1%|
|2016|6.2%|1.3%|
|2017|7.7%|2.1%|
|2018|7.4%|2.4%|
|2019|0.9%|1.8%|
|2020|-4.6%|1.2%|
|2021|3.8%|4.7%|

#### Car insurance fraud facts and statistics for 2022

The total cost of insurance fraud (non-health insurance) is estimated to be more than $40 billion per year. ...
Auto insurance application fraud is on the rise, which is not unusual when consumers begin to feel greater economic pressures. ...
72% of alleged fraud victims say their auto insurance premiums increased as a result of reporting fraudulent activity. ...
The following insurance frauds are reported in https://insurancefraud.org/fraud-stats/
Fraudsters convince drivers they need a windshield repair or replacement when they don’t. Some glass firms bill for phantom windshield replacements, or replace undamaged windshields. Dishonest glass firms also convince consumers to sign an assignment of benefits (AOB) form. This gives the glass firm the legal right to file claims, make repairs and collect insurance payments. Firms are exploiting AOBs to inflate repair claims.

* 68% of consumers on average aren’t aware of various auto insurance fraud, from faulty windshield replacements to bandit tow truck
* Nearly 1 in 3 people (32%) believe they’ve been a victim of insurance fraud 
* Auto insurance fraud is underreported, as 29% of those who say they were victims never reported their suspicions. 
* Auto insurance fraud is underreported, as 29% of those who say they were victims never reported their suspicions. Women are less likely to report suspected fraud than men (35% versus 24%).
* 72% of alleged fraud victims say their auto insurance premiums increased as a result. Premium increases are most likely to affect millennials, 78% of whom saw higher costs after being victims of fraud.
* Consumers need more education about the various types of auto insurance fraud to protect themselves and their wallets. For example, 78% haven’t heard about faulty windshield replacement scams, 77% haven’t heard about bandit tow trucks and 77% aren’t aware of faulty air bag replacement scams.
* More than one-fifth of drivers lied to their insurer. 22% admit to lying to their auto insurer, most commonly by claiming damage to their vehicle but then pocketing the money intended for repairs, or by lying about their address or number of drivers to get a cheaper premium.

Considering the loss due to fraudulant claims and the increase in premium for all consumers, it is importnant for the insurance companies to identify, investigate and stop fraudulant claims.
This model is a step towards identification of potential fraud claims. Of course, this is only a start in the process. Each flagged claim should be further investigated and there would be trade-off between the cost of resources and claim amount. However, it is still important to flag potential frauds.
### Data
Vehicle insurance claim data file is downloaded from:</br>
https://www.kaggle.com/datasets/antopravinjohnbosco/auto-insurance-claims-fraud-detection
### Methodology
The model is built using Machine Learning method. We built a number of ML models before deciding on the best performing one.
## Model Details and Steps
A number of prototypes were built using ensemble methodologies. In order to improve model performance several resampling methods were also used. The fimal model is built using a combination (over and under sampling) sampling. The final model was selected best on the performance metric of the models.



### Tableau files 
https://public.tableau.com/authoring/InsuranceFraud_16707860430090/Fraudbasedoncartypeandcapitalloss#1
https://public.tableau.com/authoring/InsuranceFraud_16707860430090/FraudintheUSA#1
