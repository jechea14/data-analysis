# Airbnb Project using Tableau

[Interactive Dashboard of the project on Tableau Public](https://public.tableau.com/app/profile/jeanie.chea/viz/AirbnbFullProject_16841281226260/Dashboard1#1)
[Airbnb Listings 2016 Dataset from Kaggle](https://www.kaggle.com/datasets/alexanderfreberg/airbnb-listings-2016-dataset?resource=download) was used for this project. 

### Situation

- A friend wants to rent out his property using Airbnb and he wants me to find the best location in Seattle, Washington to rent out his property and create a dashboard for him with starting information.
- I first joined the Listing and Calandar tables together using inner join to get matching data within the two tables.
- I wanted to show the average price for each zipcode to see which locations cost the most money to the least money, so I created a bar chart of the price by zipcode sorted in descending order by average price. Each zipcode is distinguished by its own color. From the observation, zipcode 98134 rents out the highest price.
- Then I wanted to show the locations by zipcode on a map, so I created a map showing all the locations by zip code with the same colors as the ones from the bar chart along with the average prices.
- My friend is also wondering when is the best time to rent his property. I created a line chart to show the total prices of each week of date in 2016. From the observation, prices are very low in the beginning of the year then increases dramatically after March. Best time would be during the summer and towards the end of the year.
- I created a bar chart of the average price per bedroom so my friend can decide which property with the appopriate amount of bedrooms he should rent out. From the observation, prices increase the more bedrooms a house has.
- Lastly, I created a table of his competitors of other Airbnb listings by bedroom count. From the observation, 1 bedroom has the most listings and drastically decreases with more bedrooms.