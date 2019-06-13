# eight_queens_generic
AN MIT App Inventor sample app for the Eight Queens problem, using a single generic button click event

Rules:  
Given an 8 by 8 chess board, place 8 queens on the board in such a way that none of them threaten one another horizontally,
vertically or diagonally.

Implementation:

The Designer is set up with 8 rows of 8 buttons each, all initially blank and enabled.
As each button is pressed, if it is blank then it is set to show 'Q' and the buttons it threatens
are disabled.  Otherwise, the pressed button is cleared and all 64 buttons are checked for threats
and enabled or disabled appropriately.
