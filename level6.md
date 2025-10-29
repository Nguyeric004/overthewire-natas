# Natas level 6

# Objective
Find the password for the next level through the webpage

# Solution Steps
1. Log into Natas website
    http://natas6.natas.labs.overthewire.org/
2. Prompted user for "secret" input with a submit button and a hyperlink for the source code, checked source code
3. Found code snippet for php
<?

    include "includes/secret.inc";

    if(array_key_exists("submit", $_POST)) {
        if($secret == $_POST['secret']) {
        print "Access granted. The password for natas7 is <censored>";
    } else {
        print "Wrong secret";
    }
    }
?>
4. Checked out secret webpate
    http://natas6.natas.labs.overthewire.org/includes/secret.inc
5. Found string attached to secret variable, navigated back to natas6 page and entered in string value
    http://natas6.natas.labs.overthewire.org/
    FOEIUWGHFEEUHOFUOIU
6. Extracted password from output
    password: bmg8SvU1LizuWjx3y7xkNERkHxGre0GS 

# Learned
What is PHP code 