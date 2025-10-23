# Natas level 3

# Objective
Find the password on the webpage


# Solution Steps
1. Log into Natas website
    http://natas3.natas.labs.overthewire.org/
2. Page states "There is nothing on this page", inspected page
    ctrl + shift + i
3. Checked html of page, found clue stating that not even google can find this
4. Checked robots.txt page 
    http://natas3.natas.labs.overthewire.org/robots.txt
5. Found disallow rule for /s3cr3t/ page, navigated to page
    http://natas3.natas.labs.overthewire.org/s3cr3t/
6. Found users.txt link, checked webpage
    http://natas3.natas.labs.overthewire.org/users.txt/
7. Extracted password from webpage
    password: QryZXc2e0zahULdHrtHxzyYkj59kUxLQ

# Learned
How to look at the robots.txt page to see what pages are hidden