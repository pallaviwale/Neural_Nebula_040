# Data Processing and Real-Time Dashboard Project - AIRBNB PRICE

## Objective
In this project, we worked with a provided dataset to perform data processing, clean the data, load it into an SQL database, and create a dynamic dashboard in Power BI. The dashboard was configured to automatically update whenever changes are made in the SQL database, ensuring real-time insights.

## Prerequisites
Ensure you have the following installed:

Python 3.x
MySQL server
Power BI for visualization

## Project Overview
### 1. Dataset Processing:
#### Task: We downloaded the dataset and uploaded it to Google Drive for accessibility and further processing.
#### Steps Taken:

1. Downloaded the dataset from the provided link.
2. Uploaded the dataset to Google Drive for easy access.
3. Connected to Google Drive using Python to programmatically access the dataset.
4. Loaded the dataset into a pandas DataFrame, cleaned the data (handled missing values, normalized fields), and made necessary transformations.
5. Prepared the cleaned data for loading into an SQL database.
   
### 2. SQL Database Integration:
#### Task: We stored the cleaned data in an SQL database.
#### Steps Taken:

1. Set up an SQL database and created the necessary tables to store the cleaned data.
2. Used Python to load the cleaned data from pandas into the SQL database.
3. Designed the database structure to support key insights and future analysis.
   
### 3. Power BI Dynamic Dashboard:
#### Task: We created a dynamic dashboard in Power BI connected to the SQL database.
#### Steps Taken:

1. Established a connection between Power BI and the SQL database.
2. Designed a Power BI dashboard to reflect key insights and ensure dynamic updates as the data in the SQL database changed.
3. Implemented visualizations such as:
Total sales
Monthly performance
Department-wise analysis
Ensured that the dashboard was user-friendly, visually appealing, and featured clear KPIs.

### 4. Real-Time Updates:
#### Task: We ensured that changes in the SQL database reflected in real time on the Power BI dashboard.
#### Steps Taken:
1. Configured automatic refresh intervals in Power BI to update the dashboard when changes occurred in the SQL database.
2. Validated that the updates in the SQL data were accurately reflected in the Power BI dashboard in real time.

# Installation and Setup
### 1. Clone the Repository
To get started, clone this repository to your local machine:

bash
Copy code
git clone https://github.com/yourusername/Neural_Nebula_040.git
cd Neural_Nebula_040.git

### 2. Dependencies
You will need to install the following Python libraries to run the data processing script:

pandas
sqlalchemy
google-api-python-client
pyodbc (for SQL connection)
To install the dependencies, run:

bash
Copy code
pip install -r requirements.txt

### 3. SQL Database Setup
Set up a database using your preferred SQL service (e.g., MySQL).
Create a database schema that matches the structure of your dataset.
Update the database connection settings in the config.py file to match your local or remote SQL setup.

### 4. Power BI Setup
Open Power BI Desktop.
Go to the "Home" tab and click "Get Data."
Select "SQL Server" and enter the server name and database details.
Load the data into Power BI and begin creating the dashboard.
Set up automatic refresh by configuring the dataset to update on a regular schedule.
