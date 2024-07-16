# Personal Finance Tracker

## Overview
The Personal Finance Tracker is a Python-based application designed to help you manage and track your financial transactions. It allows you to add, categorize, and analyze your income and expenses, providing a clear overview of your financial health through summary reports and visualizations.

## Features
- **Add Transactions**: Easily add new transactions with details like date, amount, category, and description.
- **View Transactions**: Filter and view transactions within a specified date range.
- **Generate Summaries**: Get a summary of total income, total expenses, and net savings.
- **Data Visualization**: Plot income and expenses over time to visualize financial trends.

## Installation
1. **Clone the repository**:
   ```sh
   git clone https://github.com/MunishMummadi/Finance-Tracker.git
   cd Finance-Tracker
   ```

2. **Install dependencies**:
   ```sh
   pip install -r requirements.txt
   ```

## Usage
1. **Initialize the CSV file**:
   The application will automatically create a CSV file named `finance_data.csv` if it does not exist.

2. **Run the application**:
   ```sh
   python main.py
   ```

3. **Follow the prompts**:
   - **Add a new transaction**: Enter the date, amount, category (Income/Expense), and description.
   - **View transactions and summary**: Enter the start and end dates to view transactions and a summary report.
   - **Plot transactions**: Optionally, generate a plot of income and expenses over the specified date range.

## Modules
- `data_entry.py`: Contains functions for capturing user input for transaction details.
- `main.py`: The main script to run the application.
- `finance_data.csv`: The CSV file where transaction data is stored.
- `requirements.txt`: List of dependencies required to run the application.

## Example
```
1. Add a new transaction
2. View transactions and summary within a date range
3. Exit
Enter your choice (1-3): 1
Enter the date of the transaction (dd-mm-yyyy) or enter for today's date: 15-07-2024
Enter the amount: 100
Enter the category (Income/Expense): Income
Enter the description: Freelance work
Entry added successfully

Enter your choice (1-3): 2
Enter the start date (dd-mm-yyyy): 01-07-2024
Enter the end date (dd-mm-yyyy): 15-07-2024

Transactions from 01-07-2024 to 15-07-2024
date       amount category description
15-07-2024    100   Income Freelance work

Summary:
Total Income: $100.00
Total Expense: $0.00
Net Savings: $100.00
Do you want to see a plot? (y/n): y
```

## Contributing
Contributions are welcome! Please create an issue or submit a pull request with your improvements or suggestions.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact
For any questions or feedback, please contact [moneymindedmunish1@gmail.com].
