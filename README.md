# Crowdfunding Excel Dashboard

Welcome to the GitHub repository for the Crowdfunding Excel Dashboard. This project aims to analyze crowdfunding data, providing insights and visualizations to understand project outcomes, funding details, and other key metrics.

## Instructions

### 1. Date Fields and Calendar Table

- **Convert the Date fields to Natural Time:**
  - The dates in the dataset are currently in Epoch time. Please refer to the attached article on [Epoch Time](https://www.epochconverter.com/) for reference.
  
- **Build a Calendar Table:**
  - Create a Calendar Table using the `Created Date` column, spanning from the minimum to maximum dates in your dataset.
  - Add the following columns using the given formulas:
    - A. Year
    - B. Monthno
    - C. Monthfullname
    - D. Quarter (Q1, Q2, Q3, Q4)
    - E. YearMonth (YYYY-MMM)
    - F. Weekdayno
    - G. Weekdayname
    - H. FinancialMonth (April = FM1, May = FM2, ..., March = FM12)
    - I. FinancialQuarter (Quarters based on Financial Month FQ-1, FQ-2, ...)

### 2. Data Model

- **Build the Data Model:**
  - Utilize the attached Excel files to construct your data model.

### 3. Currency Conversion

- **Convert Goal Amount to USD:**
  - Use the static USD rate to convert the goal amount into USD.

### 4. Projects Overview KPI

- **Total Number of Projects:**
  - Breakdown by outcome, locations, and category.
- **Total Number of Projects Created:**
  - Aggregated by year, quarter, and month.

### 5. Successful Projects

- **Amount Raised, Number of Backers, and Average Number of Days for Successful Projects.**

### 6. Top Successful Projects

- **Based on Number of Backers and Amount Raised.**

### 7. Percentage of Successful Projects

- **Overall and by Category, Year, Month, etc.**
- **Percentage of Successful Projects by Goal Range (define the range as per your needs).**

## Data Files

- Please find the attached Excel files in the repository for dataset and additional resources.

## Usage

- Clone the repository to your local machine.
- Open the Excel file in Microsoft Excel.
- Explore the dashboards and visualizations.

