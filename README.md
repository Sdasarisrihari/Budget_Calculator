# PHP-Budget-Calculator
This is a Simple Budget Calculator  web application Project

## How To Run the Project

To run this project, you must have a virtual server such as XAMPP installed on your PC.

### Steps to Run the Project:

 **Install XAMPP**:

 - If you haven't already, download and install XAMPP from here 
    ``` 
   (https://www.apachefriends.org/index.html).
    ````
- Once it downloaded Start the application.
- Start Apache and MySQL from the XAMPP control panel.

**Extract the Project Files**:

- Download and extract the project files from the archive.

**Copy the Main Project Folder**:

- Copy the extracted project folder.\

**Paste the Project Folder**:

- Navigate to `C:/xampp/htdocs/` and paste the project folder into the `htdocs` directory.

**Open Your Browser**:

 - Launch your preferred web browser (e.g., Chrome, Firefox).

#### Connecting the Database:

 **Open phpMyAdmin**:

-  Open your browser and go to the URL: 

   ``` 
   http://localhost/phpmyadmin/`
`  ```

 **Create a Database**:

- Click on the **Databases** tab.
- Create a new database with the name `budget_calculator`.

**Import the SQL File**:

 - After creating the database, click on the **Import** tab.
 - Click on **Browse** and select the `budget_calculator.sql` file from the project folder.
 - Click on **Go** to import the database.

##### Running the Application:

**Run the Project**:

 - Open your browser and navigate to  

    ``` 
    http://localhost/PHP-Budget-Calculator/
    ````
    to start the application.

 ###### Troubleshooting:

  - If the application doesn't load, make sure:
  - XAMPP’s Apache and MySQL services are running.
  - The project folder is correctly placed in the `htdocs` directory.
  - The database was imported successfully.
