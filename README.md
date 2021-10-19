This is a Tic Tac Toe game project. 

There are sign up / sign in fields on the main page. 

Once signed up/signed in, it will bring the user to be able to click on "New Game" to start the game. 

The game will rotate the choice of X and O between 2 players, starting at X. 

Once a winner or tie game has been declared, it will display a message of the winner or tie game, and then allow the user to reset the game board to play again. 

The user will also be able to sign out and sign back in.

Link is here: https://ktu23.github.io/ktu-tictactoe-client/

Have fun!

<br>
<br>

# User Stories
1. As a user, I want to be able to sign up and sign in/out
2. As a user, I want to be able to select "New Game" and start a brand new Tic Tac Toe game
3. As a user, I want to be able to rotate between the X's and O's, starting with X - during the game.
4. As a user, I want to be able to see who has won the game and then reset the game.

<br>

# Explanations of the Code/Functions

### ui.js
1. signUpSuccess - this lets the user know when a sign up with their email/password has been successful
2. signUpFailure - this lets the user know that email/password combo that they chose didn't work
3. signInSuccess - this lets the user know that they have signed in successfully, and displays a new page
4. signInFailure - this lets the user know that they have not signed in successfully
5. signOutSuccess - this lets the user know that they have signed out successfully
6. signOutFailure - this lets the user know that they have not signed out successfully
7. newGameStart - this lets the user display a new game board and play the Tic Tac Toe Game


### events.js
1. onSignup - this allows the user to sign up for the game
2. onSignIn - this allows the user to sign into the game with their email/password
3. onSignout - this allows the user to sign out of their account
4. checkWinner - this checks every possible X and O combination to win the game or tie
5. onNewGame - this starts a new game of Tic Tac Toe
6. onClick - this is the function of the game board that allows the user to rotate with X and O, starting with X to play the game. It will also freeze the game board once a winner has been declared and it will say who has won the game (X or O)
7. onNewGameReset - this resets the game board and restarts the game at the first player of X

<br>
<br>

# Wireframes

1. ![Wireframe 1](./public/wireframe%201.png)
2. ![Wireframe 1](./public/wireframe%202.png)
3. ![Wireframe 1](./public/wireframe%203.png)
