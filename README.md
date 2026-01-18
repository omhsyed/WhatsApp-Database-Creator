# WhatsApp-Chat-to-SQL-Database
A Python script which prompts the user for an exported WhatsApp chat .txt file and MySQL server info, and then automatically extracts data including member names, messages, dates, words, and word counts. This data is then uploaded to the user's MySQL server with automatically created databases and tables, from which further statistics are calculated and entered. The final data tables are also visualized for the user in the interface provided by running the Python script.

The data flow can be described as:
- Receive user-inputted file and information using tkinter library
- Extract and transform/clean data using standard Python
- Load data into MySQL using mysql.connector library
- Read data from MySQL using pandas library
- Present data tables to user using tkinter library


