# Needleman-Wunsch algorithm for global alignment
(Python 3)

This function finds the best global alignment for 2 character sequences in order to maximize the alignment score.



Returns : a tuple containing 2 strings with the best alignment.

Arguments :
  - seq1, seq2 (String) : 2 character sequences
  - match (Int) : score of a character match
  - mismatch (Int) : score of a character mismatch
  - gap (Int) : score of adding a gap
