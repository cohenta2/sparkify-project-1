# Project 1

## Description
The startup company Sparkify needed a Postgres database that optimized reads for songplay.  This is implemented with a songplays fact table that can join to users, songs, artists, and time dimension tables.

## Setup
- This project requires and enviornment with Python 3.6.3 and PostgreSQL 9.5.21

##  Create Database & Tables
- run  `python create_tables.py`

## Populate Tables
- data directory needs be a sibling of etl.py
- run `python etl.py`

## Output
If successful you should see messages iterating over the data files saying that they were successfully processed.
