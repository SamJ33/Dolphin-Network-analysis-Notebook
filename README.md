# Dolphin Social Network Analysis (SNA) Project

## Project Overview
This project analyzes the social network of 62 dolphins based on frequent associations among individuals. The network is undirected, representing mutual social interactions, and is commonly used as a canonical dataset in social network analysis (SNA) studies.

## Objectives
- Identify **leaders** (most connected dolphins) and **non-leaders** (least connected dolphins)
- Compute **degree** for each node to measure social influence and activity
- Analyze **shortest paths** to understand connectivity and information spread
- Visualize network structure and clusters in Python and Gephi

## Dataset
- **Source:** [SNAP — Dolphin Social Network](https://snap.stanford.edu/data/)
- **Nodes:** 62 (dolphins)
- **Edges:** 159 (associations)
- **Format:** GML (`dolphins.gml`) with node IDs and labels

## Implementation
- **Language & Libraries:** Python 3, NetworkX, Pandas, Matplotlib
- **Steps:**
  1. Load the GML dataset using `nx.read_gml()`
  2. Compute **degree**, **leaders**, and **non-leaders**
  3. Calculate **shortest paths** and average path lengths
  4. Visualize the network in Python and export edge list for Gephi

## Key Analyses
- **Degree Analysis:** Highlights central dolphins (leaders) and peripheral dolphins (non-leaders)
- **Shortest Path Analysis:** Measures how quickly social influence can propagate
- **Network Visualization:** Shows clusters, core-periphery structure, and central figures

## Deliverables
- Jupyter notebook with full analysis
- Network visualizations in Python and Gephi
- Exported edge list for further exploration

## How to Run
1. Place `dolphins.gml` in the project directory
2. Open the Jupyter notebook (`Dolphin_SNA.ipynb`)
3. Install required packages:
   ```bash
   pip install networkx pandas matplotlib
