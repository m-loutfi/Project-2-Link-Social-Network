# Project 2: Link Social Network


## Project Description

Link Social Network is old school "Facebook" type of application with basic social media functions. A platform where users can potentially connect with each other online when they are not able to in person. Link has nice features like creating posts with images and youtube links. Also, there is a live chatroom to communicate with other online users!
## Technologies Used
* Tomcat
* Angular
* Hibernate
* Spring
* Java
* S3 Buckets (AWS)  
* SQL
## Features
List of features ready and TODOs for future development
* Create a User account
* Login/Logout and edit User info.
* Reset User password through email.  
* Create Post of different types (ie. with image etc.)
* Chat in a global chatroom with other online users
* Like and Comment on other Posts  
  To-do list:
* Notification area for updates to User
* Personal messaging between users
## Getting Started
Step 1:
* Create an RDS instance and S3 Bucket with AWS.
* Hold onto the database credentials and URL.
* Create an IAM user with access to your S3 bucket.
* Hold on to the IAM user credentials.

Step 2:
* Create a gmail account.
* Hold on to the credentials.

Step 3:
* Make sure you have Java 8, tomcat 9.0.45, NodeJS and npm installed.
* Setup your system environment variables with names as shown in img1, img2 and img3 in the images folder.
* Assign the corresponding values with the various credentials you have acquired.
* "img1" refers to applicationContext.xml file.
* "img2" refers to UserController.java.
* "img3" refers to S3ConfigImpl.java.

Step 3:
* Create a gmail account.
* Hold on to the credentials.

Step 4:
* Open "Java" project folder in a Java IDE.
* Create a tomcat configuration as shown in img4 in the images folder.  
* Open "Angular" project folder in VS Code.
* Run the following commands in a new terminal window while in the project directory:
"npm install"
"ng serve -o"
##Contributors
* Rafael Malespin
* Suliman Sam
* Sam Jenkins
