---
url: https://anonymous.4open.science/r/E2EDev/E2EDev_data/E2ESD_Bench_29/
domain: finance
prompt: Develop a personal expense tracker web application.
---

- [ ] When the user loads the application, the system must display the current balance, total income, and total expenses, initialized to $0.00 if no transactions exist.
- [ ] The user must be able to enter a transaction description in the 'Description' input field. The system must accept text input and display it in the transaction history upon adding a transaction.
- [ ] The user must be able to enter a transaction amount in the 'Amount' input field. The system must accept numerical input, where positive values indicate income and negative values indicate expenses.
- [ ] When the user clicks the 'Add Transaction' button, the system must validate that both the description and amount fields are filled with valid data. If not, an alert must be displayed to the user.
- [ ] Upon successful validation, the system must add the transaction to the transaction history, update the balance, income, and expense values, and clear the input fields.
- [ ] The system must display each transaction in the transaction history with the date, description, amount, and an option to remove the transaction.
- [ ] When the user clicks the 'X' button next to a transaction in the transaction history, the system must remove the transaction, update the balance, income, and expense values, and update the local storage.
- [ ] The system must store all transactions in local storage to ensure data persistence across page reloads. Upon loading the application, the system must retrieve and display stored transactions.
