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
