# Image-Op

steps to run this project:
1. Clone this Project
   
https://git-scm.com/docs/git-clone

2. Create a Database (or in existing one) Insert the name.sql database.


"""


First, log in to the database as root or another user with sufficient privileges to create new databases:

mysql -u root -p

This will bring you into the MySQL shell prompt. Next, create a new database with the following command. In this example, the new database is called new_database (or your own name):

CREATE DATABASE new_database;

You'll see this output confirming that it was created.

Output
Query OK, 1 row affected (0.00 sec)

Then exit the MySQL shell by pressing CTRL+D. From the normal command line, you can import the dump file with the following command:

mysql -u username -p new_database < name.sql

username is the username you can log in to the database with
newdatabase is the name of the freshly created database
data-dump.sql is the data dump file to be imported, located in the current directory



"""

3. Change the Database configuration in __init__.py file

4. Make sure your Virtual environment is running for flask.

5. install all the requirement using: pip install requirement.txt

6. Run the Project using "python __init__.py"
