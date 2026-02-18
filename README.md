# AI Pathfinder - Search Algorithm Visualizer

A modern, interactive pathfinding visualization tool built with **Python** and **Tkinter**. This application demonstrates the working mechanics of various search algorithms, helping users understand how they navigate through a grid to find a target while avoiding obstacles.

![Pathfinder Screenshot](https://via.placeholder.com/800x450.png?text=AI+Pathfinder+Preview)
*(Note: Replace the placeholder above with an actual screenshot of your application)*

## 🚀 Features

### Supported Algorithms
- **Breadth-First Search (BFS)**: Guarantees the shortest path in an unweighted grid.
- **Depth-First Search (DFS)**: Explores as far as possible along each branch before backtracking.
- **Uniform Cost Search (UCS)**: Explores paths based on path cost (Dijkstra's algorithm variant).
- **Depth-Limited Search (DLS)**: A DFS that stops after a specific depth limit.
- **Iterative Deepening DFS (IDDFS)**: Repeatedly runs DLS with increasing depth limits.
- **Bidirectional Search**: Runs two searches simultaneously from start and target to meet in the middle.

### Interactive Elements
- **Dynamic Grid**: Click and drag to draw walls/obstacles.
- **Movable Nodes**: Drag the **Start (Green)** and **Target (Red)** nodes to any position.
- **Real-time Visualization**: Watch the "frontier" expanding and "explored" nodes in real-time.
- **Depth Control**: Adjustable depth limit slider for DLS and IDDFS algorithms.

## 🛠️ Installation & Setup

1. **Clone the Repository**
   ```bash
   git clone https://github.com/Tahir0763/AI-Pathfinder.git
   cd AI-Pathfinder
   ```

2. **Prerequisites**
   - Python 3.x installed.
   - `tkinter` (usually comes pre-installed with Python).

3. **Run the Application**
   ```bash
   python "Search Algorithms (1).py"
   ```

## 🎮 How to Use

1. **Select an Algorithm**: Choose one of the search algorithms from the left sidebar.
2. **Draw Obstacles**: Click and drag on the grid to create walls (gray cells).
3. **Set Positions**: Drag the Green (Start) or Red (End) blocks to change their positions.
4. **Visualize**: Click the **VISUALIZE** button to start the animation.
5. **Reset**: Use **RESET GRID** to clear the board and start over.

## 🤝 Contributing
Contributions are welcome! Feel free to open issues or submit pull requests.

## 📜 License
This project is open-source and available for educational purposes.
