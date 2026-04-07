---
url: https://anonymous.4open.science/r/E2EDev/E2EDev_data/E2ESD_Bench_18/
domain: education
prompt: Develop a class timetable management web application.
---

- When the user enters a subject name in the 'Subject' input field and clicks the 'Add to Timetable' button, the system must validate that the field is not empty and display an alert if it is left blank.
- When the user selects a start time using the 'Start Time' input field and clicks the 'Add to Timetable' button, the system must validate that the field is not empty and display an alert if it is left blank.
- When the user selects an end time using the 'End Time' input field and clicks the 'Add to Timetable' button, the system must validate that the field is not empty and display an alert if it is left blank.
- When the user selects one or more days using the checkboxes in the 'Days' group and clicks the 'Add to Timetable' button, the system must validate that at least one checkbox is selected and display an alert if none are selected.
- When the user clicks the 'Add to Timetable' button after filling all required fields, the system must dynamically add a new row to the timetable table with the specified time range and subject name under the selected days.
- If a row with the same time range already exists in the timetable table, the system must update the cells corresponding to the selected days with the new subject name instead of creating a new row.
- When the user adds a new row to the timetable table, the system must insert the row in chronological order based on the start time.
- When the user clicks the 'Add to Timetable' button, the system must reset the form fields to their default state after successfully adding or updating a timetable entry.
- The system must display an empty timetable table with headers for 'Time', 'Monday', 'Tuesday', 'Wednesday', 'Thursday', 'Friday', and 'Saturday' when the page loads.
- When the user selects multiple days using the checkboxes and clicks the 'Add to Timetable' button, the system must populate the corresponding columns in the timetable table with the subject name for the specified time range.
- The system must ensure that the 'Start Time' and 'End Time' fields accept valid time inputs only, using the HTML `<input type='time'>` element.
- The system must ensure that the 'Subject' input field accepts text input only, using the HTML `<input type='text'>` element.
- The system must allow users to select multiple days simultaneously using checkboxes in the 'Days' group.
- The system must dynamically update the timetable table without requiring a page reload when the user adds or updates a timetable entry.
- The system must display an alert message if the user attempts to submit the form without filling all required fields or selecting at least one day.
