## Exercise 2.3 - Django Models

Task Requirement: 
  - The application will allow users to create recipes, inputting information such as ingredients, cooking times, and a small description of each dish. Users will also be able to search for recipes via their ingredients on the application. You can go through the Project Brief again to grasp the high-level requirements of the application. 

Task Directions: 

  - Create a folder named “Exercise 2.3” to save the output generated as part of this task.

  - Create database blueprint:
  1. Think about the information categories (entities) in your Recipe application. Identify the desired attributes of each entity and their relation with other entities.
  2. Draw the schema in a tool of your choice (or even on paper).
  3. Save a screenshot or image of the complete schema in the “Exercise 2.3” folder. Name it “recipe-app-schema.jpg”.

  - Create Apps: Now that your schema is ready, you’ll have a fairly good idea of how you want your web application to look. You can now create the apps for your project. For this, make sure that you’re in the "src" folder in your terminal in VSCode. Then:
  1. Run the "startapp" command as many times as needed to create the apps in your project.
  2. Go to your project’s "settings.py" file to link your apps to the "INSTALLED_APPS" parameter.
  3. Screenshot the tree structure showing all the apps and the "settings.py" file in VSCode.
  4. Use the annotation tool in your image-editing software to point out the apps and the linkage. The following figure, for example, has annotations of two apps—books and customers—from the Bookstore application.
  5. Save this image as “project-structure.jpg” in “Exercise 2.3”.

  - Create Models: Based on your blueprint, create models for your entities in the "models.py" files within the apps. Define the fields and __str__ for each class.

  - Register Models: Navigate to the respective "admin.py" files in each app folder and register your class(es).

  - Migrate:
  1. Run "makemigrations" and "migrate" in the terminal to convert your class models into database tables.
  2. Take a screenshot of your terminal after running these commands to show that the status of applying all migrations is OK.
  3. Name the screenshot "run-migrations.jpg" and save it in “Exercise 2.3”.

  - Write Tests:
  1. Add tests to your apps to cover the models.
  2. Run the tests.
  3. In case of failed tests, fix the bug(s) and run again. Repeat till all tests have passed.
  4. Take a screenshot of the test report, save it as “Test-Report.jpg” and upload it to “Exercise 2.3”.

  - Run Server: 
  1. Using the appropriate command in the terminal, run the server.
  2. Copy the link and navigate to the admin panel.
  3. Log in using the superuser credentials that you created in Exercise 2.2.

  - Add data from the Django site admin:
  1. Add at least five recipes into your database.
  2. Take screenshots of the list of data elements that you entered.
  3. Name them appropriately and save in the “Exercise 2.3” folder.

  - Upload the “Exercise 2.3” folder to the “Achievement 2” folder in your GitHub repository.

  - Create another GitHub repository called “recipe-app” and push your code in the "src" folder to the repository. Make sure that you include a Python-based ".gitignore" file while creating the repository. Add the following lines in the ".gitignore" file to ensure that the backup and database files are not uploaded:

                      # Text backup files
                      *.bak

                      # Database
                      *.sqlite3

  - Add a "README" for your repository and include introductory information about the Recipe application (minimum three sentences).

  - Share GitHub links to the “Exercise 2.3” folder and your newly created “recipe-app” repository with your mentor for review.
