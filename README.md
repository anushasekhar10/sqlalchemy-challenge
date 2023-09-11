# sqlalchemy-challenge
**Module 10 Challenge**

Using the files provided in the Resources folder in this Module we will

**Part1 Analyze and Explore the Climate Data**

Use Python and SQLAlchemy to do a basic climate analysis and data exploration of your climate database

**1.Precipitation Analysis:**
Find the most recent date in the dataset.

Using that date, get the previous 12 months of precipitation data by querying the previous 12 months of data.

Select only the "date" and "prcp" values.

Load the query results into a Pandas DataFrame. Explicitly set the column names.

Sort the DataFrame values by "date".

Plot the results by using the DataFrame plot method

Use Pandas to print the summary statistics for the precipitation data.

**2.Station Analysis:**
Design a query to calculate the total number of stations in the dataset.

Design a query to find the most-active stations (that is, the stations that have the most rows). To do so, complete the following steps:
  
  List the stations and observation counts in descending order.

  Answer the following question: which station id has the greatest number of observations?

Design a query that calculates the lowest, highest, and average temperatures that filters on the most-active station id found in the previous query.

Design a query to get the previous 12 months of temperature observation (TOBS) data. To do so, complete the following steps:

Filter by the station that has the greatest number of observations.

Query the previous 12 months of TOBS data for that station.

Plot the results as a histogram with bin size of 12.

**Part 2: Design Your Climate App**

Design a Flask API based on the queries that you just developed

**Submission files will be **

1.Jupyter Notebook

2.Python-executable file 
