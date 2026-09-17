(This project was created to showcase my working knowledge with EXCEL. It covers the most common formulas, functions, and methods use in real-world excel related task.)

Payroll & Workforce Analytics System

An Excel payroll workbook that tracks employees, attendance, pay, deductions, taxes, payslips, and company results in one place.
About This Project.

This workbook was built to show how a small company could manage payroll in Excel. The main figures are calculated automatically, and the reports update from the same payroll data.

Role: Excel setup, calculations, dashboard design
Tools: Microsoft Excel, PivotTables, Charts, VBA
Scope: Fictional Philippine payroll cycle, 20 employees

Project Goal

- Organize employee, attendance, leave, deduction, and rate information.
- Calculate basic pay, overtime, holiday pay, contributions, tax, and take-home pay.
- Create an automated Pay-slip that shows relevant information per employee selected.
- Create a Dashboard that shows payroll and employee results with tables, charts, and filters.
- Make the Dashboard Interactive.

  
What I Built

The workbook moves from employee and attendance records to payroll, payslips, and dashboard reports.
A separate Rates sheet keeps contribution rules, pay multipliers, and tax brackets in one easy-to-update place.

Tools and techniques used: XLOOKUP, SUMIFS, COUNTIFS, PivotTables, Charts, Filters, VBA.

Dashboard Overview : 

The dashboard shows the main payroll numbers, department totals, deductions, payroll status, pay components, and highest-paid employees in one view.
Quick numbers:
20 fictional employees
12 connected worksheets
11 summary tables
70% sample payroll completion
A short screen recording is included in the project files showing how the department slicer and macro button work.
Instant Employee Payslip
The Payslip sheet pulls one employee's records into a clear semi-monthly statement. A screenshot and recording (included in the project files) show how the selected employee's pay details update in the workbook.
Example payslip:
Employee ID
EMP007
Employee Name
Daniel Torres
Department
Sales
Payroll Status
Approved
Basic Pay
₱13,000.00
Overtime Pay
₱156.25
Holiday Pay
₱0.00
Gross Pay
₱13,156.25
SSS
₱650.00
PhilHealth
₱325.00
Pag-IBIG
₱100.00
Withholding Tax
₱249.64
Total Deductions
₱1,075.00
Net Pay
₱11,831.61

How the Workbook Is Organized?

The workbook is split into four parts, each with a clear job:
Setup (Reference) — Rates, holidays, deduction types, and notes explain the rules used by the workbook.
Daily Records (Input) — Employee details, attendance, leave, and deductions are entered here.
Payroll (Calculation) — The workbook calculates earnings, contributions, tax, deductions, and take-home pay.
Results (Reporting) — Payslips, tables, charts, filters, and dashboard cards present the results.

Data flow:

Employee details → Attendance & Leave → Payroll period → Earnings → Contributions → Deductions → Take-home pay → Payslip → Dashboard

Important Features:

1. Employee details stay consistent — The Employees sheet is the main list. Other sheets use the Employee ID to bring in the right name, department, and pay details.
2. Dates control the payroll run — Attendance and deductions are counted using the selected payroll start and end dates, so the next pay period can be prepared quickly.
3. Pay rules are in one place — Contribution rates, overtime pay, holiday pay, and tax brackets are kept on the Rates sheet instead of being spread across many formulas.
4. Dashboard numbers stay linked — The dashboard reads from the summary tables, so the cards and charts stay aligned when a department filter is used.
5. One-click filter reset — A small VBA macro clears the Department filter and returns the dashboard to its full-company view.
6. Clear project limits — The records are fictional and the rates are examples. This is a portfolio project, not a production payroll system.

Limitations and Recommendations:

The workbook is a working demo, so a few parts would need more work before real company use.
Current limitations:

Limited holiday coverage — The sample covers only a small number of days for demonstration. Holiday pay would be more reliable with a full-year holiday calendar and more attendance records.
Example rates — Contribution rates and tax brackets are examples based on known Philippine rules. They should be checked against current official rates before use.
Small sample data — The employee and attendance records are fictional and limited in size. More records and edge cases would help test the workbook further.
Recommended next steps:
Add more payroll cases — Future versions could include night differential, undertime, unpaid leave, multiple payroll periods, bonuses, and more holiday types.
Add stronger checks — Input warnings, approval steps, error checks, and locked formula cells would make the workbook safer to share.
Prepare for real use — A production version would need updated rules, access controls, data backups, and a formal review by payroll or HR staff.

Project Notes :

Dataset: Self-generated and fully fictional — 20 employees and 100+ attendance records. Employee names, government IDs, bank details, attendance logs, and contact information are portfolio-only examples. Payroll rates and tax brackets are examples based on publicly known Philippine rules and have not been validated for production use.
This workbook was built as a self-directed exercise to practice Excel, payroll reporting, dashboard design, and simple automation skills relevant to payroll and HR analytics roles.

ALL RIGHTS RESERVE 2026 Project 02 · Payroll & Workforce Analytics System · Excel-based portfolio case study · Sherjames Compania
