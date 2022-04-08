# Who are Canada's Extreme Commuters?

**9.7%** of commuters in Canada are **extreme commuting**, they spend more than 2 hours per day travelling to work (based on 2016 census data).

However, in our analysis of this data, we find that there are stark differences among different population groups.

![income](income_commute.png)

![race](race_commute.png)

This has since there is conventional wisdom, as well as extensive academic [research](https://doi.org/10.1080/01441647.2019.1649317), that spending a long time commuting to work undesirable. People who spend more time commuting are less able to participate in other activties, have lower work performance, increased stress and worse sleep, and even higher divorce rates.

The term **extreme commuting** can been used to define arduous journey-to-work trips.

We are interested in uncovering whether there inequities about who in Canada are more likely to be extreme commuters.

To do so, we look at full-sample of the 2016 Canadian census. This is a 25% sample of all Canadians, which includes over 4.5 million Canadians who reported commuting to a usual place of work.

The Canadian census asks workers to self-reprot their one-way commute time. We use this data to classify whether individuals have commutes of more than 60 minutes (i.e. 2 hours in total). 

We then visualize how these rates very for different socio-economic and demographic groups.

Let's first look at low-income status. Clearly low-income workers have longer commutes than non-low-income workers


Racialized Canadians are also over-represented as extreme commuters, paticularly among Black commuters where over 18% have commutes in excess of 60 minutes, compared to less than 9% of White commuters.


Immigrants are also more likely to be extreme commuters.

Overall there are clear differences about who are Canada's extreme commuters. 

We've also computed logistic regression models predicting the likelihood of being an extreme commuter, and we find that these inequaities persist, even after controlling for occupation, geography, job accessibility, and mode choice among other variables.




## Notes

The full sample of the long-form 2016 Canadian census was accessed at the Toronto Research Data Centre (RDC), which is operated by Statistics Canada. All analysis was run in R. Only aggregeted statistics, like those shown above, were released from the RDC.

Our analysis was based on 2016 census data, back when most workers travelled to work 5 days a week. Clearly this has shifted during COVID-19. Continueing this analysis using data from 2020 onward should also look at weekly commute frequency.