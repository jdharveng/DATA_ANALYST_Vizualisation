# DATA_ANALYST_Vizualisation

### by Jérôme d'Harveng

## by Jérôme d'Harveng


## Dataset

> The flight dataset was used with reports of flights in the US, including carriers, arrival and departure delays and reasons for delays, from 1987 to 2008. For this specific analyse, data was limited to the period going from 2003 till 2008.

https://www.google.com/url?q=http://stat-computing.org/dataexpo/2009/the-data.html&sa=D&ust=1545420929900000

## Summary of Findings

> In the exploration of the data from 2003 till 2008:
> During the Univariate Analysis, I found that most flights departed between 5am and 11pm. For flights (non-cancelled) the distance is right-skewed (25%<314miles and 50%<562miles) aswell as the Departure Delay (50%<14min and 75%<36min). The last is logical as most carrier will try to minimise the delay. In 2007 the biggest amount of flights were cancelled. Looking at the months, December till February have the highest cancellation rate. This is probably explained by the weather conditions, as we saw analysing the cancellation codes, weather is on of the 2 main reasons together with the carrier. The airport of Chicago has also the highest cancellation rate. For this airport, weather seems to have a high impact, but a bit less than the NAS (National AViation System), as we could see in the Bivariate analysis.
Further on in the Bivariate analysis, we noticed some logical linear relationships between following pairs: Distance-AirTime, DepTime-ArrTime, DepDelay-ArrDelay. We noticed also that the distribution of the departure delay (DepDelay) had similar distribution, regarding the different years, months or days of the week. The carriers are logically using the same departure time range, mainly between 6am and 11pm. And finally almost no flights are cancelled for security reasons, as weather is often one of the main reasons across the 10 airports with most cancelled flights.
The multivariate analysis, confirmed that most delays are on smaller distances, for the 3 worst (ORD, ATL, DFW) < 1000miles,
for the other ones < 500miles.

## Key Insights for Presentation

> For the presentation after looking at the distribution of the "departure time" and "Distance" of the flights through histrograms. I looked at the distrubition of the "Departure Delay" for flights that wern't cancelled.
>Afterwards I focused on cancelled flights, by study different parameters ("CancellationCode","Year","Month","DayOfWeek" with Bar plots.
> Finally I analysed for the amount of cancelled flights depending on of the "CancellationCode" and the"Month", for the 5 airports having most total flight cancellation. Herefor I used a facetting Count plots.

