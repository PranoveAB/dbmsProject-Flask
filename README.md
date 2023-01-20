# Steps to Run the Project

1. Unzip the project, and open the project in Visual Studio Code (You can download it from here: https://code.visualstudio.com/download)
2. Download the latest version of python from here: https://www.python.org/downloads/)
2. Open the terminal in Visual Studio Code and run the command "pip3 install -r requirements.txt". If this command doesn't work, try "pip install -r requirements.txt". This will install all the required libraries and dependencies.
3. Using MySQL Workbench, create a database named "dbmsprod" and import the dump file "SqlDump.sql" into the database.
3. In the file app.py, change the value of the database connection credentials to your own database credentials. Set value of db to "dbmsprod" and set the value of user and password to your own database credentials.
4. Run the command "python3 app.py" or "python app.py" to run the project.
5. Open the browser and go to the URL "http://localhost:5000" to view the project.
