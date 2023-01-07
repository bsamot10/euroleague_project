# EuroleagueProject
A collection of Python tools for Euroleague data analysis.

### Brief description of existing folders

##### euroleague_api_etl
A simple Python program that fetches _json_ files from 7 possible Euroleague APIs.

##### euroleague_json_data
A samle of the _json_ files that are fecthed by the _euroleague_api_etl_ tool.

##### euroleague_postgres_etl
A Python program that loads the fetched _json_ files of the Euroleague APIs to a PostgreSQL database.

##### euroleague_tables_to_csv
A very simple Python program that creates one csv file for each available table of the PostgreSQL database.

##### euroleague_csv_data
A samle of the _csv_ files that are created by the _euroleague_tables_to_csv_ tool.
