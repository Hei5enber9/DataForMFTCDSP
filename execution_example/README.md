# Execution Process of the Swap-Based Local Search Algorithm for the Minimum Fault-Tolerant Connected Dominating Set Problem

&nbsp;

This execution example, using the graph data from "./instances/v30_d20.txt" and parameters $k=m=2$, demonstrates the algorithm's process.
In each figure, vertices in $X^{*}$, $X^{+}$, and $X^{-}$ are marked by red, grey, and blue, respectively. 
During the execution process, the vertex removal set $RS$ records the sequence of vertices deleted from $X^*$, in order.
Red blocks represent the phase of shrinking feasible solutions, and green blocks represent the phase of local search.


The swap-based local search algorithm begins with the entire vertex set $V$. 
- When $|X^*|\ge 16$, the algorithm deems the solutions after shrinking as feasible, and thus, it skips the local search phase.  
- During the process of improving the feasible solution from $|X^*|=16$ to $|X^*|=13$, due to the infeasibility of the shrunken solutions, only one swap operation is performed in each local search stage.
- During the process of improving the feasible solution from $|X^*|=13$ to $|X^*|=12$, two swap operations are performed in the local search stage. 
- During the process of improving the feasible solution from $|X^*|=12$ to $|X^*|=11$, six swap operations are performed in the local search stage. Eventually, the optimal solution $X_{best}$ is found. 
- Note that the execution process illustrated here is conducted on a small-scale instance; for large-scale instances, the number of swap operations may significantly increase.

