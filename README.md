# Project 1

## Description
The startup company Sparkify needed a Postgres database that optimizes reads for songplay.  This is implemented with a songplays fact table that can join to users, songs, artists, and time dimension tables.

## Files

- **create_tables.py** - Creates new database, or connects to an existing one, drops all tables contain in drop_table_quries, and then adds all tables in create_table_queries

- **etl.pynb** - A tutorial Jupyter notebook explaining the ETL steps

- **etl.py** - Reads from filepaths data/song_data and data/log_data, and then populates the songplay, users, songs, artists, and time tables from this data.

- **sql_queries.py** - Contains create_table_queries, drop_table_queries, and the query strings that make them up.

- **test.pynb** - A Jupyter notebook to check ETL results

## Setup
- This project requires and enviornment with Python 3.6.3 and PostgreSQL 9.5.21

##  Create Database & Tables
- run  `python create_tables.py`

## Populate Tables
- data directory needs be a sibling of etl.py
- run `python etl.py`

## Output
If successful you should see messages iterating over the data files saying that they were successfully processed.
