# Easyrecipes

Easy recipes is a web application for healthy recipes meals, snacks, drinks, and desserts. This is a front-end and back-end application. In the front-end, our customers can see all the recipes and the corresponding information such as ingredients, category, time to prepare, the chef that published the recipe, and a description of how that the customer should cook the food. Also when the customer clicks on the chefs button on the navigation bar, they can find more information about the chef including their name, specialty, years of experience and who is employed on the easy recipes team. To go to the back end area, the admin should sign-in first with a username and password and if the data is correct the admin can have access to Create, Read Update and Delete (CRUD) recipes and CRUD chefs and it is possible to create, edit, add and delete chefs or recipes. I developed this web application using languages such as HTML, CSS, C#, .NET CORE MVC, bootstrap, and azure database.


Run database:

add-migration -Context ApplicationDbContext initial
add-migration -Context AppIdentityDbContext Initial
update-database -Context AppIdentityDbContext
