# Fitness App Coursework
#Logging in

The first screen accessed by the user is a laoding screen which checks the login state of the user.
If they are not logged in then they are routed to the Login Page
On the login page they are prompted to enter username and password for authentication

If they do not have an account they can click the link to the Sign Up page
Here they can enter a username, email and password and sign up for the app

#Dashboard
This is seen as the home page of the app which is protected and only logged in users can access
From here they can access the app's other pages

#BMI calculator
The BMI calculator takes the value set by the two sliders: Height and Weight
From here the BMI is calculated once the user hits enter
Their BMI will be displayed on screen with a traffic light system for the output message
depending on if the users BMI shows that they are under, over, of healthy weight or obese

#Running Log
The app is aimed at runners to track their run times.
In the running log they can enter the day of the run to identify it
and then the run time.
users can enter new run logs which will populate at the bottom of the log.
Or they can edit pre existing logs
Or they can delete logs.
The logs are added to an SQL database that the app is connected to.
