# Data Cleaning and Joining with Power Query

This project demonstrates data cleaning and joining techniques using Power Query within Microsoft Excel. The provided Excel file, `Data - Survey Monkey Output.xlsx`, was created following tutorials from the YouTube channels linked below.

## Datasets

-   Survey Data: [https://youtu.be/pKvWD0f18Pc?si=_comfSd9408_JZCM](https://youtu.be/pKvWD0f18Pc?si=_comfSd9408_JZCM)
-   Additional Data: [https://youtu.be/GNgutUElOTk?si=Lt1MxWREr9jVsgW0](https://youtu.be/GNgutUElOTk?si=Lt1MxWREr9jVsgW0)

## Data Joining Using Power Query

This section outlines the steps taken to load and combine data from CSV and Excel sources using Power Query.

### Loading CSV Data

1.  **Open Excel:** Launch Microsoft Excel.
2.  **Navigate to the Data Tab:** Click on the "Data" tab in the Excel ribbon.
3.  **Initiate Data Import:** Click on "Get Data."
4.  **Select File Source:** Choose "From File."
5.  **Choose Text/CSV:** Select "From Text/CSV."
6.  **Select CSV File:** Browse and select the desired CSV file.
7.  **Load Data:** Click "Load" to import the data into Excel as a query.

### Appending Queries (Combining Rows)

1.  **Navigate to the Data Tab:** Click on the "Data" tab.
2.  **Access Combine Queries:** Click on "Get Data" and then "Combine Queries."
3.  **Select Append Queries:** Choose "Append Queries."
4.  **Specify Queries:** Select the queries you want to append (stack rows from different tables).
5.  **Confirm Append:** Click "OK" to execute the append operation.

### Merging Queries (Combining Columns)

1.  **Navigate to the Data Tab:** Click on the "Data" tab.
2.  **Access Combine Queries:** Click on "Get Data" and then "Combine Queries."
3.  **Select Merge Queries:** Choose "Merge Queries."
4.  **Select Queries:** Select the queries you want to merge (join based on matching columns).
5.  **Select Merge Columns:** Choose the columns from each query that will be used for the merge (join keys).
6.  **Confirm Merge:** Click "OK" to execute the merge operation.

## Usage

To reproduce the data cleaning and joining steps:

1.  Download the provided Excel file (`Data - Survey Monkey Output.xlsx`).
2.  Open the Excel file and navigate to the "Data" tab.
3.  Explore the queries created in Power Query to understand the data transformation process.
4.  Review the appended and merged tables to see the combined results.

This project serves as a practical example of utilizing Power Query for efficient data manipulation within Excel.
