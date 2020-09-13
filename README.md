# Report
# Introduction
***
This project focuses on researching the location of restaurants in Manhattan, New York. As we all know, the location of a restaurant can affect the size of the passenger flow and the choice of customer types, which will ultimately determine the revenue. A good location can bring stable customer traffic, targeted customers and popularity to the restaurant.So for this person who wants to open a restaurant in New York, choosing a location is undoubtedly a challenge, and this project will help these people. Therefore, this project will attract owners who want to open restaurants in New York and investors who want to invest in New York restaurants.

# Data Discription
***
In this article, we will take the Manhattan area as an example to discuss the location of restaurants. Because the location of restaurants is generally determined by population and the density of restaurants. A sufficient population means a huge customer flow, and the right restaurant density will form a certain scale effect, helping new restaurants to better survive the first three years when they are most likely to fail. The data in this article comes from the following two websites and the API provided by FourSquare, which provide geographic location data of New York towns, population data of New York districts, and restaurant distribution data of Manhattan.

# Methodology
***

First, I obtained the geographic location data of neighborhoods in New York and saved them in json format, then converted it into a DataFrame and displayed the first ten rows. Then the population data of New York neighborhoods was obtained through crawlers. Then I continued to use FourSquare's API to obtain addresses related to "food" near Manhattan, and find out the distance between these addresses and downtown Manhattan, because I want to know how far away the number of restaurants is from the city center. Finally, I took the average of these distances, and the distance obtained was more than 4000, but the median showed that it was 2488, so I think it is better to take the median, so the restaurant should be located about 2500 meters from the city center. Finally, I showed these restaurants with blue dots on the map, and it can be seen that there are more restaurants in the northern part of Manhattan, which is consistent with the denser population in the northern part of the area.

# Results
***
Because the northern part has more population and denser restaurants, we should choose a place in northern Manhattan that is 2500 meters away from the city center to open a restaurant, so that there will be a rich cluster effect and sufficient passenger flow to support this restaurant.

# Discussion
***
Although this article can write suggestions for people who want to open restaurants or invest in restaurants around Manhattan, we have not considered the impact of traffic and rent. If the project is actually implemented, more places rather than a few ideas need to be considered.

# Conclusion
***
This article briefly analyzes the location of restaurants in Manhattan, New York, United States by combining population density, geographic location and the distribution of restaurants, and suggests that restaurant owners or investors consider finding a restaurant location 2,500 meters north of downtown Manhattan.

More information has been shown in here: https://github.com/zixinlin/Coursera_Capstone/blob/master/Untitled.ipynb
