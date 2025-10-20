# Natas level 2

# Objective
Find the password for the next level

# Solution Steps
1. Log into Natas website
    http://natas2.natas.labs.overthewire.org/
2. Inspected elements of page
    ctrl + shift + i
3. Looked at html body of page, found very small image with source from /files/pixel.png. Checked page of image 
    http://natas2.natas.labs.overthewire.org/file/pixel.png
4. Found nothing, decided to go back one page
    http://natas2.natas.labs.overthewire.org/file/
5. Found page with users.txt link, checked contents of link
    http://natas2.natas.labs.overthewire.org/file/users.txt
6. Extracted password for natas3 from link
    password: 3gqisGdR0pjm6tpkDKdIWO2hSvchLeYH

# Learned
How to find sources of pages using inspect element