![image](https://github.com/Bryan-Corn/14-bikesharing/blob/main/Images/bikeshare01.png)
# bikesharing 
[link to story](https://public.tableau.com/app/profile/bryan.corn4415/viz/CitibikeChallenge_16569975494410/Story1)     
     [link to dashboard 1](https://public.tableau.com/app/profile/bryan.corn4415/viz/CitibikeChallenge-Dashboard/Dashboard1?publish=yes)     
          [link to dashboard 2](https://public.tableau.com/app/profile/bryan.corn4415/viz/CitibikeChallenge-Dashboard2/Dashboard2?publish=yes)     
               [link to dashboard 3](https://public.tableau.com/app/profile/bryan.corn4415/viz/CitibikeChallenge-Dashboard3/Dashboard3?publish=yes)


## Overview of the statistical analysis:
The purpose of this analysis is to investigate the feasablility of implementing a bike-sharing service in Iowa, use the data visualizations to support a business proposal, and learn about Tableau.

        
 ![image](https://github.com/Bryan-Corn/14-bikesharing/blob/main/Images/bikeshare1.png)
 
 For deliverable 1, the trip duration column needs to be changed from integer to a dateTime format.
 
 ![image](https://github.com/Bryan-Corn/14-bikesharing/blob/main/Images/bikeshare2.png)
 
 First, the citibike data from 2019-08 is imported into a pandas dataFrame. Then the tripduration column (in seconds) is converted.
 
 ![image](https://github.com/Bryan-Corn/14-bikesharing/blob/main/Images/bikeshare3.png)
 
 The tripduration data is now converted to datetime, showing each trip in hours, minutes, and seconds (with a date of 1970-01-01.)
 
 ## Results:
        There are at least seven visualizations for the NYC Citibike analysis (7 pt)
        There is a description of the results for each visualization (7 pt)
 
 ![image](https://github.com/Bryan-Corn/14-bikesharing/blob/main/Images/bikeshare4.png)
 
 This line plot shows the total number of trips per duration. The duration divided by hours and then minutes within the hours. There are almost no trips that lasted over an hour and most were less than 20 minutes.
 
 
 ![image](https://github.com/Bryan-Corn/14-bikesharing/blob/main/Images/bikeshare5.png)
 
 Here is the same data from the last image but it is further divided by gender. Male and female trip duration data has the same skew but far more trips were taken by males.
 
 
 ![image](https://github.com/Bryan-Corn/14-bikesharing/blob/main/Images/bikeshare6.png)
 
 This heatmap shows the hours and day with the most bike checkouts.
 
 
 ![image](https://github.com/Bryan-Corn/14-bikesharing/blob/main/Images/bikeshare7.png)
 
 Again, the same data as presented in the last image, but it is broken down by gender.
 
 
 ![image](https://github.com/Bryan-Corn/14-bikesharing/blob/main/Images/bikeshare8.png)
 
 This heatmap is limited to the day of each trip but is broken down by gender and customer type. 
 
 
 ![image](https://github.com/Bryan-Corn/14-bikesharing/blob/main/Images/bikeshare9.png)
 
 This map shows the starting locationd for rides (08-2019). The more trips taken from a location, the darker the color and larger circle.
 
 
 ![image](https://github.com/Bryan-Corn/14-bikesharing/blob/main/Images/bikeshare10.png)
 
 Similar to the last image, this shows the ending locations of trips and uses color intensity and circle size to show the number of trips.
 

## Summary:
Most trips are short, taken by male subscribers, and are likely to be a the start or end of the work day. The start and end locations are heavily clustered around major downtown areas. Bike use is very low in the early morning hours to allow for repair and maintenance. 

More investigation and analysis should be dome with respect to revenue, expenses, and actual distance traveled per trip.
        
