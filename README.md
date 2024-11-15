# Dynamic Programming

* DP is an algorithmic technique used in computer science and mathematics to solve complex problems by breaking them down into smaller overlapping subproblems.
* The core idea behind DP is to store solutions to subproblems so that each is solved only once.
* To solve DP problems, we first write a recursive solution in a way that there are overlapping subproblems in the recursion tree (the recursive function is called with same paramaters multiple times)
* To make sure that a recursive value is computed only once (to improve time taken by algorithm), we store results of the recursive calls.
* There are two ways to store the results, one is top down (or memoization) and other is bottom up (or tabulation).
