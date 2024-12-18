# 🐍 Python Projects Portfolio

This portfolio presents Ahmed Hegazy’s hands-on Python projects, showcasing expertise in data cleaning, API integration, and analytical problem-solving. These projects highlight skills in working with real-world datasets, performing advanced cleaning techniques, and integrating third-party APIs to extract actionable insights.

---

### 🚴 [Case Study: How Does a Bike-Share Navigate Speedy Success](https://github.com/AhmedHegazy121/portfolioProjects/blob/main/Share%20_Bike.ipynb)  
**[GitHub Link](https://github.com/AhmedHegazy121/portfolioProjects/blob/main/Share%20_Bike.ipynb)**  

**📝 Brief Summary of the Data Cleaning and Analysis Process:**
- **Loaded Data**: Imported 12 CSV files representing each month of 2023.  
- **Merged Data**: Combined these files into a single dataframe for analysis.  
- **Datatype Conversion**: Transformed `started_at` and `ended_at` columns into `datetime` format.  
- **Column Renaming**: Adjusted column names to enhance clarity and consistency.  
- **New Columns Added**: Created additional columns to extract insights such as:  
  - Time, month, year, day of the week, and a combined month-year column.  
- **Ride Length Calculation**: Determined ride durations in minutes.  
- **Data Cleaning**: Removed rows with negative ride durations.  
- **Descriptive Analysis**: Conducted statistical exploration of the data.  
- **Summary Export**: Generated a summary file for further insights.  

---

### 🧹 [Cleaning Data with Python](https://github.com/AhmedHegazy121/portfolioProjects/blob/main/Clean_Cricketers.ipynb)  
**[GitHub Link](https://github.com/AhmedHegazy121/portfolioProjects/blob/main/Clean_Cricketers.ipynb)**  

**📝 Key Steps in the Data Cleaning Process:**
- **Reading Data**: Imported a CSV file named `New.csv` containing cricket players' performance statistics into a Pandas DataFrame.  
- **Renaming Columns**: Simplified column names, e.g., `Mat` → `matches_played`, `Inns` → `innings_batted`.  
- **Null Value Handling**:  
  - Identified null values in `balls_faced` and `batting_strike_rate`.  
  - Replaced these null values with 0 for data consistency.  
- **Duplicate Removal**: Eliminated duplicate rows to ensure uniqueness.  
- **Splitting Columns**:  
  - Split the `Span` column into `Rooki_year` (start year) and `final_year` (end year).  
  - Dropped the original `Span` column as it was no longer needed.  
- **Dropping Irrelevant Data**: Removed unnecessary rows and columns, including a row with all NaN values.  

---

### 💰 [The CoinMarketCap API](https://github.com/AhmedHegazy121/portfolioProjects/blob/main/API.ipynb)  
**[GitHub Link](https://github.com/AhmedHegazy121/portfolioProjects/blob/main/API.ipynb)**  

**📝 Project Highlights:**
- **API Integration**: Set up a session with appropriate headers, including an API key, to securely interact with the CoinMarketCap API.  
- **Latest Listings**: Fetched real-time cryptocurrency data using a GET request.  
- **Error Handling**: Implemented safeguards against:  
  - Connection issues.  
  - Timeout errors.  
  - Excessive redirects.  
- **Readable Output**: Parsed the API's JSON response into a clear, structured format for easy interpretation.  

### 🌐 [Web Scraping Project](https://github.com/AhmedHegazy121/portfolioProjects/blob/main/Scraping%20Data%20.ipynb?short_path=17a3f57)
 ---


