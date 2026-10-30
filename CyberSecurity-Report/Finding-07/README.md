# Findings 07 - [Login Admin]

## 1. Overview
This challenge is about SQL injection to access the admin account.

## 2. Objective
The objective of this challenge is to introduce SQL injection to access information.

## 3. Methodology and Actions
I use basic SQL injection attack to username box, and I can add the password whatever I want.
I add 
username : admin' OR 1=1;==
password : 12345678910

## Challenge Completed

## 4. Security Impact and Severity
This is like the same principle as XSS attack. They are injection attacks to user input box like search bar or login form.

## 5. Recommended Mitigation
The same as XSS, developers should focus more on the user input and inputs must be considered as strings to prevent this kinds of attack.

## 6. Limitation
I can only report the vulnerability, cannot fix the source code.

## 7. Lessons Learned
This challenge taught me that some websites without proper input handling can be exploited and should be fixed as soon as possible.
