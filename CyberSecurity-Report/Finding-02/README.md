# Finding 02 - [DOM-XSS]

## 1. Overview
This challenge is about performing basic Cross Site Scripting(XSS) on Juice Shop website.

## 2. Objective
To perform and complete the challenge named 'DOM-XSS' by using basic XSS script.

## 3. Methodology
I used google and GTFOBin.com to find basic XSS syntax and write it in user input-box of the website.

## 4. Actions
### step 1
I go to the GTFOBin.com to find the syntax of the XSS script.
(You can use other site ofcourse)

### step 2
I then go to the Juice-Shop site and add this script
script : (sorry GitHub doesn't allow any injection type script)
And I get the notification window.

## Challenge Completed

## 5. Security Impact and Severity
In real website with valuable user information, this kind of attack is dangerous.
This challenge is just the top of the iceberg of what XSS attack can do.

## 6. Recommended Mitigation
Developers should handle user input carefully and every user input should be labelled as string or string like variable.

## 7. Limitation
I cannot edit the source code to fix this vulnerability , this document is just for security testing.

## 8. Lessons Learned
Basic syntax of XSS attack
