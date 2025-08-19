# Network-Visualization-using-NetworkX
This project demonstrates the generation and visualization of Erdős-Rényi random graphs using the NetworkX library in Python. The Erdős-Rényi model is a fundamental model for random graphs, where each edge between nodes is created with a certain probability.
Overview

This project demonstrates the generation and visualization of Erdős-Rényi random graphs using the NetworkX library in Python. The Erdős-Rényi model is a fundamental model for random graphs, where each edge between nodes is created with a certain probability.

Objectives

Generate random graphs: Create two Erdős-Rényi random graphs with different edge creation probabilities.
Visualize the graphs: Use Matplotlib to plot the graphs, ensuring clarity in node sizes, edge thicknesses, and labels.
Implementation Steps

Define the Function: A function generate_er_network(n, p) is created to generate an Erdős-Rényi random graph with n nodes and an edge creation probability p.

Generate Graphs: Two random graphs are generated with:

n=50
n=50 nodes
p=0.05
p=0.05 (low density)
p=0.1
p=0.1 (medium density)

Visualization: 
Both graphs are plotted using Matplotlib, with adjustments made for:

Node sizes for better visibility
Edge thicknesses to distinguish between connections
Clear node labels for identification
Distinct visual styles for the two graphs to facilitate comparison.

Conclusion

This project effectively illustrates the use of the Erdős-Rényi model for generating random graphs and highlights the capabilities of NetworkX and Matplotlib for graph analysis and visualization.
