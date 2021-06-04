# UFOs-Challenge
# Overview of Project
Build a table to hold and display the data we want to work with. Then we will add filters of that table which will let users refine their search on more than one level. Our table will be inserted into, and visually displayed by an HTML page. We will use basic HTML, Bootstrapt, and CSS to build and style the entire page.
## Purpose of Analysis
The purpose is to provide more in-depth analysis of UFO sightings by allowing users to filter multiple criteria at the same time. 
# Results
Users are able to refine their search by four different criterias:
- date
- city
- state
- country
- shape
Search criterias can be used simultaneosuly or by itself.
## Search by date
User can input a date using the MM/DD/YYYY format on the "Enter Date" field and press Enter. The results will filter accondingly and displayed on the table. Example for 1/4/2010:
![Image for 1/4/2010](https://github.com/arelysrsd87/UFOs-Challenge/blob/main/images/1_4_2010.png).
## Search by city
User can input city name on the "Enter City" field and press Enter. The reults will filter accondingly and displayed on the table. Example for the city of Sacramento:
![Sacramento](https://github.com/arelysrsd87/UFOs-Challenge/blob/main/images/Sacramento.png).
## Search by state
User can input a state name using the lowercase two-letter code on the "Enter State" field and press Enter. The results will filter accondingly and displayed on the table. Example for the state of Florida (fl):
![Florida](https://github.com/arelysrsd87/UFOs-Challenge/blob/main/images/Florida.png).
## Search by country
User can input a country name, again, using the lowercase two-letter code on the "Enter Country" field and press Enter. The results will filter accordingly and displayed on the table. Example for the country of United States (us):
![US](https://github.com/arelysrsd87/UFOs-Challenge/blob/main/images/US.png).
## Search by shape
User can input a shape name on the "Enter Shape" field and press Enter. The results will filter accordingly and displayed on the filtered table. Example for the triangle shape:
![triangle](https://github.com/arelysrsd87/UFOs-Challenge/blob/main/images/triangle.png)
## Reset table to unfiltered state
To reset table to unfiltered state, user can delete search criteria for search field and press Enter. This will return the table to the unfiltered state.
# Summary
## Drawback
- A drawback from the webpage is it's inability to allow users to download the results.
## Recommendations for further development
- We recommend adding a reload button to reset the table to its unfiltered state as opposed to deleting the search criteria from the search field. A refresh button is more intuitive for users and commonly used on other interfaces. 
- We recommend displaying the total number of filtered results out of the total number of unfiltered results at the bottom if the filtered table. This will allow users to easily quantify results based on search criteria and potentially use the results for further analysis.