### This is a Selenium test case application for conducting analysis tests. The test cases are as follows:


- [ ] When username and password fields are left empty, the warning message "Epic sadface: Username is required" should be displayed.
- [ ] When only the password field is left empty, the warning message "Epic sadface: Password is required" should be displayed.
- [ ] When the username "locked_out_user" and the password "secret_sauce" are entered, the message "Epic sadface: Sorry, this user has been locked out." should be displayed.
- [ ] When both the username and password fields are left empty, a red "X" icon should appear next to these two inputs. When the close button of the warning message that appears below is clicked, these "X" icons should disappear. (Implement in a single test case)
- [ ] When the username "standard_user" and password "secret_sauce" are entered, the user should be directed to the "/inventory.html" page.
- [ ] After logging in, the number of products displayed to the user should be "6".