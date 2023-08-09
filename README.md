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