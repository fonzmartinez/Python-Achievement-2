## Exercise 2.5 - Django MVT Revisited

Task Requirement:
  - It’s now time to apply what you’ve learned in this Exercise to your Recipe application. You’ll first be working on the backend of the application to ensure that your tables have all the relevant attributes. Then, you’ll connect them to the frontend for display.

Task Directions:

  - 1.- Update your models (if needed).

    First, take some time to think about your model(s) again and update them to ensure all relevant attributes are there. Once you start entering the data and creating templates, changes will be more costly in terms of effort.

    a. Create an empty document (named “Task-2.5” or similar), mention your models/tables from Exercise 2.3, and specify if (and why) you’re changing any attributes. This will include the addition or deletion of attributes, updates in data type, moving attributes from one table to another, or any other reason that you consider important.

    b. Make necessary changes in the models.py files of the affected apps.

    c. Toggle the terminal ON in VSCode.

    d. Navigate to A2_Recipe_App/src.

    e. Activate virtual environment: a2-ve-recipeapp.

    f. Run makemigrations, migrate, and runserver.

  - 2.- Add records (for at least five reciptes).

    a. Prepare the information that’ll go into your database. Download any images and save them on your computer.

    b. Proceed to the Django admin panel in the browser at “http://127.0.0.1:8000/admin/” and make the corresponding entries.

  - 3.- Develop a welcome page for your application.

    a. Take inspiration from existing recipe applications. Create a section called “frontend inspirations” in your journal.doc document and add links to your favorite recipe applications (three at most). Take screenshots and write a few lines on what you like most about them.

    b. Try to reproduce the look and feel of your favorite application in your own application. Feel free to mix and match.

    c. Take a screenshot of your new homepage and save it as welcome.jpg.
  
  - 4.- Generate a recipes list.

    Develop a recipes sub-page that lists all your recipes. Feel free to be creative and add as much or as little information on the page as you want. Use your HTML and CSS knowledge to enhance the page’s look. Ensure that the entries are individually clickable and linked to the details page (which will be created in the next step). Load the page in the browser and take a screenshot. Save it as recipes-overview.jpg.

  - 5.- Add recipe details.

    Create a details page for your recipes connected to “recipes-overview” page from Step 4. Again, be creative and feel free to display the information in the most presentable way. In addition to the information stored in the database, also calculate the “difficulty” parameter of your recipe and display it, as well (refer to Achievement 1 for the logic for calculating the difficulty of the recipe). Take screenshots of at least two recipe details and save them as recipe1.jpg and recipe2.jpg.

  - 6.- Repeat (if necessary).

    If you have multiple tables (i.e., models) in the application, repeat steps 1, 2, 4, and 5 to make sure they have all the necessary attributes and that the records have been added. Also, if you need to display these records as lists and/or details, create views and templates for them now.

  - 7.- Write your tests.

    Add tests corresponding to the functionality that you added. Make sure that all the links work. Run tests and ensure that all of them pass.

  - 8.- Upload your document and screenshots to Github.

    a. Create a folder named Exercise 2.5 in your Achievement 2 folder on GitHub.

    b. Upload the document Task-2.5.
    
    c. Create a Screenshots folder under Exercise 2.5 and upload all the screenshots to it.

  - 9.- Upload your code to Github.

    Push your code in the "src" folder to the recipe-app Github repository that you (previously) created.