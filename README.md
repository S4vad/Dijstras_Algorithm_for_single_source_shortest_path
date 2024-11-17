# Dijkstra's Algorithm - Single Source Shortest Path

This repository implements Dijkstra's Algorithm in JavaScript for finding the shortest path between a single source and all other nodes in a weighted graph. It includes two versions of the implementation, showcasing different approaches for the priority queue.

---

## 🚀 Features

- **Efficient Shortest Path Calculation:** Uses Dijkstra's algorithm with a weighted graph.
- **Two Priority Queue Implementations:**
  - **Version 1:** Simple priority queue with array-based sorting.
  - **Version 2:** Optimized priority queue using a binary heap for improved performance.

---

## 🖥️ Tech Stack

- **Programming Language:** JavaScript (Node.js compatible)

---

## 📖 Table of Contents

- [About the Algorithm](#about-the-algorithm)
- [Code Versions](#code-versions)
  - [Version 1](#version-1)
  - [Version 2](#version-2)
- [How to Use](#how-to-use)
- [Example Usage](#example-usage)
- [Contributing](#contributing)
- [License](#license)

---

## 📜 About the Algorithm

Dijkstra's Algorithm is a greedy algorithm used for finding the shortest paths between nodes in a graph with non-negative weights. It is widely used in navigation systems, network routing, and other fields requiring shortest-path computations.

**Use Cases:**
- GPS navigation systems
- Network routing protocols
- AI pathfinding algorithms


---

## 📂 Code Versions

### **Version 1**
In this version:
- The priority queue is implemented using an **array**.
- Nodes are sorted after every `enqueue` operation based on their priority.
- Simpler implementation but less efficient.

---

### **Version 2**
In this version:
- The priority queue is implemented using a **binary heap** for better efficiency.
- Includes custom `Node` objects for each graph vertex.
- More optimized, especially for large graphs, as insertion and deletion operations in the heap are faster.

---

## ⚙️ How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/S4vad/Dijstras_Algorithm_for_single_source_shortest_path.git
   cd Dijstras_Algorithm_for_single_source_shortest_path

---

## ⭐ Acknowledgements
Dijkstra's Algorithm - Wikipedia
