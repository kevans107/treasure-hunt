# React Treasure Hunt

### This project was built as part of Learn Academy's Jump Start Program. This was a pair programming project built over the span of three days. 

## The Setup:
- 3 components
    - App.js
    - Board.js
    - Square.js
- App.js contains the board
- Board.js contains 9 squares represented in state like this:
    ``` javascript
    this.state = { spaces: [0, 0, 0, 0, 0, 0, 0, 0, 0] }
    ```

## Remember:
- Pseudocode!!
- Ask clarifying questions

## User Stories
- As a player, I can see a web page with a 3 by 3 grid board game with question marks in each square
- As a player, when I click on one of the question marks, an alert appears with the id of the position in the grid
- As a player, when I click on one of the question marks, instead of the alert the space turns into a tree icon (In order to focus on the functionality of this step, you can start with switching the ‘?’ to the word ‘tree’)
- As a player, I can click on the question marks and behind one of the question marks is a treasure box icon and an alert appears with the text “You Win”
- As a player, I can see a counter that shows how many guesses I have left (starting at 9, 8, 7, etc)
- As a player, I can see a “win” or “lose” message when the game is won or lost
- As a player, I can click on a “Play Again” button to restart the game

## Stretch
- As a player, I can click on the question marks and behind one of the question marks is a bomb icon and an alert appears with the text “You Lose"
- As a player, I can play a 25 square game with three bombs

# How to Use this Repo

When your team is ready to begin coding, open this project in Atom and edit it directly. Remember to add and commit regularly and, at the end of the project day, be sure to push your changes to Github.
