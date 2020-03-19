## DESCRIPTION
In this project, we build a variety of charts, we will leverage our knowledge of Python arrays and turples, and learn how to apply Pandas methods, functions, and conditional expresion, as well as perform mathematical calculations on Series and DataFrames.

### SITUATION/TASK
You ahve been tasked by our CEO to create an overall snapshot of the ride-sharing data. In addition to scatter and pie charts, she would like to see a summary table of key metrics of the ride-sharing data by city type, and a multiple-line graph that shows the average fare for each week by each city type.

### APPROACH
* Use Pandas functions like groupby, pivot, resample, and reset_index on a DataFrame.
* Use Pandas methods and attributes on a DataFrame or Series.
* Create a newDataFrame from multiple groupby() Series.
* Format columns of a DataFrame.
* Create a multiple-line graph.
* Annotate and apply styling to the chart.

### RESULTS
* Write a summary for the data in the summary DataFrame.

    * Urban City Type: 
      The urban city type had the majority total rides and total drivers, which also translates into the highest
      total fare of the 3 city types. It is safe to say that the large number of total drivers and total rides in urban,
      could account for the lowest in average fare per ride and average fare per driver.
           
    * Suburban City Type:
      Similarly, the suburban city type saw the second lowest in average fare per ride and average fare per driver,
      because of the relatively high total driver and total ride counts. Though of note, the city's driver count 
      and total rides are about 7 and 3 times lower respectively,  than that of the urban city's driver count and 
      total rides, the suburban city's average fare per driver isn't much higher. 
       
    * Rural City Type: 
      The rural city type on the other hand experienced the highest in average fare per ride and average fare per driver.
      This too could be as a result of the low counts in total drivers and total rides. The fewer the drivers and rides, 
      the more expensive the fares.
                 
* Write a summary on what the multiple line graph tells you about the fares for each city type over time.   

     * Urban City Type: 
       In the urban city fares are relatively high at the beginning of the month than at months end.
       Fares are the highest in March. And comparatively, the urban city sees a frequent fluctuation in fares,
                 
     * Suburban City Type:
       The peek fare occurs in the month of April. Interestingly, there are specific months that fares tend to be lower 
       in the suburban city, when it's rather high in the urban city or vice versa, eg. months Jan, beginning Feb, Mar, mid Mar etc.            Fares do plateau mid Mar to early Apr.
                   
     * Rural City Type:
       Fares overtime, is almost linear in comaprison to the other cities. A few instances of high fare prices as seen in Feb, 
       end of Feb, begining March, beginning April. Generally, some months have higher fares than others in all 3 cities.
                 
### THINGS LEARNED
* Creating line, bar, scatter, bubble, pie, and box-and-whiskers plots using Matplotlib.
* Adding and modifying features of Matplotlib charts.
* Adding error bars to line and bar charts.
* Determining mean, median, and mode using Pandas, NumPy, and SciPy statistics.

### SOFTWARE/TOOLS/LIBRARIES
Anaconda 4.7.12, PythonData, Jupyter Notebook, Pandas, SciPy, Pandas, NumPy, and Matplotlib.
