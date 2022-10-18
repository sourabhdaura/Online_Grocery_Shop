# Online_Grocery_ShopGrocery Store Management System Python Database Project
The objective of this python project is to design a GUI for the Grocery store Management System which incorporates details of the Employees, the Manager, the Designation of the employees, the categories of the products, the details of the Customer, and a list of available commodities, and location information of the grocery stores.

Suppliers and details of commodities which shows which items are going to be out of stock for the store which has various branches situated in various areas with different Managers taking care of that data set.

This database is efficacious in running the grocery stores. The users of the database will be the store managers.

Grocery Store Management System is designed to provide the grocery stores with the benefit of having everything online, from products data to customers data.
It helps the store managers to perform various functions like checking the products stock, suppliers information, customers information and also allows them to check if a particular product is available in any other branch.
It also helps to keep track of the store employees.
Provides a user-friendly interface where everything can be accessed with just a button click.
Database
Created views using joins to have a virtual table that can be accessed anytime.
Created a table for login credentials that allow only the managers of the store to access the database.
We have used the database queries effectively and carefully to implement the insert, update, delete and search. We have also used a view to join our tables and view the records. A database with the name grocery store has been created.
In Grocery store management, we have the following tables which will store the corresponding data

Database table Design for Grocery Store Management System

Location

The Location table has records of the location information of the grocery stores. For now, we have defined grocery stores in 20 locations.

Employees

The employee’s table has records of the Employees working in the grocery store. As we have defined our model to have managers for each store and they exclusively have the access to the database of the grocery store (DB Users), for now, we have defined all the managers for all the grocery stores listed in the Location table.

Designation

The Designation table has various records of different designations applicable/available in the grocery store.

Customers

The Customers table holds the details of the customer

Manager

The Manager table holds the details of the employee

DB Users

DB Users are the Managers

Commodities

The Commodities table holds the details of various products such as the product number, product name, product quantity, and product price. 

Suppliers

The Suppliers table holds the details of the product suppliers

Categories

The Categories table holds the details of the Product categories

GUI

The GUI for our project, the Grocery Store Management system is built using Python Tkinter. We have created GUI for all our tables, where we can perform operations, such as INSERT, UPDATE, DELETE, and SEARCH on all the tables of our Grocery Store database. 

Database connection to GUI
 To establish a connection to the database and GUI the following syntax needs to be used.              

Here, I have used the credentials of my localhost database connection, however, one has to replace it with the credentials in their system. By using this, the user can connect to the database and a GUI will be displayed accordingly.

Description of GUI
The main.py file has to be run, in which all the other modules are imported. Each module is for each table in our database. Main.py holds everything and it directs us to different modules with the help of buttons. When we run “main.py”, a login window, where we have to enter the credentials will be displayed and will only take you inside, if you enter valid credentials. If the credentials are correct, then a window is displayed with image buttons for all our tables.

When we click on each button, it will be redirected to the respective module, and a connection is established with the database. To establish a successful connection with the database “grocery store”, it should be available in our system.

