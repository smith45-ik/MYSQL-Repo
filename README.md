

# HR Data Analytics Project

This repository contains a data analytics project that focuses on analyzing Human Resource (HR) data for a brand. The project utilizes MySQL for data storage and manipulation, as well as Power BI for data visualization. The HR dataset was initially loaded from a CSV file into a MySQL database, and then cleaned and analyzed using SQL queries. The results of the SQL queries were subsequently visualized using Power BI to gain insights and create interactive visualizations.

## Dataset

The HR dataset used in this project contains information about employees, including attributes such as employee ID, name, department, salary, years of experience, performance ratings, and other relevant details. The dataset was loaded into a MySQL database to facilitate data analysis and visualization.

## Project Structure

The project repository is organized as follows:

- **data**: This directory contains the original HR dataset in CSV format.

- **scripts**: This directory contains the SQL scripts used to load the CSV data into a MySQL database, perform data cleaning, and execute exploratory data analysis (EDA) queries.

- **results**: This directory stores the output files generated from the SQL queries. These files include cleaned datasets, aggregated data, and other intermediate result sets.

- **visualizations**: This directory contains the Power BI files (.pbix) that visualize the analyzed HR data. These files provide interactive dashboards, charts, and reports.

## Getting Started

To reproduce the analysis and visualizations or explore the project, follow these steps:

1. Install MySQL: If you haven't installed MySQL, download and install the latest version suitable for your operating system.

2. Create a database: Set up a MySQL database to store the HR data. You can create a new database specifically for this project or use an existing one.

3. Load the dataset: Import the HR dataset from the CSV file into the MySQL database using SQL statements or a MySQL client tool such as MySQL Workbench.

4. Data Cleaning and EDA: Use the SQL scripts in the `scripts` directory to clean the data and perform exploratory data analysis. Modify the scripts as necessary to suit your specific data and analysis requirements.

5. Execute SQL queries: Run the SQL scripts to execute the data cleaning and EDA queries. The output files will be saved in the `results` directory.

6. Visualize the results: Open the Power BI files in the `visualizations` directory using Power BI Desktop or Power BI Online. Connect to the MySQL database and import the result sets generated from the SQL queries. Customize and explore the visualizations to gain insights into the HR data.
