# Expenditure_calculation


Abstract: The aim of this project is to analyze bank statement data and provide users with an expenditure calculator.
The analysis includes categorizing transactions based on the platform and aggregating expenses by category. The
expenditure calculator allows users to input their income and expenses, and it calculates the savings or deficit. The
project utilizes several Python packages such as pandas, panel, hvplot, and holoviews.
Methods:
1. Data Import and Manipulation:
• The pandas library is used to import the bank statement data from a CSV file.
• The imported data is then manipulated using pandas DataFrame operations to categorize
transactions based on the platform.
2. Last Month's Expenses Analysis:
• The pandas library is used to convert the "Date" column to datetime format.
• The last month's transactions are filtered using the maximum date from the "Date" column.
• Grouping the transactions by category and summing the corresponding amounts provides the total
expenses for each category in the last month.
• The resulting data is sorted in descending order of expenses.
3. Expenditure Calculator:
• The panel library is used to create interactive widgets for the income, recurring expenses, and nonrecurring expenses inputs.
• The calculated difference between income and expenses is displayed using a widget.
• The panel library's parameter watching functionality is utilized to update the difference when input
values change.
4. Visualization:
• The hvplot.pandas and holoviews libraries are used to generate interactive and visually appealing
visualizations.
• A bar chart is created to visualize the last month's expenses by category.
• The select widget allows users to choose a specific category to view its monthly expense trend.
5. Filtering and Summary Table:
• The panel library's DataFrame widget is used to create a table displaying the bank statement data.
• A callback function is defined to update the summary table when the category filter is changed.
• The summary table is filtered based on the selected category using pandas DataFrame operations.
Packages Used:
• pandas: Data manipulation and analysis.
• panel: Interactive widget creation.
• hvplot.pandas: Interactive plotting for pandas dataframes.
• holoviews: Composable visualizations.
• pn.widgets: Interactive widgets for the expenditure calculator.
• pn.template: FastListTemplate for creating the layout of the dashboard.
Conclusion: This project demonstrates the use of Python libraries such as pandas, numpy, matplotlib, panel, hvplot,
and holoviews to analyze bank statement data and provide an interactive expenditure calculator. The project allows
users to categorize transactions, analyze expenses by category, and calculate their savings or deficit based on income
and expenses. The visualizations and widgets enhance the user experience and provide valuable insights into
personal finance management.
