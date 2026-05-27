---
url: https://anonymous.4open.science/r/E2EDev/E2EDev_data/E2ESD_Bench_32/
domain: productivity
prompt: "Develop a task management web application. You can ask questions if you need more information, except for technical questions. At the end of every response, include exactly one line in the form, DEVELOPMENT_COMPLETE: true if application development is complete and no further user input is needed before testing, otherwise DEVELOPMENT_COMPLETE: false."
---

1. Users can add a task by clicking the 'Add Task' button. Context: User enters text in the task input field and clicks the 'Add Task' button. User Action: Clicks 'Add Task' button. System Response: The system adds the task to the task list, clears the input field, and displays the 'Clear All' button.
2. Users can add a task by pressing the 'Enter' key. Context: User enters text in the task input field and presses 'Enter'. User Action: Presses 'Enter' key. System Response: The system adds the task to the list and clears the input field.
3. Each task entry includes a 'Completed' button to toggle its completion status. Context: User views tasks in the list. User Action: Clicks 'Completed' button on a task. System Response: The system toggles the task's visual completion status.
4. Each task entry includes a 'Delete' button to remove the task from the list. Context: User views tasks in the list. User Action: Clicks 'Delete' button on a task. System Response: The system removes the task from the list and checks if the 'Clear All' button should be hidden.
5. Users can clear all tasks by clicking the 'Clear All' button. Context: User wants to remove all tasks from the list. User Action: Clicks 'Clear All' button. System Response: The system clears all tasks from the list and hides the 'Clear All' button.
6. The task input field provides a placeholder text to guide task entry. Context: User views the task input field. User Action: None required. System Response: The system displays 'Enter a new task...' as placeholder text in the input field.
