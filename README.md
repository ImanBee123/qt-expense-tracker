# Qt Expense Tracker

## 1. Project Overview
The Expense Tracker is a desktop application developed using Qt and C++. It is designed to help users record, organise and monitor their personal expenses. Users can manage their expenses, filter expenses by category, calculate their total spending and view monthly spending summaries. The application aims to help users understand their spending habits and manage their money more effectively.

## 2. Problem Statement
Managing personal expenses can be difficult when expenses are not recorded or organised regularly. Manually calculating daily and monthly expenses can also be time-consuming and make it harder to understand where money is being spent.

Without a clear overview of their spending, users may struggle to prioritise expenses, control unnecessary spending and set aside money for savings. The Expense Tracker addresses these problems by providing a centralised way to record expenses and automatically calculate spending totals.

## 3. Project Objectives
The objectives of this project are to:

1. Develop a functional desktop application that allows users to record and manage personal expenses.
2. Provide spending summaries and visualisations to help users understand their spending habits.
3. Apply fundamental C++ and Qt concepts through the development of a practical application.
4. Gain practical experience with the software development lifecycle, including requirement documentation, design documentation, implementation, testing and deployment.

## 4. Project Scope and Features
This project focuses on developing a desktop application for managing personal expenses. The application will allow users to record transactions, organise expenses into predefined categories and review their spending.

### 4.1 Essential Features
The following features are considered essential to the application:

- **Add Expense:** Allow users to record a new expense by entering its amount, date, category and description.
- **Edit Expense:** Allows users to modify the details of an existing expense.
- **Delete Expense:** Allows users to remove an existing expense.
- **Filter by Category:** Allows users to view expenses belonging to a selected category.
- **Calculate Total Spending:** Automatically calculate the total amount spent based on recorded expenses.
- **View Monthly Spending:** Automatically display a summary of expenses for the current month.
- **Category Breakdown:** Display the distribution of expenses across different categories using a pie or doughnut chart.
- **Local Data Storage:** Save expense records locally so that they remain available when the application is closed and reopened.

### 4.2 Additional Features
The following features may be considered, but are of lower priority due to time constraint:

- **Monthly Spending Comparison:** Display a chart comparing total spending across different months.
- **Budget Tracking:** Allows users to set a monthly spending limit and monitor their spending against it.

### 4.3 Out of Scope
The following features are excluded from the current project scope:

- **Cloud Synchronisation:** Synchronising expense records across multiple devices.
- **Multiple Accounts/Profiles:** Supporting multiple users with separate accounts and expense records.
- **Credit/Debit Card Integration:** Connecting directly to bank accounts or payment cards to retrieve transactions automatically.

## 5. Requirements
This section describes the functions the application must provide and the expected qualities of the application.

### 5.1 Functional Requirements
The application shall:

1. Allow users to add expenses by entering the amount, date, category and description.
2. Allow users to edit existing expense records.
3. Allow users to delete existing expense records.
4. Provide predefined expense categories for users to select.
5. Allow users to filter expense records by category.
6. Calculate and display total spending based on recorded expenses.
7. Automatically display a spending summary for the current month.
8. Display the distribution of expenses across categories using a pie or doughnut chart.
9. Display expense records in an organised format.
10. Save expense records locally and retrieve them when the application is reopened.

### 5.2 Non-Functional Requirements
The application should:

1. **Usability:** Provide a simple and easy-to-understand interface.
2. **Performance:** Perform common operations, such as adding expenses and calculating totals, without noticeable delays during normal use.
3. **Reliability:** Calculate spending totals accurately based on recorded expense data.
4. **Maintainability:** Use an organised code structure that makes the application easier to understand, modify and maintain.

## 6. Data Visualisation and Presentation
The application will present expense records and spending summaries in a way that makes financial information easy to understand.

The proposed methods of displaying data include:

- **Expense Table:** Display individual expense records, including their amount, date, category and description.
- **Category Breakdown:** Use a pie or doughnut chart to show how spending is distributed across different categories. This is a priority visualisation.
- **Current Monthly Spending Summary:** Display the total expenses for the current month automatically.
- **Monthly Spending Trend:** Use a bar or line chart to compare spending across different months. This is an additional feature.

## 7. Storyboard and Wireframes
This section illustrates the proposed application interface and how users will interact with its main features.

The storyboard and wireframes will cover the following user interactions:

1. Opening the application and viewing the main dashboard.
2. Adding a new expense.
3. Editing an existing expense.
4. Deleting an existing expense.
5. Filtering expenses by category.
6. Viewing total and monthly spending summaries.
7. Viewing the category breakdown chart.

The diagrams and wireframes will represent the proposed application interface before implementation.