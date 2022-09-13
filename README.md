# Covid-Project-Repository

![covid_dash](https://user-images.githubusercontent.com/91815051/149006650-dfb19f2c-fba8-47f5-9c2d-c456d063d4c9.png)

This project inspired by [Alex The Analyst](https://github.com/AlexTheAnalyst) and his [Covid Analysis](https://www.youtube.com/watch?v=qfyynHBFOsM&t=567s).  

I liked the way Alex presented his queries in his analysis and wanted to put my own spin on the project by taking it a step further by querying through Python, that way I can display a step by step process in a Jupyter notebook.  

The main goal of this project is to extract insights and deliver a interactive visualization to showcase the analysis on historical data of COVID-19, up to the date Jan 8, 2022.

Another part of this project is to showcase how to integrate Postgres SQL with Python to run queries, and use libraries like Pandas for analysis and data manipulation

We will accomplish these goals by using python to connect to a Postgre SQL database, performing some SQL queries to extract data,  save those quesries as views, and finally use those views in a data visulization tool, such as Tableau or PowerBI, to create an interative visualization. 

The data for this project was downloaded as a .csv file from [Our World In Data](https://ourworldindata.org/covid-deaths), modified and formatted in Microsoft Excel into two separate .csv files ("CovidDeaths.csv" and "CovidVaccinations.csv"), and then uploaded to a local Postgre SQL database.
