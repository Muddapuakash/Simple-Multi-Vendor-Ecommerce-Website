# Simple-Multi-Vendor-Ecommerce-Website
his website has a user-friendly interface which helps the users to view the detailed goods and services provided, browse through the items, and navigate in the website hassle free.
Django Simple Multi-Vendor Website with Payment
This is a simple MultiVendor e-commerce website built with Django (Ptyhon) and Stripe is added as payment processor.

In this website, Vendors (Stores) can register and add their products.

And Users can visit the product and order by paying with Debit/Credit Card (Stripe is Used).

Then Vendor gets the email notification about the order and should deliver the product to the customer based on the address details.

And if you like this project then ADD a STAR ⭐️ to this project 👆

Features of this Project
A. Admin Users Can
Manage Category (Add, Update, Filter and Delete)
Manage Products (Add, Update, Filter and Delete)
Manage Users (Update, Filter and Delete)
Manage Orders (View and Process)
B. Vendors Can
Add Products
Update Profile
Gets Notification When an Order is made by Users
Get Orders and Manage Them
C. Users Can Can
Add to Cart
Pay with Debit/Credit Card and Order
While Checkout, User should give the address to deliver
Get Email Notification about the confirmation of the order
Support Developer
Subscribe & Share my YouTube Channel - https://bit.ly/vijay-thapa-online-courses
Add a Star 🌟 to this 👆 Repository
Donate
PayPal

Buy me a Coffee ☕️

Donate by wire transfer: E-Mail at donate@vijaythapa.com for wire transfer details.

How to Install and Run this project?
Pre-Requisites:
Install Git Version Control [ https://git-scm.com/ ]

Install Python Latest Version [ https://www.python.org/downloads/ ]

Install Pip (Package Manager) [ https://pip.pypa.io/en/stable/installing/ ]

Alternative to Pip is Homebrew

Installation
1. Create a Folder where you want to save the project

2. Create a Virtual Environment and Activate

Install Virtual Environment First

$  pip install virtualenv
Create Virtual Environment

For Windows

$  python -m venv venv
For Mac

$  python3 -m venv venv
Activate Virtual Environment

For Windows

$  source venv/scripts/activate
For Mac

$  source venv/bin/activate
3. Clone this project

$  git clone https://github.com/vijaythapa333/simple-multivendor-site.git
Then, Enter the project

$  cd simple-multivendor-site
4. Install Requirements from 'requirements.txt'

$  pip install -r requirements.txt
5. Add the hosts

Got to settings.py file
Then, On allowed hosts, Add [‘*’].
ALLOWED_HOSTS = ['*']
No need to change on Mac.

6. Now Run Server

Command for PC:

$ python manage.py runserver
Command for Mac:

$ python3 manage.py runserver
7. Login Credentials

Create Super User (Admin)

Command for PC:

$  python manage.py createsuperuser
Command for MAC:

$  python3 manage.py createsuperuser
Then Add Email, Username and Password
