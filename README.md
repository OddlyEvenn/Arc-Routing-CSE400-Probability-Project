# 🧠 Probability Project: Randomized Arc Routing with Dijkstra's Algorithm

**Short Description:**  
A probability-based solution to the Arc Routing Problem using Dijkstra’s Algorithm. Incorporates traffic simulation with Poisson distribution and randomization in path selection. Includes basic, randomized, and multi-node versions to show the impact of congestion on shortest paths.

## 📌 About the Project

This project addresses the **Arc Routing Problem (ARP)** under real-world traffic conditions using **probabilistic modeling** and **Dijkstra’s Algorithm**. Each road segment’s traffic is simulated using the **Poisson distribution**, and a **congestion factor (α)** is applied to dynamically adjust travel times.

The primary goal is to explore how **randomization** impacts routing decisions, especially when multiple shortest paths exist. This models real-world behavior where decisions are affected by uncertainty and variable traffic.


## 🔧 Project Structure

| File Name                                | Description                                            |
|-----------------------------------------|--------------------------------------------------------|
| `SHORTEST_PATH_CODE.py`                 | Basic Dijkstra's Algorithm without randomization       |
| `RANDOMIZED_CODE.py`                    | Dijkstra with randomized selection for equal paths     |
| `RANDOMIZED_CODE_WITH_MULTIPLE_NODES.py`| Handles routing across multiple nodes with randomization|


## 🎯 Features

- ✅ Traffic-aware routing using Poisson-distributed vehicle counts  
- ✅ Congestion factor (α) modifies travel times dynamically  
- ✅ Deterministic and randomized path selection models  
- ✅ Multi-node routing support in advanced version  
- ✅ Graph visualization for before and after traffic changes  


## 🧪 Technologies Used

- Python
- NetworkX (for graph modeling)
- NumPy
- Matplotlib
- SciPy (for Poisson distribution)


## 🗺️ How to Run

1. **Clone the repository:**
```bash
git clone https://github.com/your-username/Arc-Routing-CSE400-Probability-Project.git
cd Arc-Routing-CSE400-Probability-Project
```

2. **Run the Code**
Make sure you have Python installed. Then run any of the files:
# Deterministic shortest path
python SHORTEST_PATH_CODE.py

# Randomized shortest path
python RANDOMIZED_CODE.py

# Randomized routing across multiple nodes
python RANDOMIZED_CODE_WITH_MULTIPLE_NODES.py

# You may need to install required packages using:
pip install networkx matplotlib numpy scipy
