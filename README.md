# Data-Mining-with-Youtube-API-v3-using-LDA-in-Python

In this project, the latest YouTube API v3 was used to extract top 50 most popular videos across a certain set of regions across
the world. For each video we extract information like ID, snippet, title, description, views, likes, dislikes and region.
Using the titles of all videos for each region we perform individual Latent Dirichlet Allocation(LDA) analysis to get 2 topics for each 
region that could provide insights on what's trending among viewers in any given country

There are two python functions which are central to this project:
    
      (a) The first user defined function helps us extract information about most popular videos along with video
      statistics for a given region
      
      (b) The next user defined function can be used to perform LDA analysis on the titles retrieved by the first function.
      The second function is essentially used for topic modeling
      
The most prominent topics extracted for each region are printed which can be used for further analysis.
