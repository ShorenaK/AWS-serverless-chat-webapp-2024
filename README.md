# serverless-chat-webapp-2024-
## Shorena K. Anzhilov  "

## Game Descriptiion:


So to recap, we've used S3, Lambda, API Gateway,

DynamoDB, Cognito, CloudFront, and IAM together

to build a complete web application

The services we're going to use in this course are S3,

the API Gateway, the Lambda, DynamoDB,

Cognito, CloudFront, IAM, and CloudWatch services.

The other thing we're going to cover is a bit of JavaScript.

So we're going to go over some basics

and we're gonna make some AJAX calls

to start turning our boring static site

into something that's actually dynamic and useful.

Instructor: So let's go into some more depth here.

One of the first things we did

Build a chat application entirely with AWS services, and no stand-alone servers at all
Architect and design serverless applications
Serve static resources to browsers using AWS's S3 (Simple Storage Service)
Use Javascript to dynamically modify web pages
Manage permissions and access policies using IAM (Identity and Access Management)
Manipulate and vend data in the cloud using AWS Lambda
Use CORS to manage client-side security in serverless apps
Store and retrieve data with DynamoDB
Model API's and create SDK's with API Gateway
Create a user login system with Cognito
Speed up your web app with a CloudFront CDN

Immerse yourself in Amazon Web Services (AWS) with this hands-on, project-based course - and truly internalize some highly valuable skills in the world of technology. We'll walk you through building your own chat website using nothing but AWS services - and no standalone services or server instances at all! 

Building a "serverless app" using AWS and its Lambda service is a great introduction to the core services AWS offers. As you create your chat application, you'll learn and use the following AWS services:



S3 (Simple Storage Service) - For storing static HTML and vending it to your users' browsers

Lambda - For executing logic in the cloud for storing and retrieving data in your application

IAM (Identity and Access Management) - For securing access to your services

API Gateway - For presenting a well-modeled API to your clients and automatically generating client-side code to communicate with it

DynamoDB - For quickly storing and retrieving data at scale

Cognito - For managing users, account creation, and logins securely

CloudFront - For accelerating the delivery of your site to end users with a CDN

We'll tie it all together by learning and practicing Javascript, and we'll learn about CORS to grant browsers the permissions they need to run a serverless application.

Even if you're familiar with AWS, you'll learn valuable techniques on how to build a fully functional, dynamic website without maintaining any servers at all - not even via EC2!

## Preview 
![alt text](/static/images/1.png)
![alt text](/static/images/2.png)


## Go to app:
[CLICK HERE!](http://serverless-chat-webapp-2024.s3-website-us-east-1.amazonaws.com/chats.html)


## Technologies Implemented - Tech Stack:

- Server-side: Python3, Flask
- Frontend: HTML, JavaScript (with Ajax for asynchronous requests)
- CSS
- Deployed on AWS (Amazon Web Services) - Lambda. 

Description:

Server-side: The backend of the application is powered by Python3 with the Flask lightwaight web framework, handling the game logic and serving responses to client requests.

Frontend: The user interface is built using HTML for structure, JavaScript for dynamic interactions (including Ajax for asynchronous communication with the Flask server), and CSS for styling.

## Resources:
- 1. [Flask Documentation](): Official documentation for Flask, the web framework used in this project.
- 2. [JQuery Documentation](): Documentation for JQuery, a JavaScript library used for making asynchronous requests in this project.
- 3. [Python Documentation](): Official documentation for the Python programming language.
- 4. [Blackjack Rules](): A resource explaining the basic rules of Blackjack for reference.
- 5. [CSS Tricks](): Helpful tips and tricks for working with CSS.

- 6. [Flask Tutorial](): Step-by-step guide for getting started with Flask. A great resource if you're new to Flask development.
- Google & Stak OverFlow.
- reddit.

## Missing Features:
- Multiplayer Support
- User Authentication
- Graphics and Animation
- Sound Effects
- Betting Options
- Game Statistics

## Next Steps - Features Implementations:
1. Multiplayer Functionality:
Enhance the gaming experience by introducing multiplayer functionality, allowing multiple players to compete against the dealer.

2. User Authentication:
Implement user authentication to provide a personalized gaming experience and enable tracking of individual player statistics.

3. Game Statistics:
Introduce a statistics feature to keep track of players' performance, including win-loss records and other relevant gameplay metrics.

4. Dealer's Unrevealed Cards:
Mimic the real blackjack experience by initially keeping all of the dealer's cards unrevealed. Unveil the cards as the game progresses, following the player's actions.

5. Enhanced Dealer Interaction:
Create a more realistic gaming environment by allowing the dealer to draw a third card based on specific conditions, similar to real blackjack rules.

6. Improved User Interface:
Enhance the user interface to provide a visually appealing and intuitive gaming experience for players.

7. Integration of Real Blackjack Rules:
Further align the game with traditional blackjack rules, ensuring a more authentic representation of the classic card game.

## Challenges:

#### I encountered challenges while running unit tests on a Python file with Flask framework.RuntimeError specifically: "Working outside of application context." Additionally, faced "Unable to build URLs outside an active request" due to missing configurations like 'SERVER_NAME' and 'APPLICATION_ROOT.

### Steps Taken:

-  Added Flask app context using self.app.app_context().
-  Modified the BlackjackGame class to handle both Flask and non-Flask contexts.
-  Separated Flask-dependent logic to run only when the context is available.

![alt text](/static/images/git_self_app1.png)

![alt text](/static/images/git_self_app2.png)

### Persisting Issue:

#### Despite these changes, a RuntimeError persisted, indicating Flask's inability to build URLs outside an active request. I think a configuration change is needed, but I haven't found the solution yet.

### Alternate Approach:
#### To ensure unit testing functionality, I have created a separate Python file, app_blackjack.py, detached from Flask, it is only for testing purposes. This file is connected to test_blackjack.py file, to run unittests. 

![alt text](/static/images/git_test1.png)

![alt text](/static/images/git_test2.png)

## Highlights:  

- Multilingual Development: Crafted the project using a combination of Python and JavaScript.

- Learning AJAX: Implemented AJAX to enhance the project's scripting capabilities.

- Python Flask Framework: Leveraged the Python Flask framework for efficient development.

- AWS (Amazon Web Services): Successfully deployed the project on AWS EC2 instance, it took me 4 days and was challenging but I made it happen.

## Developer:
- [Shorena K. Anzhilov](https://github.com/ShorenaK)



## Support: 
 If you have any concerns or questions, you are welcome to reach out via email at skadigitalllc@gmail.com 
