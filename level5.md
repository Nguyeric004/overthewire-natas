# Natas level 5

# Objective
Find the password from the website

# Solution Steps
1. Log into Natas website
    http://natas5.natas.labs.overthewire.org/
2. Promped page that says "Access disallowed. You are not logged in.", tried connecting using curl
    curl -v -u natas5:0n35PkggAPm2zbEpOU802c0x0Msn1ToK http://natas5.natas.labs.overthewire.org/
3. Did not find anything, tried inspecting page elements
    ctrl + shift + i
4. Looked through page element tabs, found cookies tab in storage with name "loggedin" with value 0. Changed value to 1.
5. Nothing changed, refreshed page
    f5
6. Extracted password from page
    password: 0RoJwHdSKWFTYR5WuiAewauSuNaBXned
# Learned
How to check cookies and manipulate their values