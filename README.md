# Surfs up

## Overview of the analysis: 
This is an analysis of Hawaii's temperature information stored in SQLite flat file using Python, pandas and sqlalchemy to extract pertinent data.  The queries include extracting data for months of June and December in 2010 - 2017.  

## Results: 
Provide a bulleted list with three major points from the two analysis deliverables. Use images as support where needed.

1. For months of June, after extracting the data and converting it to a list and dataframe, statistical analysis was performed with below results:

[!June Temps.png](Resources/June Temps.png)

2. For months of December, after extracting the data and converting it to a list and dataframe, statistical analysis was performed with below results:

[!December Temps.png](Resources/December Temps.png)

3. Below histograms of June and December months data shows the distribution.  Both graphs show peaks at the mean average of ~75.

[!June Temp Histogram.png](Resources/June Temp Historgram.png)

[!Dec Temp Histogram.png](Resources/Dec Temp Histogram.png)

## Summary: 
From the query results and represented in the histogram, Hawaii's average temperature for both June and December months between 2010-2017 has been very similar.  June and December are normally the two opposite seasons; June in summer and December in winter seasons.  The average temperatures for Hawaii falls around ~70 - 75 degrees for both months, which may indicate this as an average temperature throughout the year, regardless of the season.

Additional queries and analysis to support this hypothesis may be to check using date or month ranges to capture full seasons for comparison.  This analysis also used data from 2010 - 2017 and may want to get more updated temperature data to current (2020) and create another query to limit to previous year only.
