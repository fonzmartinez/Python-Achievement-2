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