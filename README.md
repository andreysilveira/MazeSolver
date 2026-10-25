# 🧩 Maze Solver

**A Java-based maze solver that explores possible paths to find the exit.**

Maze Solver is a Java project that explores a maze using directional movement and path validation. The program identifies the entrance and exit, checks available paths, and determines whether the exit can be reached.

## 📌 About the Project

Maze Solver is a learning project focused on programming logic, algorithmic thinking, and problem-solving through maze exploration.

The program works with predefined maze layouts and searches for the entrance and exit positions. Once these positions are identified, it explores possible movements while checking for walls and obstacles.

During execution, the program displays coordinates and movement possibilities, helping illustrate how a maze can be explored programmatically.

The objective is to determine whether a valid path from the entrance to the exit exists.

## ✨ Features

- 🗺️ Predefined maze layouts.
- 🚪 Entrance (`E`) and exit (`S`) detection.
- 🧭 Four-directional movement: up, down, left, and right.
- 🧱 Wall and obstacle detection.
- 📍 Coordinate-based navigation.
- 🔎 Exploration of available paths.
- ✅ Verification of whether the exit can be reached.
- ❌ Handling of mazes with no reachable exit.

## ⚙️ How It Works

The program follows a sequence of steps to explore the maze:

1. **Maze initialization:** Loads a predefined maze layout.
2. **Position detection:** Identifies the entrance (`E`) and exit (`S`).
3. **Path exploration:** Checks possible movements in four directions.
4. **Obstacle validation:** Determines whether each potential movement is blocked or available.
5. **Navigation:** Continues exploring available paths according to the implemented movement logic.
6. **Result evaluation:** Determines whether the exit has been reached.

This process demonstrates how a program can navigate a grid-based environment by evaluating possible movements and obstacles.

## 🧱 Maze Legend

The following table describes the intended maze representation. Confirm that these symbols match the characters used in the source code.

| Symbol | Description |
|:---:|---|
| `E` | Entrance |
| `S` | Exit |
| `*` | Wall or blocked path, depending on the implementation |
| ` ` | Open space available for movement |

## 🛠️ Technologies

- **Java** — programming language used to implement the maze exploration logic.
- **IntelliJ IDEA** — recommended development environment.

## 🚀 Getting Started

Follow these instructions to run the project locally.

### Prerequisites

Before running the project, make sure you have:

- A Java Development Kit (JDK) installed.
- IntelliJ IDEA or another Java-compatible IDE.

### Installation

**1. Clone the repository**

```bash
git clone https://github.com/andreysilveira/maze-solver.git
```

**2. Open the project**

Open the cloned project directory in IntelliJ IDEA or your preferred Java IDE.

**3. Configure Java**

Ensure that the project is configured to use an installed JDK compatible with the source code.

**4. Run the application**

Locate the Java class containing the `main` method and run it through your IDE.

> If you rename the GitHub repository from `labirinto` to `maze-solver`, use the updated repository URL when cloning it.

## 🎯 Learning Objectives

This project provides an opportunity to practice fundamental programming and algorithmic concepts:

- **Problem-solving:** Breaking a navigation problem into smaller steps.
- **Control flow:** Using conditional statements and loops to evaluate possible movements.
- **Coordinate systems:** Representing and navigating positions within a grid.
- **Grid representation:** Modeling a maze using a structured layout.
- **Obstacle detection:** Checking whether a movement is valid.
- **Path exploration:** Investigating possible routes through a maze.
- **Algorithmic thinking:** Developing a systematic approach to reaching a destination.

## 🔮 Future Improvements

The project could be extended with additional features and pathfinding algorithms.

- [ ] Allow users to define custom maze layouts.
- [ ] Implement Depth-First Search (DFS) for systematic path exploration.
- [ ] Track visited positions to prevent unnecessary repeated exploration.
- [ ] Display the path taken from the entrance to the exit.
- [ ] Add a visual representation of the maze and the solver's movements.
- [ ] Implement Breadth-First Search (BFS) to find the shortest path in an unweighted maze.
- [ ] Compare the behavior of different pathfinding algorithms.
- [ ] Add automated tests for valid paths, blocked exits, and unreachable destinations.

## 📚 Possible Algorithmic Extensions

Two algorithms that could make interesting extensions to this project are:

### Depth-First Search (DFS)

DFS explores one path as far as possible before backtracking to investigate alternatives. It is useful for systematically exploring a maze, although it does not guarantee the shortest path.

### Breadth-First Search (BFS)

BFS explores positions level by level. When every movement has the same cost, it can find the shortest path to the exit in terms of the number of moves.

These are potential extensions and should not be considered implemented features unless they are present in the source code.

## 👨‍💻 Author

**Andrey Silveira**

- GitHub: [@andreysilveira](https://github.com/andreysilveira)

## 📄 License

No license has been specified in this README. Add a license section once a license has been selected and included in the repository.

---

<p align="center">
  Built with Java to explore maze navigation and algorithmic problem-solving.
</p>
