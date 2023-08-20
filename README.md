# Inventory Management System

Bulit a java application for inventory management of a store using NetBeans IDE and connecting the frontend to an Oracle Database (Oracle 11g).

Stock details, Supplier details, Employee details are kept track of in the database. 
Admin and Staff personnel have varied privileges.  
Billing function updates the stock and invoice is generated as a pdf.

## Setting up the environment and adding libraries
Download Netbeans IDE (We have used Netbeans IDE 8.2)
Download Oracle 11g and setup sqlplus. Set userid and password.

Execute the commands in the "CreateTables.txt" file in sqlplus Command Line Client one-by-one for creating the necessary tables for the application.

Open the project folder using the IDE.
On the left, below a line of icons, you will see- Projects, Services, Files.
Click on Services.
Under Services, right-click on Drivers and add the "ojdbc8.jar" file which you can find in the "JAR FILES" folder of this repository.
Now, under "Drivers" you will see "Oracle Thin". Select "Oracle Thin". In the window that opens, replace the userid and password with your localhosts's userid and password and click on "Finish"

This should connect your application to the database.

Under the Projects section in the left side, click on Libraries and add all the jar folders which are available in the "JAR FILES" folder of this repository.

## To run the application:

Under the Projects section, in the project folder, navigate to "Source Packages"->"MainFiles". 

Run the file named "Homes.java"

You are now good to go!

For a complete application walkthrough and other implementation details, please check out the Project Report and the Program Walkthrough documents!
