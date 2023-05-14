<h1>Registration Form</h1>

<p>This is a simple registration form application implemented in Java using Swing for the graphical user interface and JDBC for database connectivity. The application allows users to create a new account by providing their name, email, phone number, address, and password.</p>

<h3>Prerequisites</h3>
<ul>
  <li>Java Development Kit (JDK) installed</li>
  <li>MySQL Database Server installed and running</li>
  <li>IntelliJ IDEA or any Java IDE</li>
</ul>

<h3>Setup</h3>
<ol>
  <li>Clone or download the project files from the repository.</li>
  <li>Open the project in your Java IDE (e.g., IntelliJ IDEA).</li>
  <li>Make sure to include the required JDBC driver library for MySQL in your project's dependencies.</li>
  <li>Update the database connection details in the addUserToDatabase method of the <b>'RegistrationForm'</b> class to match your MySQL server configuration:</li>
    <ul><b>DB_URL:</b> The JDBC URL for your MySQL server. Update the hostname, database name, and timezone if necessary.</ul>
    <ul><b>USERNAME:</b> The username to access your MySQL server.</ul>
    <ul><b>PASSWORD:</b> The password for the specified username.</ul>
</ol>

<h3>Running the Application</h3>
    <ol>
        <li>Locate the main method in the RegistrationForm class.</li>
        <li>Right-click on the main method and select "Run" to start the application.</li>
        <li>The registration form window will appear.</li>
        <li>Fill in all the required fields: name, email, phone, address, and password.</li>
        <li>Click the "Register" button to submit the registration form.</li>
        <li>If the registration is successful, the user's details will be stored in the MySQL database, and the application will display a success message.</li>
        <li>If any fields are empty or the password confirmation does not match, an error message will be displayed.</li>
        <li>Click the "Cancel" button to close the registration form without registering a new user.</li>
    </ol>

<h3>Database Schema</h3>
<p>The application uses a MySQL database named "registration" with a table named "users" to store user information. The table has the following columns:</p>
<ul>
    <li><b>id</b> (INT): Auto-incrementing unique identifier for each user.</li>
    <li><b>name</b> (VARCHAR): User's full name.</li>
    <li><b>email</b> (VARCHAR): User's email address.</li>
    <li><b>phone</b> (VARCHAR): User's phone number.</li>
    <li><b>address</b> (VARCHAR): User's address.</li>   
    <li><b>password </b>(VARCHAR): User's password.</li>
</ul>

<h3>Dependencies</h3>
<ul>MySQL Connector/J: A JDBC driver for MySQL. Make sure to include this library in your project's dependencies.</ul>

<h3>Note</h3>
<ul>The application's database connection assumes the default MySQL server configuration with the username "your username" and password "your password". Update these credentials if required.</ul>

<p>Feel free to modify and enhance the code as per your project's needs.</p>