|Summary|Checking the authorization on the website using the invalid data||
|---|---|---|
|Preconditions|1. The http://opencart.qatestlab.net/ is opened;<br/>2. The user is registered.|
|1|Click the "My Account" link|The "My Account" page is opened|
|2|Enter the invalid data into the "E-Mail Address" field (only numbers, symbols or empty spaces without "@" and domain)|The entered data is not accepted. The field is highlighted red. The  "Please enter a valid email address." Notification is dispayed under the "E-Mail Address" field|
|3|Enter the invalid data into the "Password" field (length of 5 characters or less, leave the field empty)|The entered data is not accepted. The field is highlighted red. The "Please enter at least 6 characters." Notification is dispayed under the "Password" field|
|4|Click the "Login" button|The "Warning: No match for E-Mail Address and/or Password."
Notification is displayed. The "E-Mail Address" and "Password" fields are highlighted red|
