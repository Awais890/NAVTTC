# Installing Xampp for wordpress

step-by-step text guide to installing XAMPP and WordPress on a Windows computer:

1- Install XAMPP:

    - Download the latest version of XAMPP from the official website
      https://www.apachefriends.org/
    - Double-click the downloaded installation file to launch the XAMPP installer.
    - Follow the on-screen instructions and select the components you want to install (Apache, MySQL, PHP, phpMyAdmin).
    - Choose the installation directory (e.g., "C:\xampp") and complete the installation process.
    - Start the XAMPP Control Panel.

2- Prepare XAMPP for WordPress:

    - In the XAMPP Control Panel, start the Apache and MySQL services by clicking the "Start" buttons next to their names.
    - Open your web browser and navigate to "http://localhost/phpmyadmin" to access the phpMyAdmin interface.

3- Create a User and Database for WordPress:

    - Open your web browser of choice and type in the URL 'localhost/phpMyAdmin' and press enter.
    - In phpMyAdmin click on user accounts and then 'add user account'.
    - Type in your username and password of your choice along with retry password.
    - Scroll down to the section "Database for user accounts"
    - Select both the option 
        - Create database with same name and grant all privileges.
        - Grant all privileges on wildcard name (username\_%)
    - Scroll down to the section "Global privileges" and click on check all. 
    - After performing all the above actions scroll down to the bottom of the screen and click on the button "Go" to execute the command and create a new user alone with its database. 

4- Download WordPress:

    - Visit the official WordPress website (https://wordpress.org/) and download the latest version of WordPress.
    - Extract the downloaded WordPress ZIP file to a location of your choice (e.g., "C:\xampp\htdocs\wordpress").
    


5- Install WordPress:

    Open your web browser and navigate to "http://localhost/wordpress".
    Select your preferred language and click the "Continue" button.
    On the next screen, WordPress will display some information about the database connection.
    Provide the details we've create earlier, i.e. 
        In the database & username field enter the username we created in 'phpMyAdmin'
        In the password field enter the password
        and then click on to continue. 
    
    Click the "Submit" button.
    On the next screen, click "Run the installation" to proceed.
    Provide the required information, such as site title, username, password, and email address.
    Click the "Install WordPress" button.
    WordPress will install and show you a success message.
    Accessing WordPress:

    After installation, you can access your WordPress site by visiting "http://localhost/wordpress" in your web browser.
    Log in with the username and password you provided during the installation process.
    You can now start customizing your WordPress site and building your content.
    That's it! You have successfully installed XAMPP and WordPress on your Windows computer. Now you can develop and test your WordPress website locally before deploying it to a live server.