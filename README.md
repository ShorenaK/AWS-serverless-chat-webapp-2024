# serverless-chat-webapp-2024-
## Shorena K. Anzhilov  "

## Game Descriptiion:




## Preview 
![alt text](/static/images/new_back.png)
![alt text](/static/images/image1.png)


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
