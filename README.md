# NYC-taxi
## Data
http://www.nyc.gov/html/tlc/html/about/trip_record_data.shtml
The source of the data is NYC open data, which contains over 60 million yellow and green taxi trip information.

## Analysis
The analysis uses the parallel processing power of SparkSQL and MLlib. The Spark infrastrusture was set up on AWS EMR to take advantage of the on-demand feature.

The analysis itself involves exploratory data analysis and unsupervised learning. The final model is a KMeans clustering implemented using Spark's MLlib package. Visualizations of the results were generated using Bokeh, a Python graphing library.

## Results
Here are some examples of analysis results visualized.

![Rush Hour Trip Time to JFK Heat Map]
(https://github.com/wenmwang/NYC-taxi/blob/master/JFK_r.png)

![Rush Hour Trip Time to LGA Heat Map]
(https://github.com/wenmwang/NYC-taxi/blob/master/LGA_r.png)

![Trip Time range from Midtown to JFK by trip start hour]
(https://github.com/wenmwang/NYC-taxi/blob/master/trip_length_to_JFK.png)
