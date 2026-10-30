# Findings 06 - [Exposed Metrics]

## 1. Overview
This challenge is to find the hidden directory.

## 2. Objective
To find a directory containing metrics like page views, unique visitors and other performance indicators.

## 3. Methodology
I use developer tools from the browser to find the metrics.

## 4. Actions
### step 1
I first inspect the source code and go to the search section.
### step 2
I search 'metrics' and find a new directory.
### step 3
I go to the directory and 

## Challenge Completed

## 5. Security Impact and Severity
Leaving hidden directory in public source code can lead to severe data leakage and user credential loss.

## 6. Recommended Mitigation
Don't leave sensitive information in publicly available pages.
Store them in secure database.

## 7. Limitaion
Can only report the vulnerability, cannot fix it.

## 8. Lessons learned
Improve my source code inspection skill
