# Match 3 Game
###Summary
The Match Three game is a puzzle game in which the player must swap adjacent gems on a game board to create matches of three or more gems of the same color. When a match is made, the gems disappear from the board and are replaced by new gems falling from the top of the board. The player earns points and additional time for making matches, and the game ends when the timer runs out or the player reaches a certain score threshold. The game features colorful gem graphics, sound effects, and real-time communication of player scores to a server using WebSockets. The game is built using HTML, CSS, and JavaScript, and runs on a Node.js web server.

###Files Summary
A detailed summary of each file in the repository and an overview of the Match Three game:

Client-side files:
index.html: This file contains the main HTML structure of the game, including the game board and user interface elements such as the score and timer displays. It also includes links to the CSS and JavaScript files needed to run the game.

style.css: This file contains the CSS styling rules for the game's user interface, including the colors and layout of the game board and other elements. It defines the size and position of the game board, the appearance of the gem icons, and the styling of the score and timer displays.

script.js: This file contains the JavaScript code that handles the game's user interface and gameplay logic. It sets up the game board, listens for player moves and clicks, updates the score and timer displays, and handles the game's win and lose conditions. The code also includes a function that communicates with the server-side code to send and receive player scores.

Server-side files:
server.js: This file contains the Node.js code that sets up and runs the game's web server. It handles HTTP requests from the client-side code, sets up a WebSocket connection for real-time communication with the client, and handles the storage and retrieval of player scores in a MongoDB database.

database.js: This file contains the code that sets up and communicates with the MongoDB database used to store and retrieve player scores.

Node.js modules:
express.js: This is a Node.js web application framework that provides a set of features for building web applications and APIs. It is used in this project to handle HTTP requests from the client-side code and set up the game's web server.

socket.io.js: This is a JavaScript library that provides real-time, bidirectional communication between the client-side and server-side code using WebSockets. It is used in this project to set up the WebSocket connection between the client-side and server-side code for real-time communication of player scores.


---

### HOW TO PLAY

- Start the game by pushing the play button.
- You have 60 seconds to complete the game.
- Drag and drop the candies to match them.
- Can only drag and drop to right, left, top and bottom.
- Match at least 3 candies in a row or column to score.
- Create combos by matching more than 3 candies.
- Click the timer box to stop it from bouncing.

### Play it [here]()!

---

### Run it locally
- Clone this repository 
- Open `index.html` file in your prefered browser - either by double-click the file in explorer or by drag & drop the file into the browser's search field.

---

### Run ESlint

- Install Node.js

- Install dependencies

```
npm install
```

- Run eslint on scripts folder

```
npm run eslint
```

Some rules will be auto-fixed, others will be logged so developer can fix them manually.

---

### Where I am at now 🍬

- Basic drag and drop functionality
- Rows are being replaced when matched
- Score keeping
- 5+ row and column matching
- Styled background
- Simple animation when candy disappears
- Github pages
- Implement a time limit
- Have a "Start" and Restart Button
- Fix bug that crashes game at the bottom right candy

![CandyCrushgif](currentstate.gif)

### Future Features 🧁

- Update background image
- More cohesive color pallet

### Art and Assets Credit
- Halloween Theme candy [silverwavetidaldragon](https://github.com/silverwavetidaldragon) 

#### This project is licensed under the terms of the [MIT license](https://choosealicense.com/licenses/mit/#).
