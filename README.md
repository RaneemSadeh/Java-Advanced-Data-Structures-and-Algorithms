# Advanced Data Structures & Algorithms in Java

A Java-based console project that demonstrates the implementation and analysis of advanced data structures and algorithms in real-world task management scenarios. The project emphasizes hands-on understanding of Abstract Data Types (ADTs), sorting performance, and graph algorithms.

---

## ✅ Core Features

- **Custom Data Structures**
  - **Linked List**: Manages the main list of active tasks, sorted by due date.
  - **Stack**: Holds urgent tasks in a Last-In, First-Out manner.
  - **Queue**: Records completed tasks in First-In, First-Out order.

- **Object-Oriented Design**
  - Modular classes with encapsulated logic
  - ADTs designed for reusability and clarity

- **Sorting Algorithm Comparison**
  - **Merge Sort (O(n log n))** vs. **Enhanced Selection Sort (O(n²))**
  - Tested across different input distributions and sizes

- **Graph Theory Implementation**
  - **Dijkstra's Algorithm** for non-negative edge weights
  - **Bellman-Ford Algorithm** for graphs with possible negative edges

---

## 🧱 System Architecture: Console-Based Task Manager

The project is structured around a terminal-based task management system with the following architecture:

### 1. Linked List (Active Tasks)
- Stores task objects sorted by due date
- Supports insertions, deletions, and traversal

### 2. Stack (Urgent Tasks)
- Tasks marked "urgent" are pushed onto a stack
- Ensures the most recent urgent task is handled first

### 3. Queue (Completed Tasks)
- When a task is completed, it is moved to the queue
- Maintains the order in which tasks were finished

---

## 📊 Algorithm Analysis

### Sorting: Merge Sort vs. Enhanced Selection Sort

- **Merge Sort**
  - Divide-and-conquer strategy
  - Consistent performance across sorted, reversed, and random inputs
  - Time Complexity: `O(n log n)`

- **Enhanced Selection Sort**
  - Simple nested-loop algorithm
  - Degrades significantly as data size increases
  - Time Complexity: `O(n²)`

Result: Merge Sort is vastly superior for large datasets.

---

### Graph Algorithms: Dijkstra vs. Bellman-Ford

#### Dijkstra’s Algorithm
- Efficient for non-negative edge weights
- Single-source shortest path
- Time Complexity: `O(V²)`

#### Bellman-Ford Algorithm
- Works with negative weights
- Detects negative weight cycles
- Time Complexity: `O(V * E)`

Used to model interdependent tasks or processes with costs/delays.

---

## 🚀 Getting Started

### Requirements

- Java Development Kit (JDK)

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/Java-Advanced-Data-Structures-and-Algorithms.git
cd Java-Advanced-Data-Structures-and-Algorithms
