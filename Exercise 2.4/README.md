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
