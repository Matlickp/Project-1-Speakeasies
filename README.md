# Project-1-Speakeasies
Locations and Ratings of Speakeasies across America

I realize some of these could probably be consolidated but mworking with the gmaps plots I had split them to cut down on the memory load when I was running them.

1. uscitiesv1.4.csv
	CSV of all the cities with population, lat, and lng. Used to create list for yelp api call.

2. speakeasies.csv
	CSV of all the search results from the yelp api. ~1600 cities with a max of 50 results per. 

3. YelpAPI.ipynb
	This is the code to loop through te city lat/lngs and search yelp for speakeasies. It the pulls the relevant information and appends it to the bottom of the data frame. Last, it saves the results to a cs file   (speakeasies.csv).

4. Speakeasy Plots.ipynb
	This code finds the ratings by each price code and also determines the average rating by state. One listed alphabetically and the other ascending by rating.

5. Speakeasy Heatmap.ipynb
	This is a heatmap of all the speakies from the api. It is not rated or filtered but just shows where the oerall concentration of them are.

6. Speakeasy Weighte Heatmap.ipynb
	This is a heatmap of all the speakeasies but it has been weighted by rating. the lower the rating the lower the heat signature. This allows you to see which cities have the best overall concentration of higher rated speakeasies.

7. City Location.ipynb
	This allows you to type in a city and pull all the locations in that city and plot the onto a map.

8. Price vs Rating Correlation.ipynb
	This is a simple code that determined the correlation coefficient between Ratings an Price to determine if they were relate or not.

9. Project 1 Presentation-Speakeasies.pptx
	This is the presentation that was given in the class

10. The rest are just the output PNG files that were used in the power point


