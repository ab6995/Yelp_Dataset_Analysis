# Yelp_Dataset_Analysis
Used Hadoop (Map/Reduce Python, or Pig, and Spark ) to analyze the Yelp data challenge:  
https://www.yelp.com/dataset_challenge
 
Specifically, provided the answers (and code) to the 5 following questions using pig and spark:

1. Summarize the number of reviews by US city, by business category.

2. Rank all cities by # of stars descending, for each category

3. What is the average rank (# stars) for businesses within 20 miles of the University of Wisconsin - Madison, by type of business?

Center: University of Wisconsin - Madison
Latitude: 43 04’ 30” N, Longitude: 89 25’ 2” W
Decimal Degrees: Latitude: 43.0766, Longitude: -89.4125

The bounding box for this problem is ~20 miles, which we will loosely define as 20 minutes. So the bounding box is a square box, 40 minutes long each side (of longitude and latitude), with UWM at the center.

4. Rank reviewers by number of reviews. For the top 10 reviewers, show their average number of stars, by category.

5. For the top 10 and bottom 10 food business near UWM (in terms of stars), summarize star rating for reviews in June through December.
