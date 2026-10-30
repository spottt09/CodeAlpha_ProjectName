# Finding 01 - [Score Board]

## 1. Overview
The security issue for this challenge is adding sensitive or private directory in main.js file.

## 2. Objective
The objective of the challenge is to find secret web directory in website.

## 3. Methodology
I use developer tools in browser to find the directory.

## 4. Actions
### step 1
I fist inspect the source code by clicking F12.
### step 2
Since, I have to find score board directory, I go to debugger => search .
And search 'score' in main.js.
### step 3
In line 4347, I find a code about the directory.
and Go to there to complete the first challenge.

## Challenge Completed

## 5. Security Impact and Severity
In real-world systems, attackers can find sensitive information and credentials of the user accounts.

## 6. Recommended Mitigation
The developer should not leave source code that contain private information to public.

## 7. Limitation
I cannot fix the source code since it is only built for security testing.
This challenge is done in safe and authorized lab where security testing is allowed.
Testing unauthorized systems can be a serious crime.

## 8. Lessons Learned
The challenge taught me to inspect source code when testing web application.
