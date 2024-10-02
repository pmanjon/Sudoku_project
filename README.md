10/2/2024 - Start of project. Will be using 
**curl -v https://sudoku-api.vercel.app/api/dosuku**
to generate new sudoku puzzles.

New idea: Chaos Sudoku. Sudoku with power-ups. You have limited time to solve the sudoku, making the power-ups valuable. Try to implement after building simple sudoku

Features planned for simple sudoku:
 - Website initially compatible with Chrome, will eventually work on Firefox.
 - You can enter a custom sudoku puzzle or request a random one. The random sudoku's solution will be known in advance.
 - (?) Allow user to input solution for their custom sudoku in advance?
 - Features planned for sudokus with a solution known in advance:
  -- Check square, column, row, or 3x3 box (Tells user if their answers so far are correct)
  -- Reveal square, column, row, 3x3 box, or whole sudoku
 - "Check rule violation" button that tells the user if their current work-in-progress solution violates any sudoku rules. Toggleable feature in settings to passively run CRV at all times
 

Features planned for Chaos Sudoku: 
 - You win by solving 1+ sudoku puzzles with limited time
 - Power-ups divided into "big"/"small".
 - Big power-ups: Reveal column, row, 3x3 box
 - Small power-ups: Check two squares, reveal a square (costs 2), check box, is square a multiple of 3, is square even 
 - (?) Limit amount of power-ups used by point system
