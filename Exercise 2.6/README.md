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

  1. Toggle the terminal ON in VSCode and follow the steps to run the server:

    a. Navigate to A2_Recipe_App/src.

    b. Activate the virtual environment: a2-ve-recipeapp.

    c. Execute runserver.

  2. Head to the browser and follow a typical user journey:

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
  