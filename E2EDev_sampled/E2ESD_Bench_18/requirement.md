---
url: https://anonymous.4open.science/r/E2EDev/E2EDev_data/E2ESD_Bench_18/
domain: education
prompt: "Develop a class timetable management web application. You can ask questions if you need more information, except for technical questions. At the end of every response, include exactly one line in the form, TASK_DONE: true if you believe the application is complete and no further user input is needed, otherwise TASK_DONE: false."
---

1. When the user enters a subject name in the 'Subject' input field and clicks the 'Add to Timetable' button, the system must validate that the field is not empty and display an alert if it is left blank.
2. When the user selects a start time using the 'Start Time' input field and clicks the 'Add to Timetable' button, the system must validate that the field is not empty and display an alert if it is left blank.
3. When the user selects an end time using the 'End Time' input field and clicks the 'Add to Timetable' button, the system must validate that the field is not empty and display an alert if it is left blank.
4. When the user selects one or more days using the checkboxes in the 'Days' group and clicks the 'Add to Timetable' button, the system must validate that at least one checkbox is selected and display an alert if none are selected.
5. When the user clicks the 'Add to Timetable' button after filling all required fields, the system must dynamically add a new row to the timetable table with the specified time range and subject name under the selected days.
6. If a row with the same time range already exists in the timetable table, the system must update the cells corresponding to the selected days with the new subject name instead of creating a new row.
7. When the user adds a new row to the timetable table, the system must insert the row in chronological order based on the start time.
8. When the user clicks the 'Add to Timetable' button, the system must reset the form fields to their default state after successfully adding or updating a timetable entry.
9. The system must display an empty timetable table with headers for 'Time', 'Monday', 'Tuesday', 'Wednesday', 'Thursday', 'Friday', and 'Saturday' when the page loads.
10. When the user selects multiple days using the checkboxes and clicks the 'Add to Timetable' button, the system must populate the corresponding columns in the timetable table with the subject name for the specified time range.
11. The system must ensure that the 'Start Time' and 'End Time' fields accept valid time inputs only.
12. The system must ensure that the 'Subject' input field accepts text input only.
13. The system must allow users to select multiple days simultaneously using checkboxes in the 'Days' group.
14. The system must dynamically update the timetable table without requiring a page reload when the user adds or updates a timetable entry.
15. The system must display an alert message if the user attempts to submit the form without filling all required fields or selecting at least one day.
