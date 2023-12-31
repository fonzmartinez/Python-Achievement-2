## Python-Achievement-2


## Exercise 2.1 - Getting Started with Django

Task Requirement:
  - In this first task of the second Achievement, you’ll answer a couple of questions, as well as prepare your Django development environment.


Task Directions:

  - Create a text document where you can write your answers to the following questions. You’ll want to do some research online to help you develop your answers.

  - Write two to three sentences on why Django is so popular among web developers.

  - After some research, list five large companies that use Django. Specify what the company’s product or service is and what they use Django for.

  - For each of the following scenarios, explain if you would use Django (and why or why not):
  1. You need to develop a web application with multiple users.
  2. You need fast deployment and the ability to make changes as you proceed.
  3. You need to build a very basic application, which doesn’t require any database access or file operations.
  4. You want to build an application from scratch and want a lot of control over how it works.
  5. You’re about to start working on a big project and are afraid of getting stuck and needing additional support.

  - Download and install Python (if you haven’t done so already).
  1. Run the appropriate command to check the Python version.
  2. Take a screenshot of the terminal window with the command and version and paste it into your answers document.

  - Open a new terminal window and go to the folder where you want to create your projects.

  - If you haven’t done so already, set up and create a virtual environment and name it "achievement2-practice". Then:
  1. Activate the virtual environment.
  2. Take a screenshot of the activated environment and paste it into your answers document.

  - Install Django and verify the installation by checking the version. Then:
  1. Take a screenshot of the terminal with the command and version.
  2. Paste it into your answers document.

  - Export your document as a PDF.

  - You can continue working on your learning journal! You'll update the journal for each Exercise as you move through this Achievement.

  - In the GitHub repository that you created in Achievement 1, create a folder for this Achievement (if not done already) and name it “Achievement 2”. Create a subfolder for your Exercise (“Exercise 2.1”) and upload the PDF and learning journal to this folder.


## Exercise 2.2 - Django Project Set Up

Task Requirement: 
  - In this Achievement, you’ll recreate your Recipe application from Achievement 1. This time though, you’ll be deploying a full-fledged web application using the Django framework. Once complete, users will be able to input recipe details—ingredients, cooking times, descriptions—into the application, as well as search for recipes via their ingredients. 

In this task, you’ll set up the structure of your Recipe application project. This will be your first step towards building the application using the Django framework.


Task Directions: 

  - Create a folder in your system and name it “A2_Recipe_App”.

  - Create a virtual environment named 'a2-ve-recipeapp' and activate it. (Note: If your 'web-dev' virtual environment is still active, deactivate it before creating the new virtual environment).

  - Install Django in the virtual environment.

  - In the “A2_Recipe_App” folder in your system, create your Django project and name it “recipe_project”.
  1. Screenshot the contents and structure of the “A2_Recipe_App” folder and subfolders.
  2. Name the screenshot “proj_contents_before_renaming.jpg.”

  - Rename the “recipe_project” project directory “src”.
  1. Screenshot the contents and structure of the “A2_Recipe_App” folder and subfolders.
  2. Name the screenshot “proj_contents_after_renaming.jpg.”

  - From within the “src” folder, run migrations and then run the server. Screenshot the browser window with the success message.

  - Create superuser: Since you’ll need to log in as an admin to your application soon, it’s a good idea to create a superuser now.
  1. Create a superuser for your application following the steps in this Exercise, and use it to log in to the server in the browser.
  2. Screenshot the admin dashboard and highlight the superuser in the list of users. Save this as an image titled “admin-dashboard.jpg”. Press Ctrl+C in the terminal to quit the server.

  - Create a folder “Exercise 2.2” in your “Achievement 2” folder on GitHub.

  - Upload the “A2_Recipe_App” folder to the “Exercise 2.2” folder.

  - Create a “screenshots” sub-folder in “Exercise 2.2” and upload the screenshots from this task to it.


## Exercise 2.4 - Django Views and Templates

Task Requirement: 
  - A custom welcome page is a good first step for any application, so that’s what you’ll focus on in this task. Feel free to be creative with your HTML knowledge when creating your custom welcome page. The task directions are as follows:
  

Task Directions: 

  - 1.- Load Project: 
  
    In VSCode, open the "A2_Recipe_App/src" folder.

  - 2.- Create the view: 
  
    Pick the app where you want to create the view. Navigate to <app>/views.py and define the view. Save the file.

  - 3.- Create template:  

    a. Create a "templates" folder under <app> (the app name will be the app that you chose).

    b. Create a folder named <app> under the newly created "templates" folder.

    c. Create an HTML file to define your template. Name the file "recipes_home.html". Be careful to specify the correct template path in the <app>/views.py file.

    d. The HTML file is currently empty. Design your welcome page using your desired elements and HTML blocks in the "recipes_home.html" file. Save it.

  - 4.- Map view to URL:

    As this is the welcome page, you’ll want it to appear when the main site (“http://127.0.0.1:8000/”) loads. For this:

    a. Create a "urls.py" file in the <app> folder.

    b. Specify the path in <app>/urls.py to connect the route corresponding to “http://127.0.0.1:8000/” with the view specified by <app>/views.py. Ensure you import the necessary packages and specify the app name. Save the file.

    c. Update the "urls.py" file in your main recipe project by registering the view to "urlpatterns". Ensure you import the necessary packages to include the app. Save the file.

  - 5.- Run Server:

    If not done already, toggle the terminal ON and do the following:

    a. Navigate to "A2_Recipe_App/src".

    b. Activate the virtual environment: "a2-ve-recipeapp".

    c. Run the server.

  - 6.- Load site in browser:

    Copy the link to your app and paste it into the browser. You should see your custom welcome page. Take a screenshot of the homepage and save it as “welcome.jpg”.

  - 7.- Upload screenshot to GitHub:

    a. Create a folder named “Exercise 2.4” within your “Achievement 2” folder on GitHub.

    b. Create a “screenshots” folder within “Exercise 2.4” and upload the “welcome.jpg” screenshot to it.

  - 8.- Upload code to GitHub:

    Push your code in the "src" folder to the recipe-app GitHub repository that you’ve already created (in the last Exercise).


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


## Exercise 2.6 - User Authentication in Django

Task Requirement:
  - Add login and logout features to your Recipe application.

Task Directions:

  - 1.- Provide authentication:

    Create a login feature for your application. The login page should be accessible from your homepage via the link directly at “http://127.0.0.1:8000/login/”. To achieve this, you need to:

    a. Create a login view.

    b. Create a login template.

    c. Register a view and map URL.

    d. Provide a clickable login link or button on the homepage that routes to the authentication form.

    e. Identify which page you want to protect via authentication and redirect the user to that page after a successful login.

  - 2.- Protect views:

    Identify which views or pages you want to protect via authentication. Then go ahead and add the necessary code at all relevant views to ensure that the page isn’t called if the user isn’t logged in. Access the URLs of the protected views in your browser and make sure that you’re redirected to the login page.

  - 3.- Implement logout:

    Provide a logout link or button on each protected page.

    a. Create a new view and template for your application with the message “You’ve successfully logged out.” Call this success.html.

    b. Provide a link to log back in to success.html.

    c. Create the view and template for logging out.

    d. What other information or feature do you want to place on the success.html page? Go ahead and add it to the template. Be creative!

- 4.- Run server and capture output:

  - Toggle the terminal ON in VSCode and follow the steps to run the server:

    a. Navigate to A2_Recipe_App/src.

    b. Activate the virtual environment: a2-ve-recipeapp.

    c. Execute runserver.

  - Head to the browser and follow a typical user journey:

    a. User lands at homepage.

    b. User clicks login button.

    c. Authentication form is shown.

    d. User enters username and password.

    e. Information is authenticated and user is redirected to sales page.

    f. User logs out and returns to successful logout page.

    g. Now, create a screencast recording the user journey using any screen recording tool of your choice. Upload the video as part of your task submission.

- 5.- Upload code to Github:
Push your code in the src folder to the recipe-app GitHub repository that you created previously.

- 6.- Share:
Share the video and link to your recipe-app GitHub repository with your mentor for review.


## Exercise 2.7 = Data Analysis and Visualization in Django

Task Requirement: 
  - Provide Recipe application with search and data visualization features.

Task Directions: 

  - Implement Search for Recipes:
  1. Take some time to think of what you want users to search for, the criterion for search, and format of output. Create a new empty document and call it “Task-2.7”. Place your thoughts in this document. Save the document.
  2. Create a user form to allow your user to input the search criteria.
  3. Extract the data as QuerySet using the search criteria.
  4. Convert the QuerySet to pandas DataFrames (Ensure you have pandas installed).
  5. Display search results as a table.
  6. Ensure that the recipes returned by the search criteria are clickable and lead to the details page of the recipe.
  7. Bonus: Allow users to search on the basis of wild cards and partial search queries. For example, in the Bookstore application, this will mean that searching for “Pride and” will also return “Pride and Prejudice” book results.

  - Implement Show-All (Optional): 
  
  Give users the ability to view all recipes without any search filter from the search criteria.

  - Data Visualization:
  1. In your “task-2.7” document, add a new heading named “Data Analysis”, and note down at least one visualization using a bar, pie, and line chart (at least one for each). For each of the scenarios, identify the x- and y- axes and labels (if any). Also determine if you want charts to be displayed based on user input or simply to provide them at your own discretion.
 2. Head to VSCode and ensure that you have matplotlib installed.
 3. Implement the charts that you shortlisted in 3a.

 - Write Tests:
 1. Follow the same testing process (that you previously used for models and views) to test your new forms and views. For this, you can create classes like RecipeFormTest. Testing will need to include checking the fields for values, formats, or lengths, ensuring login protection of views, appropriate pagination, and any other checks you feel are relevant. As specified earlier, for smaller projects all your tests can be placed in the same file, but feel free to create separate files for each of them if you prefer. In each case, you’ll need to import the form or view that you want to test, create a class, specify the setUp and setUpTestData methods, and write tests.
2. Run the tests with verbosity set to 2, and take a screenshot of the outcome in the terminal. Save the screenshot as “test-outcome.jpg”, or similar.

- Run Server and Capture Output:
1. Open “Task-2.7” and add a heading called “Execution flow”.
2. Think of the user’s journey from the moment they land on the homepage, considering all the different navigation possibilities and search options. For example, a user lands on the homepage, logs in to the account, searches for a recipe based on a recent date, sees the plots, checks details, and then logs out. Represent this journey as a flow chart.
3. Toggle the terminal ON in VSCode and do the following to run the server: Navigate to A2_Recipe_App/src, activate the virtual environment (a2-ve-recipeapp), and execute the runserver command.
4. Head to the browser, and follow the user journey noted in 5b. At each step, note the URL and take a screenshot. Paste the screenshots in the “Task-2.7” document. Alternatively, you can create a screencast recording the journey using your favourite screen-recording tool. Save it by the name “user-journey.mp4” (or any other movie extension of your choice).

- Upload journal to Github:
1. Create a folder named “Exercise 2.7” in your “Achievement 2” folder on GitHub.
2. Upload the “Task-2.7” document.
3. Upload the “test-outcome.jpg” screenshot (from Step 4) in the “screenshots” subfolder.

- Upload code to Githib:

Push your code in the src folder to the Recipe application GitHub repository that you created previously.


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