# python-car-parking-system
-------------------------------------------------------------------------------------
-------------------------------------------------------------------------------------
 INTRODUCTION: 
-------------------------------------------------------------------------------------
-------------------------------------------------------------------------------------
IN OUR PROJECT USER CAN BOOK THE PARKING SLOTS FOR PERTICULAR DATES AND IF THAT SLOTS ARE ALREADY BOOKED AT THAT DAY THEN THE SLOT WILL BE SHOWN DISABLED AND USER WON’T BE ABLE TO BOOK THAT SLOT.THEN USER NEED TO BOOK ANOTHER SLOT AND AFTER THE BOOKING IS DONE, WE ARE GENERATING BOOKING ID FOR THE USERS AND FOR ADMIN REFERENCE SO THAT USER CAN VIEW THIER BOOKING AND ON OTHER HAND ADMIN CAN VIEW ALL THE BOOKINGS AND ADMIN CAN CANCEL THE BOOKING OF PERTICULAR USER. 
-------------------------------------------------------------------------------------
-------------------------------------------------------------------------------------
#STEPS
-------------------------------------------------------------------------------------
-------------------------------------------------------------------------------------
    1.Python version 3.7.x is used for this project
    2.Install all the packages (PyQt5,pymysql,smtplib)
    3.Install mysql and then set up its server and make necessary changes in py file for database
    4.Open 'cmd' in the folder and type ----python welcome.py
    4.You are ready to go.
-------------------------------------------------------------------------------------
-------------------------------------------------------------------------------------
#Database
-------------------------------------------------------------------------------------
-------------------------------------------------------------------------------------
	Step-1. Create schema by name customer
	step-2. import customer.login and customer.bookingdetails files
	setp-3. Makes changes in F1login and F1Booking.
	i.  host:"localhost"   --Dont change
	ii. user:"You_db_name"
	iii.password:"your_db_password"
	iv. db:"customer" --Dont change
-------------------------------------------------------------------------------------
-------------------------------------------------------------------------------------
#Libraries
-------------------------------------------------------------------------------------
-------------------------------------------------------------------------------------
	1. pip install PyQt5
	2. pip install pymysql
	3. pip install smtplib
-------------------------------------------------------------------------------------
-------------------------------------------------------------------------------------
#File Sequence
-------------------------------------------------------------------------------------
-------------------------------------------------------------------------------------
	1. Welcome.py
	2. F1login.py
	3. F1booking.py
