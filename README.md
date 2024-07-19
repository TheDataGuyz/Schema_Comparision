# Schema Comparison Tool

This Excel-based Schema Comparison Tool is designed to compare the schema and metadata of two SQL Server databases sitting in different servers / same server. It identifies differences in tables, columns, and metadata between the databases being compared. This tool is particularly useful for database administrators and developers who need to ensure consistency between different database environments.

## Features

- **Object Comparison**: Compares tables and views between two databases and identifies objects that have been added or removed.
- **Column Comparison**: Compares columns within tables and views between two databases and identifies columns that have been added or removed.
- **Metadata Comparison**: Compares metadata of columns (e.g., data type, length, precision) and identifies changes in metadata attributes.

## Usage

1. **Input Server Details**: On the `User Input Page`, enter the details of the servers and databases you want to compare.
    - **Comparing From**: Enter the source server and database details.
    - **Comparing To**: Enter the target server and database details.

2. **Run the Report**: Click the "Run the Report" button to execute the comparison queries.

3. **Review the Results**:
    - **Object Comparison**: Review the `Object_Comparison` sheet to see a list of objects that have been added or removed.
    - **Column Comparison**: Review the `Column_Comparison` sheet to see a list of columns that have been added or removed.
    - **Metadata Comparison**: Review the `MetaData_Comparison` sheet to see a list of columns with changes in their metadata attributes.

## Highlights

- **Added Objects/Columns**: Highlighted in **green**.
- **Deleted Objects/Columns**: Highlighted in **red**.

## Glossary

- **Added**: Object/Column added in the database being compared from (highlighted in green).
- **Deleted**: Object/Column deleted in thevdatabase being compared from (highlighted in red).

## Additional Information

This tool allows comparisons between databases in different environments/same environment. Ensure you have the necessary permissions to access the databases and run the required queries on both servers.