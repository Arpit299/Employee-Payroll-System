## Employee Payroll System
This project implements a simple Python-based payroll management system that calculates weekly earnings for different types of employees and visualizes the results using Matplotlib.

## Features
Object-Oriented Design: Utilizes inheritance to manage different employee payment structures.
Multiple Employee Types:
SalaryEmployee: Fixed weekly rate.
HourlyEmployee: Paid based on hours worked and hourly rate.
CommissionEmployee: Fixed weekly salary plus a commission bonus.
Data Visualization: Generates a bar chart to compare payroll distributions across the team.
## Requirements
Python 3.x
Matplotlib
## Usage
Define your employees using the provided classes.
Add them to the employees list.
Run the script to calculate payroll and display the bar chart visualization.
# Example usage
employees = [
    SalaryEmployee(1, 'John Smith', 1500),
    HourlyEmployee(2, 'Jane Doe', 40, 15),
    CommissionEmployee(3, 'Kevin Bacon', 1000, 250)
]
## Visualization
The system produces a clear visual representation of payroll expenses, making it easy to identify compensation trends within the organization.
