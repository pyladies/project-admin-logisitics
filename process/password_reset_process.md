# How Password Reset is Handled

This documentation is for PyLadies Admin leads (those with administrative access to PyLadies G-Suite account).

## List of Administrators

- Mariatta

- Elaine Wong

- Lorena Mesa

- Debora Azevedo

## How to reset password?

1. A PyLadies organizer fills in the form at <https://forms.gle/NWBwKgoFMjJyJpST8>

2. PyLadies Slack Bot posted the following details to the (private) `#password-reset-requests` channel:

   **Timestamp**: date and time the password reset request was initiated
   
   **From**: The name of the person who submitted the request
   
   **Email**: Personal email address of the person who submitted the request
   
   **Email to send the password to**: The email address where the password should be sent to
   
   **Email that needs reset**: The pyladies.com email address
   
   **Additional info**: Additional info needed to verify the password request
 
3. PyLadies administrator will review and verify the request (manual work)

4. If everything looks good and legitimate, PyLadies administrator will reset
   the password through GSuite admin: (manual work)
   
   - Login to admin.google.com (using their own pyladies.com email address)
   
   - Find the email address that needs reset
   
   - Click on the "Reset Password" link
   
   - Click "Automatically generate password"
   
   - When prompted, choose the "Email the password to the user ", and use the preferred email address from the form
   
   See also: [GSuite Admin Help on Resetting User Password](https://support.google.com/a/answer/33319?hl=en)
 
 5. PyLadies administrator react to the bot's Slack message, by adding the :white_check_mark: emoji
 
 6. PyLadies Slack bot marked the request as completed, and recorded the timestamp and the administrator's
    username to the Google Spreadsheet.
 
 
 
   
   
