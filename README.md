<h1>GAME TICTACTOE</h1>

The goal of this game is to collect 5 noughts or crosses in a row.

<h4>CONTENT:</h4>
<ol>
  <li>TASK ANALYSIS</li>
  <li>PLAN</li>
  <li>EXECUTE
     <ul>
     <li>GRAPHIC INTERFACE</li>
     <li>USER ACTIONS</li>
     <li>TIMER</li>
     </ul>
  </li>
  <li>SOURCES</li>
  <li>SUPPLEMENT</li>
</ol>

<hr>

<h3>TASK ANALYSIS:</h3>

We need to develop a game with a graphic user interface. 
And we shoud split our programm into several small tasks.

Let's start with describing how our user interacts with the system.

- the playing field is a set of buttons placed on a grid. 
button can be empty, contain X or O;
- there are two types of users - the first goes with crosses, the second - with zeros;
- each player is given a certain amount of time for the whole game (5 minutes);
- to make a move, users click an empty cell with the left mouse button;
- players take turns until the game is over;
- the game ends if:
   - a continuous line of 5 of his symbols - the player wins. 
   - or one of the players runs out of time - the player loses;
- the game window has:
   - the playing field;
   - the button to start the game;
   - information about the type of the current player;
   - countdown timer for the current player.
