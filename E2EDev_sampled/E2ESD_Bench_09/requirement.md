---
url: https://anonymous.4open.science/r/E2EDev/E2EDev_data/E2ESD_Bench_09/
domain: productivity
prompt: "Develop a schedule management web application. You can ask questions if you need more information, except for technical questions. At the end of every response, include exactly one line in the form, TASK_DONE: true if you believe the application is complete and no further user input is needed, otherwise TASK_DONE: false."
---

1. When the user fills out the 'Subject', 'Date', and 'Time' fields in the schedule form and clicks the 'Add Schedule' button, the system must add a new schedule item to the schedule list displaying the subject, date, and time.
2. When the user fills out the 'Task' and 'Deadline' fields in the task form and clicks the 'Add Task' button, the system must add a new task item to the task list displaying the task and deadline.
3. After a schedule is added, the system must reset the schedule form fields to be empty, allowing the user to enter new data.
4. After a task is added, the system must reset the task form fields to be empty, allowing the user to enter new data.
5. The system must prevent the default form submission behavior to ensure that the page does not refresh when the user submits either the schedule or task form.
