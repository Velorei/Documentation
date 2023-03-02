|Summary|Checking the password recovering on the "Forgotten Password" page using the invalid data||
|---|---|---|
|Preconditions|1. The site http://opencart.qatestlab.net/ is opened;<br/>2. The user is registere.|
|#|Step actions|Expected Results|
|1|Click the "My Account" link|The "My Account" page is opened|
|2|Click the "Forgotten Password" link|The "Forgotten Password" page is opened|
|3|Enter the invalid data into the "E-Mail Address" field (only numbers, symbols or empty spaces without "@" and domain)| The entered data is not accepted. The "Forgotten Password" field is highlighted red.The "Please enter a valid email address." notification is dispayed.|
|4|Click the "Continue" button|The "Please enter a valid email address." notification is dispayed. The "Forgotten Password" is highlighted red|
