# Creating Superuser and Logging in to Django Admin

Follow these steps to create a superuser and log in to the Django admin interface:

1. Open a terminal or command prompt.

2. Navigate to your Django project directory.

3. Run the following command to create a superuser:

Enter a username, email address, and password for the superuser when prompted. Confirm the password.

4. Start the Django development server by running the following command:



5. Open a web browser and navigate to `http://localhost:8000/admin`.

6. Enter the username and password of the superuser you created in step 3.

7. Click on the "Log in" button.

You should now be logged in to the Django admin interface, where you can manage your Django project's data and configurations.

**Additional Notes:**

- If you're using a custom user model, make sure to create a superuser accordingly.
- Ensure that your Django project's settings.py file is properly configured for admin usage, including the `INSTALLED_APPS` setting.

That's it! You've successfully created a superuser and logged in to the Django admin interface. Happy administrating!

