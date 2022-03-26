# Data-Collector-Web-App-Development-using-Flask-and-PostgreSQL
This repository consists of the python files and PostgreSQL database related files which are used to create a PostgreSQL database and Data Collector web application.
Once DB is created and Web App is created, user can enter his/her active mail ID and height in cm (This will be stored in the database) then user will be able to see a UI screen with message 'Thank you for your submission. You will recieve email with the survey results shortly'.
The user will recieve a mail mentioning his height in cm and average height of all the people in the DB along with number of people in the DB.
For ex. if user enter his active mail ID and height as 145 cm, then he will recieve mail as follows:

'Hey there, your height is 145. Average height of all is 167.9 and it is calculated out of 15 people'

Files 'Final_UI_Page1' and 'Final_UI_Page2' are the screenshots Final UI screens. Screenshot of the email recieved - 'Final_Generated_Sample_Email' also attached.

(Please enter active email ID and valid password (from which email will be sent) in the send_email.py python file. I have hidden password of my email in this file)

Steps of developing this application:

1. While developing app, we can either start from Front End or from Back End. Here I built FrontEnd first
2. So initally, HTML and CSS part was built
3. Next, basic structure of flask application built. Then, validated the user input. (This step was intentinally done without database)
4. Then I created postgreSQL database followed by a table
5. Once database and table was ready, I fetched the input from Frontend using Python and sent them to table and save them
6. Now I wanted to send the average height of the people we have in our table to the user. So, average height was calculated.
7. Then email having average height was generated and sent to the user on email mentioned by him.
8. This application then deployed on web
