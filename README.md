# Layoffs Data Analysis Project

## Project Summary
This project focuses on analyzing layoff data across various companies, industries, locations, and time periods. Using SQL, we have performed data cleaning, standardization, and exploratory data analysis to derive meaningful insights. The dataset includes columns such as company, location, industry, total laid off, percentage laid off, date, stage, country, and funds raised (in millions).

## Data Cleaning and Standardization

### Steps Involved:
1. **Data Import and Schema Design**:
   - Created a staging table and imported the data.
   - Identified and removed duplicate records using window functions.
   - Standardized company names, industry categories, and country names.
   - Converted date columns to appropriate data types.
   - Removed records with missing key data points.

## Exploratory Data Analysis

### Key Analyses Performed:
1. **Basic Descriptive Statistics**:
   - Average and maximum layoffs.
   - Standard deviation of layoffs.

2. **Industry and Location Analysis**:
   - Average layoffs by industry.
   - Total layoffs by location.
   - Trends in layoffs over time.

3. **Layoffs by Company Stage**:
   - Total layoffs categorized by the stage of the company.

4. **Fundraising Insights**:
   - Companies with large amounts of funds raised.

## How to Use

1. **Clone the Repository**:
   ```sh
   git clone https://github.com/mirdanish6594/World-Layoffs
2. **Import SQL Script**:
Use a MySQL client to execute the World layoffs.sql script against your database.
3. **Run Queries**:
Execute the SQL queries in World layoffs.sql to perform various analyses.

### Contributing
Feel free to fork this repository, make improvements, and submit pull requests.
