
# Pathfinding Visualization

This project is a **Pathfinding Visualization Tool** that allows users to observe and interact with popular pathfinding algorithms like **A***, **Dijkstra's Algorithm**, and **BFS**. The application provides an intuitive interface to visualize how these algorithms explore paths in a grid-based environment.

## Features

- Interactive grid where users can:
  - Add or remove obstacles.
  - Set start and end points.
- Real-time visualization of pathfinding algorithms.
- Supports popular algorithms:
  - A* Algorithm
  - Dijkstra's Algorithm
  - Breadth-First Search (BFS)
- Lightweight and easy-to-run Python application.

## Project Structure

```
A-Path-Finding-Visualization/
├── .gitpod.dockerfile          # Docker configuration for Gitpod
├── .gitpod.yml                 # Gitpod environment settings
├── get_pip.py                  # Script to install pip
├── install_requirements.py     # Script to install dependencies
├── path_finding.py             # Main script for the visualization
├── requirements.txt            # List of dependencies
└── README.md                   # Project documentation
```

## Prerequisites

- Python 3.8 or higher
- `pip` installed on your system

## Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd A-Path-Finding-Visualization-master
   ```

2. Install dependencies:
   ```bash
   python install_requirements.py
   ```

## Usage

Run the main script to start the visualization:
```bash
python path_finding.py
```

Follow the on-screen instructions to interact with the grid and visualize the pathfinding algorithms.

## Screenshots

*(Add images or GIFs demonstrating the tool's interface and functionality.)*

## Contributions

Contributions are welcome! Please fork the repository and submit a pull request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.
