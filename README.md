# Needleman-Wunsch algorithm for global alignment
(Python 3)

This function finds the best alignment for 2 characters sequences in order to maximize match rate.



Returns : a tuple containing 2 strings with the best alignment.

Arguments :
  - seq1, seq2 (String) : 2 characters sequences
  - match (Int) : score of a character match
  - mismatch (Int): score of a character mismatch
  - gapr (Int) : score of adding a gap
