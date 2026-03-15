# Test Cases – Login Functionality

## TC01 – Login with valid credentials

Precondition:
User must be registered in the system.

Steps:
1. Open the login page
2. Enter a valid email
3. Enter the correct password
4. Click on "Login"

Expected Result:
User should be redirected to the dashboard.

---

## TC02 – Login with incorrect password

Steps:
1. Open login page
2. Enter valid email
3. Enter incorrect password
4. Click "Login"

Expected Result:
System should display the message "Invalid password".

---

## TC03 – Login with empty fields

Steps:
1. Open login page
2. Leave email empty
3. Leave password empty
4. Click login

Expected Result:
System should display validation message indicating required fields.
