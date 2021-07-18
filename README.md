# pwa-budget-tracker
The budget tracker is an application used to track expenses and transactions for the user. 

## Description
This is an existing application that was required to be converted to a progressive web application (PWA). The necessary functionality was added to this application to  allow for offline access and functionality. <br />
The user will be able to add expenses and deposits to their budget with or without a connection. When entering transactions offline, they should populate the total when brought back online.

## Installation
To run on local machine, open terminal window and clone repository from GitHub. 

Run ```npm install``` to install the required dependencies.

## User Guide
This section provides detailed description on how to use the budget tracker.
The application is invoked at the root of the project using the command line when the user types the following command: ```npm start```<br />
Navigate to the browser and enter  the localhost address, "localhost:3000.<br />
This application will allow the user track their expenses and budget while being able to add expenses and depositis made tp the tracker using the "Add Funds" and "Subtract Funds" buttons. They are able to do this while connected and without connection as well.<br /> This actions are made possibly using the indexedDB while offline, so that they are moved to the database when the user is back online.<br />

## Links to application
* URL of GitHub repository containing the code: https://github.com/e-giftz/pwa-budget-tracker
* URL of deployed app on heroku: https://secret-bastion-26469.herokuapp.com/


## Screenshot  Demonstrating  the App's  Functionality
![Budget Tracker](/assets/budget_tracker.png)
