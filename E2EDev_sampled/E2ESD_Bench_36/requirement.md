---
url: https://anonymous.4open.science/r/E2EDev/E2EDev_data/E2ESD_Bench_36/
domain: productivity
prompt: "Develop a text counter web application. You can ask questions if you need more information, except for technical questions. At the end of every response, include exactly one line in the form, DEVELOPMENT_COMPLETE: true if application development is complete and no further user input is needed before testing, otherwise DEVELOPMENT_COMPLETE: false."
---

1. When the user enters text into the text area, the system should allow the user to input any text without immediate restrictions.
2. When the user clicks the 'Count' button, the system should calculate and display the number of words, characters, and paragraphs in the text input.
3. When the user clicks the 'Clear' button, the system should clear the text input and reset the word, character, and paragraph counts to zero.
4. When the user enters a number in the 'Character Limit' input field, the system should monitor the text input and change the character count display to red if the limit is exceeded.
5. When the user clicks the 'Highlight' button, the system should visually highlight all occurrences of the specified word in the text input.
6. When the page loads, the system should retrieve and display the last saved text input and counts.
7. After any change in the text input or counts, the system should preserve the current state so the user's data remains available across sessions.
