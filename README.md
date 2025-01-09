# FOC_Project2 - Gnome Hat Color Analysis

## Overview
This project addresses a logical puzzle involving gnomes in a fairyland who can see each other's hat colors but not their own. Observations (evidences) about hat colors are analyzed to deduce consistent conclusions or identify contradictions. The challenge spans four interconnected questions, each building on the previous.

### Problem Setup
- **Hat Colors:** Encoded as `1` (white) and `0` (black).
- **Evidence:** A list of tuples containing:
  - A pair of gnome IDs.
  - The number of white hats observed on them (`0`, `1`, `2`).

### Key Features
1. **Contradiction Detection:** Identify whether evidences are consistent or contain contradictions.
2. **Graph Representation:** Model gnome pairs with differing hat colors as a graph.
3. **Reasoning with Graphs:** Traverse the graph to deduce hat colors using depth-first search (DFS).

## Technologies  
- Python  

### Contributors
- Ryan Huang
- University Of Melbourne COMP10001 Teaching Team (Question Provider)

## How to Run
Clone the repository and run the Python scripts for each question:
```bash
git clone https://github.com/MoltoRubato/FOC_Project2.git
cd FOC_Project2
python3 P2Q1.py
python3 P2Q2.py
python3 P2Q3.py
python3 P2Q4.py
