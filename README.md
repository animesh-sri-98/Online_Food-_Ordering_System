# Food Ordering System


How To Run -
---------

1. Install Xampp
2. Download and Unzip the project folder and copy it.
3. Go to C drive--> xampp--> htdocs--> paste the project folder
4. Run xampp.
5. Click on "Start" button in front of apache, mysql, filezilla.
6. Click on "Admin" button in front of mysql which will open php MyAdmin in the browser.
7. Create a Database with the name "food".
8. Click on Import , browse and select food.sql script provided in sql folder. This will import all the tables.
9. Type : localhost/Project_Folder_Name/login.php to run the application in browser.
 login: user1
 password: pass1
Note -
---------
1. This is not ready for PRODUCTION.
2. The username and password of sample users are stored in table `users`.
3. Only Customers with "Verified" status can place orders using "Cash on Delivery" option.
4. By default a new customer gets 2000 coins in Wallet on signing up, and a fake Credit card number & CVV number is generated and stored in SQL Table "wallet_details" with corresponding new customer's ID.
5. Use that Card Number & CVV while placing an order, else order won't be successful or use "Cash on delivery" option.
6. What's lacking? Dynamic payment(real payment system) and error reporting lacks in this project. And also one might wish for showing corresponding food item's photo and all that stuff.
