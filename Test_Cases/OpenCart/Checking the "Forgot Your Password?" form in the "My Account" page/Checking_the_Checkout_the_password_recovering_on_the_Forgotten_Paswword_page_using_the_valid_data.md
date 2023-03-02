|Summary|Checking the password recovering on the "Forgotten Password" page using the valid data||
|---|---|---|
|Precondition |1. The site http://opencart.qatestlab.net/ is opened;<br/>2. The user is registered.|
|#|Steps actions|Expected Results|
|1|Click the "My Account" link|The "My Account" page is opened|
|2|Click the "Forgotten Password" link|The "Forgotten Password" page is opened|
|3|Enter the existing e-mail address in the "E-Mail Adress" field|The entered e-mail is accepted. The field is highlighted green frame|
|4|Click the "Continue" button|The "An email with a confirmation link has been sent your email address." is displayed|
|5|Check the existing e-mail|The "To change your password, follow the following link" message is displayed|
|6|Click the "To change your password, follow the following link" link|The "Change your Password" page is opened|
|7|Enter valid password in the "Change your Password" field|The entered data is accepted. The "Password" field is highlighted green. The "Congratulations on successfully changing your password" notification is displayed. The "My Account" page is opened|
