# OGS---Assessment-Test-Q-1

Functionality:-
1) Extract the required info from the PDF invoices and save the extracted data into an excel. 
2) Send an email with created excel.

Configuration:-
 Email address can be updated by following belwo steps
a) Go to State-0
b) Go to Initialize sequence
c) Update StrMailTo & SteMailCc variables to add required email addresses.

Output:-
1) Input folder contains no file:- Then the bot will send an email stating the same.
2) Failure:- Bot will communicate regarding the issue faced by the bot.
3) Success:- Bot will send an email contianing an excel file ( PDF Data).
