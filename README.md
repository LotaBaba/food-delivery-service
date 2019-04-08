# food-delivery-service
web application by spring boot
DOCUMENTATION
This Food delivery service is basically an web application which purpose is to manage foods and restaurants so that customers can order desired foods from their home and get them whenever they want. So the main purpose is to release the workload and time of peoples who just wants food without going to restaurants. In order to do that in this web service , it manages the restaurants and foods and their native price and in the admin end there is controller where the admin can add restaurants , foods and also change the price. So this is the main purpose of my web application.
Implementation
This web app is developed in the java language and mainly user spring boot framework for the servlet part . moreover, this app follows the MVC model which refers that model view controller.
First of all the model is referring to database side of the app where we can see that how the classes such as food and restaurants are connected to each other. Which is done with hibernate framework for creating a relational database and with the help of spring boots java persistence library class to annotate the entity , primary and foreign keys and relations.
Next, the view part which is basically we see in the browser in user and admin end is built with html, css, JavaScript in the login page and thyme leaf for supporting java attributes.
Lastly, the controller part is connector between model part means the database part and the view or html part where user request for a input or output and  goes to the controller and by judging the request the controller retrieve the data or make changes in the data base .
Moreover, the backend code completely written in java 1.8 version supported java language .further, there are raw classes of restaurants ,food, card, role, user etc. where encryption is presented by the getter and setter methods and keeping the variables in private. There are also controller class which execute the functional methods of those above mentioned classes . also there are service classes which helps methods to retrieve data or manipulate data in the database. Service classes are autowired by the extends version of crud repository interface which is built in interface of spring boot to do the CRUD means create, read, delete, update operations . 
Thus the whole project is supported by gradles and converted into jar . mysql database is used here 
Reference
https://www.youtube.com/watch?v=msXL2oDexqw&list=PLmbC-xnvykcghOSOJ1ZF6ja3aOgZAgaMO by java brains
https://www.youtube.com/watch?v=Ch163VfHtvA&list=PLsyeobzWxl7oA8QOlMtQsRT_I7Rx2hoX4 by teluska
https://hellokoding.com/registration-and-login-example-with-spring-security-spring-boot-spring-data-jpa-hsql-jsp/?fbclid=IwAR1mziXArku7CTdZ51G1famLWityi4O6QowRktdhpSuDSNTmJIV_tWyt1xs
https://www.baeldung.com/spring-boot-crud-thymeleaf
