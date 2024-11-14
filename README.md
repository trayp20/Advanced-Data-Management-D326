# Advanced-Data-Management-D326 SQL Business Report for DVD Database
This project utilizes the "Labs on Demand" DVD dataset to create a SQL-driven business report, extracting and transforming data to answer a specific business question. The project includes designing and creating both detailed and summary tables, using SQL functions, triggers, and stored procedures for data automation and refresh capabilities.

# Project Components
# Report Design and Planning
A report answering a business question based on the DVD dataset, with two sections:
Detailed Table:
Contains granular data fields for in-depth analysis.

Summary Table: 
Aggregated data providing high-level answers to the business question.

Defined fields and data transformations to ensure user-friendly data presentation.

# SQL Code and Functionality

User-Defined Function: Transforms specific data fields in the detailed table for clarity (e.g., changing "Y" or "N" values to "Yes" or "No").
Table Creation: SQL statements to create the structured tables for the report.

Data Extraction Query: An SQL query to pull necessary raw data for the detailed section.

Trigger for Updates: A trigger on the detailed table to automatically update the summary table.

Stored Procedure: Refreshes data in both tables, with a recommendation for an automated job scheduler to run the procedure regularly.

# Key Deliverables
SQL Code: Includes table creation, transformation functions, data extraction, trigger, and stored procedure.

Transformation and Automation: Ensures the report remains relevant with automated data refreshes.

Demonstration Video: Provides a clear, vocalized demonstration of the code and process.
