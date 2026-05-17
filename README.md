# 🧠 IDA* Algorithm Visualization — Interactive Iterative Deepening A* Pathfinding Demo

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![Algorithm](https://img.shields.io/badge/Algorithm-IDA*-blueviolet?style=for-the-badge)
![AI](https://img.shields.io/badge/Artificial%20Intelligence-Search%20Algorithms-success?style=for-the-badge)

An interactive visualization of the **Iterative Deepening A\*** (**IDA\*** ) search algorithm — one of the most important memory-efficient pathfinding and artificial intelligence search algorithms used in AI, robotics, game development, and route optimization.

This project demonstrates how the **IDA\*** algorithm works step-by-step using the classic **Romania Map Problem** from *Artificial Intelligence: A Modern Approach* by Stuart Russell and Peter Norvig.

> 🚀 **Live Demo:**  
> https://boiakay.github.io/ida-star-visualization/

---

# 📚 What is the IDA* Algorithm?

The **Iterative Deepening A\*** (**IDA\*** ) algorithm is a graph traversal and pathfinding algorithm that combines:

- the **space efficiency of Depth-First Search (DFS)**, and
- the **optimality of A\*** search.

Unlike traditional A\* search, IDA\* uses significantly less memory because it performs repeated depth-first searches with increasing cost thresholds.

IDA\* is widely used in:

- 🧩 Puzzle Solvers (15 Puzzle, Rubik’s Cube)
- 🎮 Game AI
- 🤖 Robotics Navigation
- 🗺️ Route Planning
- 🧠 Artificial Intelligence Research
- 🚗 Autonomous Systems

---

# 🔍 IDA* Algorithm Formula

```math
f(n)=g(n)+h(n)
```

Where:

- **g(n)** = actual cost from the start node
- **h(n)** = heuristic estimated cost to the goal
- **f(n)** = total estimated path cost

The algorithm repeatedly increases the search threshold until the optimal path is found.

---

# 🎯 Why This IDA* Visualization is Useful

Understanding IDA\* from textbooks alone can be difficult. This visualization helps learners:

- See how thresholds evolve during iterative deepening
- Understand backtracking in real time
- Compare heuristic costs dynamically
- Visualize optimal path discovery
- Learn AI search algorithms interactively

Perfect for:

- 🎓 Students learning Artificial Intelligence
- 👨‍💻 Developers implementing pathfinding algorithms
- 🧪 Researchers studying heuristic search
- 📖 Educators teaching AI concepts

---

# ✨ Features

## ⚡ Interactive IDA* Algorithm Visualization

Watch the algorithm explore paths dynamically on the Romania map.

## ⏱️ Adjustable Animation Speed

Control the visualization speed from slow motion to instant execution.

## 📊 Real-Time Cost Table

Live updates for:

- `g(n)` → path cost
- `h(n)` → heuristic value
- `f(n)` → evaluation function

## 🎨 HTML5 Canvas Rendering

The graph is rendered dynamically using HTML5 Canvas for smooth animations and clean visuals.

## 🧠 Step-by-Step Search Exploration

Observe:

- node expansion
- pruning
- threshold updates
- backtracking
- final optimal route

## 🚫 Zero Dependencies

Built using pure:

- HTML
- CSS
- JavaScript

No frameworks, no libraries, no build tools.

---

# 🧪 How the IDA* Algorithm Works

The algorithm performs repeated depth-first searches while gradually increasing the cost threshold.

## Initial Threshold

```math
threshold = h(start)
```

## During Search

For every node:

- compute `f(n)`
- continue if `f(n) <= threshold`
- prune otherwise

## If Goal Not Found

Increase threshold to the minimum exceeded cost and repeat.

This makes IDA\* far more memory efficient than standard A\* search.

---

# 🗺️ Romania Map Problem

This project uses the famous Romania road map example from AI literature.

The visualization demonstrates finding the optimal route between cities using heuristic search.

Popular cities included:

- Arad
- Sibiu
- Fagaras
- Bucharest
- Rimnicu Vilcea
- Pitesti

---

# 🚀 Getting Started

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/boiakay/ida-star-visualization.git
```

## 2️⃣ Open the Project

Simply open:

```bash
index.html
```

in your browser.

No installation required.

---

# 🛠️ Technologies Used

- HTML5
- CSS3
- Vanilla JavaScript
- HTML5 Canvas API

---

# 📖 Educational Value

This project is highly useful for courses related to:

- Artificial Intelligence
- Search Algorithms
- Pathfinding
- Heuristic Search
- Graph Theory
- Computer Science Education

It can also be used in:

- university assignments
- AI demonstrations
- classroom teaching
- algorithm presentations

---

# 📈 SEO Keywords

IDA* algorithm, Iterative Deepening A*, IDA* visualization, IDA* pathfinding, artificial intelligence search algorithms, heuristic search visualization, A* vs IDA*, Romania map problem, AI algorithms, graph traversal, pathfinding visualization, AI learning project, JavaScript algorithm visualization, interactive AI demo, memory efficient search algorithm

---

# 🤝 Contributing

Contributions are welcome.

If you'd like to improve the visualization, optimize the algorithm, or add new maps and heuristics, feel free to fork the repository and submit a pull request.

---

# ⭐ Support the Project

If you found this project useful:

- ⭐ Star the repository
- 🍴 Fork the project
- 📢 Share it with AI and algorithm enthusiasts

---

# 📜 License

This project is open-source and available under the MIT License.

---

# 🔗 Related Topics

- A\* Search Algorithm
- Breadth-First Search (BFS)
- Depth-First Search (DFS)
- Heuristic Functions
- Graph Search Algorithms
- Artificial Intelligence Pathfinding
- Memory Efficient Search Algorithms
