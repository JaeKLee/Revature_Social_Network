# Revature Social Network

## Project Description

In this social network, everyone is friends with everyone. As a user, you will be able to register and login to your account. When you successfully login, you are automatically friends with everyone which means you will see a feed of everyone's posts. Users will be able to create a post and like other people's posts. Users will also have the ability to view other profiles which will display posts of that specific user.

## Technologies Used

* Spring MVC
* PostgreSQL
* Angular 2+
* GCP Compute Engine
* GCP Cloud SQL
* Spring ORM
* Java

## Features

List of features ready and TODOs for future development
* Create a new user account or login with existing login information
* Upload a profile picture and update your information on your own profile page
* Create a new post on your profile page
* User is able to view their own post in their profile page
* User is able to search for friends (everyone is a friend with everyone)
* User is able to view their friend's post in the friend's profile page
* User is able to view all the post in home/global page
* There's a custom profanity filter (set to fridge for now)
* User is able to logout of their profile
* User cannot go back to the profile page with a back button or hardcoded URL once their logged out

To-do list:
* Add comment to a post feature
* Add global chatroom and direct messaging
* Add other media connection (i.e. YouTube API)

## Getting Started
   
1. ``git clone https://github.com/JaeKLee/Revature_Social_Network.git``
2. Set the environment in your system: 
    1. Search **env** in your Windows machine 
    2. Select **Edit the system environment variables**
    3. Down in the right corner, select **Environment Variables...**
    4. Add the following variables:
      - DITTO_DB_HOSTIP - The URL to your database
      - DITTO_DB_NAME - The database name
      - DITTO_DB_USERNAME - The password to your database
      - DITTO_DB_PASSWORD - The username of your database
      - DITTO_ANGULAR_IP_AND_PORT - The URL of the Angular project (``http://localhost:4200/``)
3. Go to localhost ``http://localhost:4200/``

## Contributors
* John Benson
* Mike Keefer
* Ryan Moss
* Jae Kyoung Lee

## License

This project uses the following license: [MIT License](https://github.com/JaeKLee/Revature_Social_Network/blob/main/LICENSE).
