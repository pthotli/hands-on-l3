# 8-Puzzle Solver (A* Search)

This project implements the **A\*** algorithm to solve the 8-puzzle problem using two heuristics:

- **Misplaced Tiles** – counts tiles out of place  
- **Manhattan Distance** – total distance of tiles from goal positions  

## How it Works
- **State space**: All 3×3 board configurations  
- **Operators**: Move blank (0) up, down, left, right  
- **g(n)**: Path cost (moves from start)  
- **h(n)**: Heuristic value  
- **f(n) = g(n) + h(n)**  

The program:  
- Accepts **start** and **goal** states from the user  
- Checks **solvability**  
- Runs A* with both heuristics  
- Prints solution path, path cost, nodes generated & expanded  

## Run

python a-star.py
