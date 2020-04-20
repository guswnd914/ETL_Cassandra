# Developing ETL by Python and Apache Cassandra Modeling
## For the project, go directly to ETL_cassandra.ipynb
******************************************************************


This is originally a project hosted by Udacity and had been edited for its structure and style due to my preference.
Working for this project mainly taught me three things :
* NoSQL modeling with Apache Cassandra
* CQL
* ETL pipeline using Python

## Context
*************************************
A startup called Otto wants to analyze the data they've been collecting on songs and user activity on their new music streaming app. The analysis team is particularly interested in understanding what songs users are listening to. Currently, there is no easy way to query the data to generate the results, since the data reside in a directory of CSV files on user activity on the app.

### Data

- **event_data** : all csv files are nested in subdirectories under /data/event_data.


## Questions

### 1. Show artist, song, and length for session_id = 338, and item_in_session = 4


### 2. Show name of artist, song (sorted by itemInSession) and user full name for user_id = 10, session_id = 182
    

### 3. Show all user full name who listened to the song 'All Hands Against His Own'





## Contents : 
***********************************************************************

**event_data** - This is the original dataset. It consists 30 CSV files and has total 6821 rows.

**images** - This is a photo of data sample. It was used in the project to describe data.
                       
**loaded_data.csv** - This is the file that I loaded transfomred-data in terms of column labels.

**ETL_cassandra.ipynb** - This is the project.


# Thank you!
