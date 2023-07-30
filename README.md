# Kruskal-s-algorithm
To find Minimum Cost Spanning Tree of a given connected undirected 
graph using Kruskal's algorithm. Use Union-Find algorithms in your 
program.

# Time Complexity

Worst case time complexity of Kruskal’s Algorithm= O(ElogV) or O(ElogE)

# Analysis
• The edges are maintained as min heap.
• The next edge can be obtained in O(logE) time if graph has E edges.
• Reconstruction of heap takes O(E) time.
• So, Kruskal’s Algorithm takes O(ElogE) time.
• The value of E can be at most O(V2).
• So, O(logV) and O(logE) are same.

# Special Case-
• If the edges are already sorted, then there is no need to construct min heap.
• So, deletion from min heap time is saved.
• In this case, time complexity of Kruskal’s Algorithm = O(E + V)
