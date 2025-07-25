# PHP

PHP / Basic Code does the following:
1) Accepts user input via an HTML form.
2) Processes input securely using htmlspecialchars to prevent XSS.
3) Outputs a dynamic greeting based on the submitted name.

PHP / Script with SQL (Handles User Submission) fulfills and has the capability to do the following:
1. Allow HTML Form Collect name and email from the user.
2. Receive the submitted form data using $_POST as: submit.php
3. Create DB Connection	using MySQL credentials.
4. Create inserts the user's name and email into the users table as: SQL Query.
5. Uses prepared statements ($stmt->bind_param()) to help prevent SQL injection, which validate and keep inputs clean.
6. Shows a success or error message as output.
