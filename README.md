# Birthday_wisher
Send an email with birthday wish message to the  people listed in the excel file..

# Technology Used
Python

# Modules
1.Pandas
2.datetime
3.smtlib
4.emailmessage
5.os

# Method
Using datetime module the programs gets the current time and date then using pandas fetch the data of friends(name,date,email) from the excel sheet with using a for loop. After that program compares the current date with the friend birthday date at 12:00 AM . if the date is equal to the friend birthday date then a mail is send to that friend email with a birthdat wish. 
