# MyEcommerceBackEnd

This application allows users to create a simple ecommerce database and use GET, POST, PUT, and DELETE methods to view and manipulate data.
The express server interacts with the MySQL database using sequelize models that represent fields and records in the tables.
Fields and records are returned as json objects containing field keys and record data.
## To use the application: 
1. Change your directory into "db", run mysql -u root -p
2. Enter the password
3. Run source schema.sql to create the database
4. Exit MySQL
5. Change your directory to the root folder and run node seeds/index.js to populate the database
6. Run node server.js
7. You may now send GET, POST, PUT, and DELETE requests to the server which will manipulate data in the database
8. If the server cannot complete your request, it will present an error as a json object

## Tutorial Video
Checkout my YouTube video for a walkthrough on using the application.<br>
YouTube Video: [Link](https://www.youtube.com/watch?v=vj2rYDs0Fos)
