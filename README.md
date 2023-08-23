# Benchmark and Simulation Data for Minimum Fault-Tolerant Connected Dominating Set Problem

&nbsp;

## **Benchmark Data**
The benchmark data is in the folder "./instance/", where the file name indicates the number of vertices and density of the undirected graph.
- The first row indicates the number of vertices and edges in graphs. 
- The other rows present the edge relationships.

For example, in the instance "v300_d20.txt", the graph has 30 vertices and 87 edges, where there is an edge between the vertex with index 1 and the vertex with index 2.

```
30 87 
1 2 
1 8 
1 16 
1 19 
...
...
```


## **Simulation Data**
The simulation data for four different application scenarios is in folder "./instance_bim/", where each folder contains the following files.
- ./1-1 ./2-2 ./3-3: Figures of the simulation results.
- ./bim_data.rvt: Revit file for BIM data.
- ./bim_data.json: SLS algorithm's input extracted from interface language.
- ./fig1.png ./fig2.png: For a quick glance.