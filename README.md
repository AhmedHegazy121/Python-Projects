# Python Projects

### [Case Study: How Does a Bike-Share Navigate Speedy Success](https://github.com/AhmedHegazy121/portfolioProjects/blob/main/Share%20_Bike.ipynb)  |  [Link](https://github.com/AhmedHegazy121/portfolioProjects/blob/main/Share%20_Bike.ipynb)

 **brief summary of your cleaned dataframe bike:**
- Loaded Data: You've successfully loaded 12 CSV files for each month of 2023.
- Merged Data: Merged these files into a single dataframe.
- Converted Datatypes: Converted started_at and ended_at columns to datetime format.
- Renamed Columns: Renamed columns for clarity.
- Created New Columns: Added columns for time, month, year, day of the week, and a combined month-year column.
- Calculated Ride Length: Calculated the length of each ride in minutes.
- Removed Negative Durations: Dropped rows with negative ride lengths.
- Conduct descriptive analysis.
- Export a summary file for further analysis.








### [Cleaning Data use Python](https://github.com/AhmedHegazy121/portfolioProjects/blob/main/Clean_Cricketers.ipynb) |  [Link](https://github.com/AhmedHegazy121/portfolioProjects/blob/main/Clean_Cricketers.ipynb)

**Here's an explanation of the steps taken in your code:**

Reading the CSV File: The code reads a CSV file named New.csv into a pandas DataFrame named df, which contains data about cricket players and their performance statistics.

Renaming Columns: Several columns are renamed to more descriptive names, such as "Mat" to "matches_played", "Inns" to "innings_batted", "NO" to "not_outs", etc., for better readability and understanding of the data.

Checking for Null Values: The code checks for any null values in the DataFrame and finds that several columns contain null values.

Handling Missing Values: Specifically, the code identifies that the "balls_faced" and "batting_strike_rate" columns contain null values for some players. It fills these null values with 0 to handle missing data appropriately.

Dropping Duplicate Rows: The code identifies and drops duplicate rows in the DataFrame to ensure that each player is represented only once in the dataset.

Splitting the Span Column: The "Span" column, which contains the years a player was active, is split into two separate columns, "Rooki_year" and "final_year", representing the start and end years of the player's career.

Dropping Unnecessary Columns: The original "Span" column is dropped from the DataFrame as it has been replaced by the new "Rooki_year" and "final_year" columns.

Dropping a Specific Row: Finally, the code drops a row with index 67, which contains NaN values in all columns, to clean up the DataFrame further and ensure no irrelevant data remains.







### [The CoinMarketCap API](https://github.com/AhmedHegazy121/portfolioProjects/blob/main/API.ipynb) | [Link](https://github.com/AhmedHegazy121/portfolioProjects/blob/main/API.ipynb)

Here is a refined and complete version of the code to fetch the latest cryptocurrency listings from the CoinMarketCap API. Make sure to handle the API key securely.
The script fetches the latest cryptocurrency listings from the CoinMarketCap API. It sets up a session with the necessary headers, including the API key, and sends a GET request to the API endpoint with specified parameters.
The response is parsed as JSON and printed in a readable format. Errors such as connection issues, timeouts, and too many redirects are handled gracefully.



