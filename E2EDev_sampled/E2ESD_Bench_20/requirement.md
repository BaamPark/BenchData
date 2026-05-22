---
url: https://anonymous.4open.science/r/E2EDev/E2EDev_data/E2ESD_Bench_20/
domain: productivity
prompt: Develop a car registration management web application.
---

1. When the user clicks on the 'Register Car' tab button, the system should display the 'Register a Car' form and hide the 'View All Registrations' table.
2. When the user clicks on the 'View All Registrations' tab button, the system should display the 'View All Registrations' table and hide the 'Register a Car' form.
3. When the user fills out the 'Owner's Name', 'Car Model', 'License Number', and 'Registration Date' fields in the 'Register a Car' form and clicks the 'Save Registration' button, the system should validate that all fields are filled. If any field is empty, the system should display an alert prompting the user to fill out all fields.
4. When the user successfully submits the 'Register a Car' form, the system should save the registration data (Owner's Name, Car Model, License Number, Registration Date) to local storage and reset the form fields.
5. When the user navigates to the 'View All Registrations' tab, the system should dynamically populate the table with all saved registrations from local storage.
6. When the user clicks the 'Edit' button for a specific registration in the table, the system should populate the 'Register a Car' form with the selected registration's data and switch to the 'Register Car' tab.
7. When the user updates the data in the 'Register a Car' form after clicking the 'Edit' button and submits the form, the system should update the corresponding registration in local storage and refresh the table in the 'View All Registrations' tab.
8. When the user clicks the 'Delete' button for a specific registration in the table, the system should remove the corresponding registration from local storage and refresh the table to reflect the change.
9. When the user reloads the page, the system should automatically load all saved registrations from local storage and display them in the 'View All Registrations' table.
10. When the user clicks on the 'Save Registration' button without filling out all required fields, the system should display an alert message indicating that all fields are mandatory.
11. When the user switches between tabs, the system should visually indicate the active tab by applying the 'active' class to the selected tab button and its corresponding content section.
