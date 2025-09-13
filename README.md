<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Leftover Food to Poor - Food Waste Management</title>
</head>
<body>

<h1>Leftover Food to Poor</h1>
<!-- <img src="img/coverimage.jpeg" alt="Cover Image"> -->

<p>
  The basic concept of this project, <b>Food Waste Management</b>, is to collect excess or leftover food from donors such as hotels, restaurants, marriage halls, and individuals, and distribute it to needy people.
</p>

<h2>Tools and Technologies</h2>
<ul>
  <li><b>Frontend:</b> HTML, CSS, JavaScript</li>
  <li><b>Backend:</b> PHP</li>
  <li><b>Web Server:</b> XAMPP</li>
  <li><b>Database:</b> MySQL</li>
</ul>

<h2>System Modules</h2>
<ul>
  <li>User</li>
  <li>Admin</li>
  <li>Delivery</li>
</ul>

<h3>User Module</h3>
<p>
  The User module is designed for people who wish to donate their excess or leftover food to help reduce wastage. 
  Users can register, log in, and donate food by selecting the type and quantity. The system will match their donation with the nearest needy people or organizations. 
  Users can also view their past donations. This information is shared with the Admin module for further processing.
</p>

<h3>Admin Module</h3>
<p>
  The Admin module is designed for NGOs, trusts, and charities registered on the platform. 
  Admins receive information about food donations from users and list them for NGOs and charities to choose from. 
  Admins can view and manage donations, track requests, and record which organizations have taken which donations. 
  NGOs can request a pickup, which will be assigned to the Delivery module.
</p>

<h3>Delivery Module</h3>
<p>
  The Delivery Person module is for individuals who provide pickup and delivery services. 
  Delivery personnel can register, view pickup and drop-off details, and ensure that food donations are delivered safely to the requesting NGOs or charities.
</p>

<p>
  Overall, the <b>Food Waste Management System</b> ensures efficient management of excess food. 
  The User module collects donations, the Admin module organizes them, and the Delivery module ensures distribution. 
  This system reduces food wastage and helps needy people.
</p>

<h2>Module Illustrations</h2>
<h3>User</h3>
<!-- <img src="img/User-module.jpg" alt="User Module"> -->
<img src="img/mobile.jpg" alt="User Mobile">

<h3>Admin</h3>
<img src="img/Admin.jpg" alt="Admin Module">

<h3>Delivery</h3>
<img src="img/Delivery_module.jpg" alt="Delivery Module">

<h2>Features</h2>
<ul>
  <li>Mobile-friendly responsive design</li>
  <li>Chatbot support</li>
  <li>Secure login</li>
</ul>

<h2>Mobile-Friendly Website</h2>
<img src="img/responsive.gif" alt="Responsive Design">

<h2>Chatbot Support</h2>
<img src="img/chatbotsupport.jpg" alt="Chatbot Support">

<h2>Secure Login</h2>
<img src="img/hash-flow.png" alt="Secure Login">

<h2>How to Run</h2>
<ol>
  <li>Download the project zip file</li>
  <li>Extract the file and copy the folder</li>
  <li>Paste it inside the root directory (<code>xampp/htdocs</code> for XAMPP, <code>wamp/www</code> for WAMP, <code>var/www/html</code> for LAMP)</li>
  <li>Open PHPMyAdmin (<a href="http://localhost/phpmyadmin">http://localhost/phpmyadmin</a>)</li>
  <li>Create a new database</li>
  <li>Import <code>demo.sql</code> (inside the database folder)</li>
  <li>Run the project at <code>http://localhost/folderName</code></li>
</ol>

<h2>View Project</h2>
<a href="https://krishna-045.github.io/food-donate/index.html" target="_blank">View Demo</a>

</body>
</html>