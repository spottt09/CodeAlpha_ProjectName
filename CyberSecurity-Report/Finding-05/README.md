# Findings 05 - [Confidential Document]

## 1. Overview
This challenge is about finding the information in web page.

## 2. Objective
To find a file containing confidential information.

## 3. Methodology
I inspect the website manually to find a directory and requiring file.

## 4. Actions

### step 1
I inspect the website manually this time.
### step 2
I found a link for new directory. The new directory is '/ftp/legal.md'.
### step 3
I change the directory to '/ftp' and manually check every file directory.
### step 4
In 'acquisition.md', I can confirm that this is the confidential I'm looking for.

## 5.Security Impact and Severity
Leaving sensitive information to public can bring danger of attacks to server and its database.

## 6. Recommended Mitigation
Developers should not expose sensitive information to public and should maintain them in secure environment.

## 7. Limitation
Since this document is about testing, I cannot fix this vulnerability.

## 8. Lessons Learned
This challenge improves my manual inspecting on website page.
