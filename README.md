# UMS - University Management System

### [Live Site](https://univ-mngr.herokuapp.com/) 👈

#### This is Course project for CS-207. Build by group- G3 

Kuldeep Singh 190001030  
Krishanu Saini 190001029  
Deepkamal Singh 190001011  
Rahul Kumar 190001049  
<hr>

Visit any of two links for live demo. Frontend and Backend working.
https://univ-mngr.herokuapp.com/ and https://krishdevtools.pythonanywhere.com 

![index1](https://user-images.githubusercontent.com/65676476/103832796-4311d480-50a5-11eb-9b16-b27b2dcd7189.png)
![index2](https://user-images.githubusercontent.com/65676476/103832798-45742e80-50a5-11eb-87d1-53f70a1cf153.png)
![index3](https://user-images.githubusercontent.com/65676476/103832800-460cc500-50a5-11eb-9533-4101b3e7eedd.png)
![index4](https://user-images.githubusercontent.com/65676476/103832801-46a55b80-50a5-11eb-96ae-9fc8104b5acb.png)
![index5](https://user-images.githubusercontent.com/65676476/103832803-473df200-50a5-11eb-92df-6aaa25e8756d.png)
![admincourse](https://user-images.githubusercontent.com/65676476/103832804-47d68880-50a5-11eb-9df0-12ae1a71c969.png)
![faculty signup](https://user-images.githubusercontent.com/65676476/103832807-47d68880-50a5-11eb-9228-b2bd2251f3ec.png)

### Clone this project  

## Installing Requirements  
      1. Mysql (preferably use Mysql Workbench 8.0)  

      2. Python 3.7 / 3.6 ( Not compatible with python 3.9 )  
      2. Python 3.8 / 3.7 / 3.6 ( Not compatible with python 3.9 )  
 <br ><br ><br > 
        
## STEP 1  ( IMPORTING MYSQL DATABASE)
      1. Imporing export.sql in /sqldump folder to test database  
      
      2. Changing host / port / password / database name in db.yaml  
      
       Note the above step is necessary to ensure database works on your system 
<br ><br ><br >

## STEP 2  ( STARTING FLASK SERVER )  
### WINDOWS -- EVERYTHING IS AUTOMATED  

      Double click on makefile.bat -> will do all steps below  
        
      Ensure you are using python 3.7 and db.yaml is edited


### MANUAL  

      if possible use venv

      pip install -r requirements.txt

      Ensure you have edited db.yaml and imported mysql  

      Run the application by executing the command python app.py

      Use python 3.7 u

      The application runs on localhost:5000
