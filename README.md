# Data_Modeling_w_Cassandra

## Goal
The goal of this project is to build a NoSQL database using Apache Cassandra. The data includes songs and user activity collected 
from the music streaming application launched by a startup company, Sparkify. This project is going to do data modeling with Apache 
Cassandra and complete an ETL pipeline using Python. 

## The Task Overview
The main task is to extract the data from the CVS file, event_datafile_new.csv, to create a denormalized dataset. 
Then model the data tables to meet the requirement of the following queries: 
1. Give me the artist, song title and song's length in the music app history that was heard during sessionId = 338, and itemInSession = 4
2. Give me only the following: name of artist, song (sorted by itemInSession) and user (first and last name) for userid = 10, sessionid = 182
3. Give me every user name (first and last) in my music app history who listened to the song 'All Hands Against His Own'

