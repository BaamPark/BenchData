---
url: https://anonymous.4open.science/r/E2EDev/E2EDev_data/E2ESD_Bench_40/
domain: security
prompt: Develop a password generator web application.
---

- When the user clicks the 'Generate Password' button, the system should generate a password based on the selected criteria (length, inclusion of uppercase, lowercase, numbers, symbols) and display it in the result area.
- When the user clicks the 'Copy to Clipboard' button, the system should copy the generated password from the result area to the clipboard and display a notification stating 'Password copied to clipboard!' for 3 seconds.
- The user should be able to specify the password length using the number input field, with a minimum value of 4 and a maximum value of 20.
- The user should be able to toggle the inclusion of uppercase letters in the password by checking or unchecking the 'Include uppercase letters' checkbox.
- The user should be able to toggle the inclusion of lowercase letters in the password by checking or unchecking the 'Include lowercase letters' checkbox.
- The user should be able to toggle the inclusion of numbers in the password by checking or unchecking the 'Include numbers' checkbox.
- The user should be able to toggle the inclusion of symbols in the password by checking or unchecking the 'Include symbols' checkbox.
- If no character types are selected, the system should not generate a password and should return an empty result.
