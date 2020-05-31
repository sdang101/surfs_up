# surfs_up
- Used SQLalchemy:
        - to create and engine
        - create a base class for an automap schema
        - reflect tables, and
        - to query data
- Incorporated Flask into data analysis by:
    - building Flask routes
    
# Challenge
- Analyze seasonal data in Oahu in all of June and December data we have

# Statistical Data about the month of June
![June](http://localhost:8889/view/Documents/Bootcamp/surfs_up/JUNE.png)

# Statistical Data about the month of December
![Dec](http://localhost:8889/view/Documents/Bootcamp/surfs_up/DEC.png)

# Comparsion
- The June precipation data has 1574 total entries and the June temperature has 1700 total entries while the December precipation data has 1405 total entires and the December temperature has 1517 total entries. June has more 169 more precipation data entries and 183 more temperature data entries.

- The mean (0.136) and median (0.020) precipation data in June is lower than the mean (0.217) and median (0.030) precipation data in December.

- The mean (74.94) and median (75.00) temperature data in June is higher than the mean (71.04) and median (71) temperature data in December.

- December has a higher standard deviation for precipitation (0.54) and temperature (3.75) data than June (0.34/3.26).

- The minimum precipation value for both December and June is 0.00 while June (64.0) has a higher temperature value than in December (56.0). 

- The maximun precipation (4.43) value in June is lower than in December (6.42) while June's temperature (85.0) value is higher than in December (83.0).

# Further Analysis
- For further visualization purposes, I reccommend adding histogram to see the distribution of both June and December precipation and temperature data.

- I also reccommend splitting the data into seasons to see which seasons rain and/or have higher temperatures than other months.

