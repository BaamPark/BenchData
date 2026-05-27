---
url: https://anonymous.4open.science/r/E2EDev/E2EDev_data/E2ESD_Bench_19/
domain: productivity
prompt: "Develop a todo list web application. You can ask questions if you need more information, except for technical questions. At the end of every response, include exactly one line in the form, TASK_DONE: true if you believe the application is complete and no further user input is needed, otherwise TASK_DONE: false."
---

1. When the user types a task into the input field and submits the form, the system should add the task to the list of todos displayed on the page.
2. When the user submits the form without entering any text, the system should not add an empty task to the list.
3. When the user clicks on a todo item in the list, the system should toggle the 'completed' status of the item, visually indicating its completion.
4. When the user right-clicks on a todo item in the list, the system should remove the item from the list without showing an extra menu.
5. When the page is loaded, the system should retrieve and display the previously saved list of todos, maintaining their completion status.
6. When a todo item is added, completed, or deleted, the system should preserve the current todo list so it remains available after the page is reopened.
