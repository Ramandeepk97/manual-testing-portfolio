# SauceDemo Test Cases

## TC001 - Login with Valid Credentials

### Objective
Verify that a user can successfully log in using valid credentials.

### Preconditions
- User is on the SauceDemo login page.

### Test Steps

1. Enter username: standard_user
2. Enter password: secret_sauce
3. Click Login

### Expected Result

User is redirected to the Products page.

### Actual Result

User successfully redirected to Products page.

### Status

PASS


## TC002 - Login with Invalid Password

### Objective

Verify that the system displays an error message when an invalid password is entered.

### Preconditions

- User is on the SauceDemo login page.

### Test Steps

1. Enter username: standard_user
2. Enter password: wrongpassword
3. Click Login

### Expected Result

An error message is displayed and the user remains on the login page.

### Actual Result

Error message displayed:
"Epic sadface: Username and password do not match any user in this service"

User remains on login page.

### Status

PASS



## TC003 - Login with Empty Username

### Objective

Verify that the system displays an error message when the username field is left empty.

### Preconditions

- User is on the SauceDemo login page.

### Test Steps

1. Leave username blank.
2. Enter password: secret_sauce
3. Click Login

### Expected Result

An error message is displayed indicating that the username is required.

### Actual Result

Error message displayed:
"Epic sadface: Username is required"

User remained on the login page.

### Status

Status: PASS
