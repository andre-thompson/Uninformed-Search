# Andre Thompson
## Bachelor of Computer Science Specializing in Digital Forensics

**How long it takes to complete this assignment?**  
This assignment took around 2 hours to complete in whole.

**What is the most challenging part for you?**  
The most challenging part for me were the uninformed search problems in part 2 of this assignment.

**Compare BFS, DFS, and uniform cost search in terms of completeness, time complexity, space complexity, and optimality.**  
**Completeness:**  
-BFS: breadth-first search is complete when N is a finite number  
-DFS: depth-first search is complete when N is finite however will infinitely explore left and is incomplete with deep solutions  
-Uniform cost search: uniform cost search is complete and becomes BFS when all nodes have the same cost  
**Time Complexity**  
-BFS: time complexity of O(b^(d+1)), this algorithm is especially inefficent when a solution is deep within a graph/tree  
-DFS: time complexity of O(b^m), this algorithm has a lower time complexity compared to BFS but may not provide an optimal solution  
-Uniform cost search: time complexity of O(b^(c/d+1)), this algorithm has a time complexity higher than both BFS, and DFS as cost and edge cases are considered  
**Space Complexity**  
-BFS: space complexity of O(b^(d+1)), this algorithm has a higher space complexity due to storing all nodes at the current level being searched  
-DFS: space complexity of O(bm), this algorithm has a lower space complexity as it is encouraged to explore depth-first. However, if backtracking is needed to find
a solution the space needed will increase  
-Uniform cost search: O(b^(c/d+1)), uniform cost search has a higher space complexity due to its need to store/evaluate cost in a fringe  
**Optimality**  
-BFS: breadth-first search is optimal when all nodes cost the same, however due to its exponential complexity it is inefficent  
-DFS: depth-first search is not optimal especially in dense solution spaces as it prioritizes exploring downwards  
-Uniform cost search: uniform cost search is optimal as the least-cost unexpanded node is explored first    
**Based on your understanding, indicate the best suitable uninformed search strategy (BFS, DFS, or uniform search) for the following three situations:**  
**1: equal action cost and dense solution space**  
-Because each action has an equal cost BFS and uniform search become the same. These algorithms would be the best for a dense solution space as DFS explores downward
and will miss optimal solutions.  
**2: equal action cost and d is significantly smaller than m**  
-Because of a smaller solution space, DFS would likely out perform both BFS and uniform cost search in speed  
**3: actions with different costs**  
-Because each action is assigned a different cost, uniform cost search would be able to evaluate the most optimal solution  


