# Final-project-WHERE-AT-⁉️

For my final project I used Python 🐍 to write the code, Looker 👀 to further my analysis and Google Slides 📊 to create the presentation.

2- Starting with a database from Kaggle from 2019 and with 15203 businesses and 46 columns or features. I wanted to analyze the business by their rating ⭐, type ✅, and location📍. In order to answer “If want to open a business in city X, where is the best place to do so⁉️”

3- So out of the 46 columns or features I decided to stay with 9, among them latitude, longitude, ratings, and business type. Out of 4130 unique business types I worked with strings creating 10 categories ✔️

4- Working with strings means I created categories with key words a business had to describe itself.

5- For the analysis of ratings⭐. Having a big dataset of 15K business and a mean of 4.29 with a minimum of 1 and maximum of 5 stars. The analysis is passed to categories to see which are more liked and which are not doing so hot.

6- The boxplots shows the business or outliers that are not doing so good.📉

7- For sub-grouping or clustering 🌎. For the ones asking why I decided to use UML instead of group by; To answer my main question, I need to specifically know where I could open a business and for that clustering it is more appropriate. 
So in order to create clusters I used DBSCAN
Why DBSCAN? 
DBSCAN can form clusters of any shape, as it groups points that are density-connected.
DBSCAN automatically determines the number of clusters
DBSCAN classifies isolated points as noise

8- Cool I got 2985 clusters for the overall data and in this case for the world. Sweet! Now what? Let’s say that to answer the main question, our business owner wants to open a business in Dubai or cluster 87!

9- Cluster 87 or Dubai has 8123 business 🤑 and after running once again the DBSCAN algorithm; I got 85 sub-clusters. 

10- Now… to answer our question I need to show the analysis that goes with cluster, rating, and business category. Jumping to Looker 👀. Lets reframe our question  — "I want to open a retail store in city Dubai, where is the best place to do so?
While looking at the tables @Looker 👀, I could recommend to go for the top five or maybe the bottom five. Why? Because if a business owner would like to have a very nice retail store it could gain clients by having the store close to other 5 star retail stores. However lets say a business owner wants to open a restaurant next to other restaurants that are not so good, then maybe that new and good restaurant could pull clients from the bad restaurants as it is the best option to dine in! 

-- Jumping to my code... I can enter the number of cluster, we obtained from Looker and... we can see exactly the recommended location to where the business should be open.

11- In conclusion, with updated data, a defined business type, and city. I could advise or recommend a business owner where to open a new business of his/her liking. 


*The numbers for the paragraphs are actually the numbers of the slides in my presentation.
*The tables created with Looker are in PDF format in this folder. 
