# Capabilities & Characteristics

1.	Profile Display:
Presents a roster of profiles accessible to Guests (unregistered users) and Users (authorized account holders).
2.	Search Functionality:
Enables Guests and Users to explore profiles based on criteria such as name, tech stack, and bio.
3.	Account Creation:
Empowers Users to establish their own accounts.
4.	Profile Editing:
Grants Users the ability to modify their personal accounts while restricting the editing of other profiles.
5.	Account Deletion:
Permits Users to erase their own accounts, with limitations on deleting other user profiles.
6.	Authentication Mechanism:
Implements secure email and password verification for user accounts.
7.	Session Management:
Manages user sessions, ensuring a reasonable duration of login persistence following successful authentication.
8.	Form Data Validation:
Incorporates basic validation measures in sign-up and profile editing forms to enhance data accuracy and completeness.

# Server & Client Configuration Instructions
To set up a development environment on your local computer for both the server and the client:

## Server Setup:

Clone the backend repository using Git.
Open the terminal and navigate to the backend folder.
Run npm install to install the necessary dependencies.
Install nodemon for server execution using npm install -g nodemon.
Start the server by running the command 'nodemon'.

## Client Setup:

Clone the frontend repository using Git.
Open a new terminal window and navigate to the frontend folder.
Run npm install to install the required client-side dependencies.
Execute the command 'npm start' to initiate the development server for the client.
The application will automatically launch in your default browser at 'localhost:3000'.


# Required Functions & Features
Displays a list of profiles to Guests (non-account holders)
Guests and users can search for an account by name, tech stack and bio
Basic data validation in the edit profile forms

# Original Stretch goals 

Users can create an account
Users can edit their own account. (They cannot do this for any other profiles)
Users can delete their own account. (They cannot do that for any other profiles)
Email and password authentication for account holders
Session management for logged in users (users stay logged in for a reasonable period of time after successful authentication)



