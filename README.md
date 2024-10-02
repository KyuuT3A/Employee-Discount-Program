# Employee-Discount-Program
The Employee Discount Program calculates discounts for retail employees based on years of service and employment status. It applies discounts up to a $200 yearly cap and processes multiple employee transactions in real time. The program validates inputs and provides a final summary of total purchases before and after discounts for all employees.
# Features
- Calculates discounts based on employee type (manager/hourly) and years of service.
- Applies a discount cap of $200 per year, ensuring no further discounts are applied once reached.
- Processes multiple employee transactions in a single session.
- Provides detailed outputs, including discount percentage, purchase totals before and after discounts, and the year-to-date (YTD) discount amount.
- Displays a final summary for all employees, showing the total purchases before and after discounts.
- Validate input to ensure accurate data entry (e.g., ensuring years worked and purchase amounts are numeric and non-negative).
# Usage
1. Input Required:
- Number of years employed.
- Total amount of previous purchases (YTD) before the discount.
- Employee status (E for hourly employee, M for manager).
- Total purchase for the current transaction.
2. Discount Calculation:
- Discounts are applied based on a tiered system, with managers receiving higher discounts than hourly employees for the same years of service.
- No further discounts are applied if an employee has already received $200 in discounts for the year.
3. Process:
- The program processes multiple employees in a session, allowing you to calculate discounts for each employee until no further entries are required.
- A final summary displays the total purchases before and after discounts for all employees processed.
# Output
For each employee, the program provides:
- Discount percentage based on employment status and years of service.
- YTD discount in dollars.
- Purchase total before the discount.
- Purchase total after the discount.
# Summary Output:
- Total purchases before and after discounts for all employees.
