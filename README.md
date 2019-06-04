# Solve Sudoku with AI

## Synopsis

In this project, it will resolve the Sudoku game using constraint propagation with three strategies called: "Naked Twins", "Eliminate" and "Only Choice" and will use a Depth First Search to solve conflict problems.

## Visualization

**Note:** The `pygame` library is required to visualize the solution -- however, the `pygame` module can be troublesome to install and configure. It should be installed by default with the AIND conda environment, but it is not reliable across all operating systems or versions. Please refer to the pygame documentation [here](http://www.pygame.org/download.shtml), or discuss among your peers in the slack group if you need help.

Running `python solution.py` will automatically attempt to visualize your solution, but you mustuse the provided `assign_value` function (defined in `utils.py`) to track the puzzle solution progress for reconstruction during visuzalization.
