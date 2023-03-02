|Summary|Checking the "Checkout" form using the invalid data||
|---|---|---|
|Preconditions|1. The site http: //opencart.qatestlab.net/ is opened;<br/>2. The "Dry Cat Food" is added to the "Cart"|
|#|Step actions|Expected Results|
|1|Click the "Cart" button|The "Cart" drop-down list is opended|
|2|Click the "Checkout" button|The "Checkout" page is opened|
|3|Mark the "Guest Checkout" checkbox in the "New Customer" section|The "Guest Checkout" checkbox in the "New Customer" section is marked|
|4|Click the "Continue" button in the "New Customer" section|The "Step 2: Billing Details" section is opened in the "Checkout" page|
|5|Enter the valid data into the "First Name", "Last Name", "E-Mail", "Telephone" fields|The entered data is accepted. The "First Name", "Last Name", "E-Mail", "Telephone" fields are highlighted green|
|6|Enter the invalid data into the "Your Address", "Address 1", "City", "Post Code", "Country", "Region / State" (only numbers, symbols or empty spaces etc.) fields|The entered data is not accepted. The "Your Address", "Address 1", "City", "Post Code", "Country", "Region / State"  fields are highlighted red|
|7|Mark the My delivery and billing addresses are the same." checkbox|The "My delivery and billing addresses are the same." checkbox is marked|
|8|Click the "Continue" button|The "Warning: No match for "Your Address", "Address 1", "City', "Post Code","Country", "Region / State" fields are highlighted red. The "Please enter a valid data." Notification is dispayed|
