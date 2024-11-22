Visual Simulation of the Fiduccia-Mattheyses Algorithm (FM Algorithm)

The Fiduccia-Mattheyses (FM) Algorithm is a key optimization technique in VLSI CAD, focusing on minimizing the cut size in circuit partitioning. This Python project provides a dynamic visual simulation of the FM Algorithm, making it easier to understand its iterative process and impact on graph partitioning.  

####Project Highlights
1. Dynamic Visualization:  
   - Real-time partition updates with color-coded nodes (blue and red) to represent different groups.  
   - Cut edges crossing partitions are highlighted to illustrate optimization progress.  

2. Core FM Algorithm Implementation:  
   - Cut-Size Calculation: Tracks the number of edges crossing partitions.  
   - Gain Calculation: Evaluates node movement benefits by computing the difference between external and internal connections.  
   - Node Movement: Moves the highest-gain node to optimize the partition iteratively.  

3. Interactive Insights:  
   - Visual representation of the bucket list gain analysis using bar charts for each node.  
   - Iteration-by-iteration updates provide clarity on how the algorithm improves the solution.  

#### Technical Stack  
- NetworkX: For graph representation and manipulation.  
- Matplotli: For creating dynamic visualizations.  
- Python: To implement the FM Algorithm and simulate the process step-by-step.  

This project demonstrates the FM Algorithm’s effectiveness in optimizing circuit partitioning and serves as a practical learning tool for VLSI enthusiasts.  


Feel free to explore and share your thoughts!
