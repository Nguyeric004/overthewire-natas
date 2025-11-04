# Natas level 7

# Objective
Find the password for the next level through the webpage

# Solution Steps
1. Log into Natas website
    http://natas7.natas.labs.overthewire.org/
2. Found two hyperlinks labled "Home" and "About", clicked on both hyper links
    this is the front page 
    this is the about page 
3. Did not find any helpful information on the page but the URL for webpage would change according to the page it is on
    http://natas7.natas.labs.overthewire.org/index.php?page=home
    http://natas7.natas.labs.overthewire.org/index.php?page=about
4. Inpsected page for any hints
    ctrl + shift + i
5. Found hint for finding password
    hint: password for webuser natas8 is in /etc/natas_webpass/natas8 
6. Changed the page to /etc/natas_webpass/natas8
    http://natas7.natas.labs.overthewire.org/index.php?page=/etc/natas_webpass/natas8
7. Extracted password from page
    password: xcoXLmzMkoIP9D7hlgPlh9XD7OgLAe5Q 

# Learned
How to access different pages my modifying the URL