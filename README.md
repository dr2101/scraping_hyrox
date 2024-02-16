# Hyrox Race Insights: A Comprehensive Web Scraping to Visualization Pipeline

# Executive Summary
In this data engineering project we developed a comprehensive web scraping solution using Google Colab to harvest race results across multiple seasons from hyrox.com. The project involved creating a sophisticated data model, setting up a PostgreSQL database for structured data storage, and employing advanced data cleaning techniques to ensure data integrity. This clean, structured data was then visualized using Metabase, providing insightful dashboards and reports. The successful execution of this project from data extraction to insightful visualization showcases a high level of technical proficiency, problem-solving skills, and an adeptness at managing the entire data pipeline, which can significantly contribute to data-driven decision-making processes.


# Method(s)


1 –– Web Scraping Tool Development:
Developed a web scraper using Python in Google Colab
The scraper is designed to extract race results from a specified season from a Hyrox.com
Implemented error handling and logging to ensure robustness and traceability of the scraping process
Used time estimation to provide feedback on the scraping progress

2 –– Data Modeling and Database Setup:
Created a data model to structure the scraped data effectively
Set up a PostgreSQL database, aligning with the defined data model to store the race results
Configured the database schema with tables, columns, relationships, and constraints

3 –– Data Cleaning and Transformation:
Utilized another Google Colab notebook to clean and transform the scraped data
Flattened nested JSON structures and removed unnecessary fields to fit the PostgreSQL schema
Implemented Python functions for data consistency checks and normalization.

4 –– Data Import into PostgreSQL:
Imported the cleaned and structured data into the PostgreSQL database
Ensured that the import process matched the data types and constraints of the database schema
Performed any necessary data type conversions and dealt with missing values during the import

5 –– Data Analysis and Visualization:
Connected the PostgreSQL database to Metabase running on localhost
Used Metabase to create visualizations, dashboards, and reports from the race results data
Enabled stakeholders to interact with the data through Metabase's user-friendly interface for insights and decision-making

6 –– Project Management and Version Control:
Used Git for version control to manage the codebase for the scraper and data processing scripts

7 –– Testing and Quality Assurance:
Conducted thorough testing of the web scraping and data import processes to ensure data integrity
Performed quality assurance on the PostgreSQL setup and Metabase configurations to ensure accuracy and reliability of the visualizations
