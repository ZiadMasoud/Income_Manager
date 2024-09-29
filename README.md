# Home Money Manager

A simple home money management system that allows users to input their monthly salary, manage expenses, and track spending across categories. The system calculates the remaining balance and allows users to generate a PDF report of their monthly expenses.

## Features
- **Enter Monthly Salary**: Input a monthly salary to calculate the remaining balance after expenses.
- **Add Categories**: Add and delete expense categories dynamically.
- **Add Expenses**: Log individual expenses by item name, quantity, cost per unit, category, and store.
- **Expense Summary**: View a summary of all expenses for the current month, including total cost for each item.
- **PDF Report**: Generate a PDF report with all expense details.
- **Clear Data**: Option to clear all data (expenses and salary) from the system.
- **LocalStorage**: All data is stored in the browser's local storage for persistence across sessions.

## How to Use
1. **Monthly Salary**: 
    - Enter your monthly salary in the input field.
    - Click "Save Salary" to store the salary in local storage.
    - The remaining balance will be updated based on your expenses.

2. **Manage Categories**: 
    - Enter a new category in the input field under "Manage Categories" and click "Add Category" to save it.
    - The category will be listed in a table with an option to delete it.
    - Categories are also added to a dropdown menu for easier selection when logging expenses.
  
3. **Add Expenses**:
    - Fill in the fields for the item name, quantity, cost per unit, and store name (optional).
    - Select a category for the item.
    - Click "Add Expense" to add the expense to the system and update the remaining balance.
  
4. **Expense Summary**:
    - View a table with details of all the expenses logged for the current month.
    - The table includes columns for the item name, quantity, total cost, category, store, and an option to delete the expense.
  
5. **PDF Generation**:
    - Click the "Print Expenses as PDF" button to generate a PDF file that includes the monthly expense details.
    - The PDF report can be saved and printed.

6. **Clear All Data**:
    - Click the "Clear All" button to remove all stored data (salary, categories, and expenses).
    - This will reset the form fields and the displayed data.

## Technologies Used
- **HTML**: Provides the structure for the interface, including forms for salary, categories, and expenses.
- **CSS**: Styles the layout and components for a clean and user-friendly interface.
- **JavaScript**: Implements the logic for managing salary, categories, and expenses, storing them in local storage, and generating the PDF report.
- **LocalStorage**: Stores salary, categories, and expenses for persistence.
- **jsPDF**: Library used for generating PDF reports.
- **jsPDF-AutoTable**: Plugin for generating tables in the PDF report.

## Setup Instructions
1. Clone this repository:
    ```bash
    git clone https://github.com/yourusername/home-money-manager.git
    cd home-money-manager
    ```

2. Open the `index.html` file in a browser to start using the application.

## Folder Structure
