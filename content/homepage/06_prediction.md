---
title: "Prediction of recycling rates."
weight: 6
header_menu: true
---

In this section we will showcase the result of predicting the average recycling rate in each community district using a gradient boosting model with the socio-economic factors as input. The figure below shows the feature importances for the trained model. Here we see that variables such as "employed" and "less_than_10k" are quite important to the model. These features describes the percentage of employed peope in the district and percentage with an income less than 10,000 USD, and are thus intimately related to socio-economic status. 

It also appears that ethnicity is an important factor in one's recycling behaviour, since features like "born_nyc" (percentage of people born in NYC), "Hsp1p" (percentage of hispanic population), "percent_us_citizen" (percentage of population with US citizenship) are important to the model. 

We do actually also see that the distance to nearest public recycling bin is important to the model even though it was unclear from the prevuous analysis whether 


<h6 style="text-align:center;">Feature importances</h6>
![image description]({{< baseurl >}}images/feature_importance.png)

On the plot below we can see the Pearson correlation between our target variable and the 8 most relevant features. 
We can observe the positive correlation in the employed variable and the negative one in less than 10k.

This means that the percentage of people being employed changes in the same way the recycling rate does. If we have more 
people having a job we will also probably have higher recycling rates. 

The exact opposite happens with the people having 
an annual income of less than 10,000 $. If a district has a lot of low-paid residents it is possible that the recycling 
rates will be low. The correlation of the variables is a good indicator to find factors and the way they related to 
recycling rates.

<h6 style="text-align:center;">Correlations</h6>
![image description]({{< baseurl >}}images/correlation.png)

---