## GCO-November2025

# Problem 1
Find one valid assignment for a 5 by 5 grid (25 cells, using values 1-25 exactly once) that satisfies the following three highly restrictive constraints:
Fixed Seed: The center cell, Row 3, Column 3, must be set to the value 13.
C1 (Orthogonal): No two orthogonally adjacent cells (sharing a side: up, down, left, right) can contain consecutive numbers (i.e., if a cell holds N, its neighbors cannot hold N-1 or N+1).
C2 (Diagonal): No two diagonally adjacent cells (sharing a corner) can contain numbers with a difference of exactly 2 (i.e., N and N plus or minus 2).
C3 (Prime/Even Sum): The sum of the values in the 10 prime-numbered cells must be an even number.
(Hint: The prime-numbered cells are Grid(1,2),Grid(1,4),Grid(2,1),Grid(2,3),Grid(3,2),Grid(3,4),Grid(4,1),Grid(4,3),Grid(5,2),Grid(5,4)).
Submission Format: Submit the grid as a single string of 25 comma-separated integers, reading the grid row-by-row, left-to-right.

# Problem 2
Find one valid assignment for a 5 by 5 grid that satisfies all three constraints from Problem 1 (Orthogonal C1, Diagonal C2, and Prime/Even Sum C3), PLUS the following new constraint:
C4 (Global Median): The median of the values in the top row (Row 1) must be exactly 14. (i.e., when the 5 values in Row 1 are sorted, the 3rd value must be 14).
Once a solution is found, your answer is the number placed in the specific cell Grid (Row 5, Column 5) (the bottom-right corner).
Submission Format: Submit the final value in Grid(5,5) as a single integer.

# Problem 3
Find one valid assignment for a 6 by 6 grid (36 cells, using values 1-36 exactly once) that satisfies the following conditions:
Fixed Seed: The top-left cell, Row 1, Column 1, must be set to the value 1.
C1 (Orthogonal): No two orthogonally adjacent cells can contain consecutive numbers (N and N plus or minus 1).
C5 (Rook Constraint): No two numbers from the set {1, 12, 24, 36} can be in the same row or the same column.
Submission Format: Submit the grid as a single string of 36 comma-separated integers, reading the grid row-by-row, left-to-right.

# Problem 4
Using the initial simplified constraint (C1 only), and without any fixed seeds, what is the total number of unique solutions that exist for the 5 by 5 grid (values 1-25)?
Constraints: Only C1 (Orthogonal Non-Adjacent) applies.
Grid: 5 by 5.
Submission Format: Submit the total number of solutions as a single integer.
