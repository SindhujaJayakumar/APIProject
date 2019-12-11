# PROJECT
Project Outline: Using reviews and other travel criteria, will determine the best city to travel to in New Zealand out of the three highest populated cities. Once the best city has been determined, will determine the best hotel to stay at and the best restaurants to eat at for differing price ranges and based on review data. 

Why did we pick this project:

We all decided to look at a place we all might want to travel to in the future allowing us to get some insight into New Zealand and where we might like to travel too. 

What were our questions and why did we pick them:

1)	Out of the top three highest populated cities in New Zealand what is the best city to visit based on ratings?
a.	We decided to pick this question since this will give a clear best of the top 3 cities and allow us to ask further questions about that city. 
2)	In the best rated city, what is the best Hotel to stay in each price category?   
a.	We chose this second question since this would be a logical step on how people make decisions on where they are going to stay during a visit. 
3)	In the best rated city, what is the best Restaurants to eat based on number of reviews with 4.5 ratings and above?
a.	We chose this last question again we wanted to see where people would like eat while in the city. We chose to go with reviews count for places with a 4.5 rating to narrow down the data set and give people a fair representation of population of the reviews that averaged to that 4.5 rating to make a educated decision. 

What was our process :

Using Yelp API (we decided to use this API due to the amount of data present), we determined to look at the questions above. Using this API we decided to filter down our search into several categories: Hotels, Restaurants, Shopping Center and Active Life. We can to the decision to use these categories since we assumed that these are the categories tourists would most likely care about. 


Analysis of the project:

Question 1: Out of the top three highest populated cities in New Zealand what is the best city to visit based on ratings?

To determine this, we first wanted to find the overall rating per city. To do this, we combined all ratings across all categories (Hotels, Restaurants, Active Living and Shopping Centers) to find the average overall rating per city. We could then group this statistic into a pie chart to see which city’s rating outweighed the other two. The result was that Auckland had the overall highest rating.
Next, the validate the relevance of this outcome, we reviewed the number of overall reviews per city. Wellington had the highest number of reviews, but we determined Auckland had enough reviews to still be relevant. We also determined Christchurch did not have enough reviews to be considered.
Since Auckland did not have the highest total number of reviews, we wanted to review the data from another viewpoint. So lastly, we used a scatter plot to see which city had the highest number of highly rated reviews. For example, 4-star or 5-star reviews. This outcome showed that Auckland had the highest number of 3, 4 and 5 start reviews.
Using the outcomes from these 3 visuals, we determined that Auckland would be the most optimal, best, city to visit .

