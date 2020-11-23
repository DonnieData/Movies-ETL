# Movies-ETL
Utilizing python and SQL to build-out ETL pipelines that clean, transform, and load datasets into a database. 

##  Resources 
- Python 3.7.6, JupyterLab 2.26
- [PostgreSQL 12.2](https://www.postgresql.org/), [Pgadmin 4.20](https://www.pgadmin.org/) 
- Movie Data sourced from [IMDB](https://developer.imdb.com/?ref=ft_ds), [Kaggle](https://www.kaggle.com/) <small><i>(note: due to size of the raw data files, they are not included within this repo) </i></small>

## Overview 
The purpose of this project is to create a [refactorable](https://en.wikipedia.org/wiki/Code_refactoring) and intuitive [ETL Pipeline](https://databricks.com/glossary/etl-pipeline#:~:text=Back%20to%20glossary%20An%20ETL,Extract%2C%20Transform%2C%20and%20Load.) that helps automate processing large sets of data. 


## Primary steps & stages of the pipeline 

- <b>Extract</b><br>
This stage involves the initial retrieval and reading of data in various formats (csv, json) by using a python environment that can interpret the data. 

![pipeline_1](https://github.com/DonnieData/Movies-ETL/blob/main/Resource/image/pipeline_1.png)

- <b>Transform</b><br>
This stage involves several more granular step including but not limited to: 
  - Cleaning data: assessing missing values and any corrupt data, formating   
  - Transforming: filtering , formatting, classifying (data type is redefined/changed to better suit analysis interpretation), merging data
  
![pipeline_2](https://github.com/DonnieData/Movies-ETL/blob/main/Resource/image/pipeline_2.png)

- <b>Load</b><br>
this stage involves connecting to a database/server from the python environment and loading the data into the appropriate tables/schemas. 

![pipeline_4](https://github.com/DonnieData/Movies-ETL/blob/main/Resource/image/pipeline_4.png)
