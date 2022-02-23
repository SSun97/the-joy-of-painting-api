# ETL
In this project we are going to explore the idea of ETL (Extract, Transform, Load), which is the process of taking data from multiple unique sources, modifying them in some way, and then storing them in a centralized database. This is a very common practice when collecting data from systems in order to utilize that data in another system. This data may come in the form of CSV, JSON, XML, API requests with other custom formats, etc - it might even be that you have direct access to several databases with different, but relatable data that you want to be merged into another database in order to gain insight from it in some way.

# Steps
1. using AWS EC2 as the base
2. install virtual env
3. install PostgreSQL as database locally 
4. install pandas
5. install psycopg2
6. put .CSV file in the project root directory and script will transform all the .csv file rename them and save them to new created directory datasets
7. in for loop, each file will be renamed columns(use lowercase),  the table in Postgres will be created according to the file name, then data will be loaded to the databases.

 run the script
 python3 inport_data.py