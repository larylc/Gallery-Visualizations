## Gallery Visualizations


### Introduction

Static data visualizations from my website's gallery. 

### Visualizations

#### **"What 125+ Years of Temperatures Tell Us About Weather"** (R)

![](https://github.com/larylc/Gallery-Visualizations/blob/main/weatherplot.png)

**Data:** Data was web scraped from the [Rutgers Climate Lab Website](https://climate.rutgers.edu/stateclim_v1/nclimdiv/index.php?stn=NJ00&elem=mint#) which gets its data from the [National Centers for Environmental Information nClimDiv dataset](https://www.ncei.noaa.gov/access/metadata/landing-page/bin/iso?id=gov.noaa.ncdc:C00005).

**Methods:** Data was web scraped at the end of November 2022.

#### **"Percentiles Reveal Super Grandmaster Specialties"** (R)

![](https://github.com/larylc/Gallery-Visualizations/blob/main/supergmplot.png)

**Data:** The percentiles were calculated using data gathered from the `masters_table(s)` found in this [repository](https://github.com/larylc/Chess-Webscraping-Projects). The original data is from [FIDE](https://fide.com/).

**Methods:** Only chess players that had ratings that were greater than or equal to 2700 were selected. The percentiles only compared the 42 chess players >= 2700 because if other chess masters were included these 42 chess players would all be in the concentrated at the 99th percentile, making it difficult to distinguish their strengths relative to each other. 


#### **"Who Do We See Attending Need Blind Colleges"** (R)

![](https://github.com/larylc/Gallery-Visualizations/blob/main/needblindplot.png)

**Data:** You can find the US Department of Education's College Scorecard [here.](https://collegescorecard.ed.gov/data/) You can find the list of PrepScholar's need blind college list [here](https://blog.prepscholar.com/need-blind-colleges-list). 

**Methods:** Only 4 year colleges were considered. When the 2 data sources were merged, approixmately 100 colleges had need blind policies. The other 1900 had different financial aid policies. 

#### **"Seasonal Births of Grandmasters vs General Population"** (R)
![](https://github.com/larylc/Gallery-Visualizations/blob/main/seasonplot.png)

**Data:** Chess data is from the `all_grandmaster_bdates_bplaces_updated.csv` dataset in this [repository](https://github.com/larylc/More-Chess-Webscraped-Data). You can find the general population live monthly birth data from [United Nations Statistics Division's database](http://data.un.org/Data.aspx?q=birth+month&d=POP&f=tableCode%3a55).

**Methods:** Using the montly data gathered from both data sets, a "broad" season variable was created:
+ Winter Months: January- March
+ Spring Months: April- June
+ Summer Months: July- September
+ Fall Months: October- December

Average seasonal births by countries were then calculated from total seaonal births. 

