# Wordle-Solver
This is an implementation for a solver of the word game Wordle. 
This solver can be used in two ways : either the secret word may be
known to the user and specified to the program (useful for testing purposes, so
that the program can whittle down the search space until it finds the specified
word), or the solver can iteratively suggest guesses to the user, so as to
search for solutions to a live problem.

To interact with the program, call it in one of two ways:

./solver <5 letter word>

This runs the solver with your inputted 5 letter word.

./solver

This will suggest guesses for the user, and prompt them to input the result as a
string of 5 characters (some sequence of 'g' 'y' and 'x'), making more
suggestions as it narrows the search space.
