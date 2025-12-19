# AI Vacuum Cleaning Agent – Search Algorithms Project

## Overview
This project implements an autonomous vacuum cleaning agent that navigates a grid-based environment using classical **search algorithms**. The agent plans efficient paths to clean multiple dirty cells while avoiding obstacles, allowing comparison of different uninformed and informed search strategies.

The project focuses on **algorithmic problem-solving, state-space search, and cost optimization**, rather than UI or machine learning.

---

## Features
- Grid-based environment with walls and multiple goal states
- Autonomous agent capable of path planning and execution
- Visualization of explored states and final solution path
- Configurable cost functions and heuristics
- Performance comparison across search strategies

---

## Search Algorithms Implemented
- **Breadth-First Search (BFS)**
- **Depth-First Search (DFS)**
- **Uniform Cost Search (UCS)**
- **Greedy Best-First Search**
- **A\* Search**

Each algorithm explores the environment differently, highlighting tradeoffs between optimality, exploration cost, and efficiency.

---

## Cost Functions & Heuristics
### Cost Functions
- Step-based movement cost
- Turn-aware cost (penalizes frequent direction changes)
- Directional bias costs (e.g., stay-left, stay-up strategies)

### Heuristics
- **Manhattan Distance**
- **Euclidean Distance**

These are used to guide informed search strategies and reduce unnecessary exploration.

---

## Project Structure
