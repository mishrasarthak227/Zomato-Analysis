# Zomato Analysis Project
This is a project in Python which collects data from zomato to help us recommend restaurants on the basis of users' affinity to specific cuisines, establishment types, locations and price bands. We can find out whether restaurant support online reservation or not and also what is the most popular and/ or exclusive/new at a given location & time.

Dataset Collection -
Due to Zomato API Basic Plan restriction, we cannot collect enough data for analysis. To overcome this problem ‘zomato dataset.csv’ file is provided to analyse the data deeply and to get useful inference.
Data has been collected from the Zomato API in the form of .json files(raw data) using the following url and stored in CSV file -
https://developers.zomato.com/api/v2.1/search?entity_id=1&entity_type=city&start=1&count=20

CSV file has also been attached to the repository.

Details of zomato dataset.csv -


Restaurant Id : Unique id of every restaurant across various cities of the world
Restaurant Name : Name of the restaurant
Country Code : Country in which restaurant is located*
City : City in which restaurant is located
Address : Address of the restaurant
Locality : Location in the city
Locality Verbose : Detailed description of the locality
Longitude : Longitude coordinate of the restaurant's location
Latitude : Latitude coordinate of the restaurant's location
Cuisines : Cuisines offered by the restaurant
Average Cost for two : Cost for two people in different currencies
Currency : Currency of the country
Has Table booking : yes/no
Has Online delivery : yes/ no
Is delivering : yes/ no
Switch to order menu : yes/no
Price range : range of price of food
Aggregate Rating : Average rating out of 5
Rating color : depending upon the average rating color
Rating text : text on the basis of rating of rating
Votes : Number of ratings casted by people

*Country codes:
1 India
14  Australia
30  Brazil
37  Canada
94  Indonesia
148 New Zeland
162 Phillipenes
166 Qatar
184 Singapore
189 South Africa
191 Sri Lanka
208 Turkey
214 UAE
215 UK
216 USA
