# surfs_up
Analyzing weather data in jupyter notebook and making an app 

# Overview of analysis
The purpose of our analysis is to see temperature statistics for June and December to see if running a surf shop is sustainable year around. The way we get the temperature data is by running two seperate queries, one being for June and the other being December. Once we run our queries we store the temperatures in a list then convert them to a dataframe. Once our dataframe is created we are able to get our summary statistics by using the .describe() method. Here is what we found:


# Results
## June Temperatures



![june_temp](https://user-images.githubusercontent.com/89143725/139520596-9b90ddcb-141e-4f41-a24a-f4bcd3c26344.png)


 
 ## December Temperatures
 
 
 
![december_temp](https://user-images.githubusercontent.com/89143725/139520603-db9e6b56-6c60-4ed9-b128-122502dc0212.png)


 --Standard deviation is 3.25 in June and 3.75 -- making a .5 difference in the two different seasons

These two tables tell us about the differing weather patterns for the two monthly periods. Some takeaways:
1) Average temperature between June and December is 75 and 71 degrees respectively, show a moderate temperature and very little fluctuation between the two periods from an average standpoint.
2) the maximum temperatures of 85 (June) and 83 (December) are also remarkable similar.
3) the minimum temperature of 56 (December) and 64 (June) show the greatest variance, and reflects a much lower temperature level in December that may not be conducive to ice cream or surfing. However, with standard deviations of 3.25 (June) and 3.74 (December) we would expect a little more variation in the december numbers.

# Summary 

From our data we can tell what our temperatures are but since there are other attributes to the weather such as precipitation it shows that we can run additional queries to let us know whether or not people can come and visit the shop. If we are able to gain more data for the area we can run even more queries! From there we can decide how we would like to build the shop and what areas would make this a more prominent location for visitors to come.
