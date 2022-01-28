## NYC Citibike Data Analysis in Tableau
Analysis of August 2019 data from NYC's shared bike network Citibike, which includes detailed trip data for the month

### Resources
- Data Sources: Citibike trip data for August 2019
- Software: Tableau Public 2021.4.3, Jupyter Notebook 6.3.0

### Tableau Link
Tableau Public worksheets including tabs to toggle can be found [here](https://public.tableau.com/app/profile/tina.bellon/viz/Citibike_Aug_2019_Summary/TripsbyDuration)

### Overview of Analysis
Analysis of Citibike data to determine viability of the Citibike business model. Citibike data includes invividual trips for the month, including the gender of the user, the start and end location of the trip by coordinates, the start and end time and trip duration, as well as information on whether the customer is a subscriber to the network.

### Results 
Analysis of August 2019 data shows several clear findings:

- The majority of trips are of short duration, with most lasting around 5 minutes and use dropping significantly around the 30 minute mark
<img width="400" alt="Screen Shot 2022-01-27 at 22 11 08" src="https://user-images.githubusercontent.com/90064437/151486008-af043a12-e390-4e32-8dac-d91539e357a2.png">

- Citibike users skew younger, with younger cohorts spending more time on the network
<img width="400" alt="Screen Shot 2022-01-27 at 22 13 48" src="https://user-images.githubusercontent.com/90064437/151486205-251ffaff-e942-4bb3-a50b-384c398cfa67.png">

- At 65%, male users complete the majority of trips
<img width="400" alt="Screen Shot 2022-01-27 at 22 18 06" src="https://user-images.githubusercontent.com/90064437/151486577-24a33c78-cb26-413c-86a7-2e9bb52e6fd7.png">

- But usage patterns do not differ siginificantly between male and female users - both use Citibike during peak commuting hours during the work week, and for all-day leisure travel during the weekend
<img width="400" alt="Screen Shot 2022-01-27 at 22 23 10" src="https://user-images.githubusercontent.com/90064437/151487099-54a2361c-0466-418a-b43f-8521a71ffda6.png">

- Commuting patterns are also illustrated when mapping trip start locations, which center around major employment areas in Midtown Manhattan and the FiDi
<img width="400" alt="Screen Shot 2022-01-27 at 22 26 32" src="https://user-images.githubusercontent.com/90064437/151487290-1f1a7da5-c4be-45db-af0d-24afbde4d941.png">

- Trips are driven by subscribers, who make up more than 80% of overall August trips
<img width="310" alt="Screen Shot 2022-01-27 at 22 31 32" src="https://user-images.githubusercontent.com/90064437/151487618-03dcda07-2714-4d6e-a828-90f889bb3326.png">

- Non-subscribers are seen to use the platform more frequently during the weekend, suggesting more spontaneous leisure use
<img width="320" alt="Screen Shot 2022-01-27 at 22 32 50" src="https://user-images.githubusercontent.com/90064437/151487838-35c40212-a4ee-4869-8743-01582511221a.png">

### Summary
Citibike use was popular among younger and primarily among male users during August 2019, with usage centered around main commuting hours and large employment centers in Manhattan.
Additional analysis could determine particularly popular bike stations to streamline bike availability. Analyzing additional months could to determine whether usage patterns fluctuate significantly when temperatures drop. Birth year data appears inaccurate, with a large number of users entering birth years that would put them at around 130 years old. Additional analysis could determine whether there is a correlation between seemingly inaccurate birth years and user type (subscriber vs. regular customer) to eliminate ficticious birth years likely entered by entered by non-subscribers.

