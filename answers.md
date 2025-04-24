# CMPS 2200 Assignment 5
## Answers

**Name:** Emily Aymond






- **1a.** The maxium depth is log_d n.


- **1b.** The work done by delete-min is O(d log_d n).
- The work done by insert is O(log_d n)


- **1c.** The work is O(∣V∣⋅d log_d ∣V∣+∣E∣⋅log_d∣V∣)

- **1d.** The value of d that yields an overall running time of O(|E|) is d = |E|/|V|.


- **2a.** 


- **2b.**


- **2c.**

- **2d.**

- **2e.**



- **3a.** No because MST minimizes total weight. It doesn't minimize max edge weight, so MMET might prefer a tree that has a bigger total weight but a smaller largest edge.


- **3b.** Using Kruskal's algorithm, sort the edges and find the msot optimal solution. Then, iterate though each edge and find an MST without the current edge. Do this until all of the edges in MST have been iterated through, and the minimum weight difference of that edge is the second lowest weight.


- **3c.** The overall work is O(E log E) because MST dominates runtime.
