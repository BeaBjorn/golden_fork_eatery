# Created by : Beatrice Björn
## Date : 2022-08-21 

This repository contains an API with full CRUD finctionality connected to a MySql database. 

## Consuming API
The API is open and available for anyone to use as the like.   

### **INSTALL**
| Files | Description |
| --- | --- |
| install.php |  Installing the database tables|

### **API**
| Files | Description |
| --- | --- |
| config.php |  Connection to database, activating error messages when in devmode and auto including classes |
| head.php | Header settings for API and check for present id.|
| rest_about.php |  Full CRUD functionality for the database table aboutUs |
| rest_admin.php |  POST-request |
| rest_alcohol.php |  Full CRUD functionality for the database table aboutUs alcohol |
| rest_appetizers.php |  Full CRUD functionality for the database table aboutUs appetizers |
| rest_booking.php |  Full CRUD functionality for the database table aboutUsbookings |
| rest_desserts.php |  Full CRUD functionality for the database table aboutUsdesserts |
| rest_hotDrinks.php |  Full CRUD functionality for the database table aboutUs hotDrinks |
| rest_mains.php |  Full CRUD functionality for the database table aboutUs mains |
| rest_noAlcohol.php |  Full CRUD functionality for the database table aboutUs noAlcohol |

### **Classes**
| Files | Description |
| --- | --- |
| About.class.php |  Methods for full CRUD functionality for database table aboutUs and validation of data |
| Admin.class.php | Methods to login user by comparing input fields to database and validating input fields|
| Alcohol.class.php | Methods for full CRUD functionality for database table alcohol and validation of data|
| Appetizer.class.php | Methods for full CRUD functionality for database table apetizers and validation of data |
| Booking.class.php | Methods for full CRUD functionality for database table bookings and validation of data |
| Dessert.class.php |  Methods for full CRUD functionality for database table desserts and validation of data |
| HotDrink.class.php | Methods for full CRUD functionality for database table hotDrinks and validation of data |
| Main.class.php |  Methods for full CRUD functionality for database table mains and validation of data |
| NoAlcohol.class.php |  Methods for full CRUD functionality for database table noAlcohol and validation of data |
 

### **Json-object**  
{  
    "id" : 1,   
    "titel" : "About Us",   
    "info" : "Information about the company"    
}    



### Username and password  
Användarnamn : admin  
Lösenord : password



