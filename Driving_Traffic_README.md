<!-- PROJECT LOGO -->
<br />
<p align="center">
  
   <img src="generalassembly-open-graph.png" alt="Logo" width="500" height="200">
  

  <h3 align="center">Driving Licenses, Traffic Accidents and Casualties Analysis in Saudi Arabia</h3>


</p>



<!-- TABLE OF CONTENTS -->
## Table of Contents

* [Introduction](#introduction)
* [Data-sets Description](#data-sets-description)
  * [Driving Licenses](#driving-licenses)
  * [Traffic Accidents and Casualties](#traffic-accidents-and-casualties)
* [Executive Summary](#executive-summary)
* [Conclusions and Recommendations](#conclusions-and-recommendations)



<!-- ABOUT THE PROJECT -->
## Introduction

**Unfortunately, traffic accidents are very common in Saudi Arabia and causes many fatalities and injuries. Huge efforts been taken by Saudi government to reduce those accidents to provide safer environment and minimize the losses. in this project we are going to investigate and analyze given data to find out the main factors and impacts to be considered for any corrective actions.**



<!-- GETTING STARTED -->
## Data-sets Description

### Driving Licenses

[Driving Licenses](https://datasource.kapsarc.org/explore/dataset/saudi-arabia-driving-licenses-issued-in-the-kingdom-2004-2008/information/?disjunctive.administritive_area&sort=time_period&location=5,24.37495,45.08024&basemap=jawg.streets)
This dataset contains Saudi Arabia Driving Licenses Issued By Administrative Area for 1993 - 2016. Data from General Authority for Statistics .


### Traffic Accidents and Casualties
 
[Traffic Accidents and Casualties](https://datasource.kapsarc.org/explore/dataset/saudi-arabia-traffic-accidents-and-casualties-injured-dead-2008/export/?disjunctive.region&disjunctive.indicator&sort=time_period)
This dataset contains Saudi Arabia Traffic Accidents and Casualties by Region for 2016. Data from General Authority for Statistics.

|Feature |  Type  | Dataset | Description |
|---|---|---|---|
|year|integr|Driving_Licenses & Traffic_Accidents|The year where the driver's license was issued and Accidents happen|
|region|string|Driving_Licenses & Traffic_Accidents|the region for each driving licenses was issued and Accidents happen|
|driving_license|intger|saudi_drivlicenses|Number of driving licenses issued per region per year|
|indicator|string| Traffic_Accidents | Describe incidents |
|value|integr| Traffic_Accidents | Number of injuries, deaths and accidents |
|  geo_point_2d  | string | Driving_Licenses & Traffic_Accidents |Region location coordinates |
|x| float | Driving_Licenses & Traffic_Accidents | x coordinates for region |
|y| float | Driving_Licenses & Traffic_Accidents | y coordinates for region |



<!-- USAGE EXAMPLES -->
## Executive Summary

the goal of this project is to find out the relation between traffic accident versus driving license and the degree of the impact as well .the analysis shows many findings, the keys finding are :-
1. The number of driving licenses increased in 2017 while the number of accidents decreased in the same year(inversely related) which is logic and make sense.
2. the number of traffic accident in Makkah increased in 2017 by 20% comparing with them in 2016. the reason is clearly because number of pilgrims which also increased in same period.


<!-- ROADMAP -->
## Conclusions and Recommendations

Based on the features given in the data sets, we cannot come up with a more informative analysis. However, it is enough to show us the current situation.our recommendation listed below:
1. Strict law enforcement of traffic violations can highly affect the total number of accident and hence decrease the numbers of injuries and deaths.
2. Awareness social campaigns is important to remind people that they must obey the rules and respect the road and the other drivers to avoid any loss.
3. Training pilgrims from outside the Kingdom on driving laws in Saudi Arabia before them coming.

For more information ckech [My Blog](https://medium.com/@abeer.a.alshathri/driving-licenses-traffic-accidents-and-casualties-analysis-in-saudi-arabia-2c56685c4c33)