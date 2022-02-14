# Passive_ETF_Income

This project compares ETF returns and makes use of data stored in a data base rather than a csv or making use of an API call. The program reads SQL tables stored in an ETF database and pulls data as need to manipulate as a python database within Jupyter Lab.

Skills such are using SQL query’s are used to gather data as needed to perform a financial analysis. 

SQLalchemy is used as SQLite database within which the data is housed. An engine is created to interface between our notebook and the database.


# Technologies
The program is written using Jupyter notebooks, for ease of code reading and code execution via code blocks. The program lays out a stepwise reporting and program execution. The code is run in a (Dev) environment with the use of the following libraries:

Pandas
hvplot
sqlalchemy
numpy


# Usage

The use of the program requires the use of an SQLite database built using sqlalchemy. 

Daily returns of ETFs and

![daily_returns_image1](https://user-images.githubusercontent.com/95830866/153782294-5ae1047a-20b1-478f-8b65-052fd291c2ac.PNG)


cumulative returns for the ETFs are evaluated.

![cum_returns_image2](https://user-images.githubusercontent.com/95830866/153782311-98d13f5f-8fba-42bb-b18e-6d9584930670.PNG)

# Contributors
This program was developed with base code developed by the Rice-boot-camp. Code was created and added by JPinglia.

# License
License for this project and associated file is public.
