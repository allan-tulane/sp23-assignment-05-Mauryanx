# CMPS 2200 Assignment 5
## Answers

**Name:**. Mauryan Uppalapati


Place all written answers from `assignment-05.md` here for easier grading.





- **1a.**



A greedy algorithm that would produce the  fewest coins possible would be the one which takes the largest valued coins first, that is the greatest possible power of two that is less than or equal to $N. The value input would reduce by each coin taken away while greater than 0 and printing out the result once 0 is attained. This would be an optimal solution here as our denominations are in a base of two and are fixed 


- **1b.**

The work that our algorithm would have is  O(log_2(N)), The span would also be O(log_2(N)) becuase it would take us log_2(N) recursions to go all the ay to the max depth of tree


- **2a.**

A counter example would be that we are given denominations = [1, 6, 8, 9, 10] and the input amount is 14. Therefore the  algorithm used in question 1a would give us  (10, 1, 1, 1, 1)  which is 5 coins whereaas the optimal solution would be (8, 6) which gives us 2 coins


 **2b.**

With dynamic programming we would want to incorporate a bottom up approach. We would first calculating the different denominations needed for an amount of 1, and build a table of them and the powers that they are raised to. That way we construct our memoization table would directly affect our work and span
Thus, the work would be O(k*N) . Our span would be the path through the table  which would therefore be O(k+N).







