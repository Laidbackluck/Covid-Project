
## Project Overview

This project was inspired by [Alex The Analyst](https://github.com/AlexTheAnalyst) and his [Covid Analysis](https://www.youtube.com/watch?v=qfyynHBFOsM&t=567s). The goal of this project is to demonstrate how to connect a PostgreSQL database to Python and run queries through it, using the Python libraries Pandas and Psycopg2. The project also includes a Jupyter notebook that shows a step-by-step process for extracting and analyzing historical data of COVID-19 up to January 8, 2022.

## Project Outline
1. Data Preparation: We first used Microsoft Excel to format and modify a .csv file downloaded from [Our World In Data](https://ourworldindata.org/covid-deaths) into two separate files ("CovidDeaths.csv" and "CovidVaccinations.csv"), which were then uploaded to a local PostgreSQL database.
2. Connect to Database: Next, we used the Python library Psycopg2 to connect to the PostgreSQL database and run SQL queries to extract the data we needed.
3. Create Views: We also saved some of the queries as views, which were not used in this project, but can be helpful for other projects.
4. Data Analysis: Finally, we used the Pandas library to display the results of the queries, perform further analysis and manipulate the data for better understanding.

## Project Goal

The main goal of this project is to extract insights and deliver a interactive visualization to showcase the analysis on historical data of COVID-19, up to the date Jan 8, 2022. The project also demonstrates how to integrate Postgres SQL with Python to run queries, and use libraries like Pandas for analysis and data manipulation

## Sample Code
#### Connecting to PostgreSQL Database
![sample_query1](https://user-images.githubusercontent.com/91815051/214540976-dd1a76db-2bc3-4ab9-ab24-1bcbbe1429c2.png)

#### Create views and display with Pandas
![sample_query](https://user-images.githubusercontent.com/91815051/214541187-0df08b6f-6c58-47ac-a7ac-5ffdb387a896.png)
![sample_results](https://user-images.githubusercontent.com/91815051/214541348-1fdc191d-c6cc-4ebd-a7e6-60a474766415.png)

## Conclusion

This project serves as a useful resource for anyone looking to connect a PostgreSQL database to Python and run queries through it, as well as for those looking to use Pandas for data analysis and manipulation.

You can find the code for this project on [HERE](https://github.com/Laidbackluck/Covid-Project/blob/main/Covid_SQL_queries.ipynb)
