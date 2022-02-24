# django-test-project
Django test project:

=> (Project Description):

In this project users are able to join an online platform and intract with each other by sharing content.
Users will be able to bookmark any images on the internet and share it with others.
They will also be able to see activity on the platform from the users they follow and like/unlike the images shared by them.


=> (How to run the project):

You can make a admin account to access to the django admin with this command:

                 python manage.py createsuperuser

then you can run the project with:

                 python manage.py runserver
or

                 python manage.py runserver_plus --cert-file cert.crt 

since you can run the project through HTTPS.

=> (URLS):

                 /register =====> register form

                 /         =====> dashboard(root)

                 /password_change =====> change password

                 /password_reset  =====> reset password



