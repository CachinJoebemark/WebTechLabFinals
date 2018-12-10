***Setup***
--Node Admin & Super Admin--
-> Node must be installed in the user's system.
Link: https://nodejs.org/en/download/
-> To check if node is installed type in the command promt node -v
-> In order to access phpmyadmin, run xampp then start Apache and MySQL only.
-> Click the Admin button inline with MySQL and import the sql file(transient.sql)
   into your phpmyadmin.

# You may also access phpmyadmin by entering "localhost/phpmyadmin/" or 
  "localhost:*port*/phpmyadmin/".

# If the Apache and/or MySQL server would not run in xampp, the ports are being used
  by another application. To solve this problem click on the config button on the right
  side then click on Service and Port settings. Change the main port to 8080 and SSL port
  to 4433. After that click on MySQL beside Apache and change the port to 3307 then click
  save. Try accessing Apache and MySQL again.


To run the application:
1.) Go to command promt
2.) Change directories to the folder of the application
ex. C:/user/User/Desktop/HouseRental
3.) Run the code "npm i npm" to ensure that npm is up to date
4.) Install nodemon by running the code "npm install nodemon -g"
5.) Run the application by typing "nodemon" in the command promt
6.) Access the application through a web browser via localhost and port given
ex. 127.0.0.1:5000



--PHP Client--
-> Just as Node Admin & Super Admin, the database must be imported into phpmyadmin.
   If the database has been imported you may proceed to run the application.

To run the application:
1.) Start xampp in the user's system and start both Apache and MySQL
2.) Access the application through a web browser
3.) Enter localhost/transient/index.php