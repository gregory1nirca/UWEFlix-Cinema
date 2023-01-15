# UWE Flix

A cinema booking Django application written in Python with a small contribution from the front-end styling languages.  

The possibilities  of the project are listed below:
1. Users can create their user account.
2. Users can book tickets.
3. Users can update their details.
4. Users can login.
5. Users can delete their account.
// Currently the admin is the account and cinema manager.
6. Admin is pre-set and can gestionate the movies, theatres, showings and users.
7. Admin can create an account, a movie, a showing.
8. Admin can add a new theatre.
9. Admin can delete/update each detail. 

10. Users can view their previously booked tickets (in progress).
11. Tickets are downloadable as pdf document (in progress).


# Directories & Files
  - `UWEFlix` - project directory setup.
    - `settings.py` - Contains instructions and settings.
  - `users` - users directory.
    - This directory contains all of the information and instructions related to users.
  - `template` - templates directory. 
        - `logout.html` - Template for log-out message and login link.
        - `profile.html` - Update user page.
        - `book_ticket.html` - Booking page for tickets.
        - `shows_listing.html` - Base template for all pages except login & register page.
        - `ticket_booking.html` - Booking page for completing the details for the ticket.
        - `ticket_confirmation.html` - Ticket confirmation page
        - `register.html` - Register user page.
        - `login.html` - Login user page.
    - `admin.py` - Models for admin access.
    - `models.py` - Models used in the project are created in these files.
    - `urls.py` - These files handles the URLs specific to each directory.
    - `views.py` - These files contains the application views.
  - `requirements.txt` - All the packages which are required to be installed in order for the web application to run are located in this file.
  - `manage.py` - The specific py is a common file which is used in debugging, running the application. It is known as a command-line utility.
  - `DockerFile` - The docker file.

# Details

0. Compatible with Firefox and Chrome
1. Responsive webpage (in development cycle)
3. The ticket will be retrieved as a pdf through email (in progress)

# Instructions on runnig the website.

- Unzip the file 'UWEFlix Project' and open the UWEFlix Project folder in PyCharm or VS Code
- For Django setup was used PyCharm as it allows you to understand the made errors.
- Firstly, install project dependencies by running `py -m pip install -r requirements.txt` and make sure to use python 3.8 for better performance in virtual environment (as on it was tested).
- Command `py manage.py createsuperuser` create the admin profile with the credentials entered in the terminal. The current one have the followings:
  - Username: admin@admin.com
  - Password: admin 
- Command `py manage.py runserver` initiate the server.
- Acces the `127.0.0.1:8000` url in browser to launch it.
- To open admin page go to `127.0.0.1:8000/admin` use superuser credentials which were provided by me or created by you.
- The user profiles have the credentials listed below:
  - Test profile:
    - Username: test@test.com
    - Password: Djangouser1.
  - Test1 profile:
    - Username: test@test.com
    - Password: Djangouser2.
  - Test2 profile:
    - Username: test@test.com
    - Password: Djangouser3.
    or create your own profile.

- The `Demonstration.mp4` video file located in the main directory under UWEFlix folder can be watched to see the website functionality. Firstly, it needs to be extracted from the zip file which have the same name.
