# Exercise Tracker

## Requirements 
pip install requests     

## What is Exercise Tracker?
Exercise Tracker tracks the user workouts using requests, os, and datetime python modules; and google sheets.

## How does it work?

Step 1 - Setup API Credentials and Google Spreadsheet
 <ol>

  Go to [this link](https://docs.google.com/spreadsheets/d/1DHL6Y8XAHSC_KhJsa9QMekwP8b4YheWZY_sxlH3i494/edit#gid=0) and create a copy of the My Workouts Spreadsheet. 
  
  <img width="560" alt="Screenshot 2023-12-23 at 8 37 04 PM" src="https://github.com/CoboAr/Exercise-Tracker/assets/144629565/ce93ffce-296f-44a9-a2cc-e8f9d912bfdb">
  
  Go to [the Nutritionix API website](https://www.nutritionix.com/business/api) and select "Get Your API Key" to sign up for a free account.
  
  <img width="558" alt="Screenshot 2023-12-23 at 8 43 49 PM" src="https://github.com/CoboAr/Exercise-Tracker/assets/144629565/0ecb32be-b068-4adc-9479-bee062f4e868">

Once logged in, you should be able to access his API key and App id:
<img width="559" alt="Screenshot 2023-12-23 at 8 49 58 PM" src="https://github.com/CoboAr/Exercise-Tracker/assets/144629565/b34117b9-4e02-498a-8e28-8e304a0ffb5a">

Store API key and App id as environmental variables.
  
 </ol>
Step 2 - Get Exercise Stats with Natural Language Queries   

Step 3- Setup Google Sheet with Sheety
<ul>
<li>
   Log into Sheety with the same Google Account that was used to copy Google Sheet in step 1. The user needs to give Sheety permission to access your Google sheets. If this step is missed, log out of Sheety and log in again.
Under Google Account Security settings, the user should make sure that Sheety has access.
</li>
  
<li>
   In  project page, click on "New Project" and create a new project in Sheety with the name "Workout Tracking" and paste in the URL of your own "My Workouts" Google Sheet.
</li>
<img width="304" alt="Screenshot 2023-12-23 at 9 37 02 PM" src="https://github.com/CoboAr/Exercise-Tracker/assets/144629565/f41358ac-dab4-4f05-bc55-6fec82c3ebe3">
<li>
   Click on the workouts API endpoint and enable GET and POST.
</li>
<img width="532" alt="Screenshot 2023-12-23 at 9 39 45 PM" src="https://github.com/CoboAr/Exercise-Tracker/assets/144629565/21944ce0-aebf-4abc-99e5-e52336f72997">
</ul>
Step 4 - Save Data into Google Sheets    

Step 3 - Authenticate Sheety API
<ul>
  <li>
    The user can choose either "Basic Authentication" or "Bearer Token" to Sheety endpoint to secure it. I have chosen Bearer Token Authentication.
  </li>
  <img width="1432" alt="Screenshot 2023-12-23 at 9 54 39 PM" src="https://github.com/CoboAr/Exercise-Tracker/assets/144629565/930d0620-84a9-439d-a8a8-6ff979ff0dfa">
</ul>


## Demo
https://github.com/CoboAr/Exercise-Tracker/assets/144629565/d52c99fd-04c3-4e84-bb02-32685d7b6c65

Enjoy! And please do let me know if you have any comments, constructive criticism, and/or bug reports.
## Author
## Arnold Cobo
