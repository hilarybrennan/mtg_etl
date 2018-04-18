# mtg_etl

A simple ETL pipeline from TCG player API to Google Bigquery 

#Installation

1. Create .Renvrion in home directory
2. Add TCG player authorization keys:
```
TCG_PUBLIC=[USER_KEY]
TCG_PRIVATE=[CLIENT_SECRET]
```
3. Install R packages: httr, jsonlite, tidyverse