# A* Path Finding Algorithm Visualization

This project is an interactive visualization of the A* path finding algorithm using the Pygame library in Python. The A* algorithm finds the shortest path between two points on a grid, taking into account obstacles or barriers.

## Installation

To run the project, you need to have Python installed on your system. Additionally, the Pygame library is required. You can install Pygame using pip:


## Usage

Once you have Python and Pygame installed, you can run the project by executing the script `path_finding.py`. The script opens a Pygame window where you can interact with the algorithm visualization:

- Left mouse button: Place the start point, end point, and barriers on the grid.
- Right mouse button: Remove start point, end point, and barriers from the grid.
- Spacebar: Start the algorithm and visualize the shortest path between the start and end points.
- "C" key: Clear the grid and reset all points.

## How It Works

The A* algorithm is a path finding algorithm that evaluates the most promising path to reach the target. It uses heuristics to estimate the cost of reaching the goal from each node. The algorithm explores the nodes with the lowest total cost (estimated cost from start + heuristic) first.

In this project, the algorithm is visualized on a grid. The start point is marked in orange, the end point in turquoise, barriers in black, explored nodes in red, and the shortest path in purple.

## Contributions

Contributions to this project are welcome. If you find any issues or have suggestions for improvements, feel free to open an issue or submit a pull request on the project's GitHub repository.

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).

## Acknowledgements

The A* algorithm visualization in this project was inspired by various resources and tutorials available on path finding algorithms and Pygame.
