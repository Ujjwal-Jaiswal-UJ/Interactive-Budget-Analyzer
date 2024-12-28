# FinTrackPro: Smart Budgeting Assistant using Excel

## Introduction

This project is a Personalize Budget Tracker developed in Microsoft Excel. It aims to provide a user-friendly and efficient tool for tracking personal finances, analyzing spending patterns, and making informed financial decisions.

## Problem Statement

Manually tracking expenses and income can be time-consuming and prone to errors. Without a structured system, it becomes difficult to understand spending habits, identify areas for improvement, and effectively manage finances. This project addresses these challenges by providing a centralized platform for recording and analyzing financial data.

## Deployment

### Expenses Details:

The "Expenses Details" sheet is designed for recording all financial transactions.
Users enter details such as date, category, description, transaction type (debit/credit), payment method, and amount.
The date column automatically populates the corresponding year and month columns.

Automatic Date Updates: Enter the transaction date, and the corresponding year and month cells update automatically.

Comprehensive Table: Capture transaction details including Category, Description, Transaction Type, Payment Method, and Amount.

Balance Tracking: Monitor cash and bank balances with dynamically updating cells.

### Calculations:

Cash Balance: Calculates using the SUMIFS function to sum debits and credits for specific payment methods ("ATM" and "CASH").

Bank Balance: Calculates using SUMIFS to sum debits and credits for all payment methods except "CASH".

Category Table: Calculate using the IF, AND, SUMIFS functions to analyze expenses and income of different categories. Then calculate the total expenses using SUM function excluding Income category.

### Summary Dashboard:

The "Summary Dashboard" sheet provides a high-level overview of financial data.
Users can select a date range, or month, or year to analyze spending.
Category-wise expenses are calculated using the SUMIFS function.

Three charts visualize total monthly expenses and income of a year, total income-total expenses-net savings and category-wise spending.

IncomeUtilization: Percentage of income spent during the selected time frame.

Category-wise Totals: Calculate total expenses by category for any given date range, month, or year.

Dynamic Calendar: View a calendar that updates to show the current date.

Visual Charts:

Category-wise expenditure chart.

Total income, total expense, and net savings chart.

Visualize month-wise credit and debit for a selected year chart.

### Features

Data Entry: User-friendly interface for recording transactions.
Automatic Date Calculations: Auto-populates year and month based on the entered date.

Cash and Bank Balance: Real-time calculation and display of cash and bank balances.

Interactive Charts: Visualize spending trends, category-wise expenses, and overall financial health.

Date Range Selection: Analyze spending within specific date ranges, months, or years.

Percentage of Income Spent: Track the proportion of income used for expenses.

Conditional Formatting: Highlights cash and bank balance cells with different colors based on predefined limits (e.g., green for sufficient balance, red for low balance).

[Mastering Financial Management with FinTrackPro Presentation](https://www.canva.com/design/DAGad-bJgEg/AVd9z5xmScbbRvvC4SjFqQ/view?utm_content=DAGad-bJgEg&utm_campaign=designshare&utm_medium=link2&utm_source=uniquelinks&utlId=h1b174fb19c)

[FinTrackPro: Smart Budgeting Assistant](https://1drv.ms/x/c/206bbe20bed39524/EYhW2Ls3TgpCnRryWJOc61IBEYD6Sz2yeC7PDyuirHoKOw?e=Wlz4H1)