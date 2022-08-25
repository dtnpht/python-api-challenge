# python-api-challenge
The weatherpy analytic
    1/ The data I collected was 630 cities, but after filtering out missing data, the actual number of cities to use for analyzing are 567. This result can help me understand that real data always include missing parts, with the instruction from my Professor, I can use python/pandas to figure out and clean up the data and make them.

    2/ Plotting
        From 3 plots shown the relationship between Lat vs Temperature/Humidity/Wind Speed, I have some conclusion that:
        - Distribution of scatter point in Lat vs Temp graph seem organize and we can easily see the shape is curve line distribution. 
        -On the other hand, plot between Lat and Humidity seem discrete, and no trend should be found from here.
        -Move on to last graph in this part, Lat vs Wind Speed has the trend distribution but not neat as Lat vs Temp. Lat vs Wind Speed concentrate more around 0-10 mph. Then we can figure out there are existed some outlier out of the trend in this plot as well

    3/Relationship and differences between Northern Hemisphere and Southern Hemisphere.
        - This part I plot scatter plot as well but include the regression 
        - About relationship between Lat and Temp, the regression line from Northern Hem is descending trend while it is ascending trend on Southern Hem data
        - About Lat vs Humidity, both area had descending regression line but the Southern Hem's slope is larger than the Northern => Humidity at the Southern Hem decrease over the Lat change to 0
        -Next Lat vs Cloudiness, although they can graph the regression line but the there is no relationship or correlation between these factors.
        -The last is Wind Speed vs Lat, these factor occurred the relationship and can recognize through the graph, and the data distribute mostly between 0-10mph as same as when plot the whole dataset above



The vaacationpy analytic
    This part using the data set which export from weatherpy to analytic in different views:
    1/ The distribution of heatmap with layer is humidity, which can find at place has sea border or near to the sea. OF course the area near the sea always has humidity higher than inside country areas.
    
    2/ Filtering out which city considered as good weather, there are only 4 cities satisfy those conditions belong to good weather for vacation, therefore, moving on the analytic is finding the resort/ hotel near those cities.
    
    3/ The good weather cities are only at US only for purpose, but we can expand to analyze to other countries or even all over the map of Earth.
    The main task of this is filter and help vacationer who are looking for the good place to spend vacation as well as the nice place to stay during this time => the significant meaning from this homework is realistic and worth to do and learn how data analytic job doing and their role in development tourist essential not only for U.S citizens, as well as for everyone in the world, to help them prevent wasting time and money for nothing or unworthy vacation .