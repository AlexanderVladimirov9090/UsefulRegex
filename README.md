# UsefulRegex
Some useful regex for validation data will be stored here.
Could use some help to fill this list.

Name validation:
[A-Z][a-z]+
Alexander = pass
alexander = fail 

Username Validation:
([a-zA-Z])[a-zA-Z_-]*[\w_-]*[\S]$|^([a-zA-Z])[0-9_-]*[\S]$|^[a-zA-Z]*[\S]

alexander =pass
alexander123123=pass
Aasdsadqwe=fail
123asd=fail
