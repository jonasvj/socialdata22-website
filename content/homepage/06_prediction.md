---
title: "Prediction of recycling rates."
weight: 6
header_menu: true
---

In this section we will showcase the result of predicting the average recycling rate in each community district using a gradient boosting model with the socio-economic factors as input. The figure below shows the feature importances for the trained model. Here we see that variables such as "employed" and "less_than_10k" are quite important to the model. These features describes the percentage of employed peope in the district and percentage with an income less than 10,000 USD, and are thus intimately related to socio-economic status. 

It also appears that ethnicity is an important factor in one's recycling behaviour, since features like "born_nyc" (percentage of people born in NYC), "Hsp1p" (percentage of hispanic population), "percent_us_citizen" (percentage of population with US citizenship) are important to the model. 

We do actually also see that the distance to nearest public recycling bin is important to the model even though it was unclear from the prevuous analysis whether 


<h6 style="text-align:center;">Feature importances</h6>
![image description]({{< baseurl >}}/images/feature_importance.png)

<h6 style="text-align:center;">Correlations</h6>
![image description]({{< baseurl >}}/images/correlation.png)

---