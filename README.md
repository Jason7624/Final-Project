#CS50's Web Programming with Python and Javascript Final Project (Capstone)

My team:
Adimas Irfannanto
Farid Nafis Tsani
Jason

This is the last one! It's been quite a fun and interesting journey going through this course although. We want to extend my heartfelt thanks to all the staff and lecturers who made this CS50 Web Programming course possible.

## Wasters - Trash Management
Wasters is my project which was developed for the CS50 web course final project, the website contained a management style website where users can order a trash disposal service from local waste services providers, or you can also be a provider that manage waste services for the customers.


##Distinctiveness and Complexity 

First of all, This website has a few key distinctive features:
Dual User Roles: The platform supports two primary user roles, customers and service providers, each with different interface and functionalities. Customers can easily order services, manage their payment history and previous order services, while providers can handle their customer service requests and manage their previous activies. For This dual user roles feature, I got the idea from previous projects, especially the e-commerce one. The difference is that this project saved their payment history, previous order history, and their balance.

Embedded Google Maps API Integrity: This website also support embedded Google Maps API, ensuring that customers know where to look the exact location of the place and also limit the user with only the providers available in their specific area.

Admin Panel: This project also use the provided admin panel by Django. However, the admin panel that we are using is customized using the Django jazzmin library. The admin panel provides administrators with all the databases in this project with full access, such as the location/area, accounts, payments, and etc. Furthermore, there is also an admin panel in the website itself, which only contains every activity history, payments and accounts in the database. Although, there is an admin panel in the website, it could not be edited.

In term of Complexity,

Django: The application utilizes Django to manage multiple models for the database using dbsqlite (customer, address, user, etc), the function of the website (Redirects, Authenticate, calculating and rendering a page with real time data), and the admin panel view and edit the database.

JavaScript : In this project, I used JavaScript to make a single page application for the user's dashboard, track the cursor at the main page to make the navbar appear at the top while scrolling, and etc. I also use javascript libraries from bootstrap and w3 to make the website more responsive and user-friendly.

HTML and CSS: This website is also getting help from w3 and bootstrap libraries in order to make the website more easy to acknowledge with the added icons and user intuitive UI. this website is also mobile responsive because of the added meta viewport and libraries.

Mobile Responsiveness: The web application is fully mobile-responsive,  ensuring that users can access and use the platform effectively from any device. This responsiveness is achieved through careful design and implementation of CSS frameworks and media queries, providing a consistent user experience across different screen sizes.

> Main Features

- Home Page
- User Registration
- User Login & Logout
- Each user have their own saved data
- Easy to Use Dashboard
- Status
> Customers
- Payments & Services History
- Detailed Payment & Service screen
> Service Providers
- Services History & Previous Activity
- Confirmations
> Administrator
- Custom Admin Panel
- Every Previous User history (Previous Payments, Previous Services History, Previous Requested Services)




### Main Files

- manage.py (in order to run django)
- db.sqlite3 (database)
- requirements.txt (library requirements for this app)
	> staticfiles (all js and css files for the dashboard and home page)
	> templates (all dashboard and home page html files along with their own styles)
	> wms (main django directory)
	- __init__.py (initialize django)
	- settings.py (main django settings)
	- urls.py (urls for calling an app)
	> wms_app (main app django directory)
	> migrations (migration result directory)
	- admin.py (admin functions)
	- models.py (database 
	- urls.py (urls for calling functions in the app)
	- views.py (functions)

## How to Run

```
pip install -r requirements.txt
```

Install all the necessary libraries


```
python manage.py makemigrations
python manage.py migrate
```

Initialize the database


```
python manage.py runserver
```

Run the app and Enjoy!


	
	








