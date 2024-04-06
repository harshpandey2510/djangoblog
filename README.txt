# djangoblog
Django Blog Website
This is a simple blog website built using Django framework. Users can create accounts, write blog posts, comment on posts, and view posts by category.

Installation
To run this project locally, follow these steps:

1.Clone the repository to your local machine:
git clone <repository_url>
2.Navigate to the project directory:
cd django-blog-website
3.Create a virtual environment:
python -m venv env
4.Activate the virtual environment:
-On Windows:
env\Scripts\activate
-On macOS and Linux:
source env/bin/activate
5. Apply migrations:
python manage.py migrate
6.Run project
python manage.py runserver

The project should now be accessible at http://localhost:8000/. You can log in to the admin interface at http://localhost:8000/admin/ using the superuser credentials created in step 7.

Usage
Once the server is running, you can visit the website in your browser and explore its features. You can create new blog posts, comment on existing posts, and manage categories through the admin interface.

Contributing
Contributions are welcome! If you'd like to contribute to this project, please fork the repository and submit a pull request with your changes.
