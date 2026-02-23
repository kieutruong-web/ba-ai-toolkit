# Feature: Login with Email

## Business Goal

Allow registered users to securely access their accounts using email and password.

---

## User Story

As a registered user,  
I want to log in using my email and password,  
so that I can access my personal account.

---

## Acceptance Criteria

### Scenario 1: Successful Login
Given the user is on the login page  
When the user enters valid email and password  
Then the system logs the user in and redirects to the dashboard  

### Scenario 2: Invalid Password
Given the user is on the login page  
When the user enters an incorrect password  
Then the system displays an error message  

### Scenario 3: Empty Fields
Given the user is on the login page  
When the user submits without entering credentials  
Then validation messages are shown  

---

## Test Cases

| ID   | Steps | Expected Result |
|------|------|----------------|
| TC01 | Enter valid email & password | User is logged in |
| TC02 | Enter wrong password | Error message displayed |
| TC03 | Submit empty form | Validation error shown |
