# Natas level 8

# Objective
Find the password for the next level through the webpage

# Solution Steps
1. Log into Natas website
    http://natas8.natas.labs.overthewire.org/
2. Found prompt for user input as "secret" and a link to source code, checked source code
3. Found functions that checked if user input matched "$encodedSecret", encoded the user input, and the value of variable $encodedSecret
    $encodedSecret = "3d3d516343746d4d6d6c315669563362";

    function encodeSecret($secret) {
        return bin2hex(strrev(base64_encode($secret)));
    }
4. Took value of $encodedSecret and reversed operations done by encodeSecret function starting with From Hex by using CyberChef
    3d3d516343746d4d6d6c315669563362 => ==QcCtmMml1ViV3b
5. Took output and reversed string
    ==QcCtmMml1ViV3b => b3ViV1lmMmtCcQ==
6. Took output and converted from Base64 to ascii 
    b3ViV1lmMmtCcQ== => oubWYf2kBq
7. Submitted output as user input in original page
    oubWYf2kBq
8. Extracted password from page
    password: ZE1ck82lmdGIoErlhQgWND6j2Wzz6b6t 

# Learned
How to reverse engineer operations done by an encoding function