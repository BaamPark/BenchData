---
url: https://anonymous.4open.science/r/E2EDev/E2EDev_data/E2ESD_Bench_42/
domain: finance
prompt: "Develop a salary calculator web application. You can ask questions if you need more information, except for technical questions. At the end of every response, include exactly one line in the form, DEVELOPMENT_COMPLETE: true if application development is complete and no further user input is needed before testing, otherwise DEVELOPMENT_COMPLETE: false."
---

1. When the user clicks the 'Calculate Salary' button, the system should retrieve values from all input fields, perform salary calculations, and update the results section with calculated values including hourly salary, daily salary, monthly gross salary, tax deduction, monthly net salary, yearly net salary, overtime earnings, and total earnings.
2. When the user clicks the 'Clear' button, the system should reset all input fields to their default state and clear the results section, setting all displayed values to '$0' or '______'.
3. The system should allow the user to enter text in the 'Job' input field and display this text in the results section under 'Salary Overview for'. If the field is empty, the default value '______' should be displayed.
4. The system should allow the user to enter numeric values in the 'Hours per Day', 'Workdays per Week', 'Gross Monthly Salary', 'Tax Percentage', 'Overtime Hours per Week', and 'Overtime Rate per Hour' input fields. If any field is empty, the default value '0' should be used for calculations.
5. The system should calculate the monthly tax deduction as a percentage of the gross monthly salary and display it as a negative value in the results section.
6. The system should calculate the net monthly salary by subtracting the monthly tax deduction from the gross monthly salary and display it in the results section.
7. The system should calculate the hourly salary based on the net monthly salary, work hours per day, and workdays per week, and display it in the results section.
8. The system should calculate the daily salary by multiplying the hourly salary by the work hours per day and display it in the results section.
9. The system should calculate the yearly net salary by multiplying the net monthly salary by 12 and display it in the results section.
10. The system should calculate the total overtime earnings by multiplying the overtime hours per week by the overtime rate per hour and by 4 (weeks per month), and display it in the results section.
11. The system should calculate the total earnings by adding the yearly net salary and total overtime earnings, and display it in the results section.
