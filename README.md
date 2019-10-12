# Solve Sudoku with CSP

1. Read Pseudocode for naked_twins.
   

2. You can run a small set of test cases using the local test suite.

    `$ python -m unittest -v`

3. You can run the code to get the sudoku solution.

` $ python solution.py`



## Visualization

**Note:** The `pygame` library is required to visualize your solution -- however, the `pygame` module can be troublesome to install and configure. It should be installed by default with the AIND conda environment, but it is not reliable across all operating systems or versions. Please refer to the pygame documentation [here](http://www.pygame.org/download.shtml), or discuss among your peers in the slack group if you need help.

Running `python solution.py` will automatically attempt to visualize your solution, but you mustuse the provided `assign_value` function (defined in `utils.py`) to track the puzzle solution progress for reconstruction during visuzalization.
