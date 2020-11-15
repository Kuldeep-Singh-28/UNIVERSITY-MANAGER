Clone this project  
  
## Installing Requirements  
      1. Mysql (preferably use Mysql Workbench 8.0)  
      
      2. Python 3.7 / 3.6 ( Not compatible with python 3.9 )  
      
        
## STEP 1  ( IMPORTING MYSQL DATABASE)
      1. Imporing export.sql in /sqldump folder to test database  
      
      2. Changing host / port / password / database name in db.yaml  
      
      " Note the above step is necessary to ensure database works on your system "


## STEP 2  ( STARTING FLASK SERVER )  
### WINDOWS -- EVERYTHING IS AUTOMATED
      Double click on makefile.bat -> will do all steps below


## MANUAL  

      if possible use venv

      pip install -r requirements.txt

      Change the password in db.yaml to that of your MySQL's password

      Run the application by executing the command python app.py

      The application runs on localhost:5000
