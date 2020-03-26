# mysql2c

## How does it work ? 

mysql2c provides a simple to use Interface, in order to obtain and update Database Information for a MySQL database (CRUD Operations). 
It will automatically convert all Database Tables into PHP Classes. It will also provide an object oriented array of all the Database data in each class. It can then be used to manipulate the data from an object, and the library will automatically update the Data in the corresponding database entry, which will save you a tremendous amount of time, because no more SQL queries are needed. 

## Explanaiton 

See the following Graphic for a better understanding of how the library works. 

## Installation 

simply require the provided autoloader.php file. 

## Initialization  

Before you can use mysql2c it has to create the PHP Class Files first. To do this call $mysql2c->createClasses(); 
This will create all neccessary class files in /classes folder, and create an autoloader for it. 

## Loading Data 

At the start up of your application call $mysql2c->loadData(); 
This will load all entries from your Database into a array for each table. 
