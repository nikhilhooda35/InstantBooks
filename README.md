A Django Project

get MERCHANT KEY and MID from paytm and update it in shop/views.py before running the project.

Admin:
	Username: nikhilhooda
	Password: nikhil123 

Users:
	Username: user1
	Password: 1234
	Username: user2
	Password: 1234


Potential Library Requirments
pillow(pip install pillow)
pycryptodome(pip3 install pycryptodome)

Use the following payment details for payment
Mobile number: 77777 77777
Password: Paytm12345
OTP: 489871
Note: Do not try to make Payment with an official Paytm account or valid Debit/Credit card as of now.

How to run

Open CMD, PowerShell or Terminal/CommandShell of any IDE
Go to the root folder where manage.py file is located
Run command "python manage.py runserver"
Open any browser and go to 127.0.0.1:8000
You should be able to see the homepage
View Admin Panel

Run server
Open browser and visit 127.0.0.1:8000/admin
Login with provided username and password
Adding new menu items

Login as admin
Go to products
Click Add products and provide valid details of new product
To confirm visit homepage and look for added product
Changing Admin Password

Go to root folder
Run following command "python manage.py changepassword <user_name>"
Provide new password
Points to keep in mind
The payment gateway is for development purposes and must not be used for real-world payment as of now. Payment failure occurs very often in the development environment, to succeed, make sure you fill all required fields and try again till it does. for any query contact the writer.

By Nikhil Hooda
Email:
nikhilhooda35@gmail.com
