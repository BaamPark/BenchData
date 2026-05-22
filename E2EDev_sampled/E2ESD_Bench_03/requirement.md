---
url: https://anonymous.4open.science/r/E2EDev/E2EDev_data/E2ESD_Bench_03/
domain: e-commerce
prompt: Develop movie reservation web application.
---

1. When the user selects a movie from the dropdown menu, the system updates the ticket price and stores the selected movie index and price in local storage.
2. Upon clicking an available seat, the system toggles the seat's selection status, updates the count of selected seats, calculates the total price, and stores the indices of selected seats in local storage.
3. When the page loads, the system retrieves and applies previously selected seats and movie selection from local storage, updating the UI accordingly.
4. The system displays the number of selected seats and the total price dynamically as the user interacts with seat selections and movie choices.
5. The user can view the status of seats (available, selected, occupied) visually, with occupied seats being non-interactive.
