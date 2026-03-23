### TestCaseId: TC001 ###
**Title: Login with correct username and password** 
**Steps:** 
 -1.Open the browser and navigate to the web page
 -2.Navigate to the login page
 -3.Enter valid username: "standart_user"
 -4.Enter valid password: "secret_sauce"
 -5.Click login button

* Expected result: Successful login, the user is directed to the profile page *
* Actual result: Successful login, the browser directed to the profile and main page *
* Status: Passed *

### TestCaseId: TC002 ###
* Title: Login with correct username and wrong password *
* Steps: *
 1.Open the browser and navigate to the web page
 2.Navigate to the login page
 3.Enter valid username
 4.Enter wrong password
 5.Click login button
* Expected result: Unsuccessful login, error message "Incorrect username or password" should be displayed
* Actual result: "Incorrect username or password" message displayed 
* Status: Passed * 

### TestCaseId: TC003 ###
* Title: Login with blank username and password
* Steps: *
 1.Open the web browser and navigate to the web page
 2. Navigate to the login page
 3. Leave the password and username spaces blank
 4. Click login button
* Expected result: "Username is required" and "Password is required" messages should appear
* Actual result: "Incorrect username or password" message appeared 
* Status: Failed *


 Browser: Microsoft Edge
 Device: Laptop
* Preconditions: 
 User is on login page


