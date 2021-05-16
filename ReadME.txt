In this repository there will be a jar file in which you can run the java application
There is some setup that needs to be done if you choose to test the application. First 
you need to install PostgreSQL https://www.postgresql.org/download/ Once downloaded 
continue to the setup. When it asks you for a username keep the default one. For password
put whatever just remember it. Any other installation setup just keep the default items.
Once you have it installed there should be a program called pgadmin 4 which will allow you
to manage your databases. Here create a database called whatever you want. Use the sql files
in the repository to load tables and data into the database. First use RelationalSchema.sql
then SampleData.sql. Once you have that setup the you can run the SmartParking.jar which is 
like an .exe application. Here enter the database credentials. There is some examples of what 
it should look like. For username it should be postgres as long as you left that part alone 
in the installation. The url should be something like this jdbc:postgresql://localhost/NameofDatabase
Once you have that then the rest of the application should be self explanatory.

If you wish to use Eclipse to run the project instead of the jar file you can use the ParkingApplication
folder which has all the files you need to run the application. Here you would load all the files provided 
in Eclipse and then the DBLogin.java would be the starting file to run the application

The github repository link is https://github.com/sechevarria98/SmartParking
Here you can also get the files needed. However, all the files should be provided in the 
Group_10_project.zip file. Use the sql files to navigate the application specifically with the login page
with the userLogin table. This table will hold the username and password for all users.
