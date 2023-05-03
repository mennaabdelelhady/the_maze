# Maze Game with BFS Pathfinding

This project is a maze game implemented in Python using the Pygame library. The objective of the game is to find the shortest path from the starting point to the end point of the maze. The maze is randomly generated and the player navigates through it by using the arrow keys. The game also includes a feature to find the shortest path using the BFS (Breadth-First Search) algorithm.

## Maze Generation

The maze is generated using a randomized version of the Depth-First Search algorithm. The algorithm starts with a grid of cells and randomly selects a starting cell. It then carves a path through the neighboring cells, marking each cell as visited until it reaches a dead end. The algorithm then backtracks to the last cell with unvisited neighbors and repeats the process until all cells have been visited.

## Pathfinding

The BFS algorithm is implemented to find the shortest path between the starting point and the end point of the maze. The algorithm works by exploring all the neighboring cells of the starting point and adding them to a queue. It then dequeues the first cell from the queue, explores its neighbors, and adds them to the queue. The algorithm continues until it finds the end point or until all cells have been explored.

## Visualization

The game includes a feature to visualize the BFS algorithm. When the player clicks on the "Solve" button, the game displays the steps taken by the algorithm to find the shortest path. The algorithm highlights each cell that it explores and displays the shortest path once it finds the end point.

## How to Run

To run the game, you will need to have Python and Pygame installed on your computer. You can download Python from the official website and install Pygame using pip. Once you have the required dependencies, you can run the game by executing the following command in your terminal or command prompt:python main.py

## Conclusion

Overall, this project is a fun and interactive way to learn about maze generation, pathfinding algorithms, and game development in Python. Feel free to fork the repository and modify the game to suit your needs.

<br>you can watch this vedio:https://clipchamp.com/watch/J3v1PF1eovh
