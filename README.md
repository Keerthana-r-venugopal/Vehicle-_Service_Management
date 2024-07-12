# Overview
Vehicle Service Management is a web-based application developed using PHP and HTML. The system is designed to streamline the process of managing vehicle service requests, tracking service history, and maintaining records efficiently. It includes both an admin page and a user page, allowing for comprehensive CRUD (Create, Read, Update, Delete) operations.

# Features
Admin Page :<br>
<br>
» Dashboard: View overall statistics and summaries of vehicle services.<br>
» Manage Users: Create, read, update, and delete user accounts.<br>
» Manage Services: Oversee service requests, update statuses, and maintain service records.<br>
» Service History: Access and manage historical data of all vehicle services.<br>
» Notifications: Send and manage notifications to users regarding their service status.<br>
<br>
User Page :<br>
<br>
» Service Request: Users can create new service requests for their vehicles.<br>
» View Service Status: Check the status of ongoing service requests.<br>
» Service History: View past service records and details.<br>
» Profile Management: Update personal details and manage user profiles.<br>
# Technologies Used
» PHP: Server-side scripting to handle backend logic and database interactions.<br>
» HTML: Structuring and presenting the content on the web.<br>
» MySQL: Database management for storing and retrieving data.<br>
# Installation
Clone the Repository :<br>
<br>
git clone (link of your repository) <br>
cd Vehicle_Service_Management<br>
# Set Up the Database
Create a database named vehicle_service_management.<br>
Import the SQL file located in the db folder to set up the necessary tables.<br>
<br>
Configure Database Connection :
Open the config.php file located in the root directory.<br>
<br>
Update the database credentials :<br>
<br>
»<?php<br>
 $servername = "localhost";<br>
 $username = "your_db_username";<br>
 $password = "your_db_password";<br>
 $dbname = "vehicle_service_management";<br>
 ?><br>
<br>
