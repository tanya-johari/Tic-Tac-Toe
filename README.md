# [Tic-Tac-Toe Game in React](https://react.dev/learn/tutorial-tic-tac-toe)

### 1. Set up the project
   * Choose between a CodeSandbox or local development environment.
   * If you use CodeSandbox, follow the steps to set up a new tab.
   * If you use a local development environment, install Node.js and download the archive.
### 2. Create the Board component
   * The Board component will display the tic-tac-toe board.
   * You can initially define the board with nine squares using JSX. 
   * To group the squares into rows, wrap them in a div with the class “board-row”. 
   * Each square should also have a class of “square” and a unique number to differentiate them. 
### 3. Create the Square component
   * The Square component will represent each individual square on the board.
   * Each Square component should render a button element. 
   * You can initially set the value of each square to an empty string ”” using the useState function.  
### 4. Pass data through props
   * In order to avoid copy-pasting code, the squares will be created using a separate Square component. 
   * The Board component will pass the value of each square to the Square component as a prop. 
   * The Square component will then display the value that is passed to it as a prop.  
### 5. Make the squares interactive
   * In order to make the squares interactive, you will need to add a state variable to the Square component using the useState function. 
   * This state variable will store the value of the square, which will be “X” or “O”.  
   * You will also need to add an onClick event handler to the button element in the Square component. 
   * When the square is clicked, the handleClick function will update the state variable to “X”.

### 6. Game Logic
   * In the Board component, handle clicks on each square:
        - If a square is already filled or there’s a winner, ignore the click. Otherwise, update the board with the current player’s move (“X” or “O”).
        - Implement a function to calculate the winner based on possible win conditions (rows, columns, diagonals).
          
### 7. Displaying Game Status and Restarting the Game
   * Show the current player (“X” or “O”) and the winner (if any).
   * Add a restart button to reset the game.
   * Refactor the JSX code to make it more readable.
     
### 8. Adding Time Travel (Optional):
  * Implement time travel by maintaining a history of moves.
  * Allow users to jump to any previous move and replay the game.


