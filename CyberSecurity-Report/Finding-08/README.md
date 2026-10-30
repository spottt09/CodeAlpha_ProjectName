# Findings 08 - [Fivestar Feedback]

## 1. Overview
This challenge is about using admin privilege to edit contents.

## 2. Objective
In this challenge, admin privilege is used to edit the user feedbacks.

## 3.Methodology and Actions
### step 1
I first login to admin account by SQL injection.
### step 2
I use google to find about the location of the database management and content management.
### step 3
I go to the '/administration' directory and I delete the a feedback with 5 stars review.

## Challenge Completed

## 4. Security Impact and Severity
The root vulnerability of this challenge is not handling the inputs so the attackers can get access to authorized accounts and edit the web contents.

## 5. Recommended Mitigation
One of the most common mitigation is to handle user input carefully and only consider them as strings.
Another recommendation I think of is a requirement to edit from all authorized admins.

## 6. Limitation
I can only report the document, cannot fix the vulnerability.

## 7. Lessons Learned
- Most sensitive information and database management interfaces are stored in administration directory
