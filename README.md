# Excel_BuzzFeed_Analysis
SCENERIO - 
SocialBuzz is a fast growing technology unicorn that need to adapt quickly to it's global scale. The company wants to analyze it data wants to these insights given below:

1) How many unique categories are there?
2) Which are Top 5 content categories?
3) How many reactions are there to the most popular category?
4) What was the month with the most posts?
5) Which content types (e.g., photo) elicit the most positive and negative reactions from users?

# STEPS TAKEN
1) Collected the data from the Accenture Forage Website
2) Cleaned the data from Reactions, Reaction_types and Content Files 
3) Merge the data into a single file using VLOOKUP, by making the Content as the base table
   
  ![Screenshot (106)](https://github.com/PSinglaAnalytics2003/Excel_BuzzFeed_Analysis/assets/168019114/9d0e4ea2-80c5-4ca6-8318-68eae23a3700)
 
4) Used the final table to explore the data and to get the useful insights by creating pivot tables and visualizations.
   
# INSIGHTS
1) There are 16 unique Categories - removed the duplicates from the Category Column
   
   ![Screenshot (107)](https://github.com/PSinglaAnalytics2003/Excel_BuzzFeed_Analysis/assets/168019114/1b75aa9d-3386-4106-bc3e-0eaa2be355ce)

2) Animals and Science are the two most popular  categories of content, showing that the  people enjoy "real-life"  and  "factual " content the most. Used the SUMIF function to calculate the total scores by categories. And used CONDITIONAL FORMATTING to get the Top 5 Categories. 

   ![Screenshot (108)](https://github.com/PSinglaAnalytics2003/Excel_BuzzFeed_Analysis/assets/168019114/b542e853-bb2a-4365-82af-c7bb152ea801)
   ![Screenshot (112)](https://github.com/PSinglaAnalytics2003/Excel_BuzzFeed_Analysis/assets/168019114/106e59f4-6ea9-4f05-ac90-8914838c66c7)

   
3) Animals and Science are the two most popular  categories of content,  as well as has the most number of reactions to these posts.
   
   ![Screenshot (109)](https://github.com/PSinglaAnalytics2003/Excel_BuzzFeed_Analysis/assets/168019114/575bb4c5-e624-4ca7-948d-66a77fdb17e9)

4) January, May, August  and December are the months with the highest number of posts. Extracted month from datetime column
   
   ![Screenshot (110)](https://github.com/PSinglaAnalytics2003/Excel_BuzzFeed_Analysis/assets/168019114/6d24257c-2fab-4d81-bd39-11ee71d45cd1)
![Screenshot (113)](https://github.com/PSinglaAnalytics2003/Excel_BuzzFeed_Analysis/assets/168019114/750fa9c6-b631-44b0-a601-6ad01d092e7c)

5) Comparatively, users have more positive reactions than negative. Photos have both high positive and negative reactions.

![Screenshot (111)](https://github.com/PSinglaAnalytics2003/Excel_BuzzFeed_Analysis/assets/168019114/94f41cfc-f60c-4319-a8fd-58074e9a1532)



