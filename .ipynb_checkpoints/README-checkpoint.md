# ETL using Python and PostgreSQL

## Introduction

This project demonstrates an ETL process that reads attribute information and log data using Python and writes the information into a normalized database build in Postgre.  The data represents songs in a streaming service called Sparkify and log data that contains information about who listened to which songs and other related attributes.

This project was developed as part of the Udacity Data Engineering nanodegree program.

## How to install
There is no installation package.  The folder structure and all of the files can be downloaded from the repositoy and saved directly on a local computer.  The code expects the files to be saved in the /home/workspace folder of the local machine

## How to use
* The database is (re)created and refreshed by executing the create_tables.py script from the command line.
* The logic of the ddl and dml scripts in the sql_queries.py script can be tested by executing the etl.ipynb and test.ipnyb python notebooks.
* The <span>etl.py</span> script is the main script that reads and process all of the files in the data folder

## Technologies used
package (version) <br>
python (3.6.3) <br>
psycopg2 (2.7.4) <br>
pandas (0.23.3) <br>
numpy (1.12.1) <br>