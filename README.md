# Online store on Django  
## Project description  
This project is an online store developed using Django framework. It includes shopping cart management features, secure payment processing with Stripe and a fully implemented user system.

## Main features  
* Shopping cart: Add, delete and change the number of items in the cart.  
* Payment Gateway: Integrate with Stripe for secure payment processing.  
* User Creation: User registration and authentication.  
* Webhooks: Utilize webhooks to securely process payments.  
* Pagination: Easily navigate through products using pagination.  
* Product selection by categories: Filtering of products by different categories.  
* Multiple photos for each product: Ability to add multiple images for each product.  
## Technologies used in the project  
* Django: The main framework for web development.  
* Pillow: Library for image processing.  
* psycopg2: PostgreSQL adapter for Python, used for database manipulation.  
* Stripe: A payment gateway for processing payments.
## Installation
Clone the repository

* Create a virtual environment and activate it:

* python -m venv venv

* venv\Scripts\activate

* Install all the required dependencies

* pip install -r requirements.txt

* Customize the database in settings.py and run the migrations

* python manage.py migrate

* Start the development server

* python manage.py runserver

* To start Stripe, enter into the command line

* stripe listen --forward-to lacalhost:8000/payment/webhook/

* After the server starts, open your browser and go to http://127.0.0.1:8000/.

You will be able to browse products, add them to your cart and make purchases.
