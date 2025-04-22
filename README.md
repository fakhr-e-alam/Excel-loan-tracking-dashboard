# Loan Data Analysis Project using MS Excel
## Project Objectives
This project focuses on cleaning, processing, and analyzing loan data to extract actionable insights for financial decision-making. It demonstrates core data analysis skills including data cleaning, metric calculation, and data visualization using pivot tables and charts in Excel.
## Objectives
Clean and preprocess raw loan data

Calculate key loan metrics (total loan, repayments, debt, etc.)

Visualize trends and client behavior

Identify areas of risk and customer feedback sentiment
## Overview: What is this dataset about?
This is a loan tracking CRM (Customer Relationship Management) dataset used by banks or financial institutions. It helps them keep track of:
•	Who took a loan (Client details)
•	What kind of loan (Product, amount, terms)
•	Status of the loan (How much has been repaid, how much is owed)
•	Client interactions/updates (Notes)
## Execution
As a data analyst, your job is to clean, organize, and generate insights from this data — like total debt, client repayment behavior, most active branches, etc
## 1. Data Cleaning (Initial Preparation Step)
Before performing any analysis, the dataset was cleaned to ensure consistency and accuracy.
•	1.1 Remove Duplicates:
The dataset was checked for duplicate records. No duplication was found, so no action was needed.
•	1.2 Standardize Text Fields:
Client names and other categorical text fields were cleaned by applying proper case formatting (e.g., converting all names to "Proper Case" or uppercase depending on the column requirement).
•	1.3 Convert Currency Fields to Numeric:
Monetary values (e.g., loan amount, repayments) were originally in text format with currency symbols. These were converted to numeric format to allow for calculations and aggregation.
________________________________________
## 2. Key Loan Metrics Calculation (Data Processing Stage)
After cleaning, several loan-related metrics were calculated to assess the financial performance and repayment behavior.
•	2.1 Total Loan Amount:
Calculated the total disbursed loan amount from all clients.
•	2.2 Total Repaid Amount:
Summed up all repayments made by clients.
•	2.3 Total Debt Outstanding:
Derived by subtracting total repaid from total loan disbursed.
•	2.4 Statistical Summary of Loan Amounts:
Calculated the average, maximum, and minimum loan amounts to understand the distribution of loan sizes.
•	2.5 Remarks and Client Interactions:
Reviewed client remarks to note feedback, concerns, or notable interactions for further sentiment analysis.

## 3. Data Visualization (Using Pivot Tables and Charts)
To better communicate insights from the dataset, pivot tables and charts were used for visual analysis:
•	Chart 1: Repaid vs. Debt Comparison
Created a pivot chart showing the total repaid amount versus the outstanding debt across all clients. This helps identify repayment patterns and risk levels.
•	Chart 2: Loan Distribution by Product
Generated a pivot chart breaking down the total number and value of loans by product type. This visualizes which loan products are most popular or profitable.
•	Chart 3: Client Feedback Sentiment
Analyzed and categorized client remarks into Positive and Negative sentiments. A chart was created to reflect the proportion of positive versus negative feedback, offering insights into customer satisfaction.

## dashboard image
![Screenshot (69)](https://github.com/user-attachments/assets/cbe9f358-b9d0-4a65-97db-2d5454f76242)



