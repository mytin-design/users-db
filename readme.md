# REGISTRATION AND LOGIN

PHP, HTML, CSS

The code begins with registration.
# Registration process

Input is collected using HTML

Input is processed using PHP

PHP takes the input, and inputs it into the database

--The username must be unique - it is the primary key in the database;

--password is compared to the confirm password

--password is hashed 


Upon successful registration, i.e if username used does not exist in the database, user is directed to the login page
# LOGIN PROCESS

Input is through HTML,

simple validation is done using Javascript

PHP takes login data,

compares it with data in database, 

If correct, redirects to dashboard.



### Missing 
No option to reset password


The option to reset :
1. may just access the database, and update a password - based on the email of the user or username, whichever is set as primary key - in this case, the username

This section is making it a little bit harder, because I dont understand whats happening.

2. For security concerns, Send a link to email of the user, which arrives as a token - 


## RECOMMENDATIONS
Leave the email function for now

Start with the known, going to the unknown;


## send registration details to email
//There is a problem with the mailing function - or maybe i dont just undertand it yet

Once I do - send registration details to the users email - esp their new email, username and password;


## hide the error box several seconds after appearing
During login



## STYLES TAKING LONG TO REFLECT WHILE RUNNING ON A SERVER


## The notifications are not being handled appropriately

Especially those of the reset



## END OF VERSION 1 
AS AT 15/12/2023 - 12:00 


Registration - working

Login - working

Reset - working

Reset link generation - working

User preferences - working

ISSUE 00111 - STYLING
You may need to fix styling for alerts;

The code may be used as is, or modified to fit developer needs.

## ##################################DENIS KING - denismytin@gmail.com ##############################################



