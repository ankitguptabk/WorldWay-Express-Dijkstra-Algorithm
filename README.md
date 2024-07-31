Dijkstra-Travel-Planner
=======================

# WorldWay Express: Dijkstra Algorithm

## Overview
WorldWay Express is a project that implements Dijkstra's algorithm to find the shortest path between nodes in a graph. This algorithm is widely used in network routing and geographical mapping systems to determine the most efficient route.

## Features
- Implementation of Dijkstra's algorithm
- Support for weighted graphs
- User-friendly interface to input graph data
- Visualization of the shortest path
- Efficient performance for large graphs

## Installation

1. **Clone the repository**
    ```bash
    git clone https://github.com/ankitguptabk/WorldWay-Express-Dijkstra-Algorithm.git
    cd WorldWay-Express-Dijkstra-Algorithm
    ```

2. **Compile the project**
    Make sure you have a C++ compiler installed. You can use `g++` for this purpose.
    ```bash
    g++ -o WorldWayExpress main.cpp
    ```

3. **Run the executable**
    ```bash
    ./WorldWayExpress
    ```

## Usage

1. **Input Graph Data**
    The program will prompt you to enter the number of nodes and edges, followed by the edges themselves (start node, end node, and weight).

2. **Calculate Shortest Path**
    After entering the graph data, the program will ask for the source node. It will then compute and display the shortest path from the source node to all other nodes using Dijkstra's algorithm.

3. **View Results**
    The output will include the shortest distance from the source node to each node and the path taken to achieve this distance.

## Example

```bash
Enter the number of nodes: 5
Enter the number of edges: 6
Enter edge 1 (format: start end weight): 1 2 10
Enter edge 2 (format: start end weight): 1 3 5
Enter edge 3 (format: start end weight): 2 3 2
Enter edge 4 (format: start end weight): 2 4 1
Enter edge 5 (format: start end weight): 3 2 3
Enter edge 6 (format: start end weight): 3 4 9
Enter the source node: 1
```

Output:
```
Node 1: Distance = 0, Path = 1
Node 2: Distance = 8, Path = 1 -> 3 -> 2
Node 3: Distance = 5, Path = 1 -> 3
Node 4: Distance = 9, Path = 1 -> 3 -> 2 -> 4
```

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue to discuss any changes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact

For any questions or inquiries, please contact Ankit Gupta at https://github.com/ankitguptabk.

---
