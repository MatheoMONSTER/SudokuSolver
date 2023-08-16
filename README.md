**Sudoku Solver App**
This is a simple Sudoku Solver app build in Android Studio using Java. The app allows users to play Sudoku puzzles and provides mechanism to
solve the puzzle automatically or clear the board.

**Features**
- Interactive Sudoku Board: Users can tap on cells to select them and input numbers from 1 to 9
- Highlighting: The selected row, column, and the 3x3 subgrid of the selected cell are highlighted
- Number input: Users can input numbers using buttons for easy input
- Solve Button: The "Solve" button uses a backtracking algorithm to automatically solve  the puzzle
- Clear button: The "Clear" button resets the board and clears all entered numbers
- Error detection: The app highlights numbers in red if they violate Sudoku rules

**Code Structure**
The app consists of three main classes: 
1. **MainActivity.java**: This is the entry point of the app and contains the main logic for user interactions. It includes methods to handle button presses, initiate puzzle solving, and more.
2. **Solver.java**: This class contains the algorithm to solve Sudoku puzzles. It includes functions to check the validity of numbers in rows, columns, and subgrids. The solving algorithm uses a recursive backtracking approach.
3. **SudokuBoard.java**: This class represents the custom view for the Sudoku board. It handles drawing the board, numbers, and user interactions.

**How to Use**
1. Open the app on your Android device or emulator.
2. The Sudoku board will be displayed, and you can tap on cells to select them.
3. Use the number buttons to input numbers into the selected cell.
4. If you want to solve the puzzle, press the "Solve" button.
5. To clear the board, press the "Clear" button.

**Customization**
The app's appearance and behavior can be customized using attributes defined in the XML layout files for the SudokuBoard custom view. You can modify colors and other properties to match your preferences.

**Note**
This app is designed for educational purposes and may have limitations in handling complex Sudoku puzzles. The solving algorithm is basic and may not handle all possible puzzle configurations efficiently.

**Credits**
This app was created by Mateusz Dudek.

Feel free to explore, modify, and build upon this app as you see fit!
