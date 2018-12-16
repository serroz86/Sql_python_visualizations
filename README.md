# USING SQL FROM PYTHON

## Objective

In this notebook I will use python to perform a SQL query on a database, and perform statistical analysis and visualizations using python/matplotlib and python/seaborn. The data is taken from the Lahman Baseball Database.

## The Lahman Baseball Database

The data is obtained from the Lahman Baseball Database. This database contains complete batting and pitching statistics from 1871 to 2017, plus fielding statistics, standings, team stats, managerial records, post-season data, and more. I will select the database which goes to the year 2016, as the one for 2017 is not complete yet. 

All the data from the database are stored in the following webpage: http://www.seanlahman.com/baseball-archive/statistics/.

## Tools
- Python module 'sqlite3' to query the database
- Python module pandas to analyse the data
- Python module matplotlib and seaborn to plot the results.

## Requirements

a) python 3 and the following modules: sqlite3, pandas, numpy, matplotlib, seaborn, scipy 

Most of these can be installed using the basic Anaconda installation. 

b) It is necessary to download the database in form of .sqlite file (lahman2016.sqlite), retrieved from http://seanlahman.com/files/database/lahman2016-sql.zip
