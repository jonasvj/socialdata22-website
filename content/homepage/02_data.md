---
title: "Data sources"
weight: 2
header_menu: true
---

In order to investigate how the level of recycling differs between New York districts and how these levels are affected by socioeconomic factors, we need a few different data sources. Most importantly, we need recycling and social data but also geographical data for visualization purposes and for relating e.g. the locations of public recycling bins to the districts.

---

#### Recycling data

Our main recycling data set is provided by the Department of Sanitation in NYC and provides information about the waste recycling rates, i.e. the amount of waste recycled as a fraction of the total waste stream, in each district for 17 different months in 2018 and 2019. The recycling rates provided are for paper and for metal, glass, plastic & beverage cartons as well as the total rate, which is the combination of the two former. The data set is avaialable <a href="https://data.cityofnewyork.us/Environment/Recycling-Diversion-and-Capture-Rates/gaq9-z3hz">here</a>. 

Our second source of recycling data is a register of the geographical locations of all public recycling bins in New York City. This data set is also provided by the Department of Sanitation and is available <a href="https://data.cityofnewyork.us/Environment/Public-Recycling-Bins/sxx4-xhzg">here</a>.

---

#### Social data

To get insights about the socio-economics of each of the 59 community districts in New York City, we make use of a data set provided by the Department of City Planning in NYC. This data set contains detailed demographic, socio-economic and housing characteristics for the different districts. The values in the data set are provided as 5-year averages over 2015 to 2019. The dataset is quite extensive and contains roughly 600 characteristics in total. We only make use of a subset of these characteristics, for example; the median age, median household income, percentage with Bachelor's degree and median number of household rooms in each district. The data set is available <a href="https://www1.nyc.gov/site/planning/planning-level/nyc-population/american-community-survey.page.page">here</a>.

---

#### Geo data

To create map visualizations, we make use of a data set that contains shape information of the different community districts. This data set is available <a href="https://data.cityofnewyork.us/City-Government/DSNY-Districts/i6mn-amj2">here</a> and is provided by the Department of Sanitation in NYC. 

We also make use of the PLUTO data set provided by the Department of City Planning, which contains coordinates for all tax lots in NYC, amongst other things. We use this data to compute the distance to the nearest public recycling bin for all tax lots (i.e. addresses) in NYC. The data set is available <a href="https://www1.nyc.gov/site/planning/data-maps/open-data.page">here</a>. 

---
