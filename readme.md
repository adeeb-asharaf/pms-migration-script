# PMS DATA MIGRATION WITH MASKING SCRIPT

> #### How To Use this Script
> - add table names to ignore from data dump (edit ignore_tables.csv)
> - add column names for masking (edit mask_field_names.csv)
> - Note: mask_field_names.csv format [tablename , field1, field2,...]
> - Edit config/config.py for db username, password, and endpoint
> 

> #### How Run This Script
> - Run pip install - requirements.txt
> - Run python main.py

> #### Output
> - Two Kinds of output will be generated by this script
> - csv [Generates seperate CSV for each table. Location: output/csv/]
> - sql [Generates a single SQL file with all insert statements. Location:output/sql]
