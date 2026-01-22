# WhatsApp-Database-Creator

Website link (copy and paste into browser):  whatsapp-database-creator.streamlit.app

This is a Streamlit website built on a Python script which prompts the user for an exported WhatsApp chat .txt file (and optionally MySQL server info), automatically extracts data including member names, messages, dates, etc., and creates data tables with raw and calculated information. If the MySQL option is selected, the data tables are created within the user's MySQL server and any calculations are performed within SQL. 

The database tables as well as simple graphs are then viewable on the website, and a search feature is provided that allows you to filter chat messages with advanced specifications.

The data flow can be described as:
- Receive user-inputted file and information using Streamlit library
- Extract and transform/clean data using standard Python
- Load data into MySQL using mysql.connector library (if option is selected)
- Create DataFrames using pandas library
- Present data tables and graphs on website using Streamlit and pandas
- Allow for chat searching using another MySQL connection (if that option was selected) or pandas DataFrame filtering









