markdownCopy code

# Django StudyBud App

Django StudyBud is an interactive web application that allows users to create and join study rooms to discuss specific topics. It provides a platform for collaborative learning and knowledge sharing.

## Features

- **User Registration and Authentication:** Users can create accounts, log in, and manage their profiles.

- **Room Creation:** Users can create study rooms for specific topics, adding descriptions and categories.

- **Real-time Chat:** Each room features a real-time chat functionality for users to discuss and collaborate.

- **Room Discovery:** Users can search and discover study rooms based on categories and keywords.

- **Notifications:** Users receive notifications for new messages and room updates.

## Technologies Used

- Django
- Django Channels (for real-time chat)
- HTML, CSS, JavaScript
- SQLite (as the database)
- Other relevant dependencies (list them)

## Installation

Follow these steps to set up and run the Django StudyBud app on your local machine:

1. Clone the repository:
   ```bash
   git clone https://github.com/carloskim123/django_studybud_app.git` 

2.  Change into the project directory:

      `django_studybud_app` 
    
4.  Install the project dependencies:
    
    
    `pip install -r requirements.txt`
    
5.  Set up the database:
    
    
    `python manage.py migrate` 
    
6.  Create a superuser to manage the admin panel:
    
    
    `python manage.py createsuperuser` 
    
7.  Start the development server:
   
    
    `python manage.py runserver` 
    
8.  Access the admin panel at `http://localhost:8000/admin/` and log in with the superuser account to manage rooms and users.
    
9.  Visit the StudyBud web app at `http://localhost:8000/` and start creating or joining study rooms!
    

## Configuration

You can configure various settings in the `settings.py` file, including database settings, authentication, and email setup.

## Contributing

We welcome contributions to make Django StudyBud even better. Feel free to open issues, submit pull requests, or suggest improvements.

## Contact

If you have questions or need assistance, please contact [Carlos Kim](https://github.com/carloskim123).

Happy learning and collaborating!
