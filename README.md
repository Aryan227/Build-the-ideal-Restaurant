# Building the Ideal Restaurant in Bangalore
### Final Project for DSGA3001 (Probability and Statistics - 2)

<h3>Motivation:</h3>
<b>Where (location: city and area) and what type of (cuisine type, budget range, restaurant type) restaurant should we open in Bangalore? What other paramters determine the success of a restaurant?</b>
<br>
Overarchingly, we are interested in this because: We want to see if we can use data science to accurately predict the success of a restaurant based on ratings and reviews of restaurants from 5 years ago. This will be interesting to compare with the restaurants that are currently open to see if the same success metrics would apply today.
<br>
<br>
In initial conversations about answering these questions, we each came up with a preliminary intuitive approach of how we would use this data. Both of our initial intuition was to focus on location first, either to find the part of the city with the most restaurants or the highest ratings. The next step would be to look at the other three variables (cuisine, budget range, and restaurant type) to find the ones that appear the most in the dataset or that have the highest ratings. This intuitive approach produced the following results: 
<br>

<h4>Aryan:</h4>
<ul>
<li>Location: BTM </li>
<li>Cuisine: Asian, Chinese, Thai, Momos </li>
<li> Type: Buffet </li>
<li> Price Range: $$$$ </li>
</ul>

<h4>Mallory:</h4>
<ul>
<li>Location: Church Street </li>
<li>Cuisine: North Indian </li>
<li>Type: Delivery </li>
<li>Price Range: $$ </li>
</ul>
<br>
From this result, it is clear that there are many ways to approach this question which will result in different answers. This approach does not consider underlying relationships in the data that can skew the results.
It is because of this, that we plan to pursue this project and find the best answers through a data science point of view.

<h3>Dataset</h3>
The dataset for this project comes from Kaggle. It is the “Zomato Bangalore Restaurants” dataset. It includes information about restaurants in Bangalore, including URL, address, restaurant name, ability to order online, ability to book a table, rate, votes, phone number, location, restaurant type, most liked dish, cuisines, approximate cost per person, review highlights, type of food it is listed as on website and location it is listed in on website. 
<br>
<br>
The main metrics that we will focus on are ratings, location identifiers, restaurant types, cuisines, and approximate cost per person. These are appropriate to answer our question because in an intuitive sense, they capture characteristics that are important in having a successful restaurant from both the owner’s and the consumer’s point of view. 
<br>
<br>
<b>Success Metric:</b> The ratings will be used as the success metric for this project. Initially, the number of votes was considered as a success metric. However, upon exploration of the data, the distribution of votes is heavily skewed as more than 50% of the data had fewer than 50 votes as shown in Figure 1a. Additionally, older restaurants and restaurants with higher ratings are likely to have more votes. Due to these issues, the ratings were chosen as the sole success metric.

<h3>Conclusion</h3>
Since, this dataset was made in 2017, it is close to 6 years old. Since then new restaurants did open and some in the configurations we predicted, we look at their ratings to see how we did. It was analysed that all our configurations had >4.0 ratings even in the $$$ price bucket. One configuration especially had great results as 2 restaurants in that category are currently (as of 05/2023) are the highest rated restaurants in the city.

<h3>Video for Project</h3>
The project was documented throughout and contains reports (3), a final presentation and the consequent video presentation. If you want to view the [video] (https://drive.google.com/file/d/1WzAkfUKhs-25JSTSE8Lfx-x3L4-fsZrF/view?usp=share_link), request access through Google Drive.

