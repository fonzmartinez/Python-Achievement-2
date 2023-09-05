## Exercise 2.8 - Deploying a Django Application

Task Requirement: 
  - In this final task, you’ll finalize some remaining aspects of your Recipe application, such as (certain) features, content, formatting, and links. You’ll also place automated tests to ensure that no bugs have been introduced by mistake, or could be introduced when updating your application in the future. Additionally, you’ll ensure that your code is well documented and follows best practices. Finally, you’ll upload your application.

Task Directions:

  - 1 - Review Website for Functionality and Outlook:
Go through the project brief and ensure that you’ve implemented all the desired functionality. Make sure that your application has:
  1. A well formatted homepage.
  2. Links to subpages where users can view and search for recipes.
  3. A login form.
  4. Features for logged-in users, such as “add recipes”.
  5. An “About Me” page with important links to your portfolio (if it exists), contact information, GitHub, and any other relevant links. Remember, this page is more about you as a developer than the recipe or culinary world.

  - 2 - Add tests:
  1. Add tests to your apps to cover the models, views, and forms.
  2. Run these tests.
  3. In case of failed tests, fix the bug and run again. Repeat until all tests have passed.
  4. Create a folder named “Exercise 2.8” in your “Achievement 2” folder on GitHub.
  5. Take a screenshot of the test report, save it as “test-report.jpg” and upload it to a “screenshots” folder in the “Exercise 2.8” folder.

  - 3 - Upload web application to server:
  1. Follow the instructions provided throughout this Exercise to “launch” your web application:

  - 3A = Prepare to Upload Code on GitHub:
  1. Review your code to ensure it’s properly documented.
  2. Make a backup of your project to ensure you have a fallback in case something goes wrong in the following steps and you have to start over.
  3. Note: you can use the same GitHub repository (i.e., recipe-app) that you’ve used to submit your work so far.
  4. Ensure you have the necessary files in place (i.e., README, .gitignore).
  5. Ensure you remove your "settings.py" file (or at least the 'SECRET_KEY') from your GitHub.
  6. Ensure you have a clone and can push code to your GitHub from your terminal.
  7. Push it!

  - 3B - Configure Django files:
  1. Activate the virtual environment: "a2-ve-recipeapp".
  2. Configure the Django files.
  3. Install the packages needed to make your application production ready.
  4. Freeze the requirements.
  5. Push updated code to GitHub.

  - 3C - Deploy on Web Server:
  1. Create a Heroku account. If you’d like to use a different server, upload a brief note in the “Exercise 2.8” folder providing your reasons for doing so.
  2. Configure the project using Heroku CLI.
  3. Push code to Heroku remote.
  4. Push web application online.
  5. Create users: Add one superuser for your mentor with the username mentorCF and password Ment0r@CareerF0undry.
  6. Add data using the admin panel. Add at least 15 recipes.
  7. Verify that the application is working as intended.
  8. Make a final check to push the updated "settings.py" file and the hidden 'SECRET_KEY'.