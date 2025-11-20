# 📌 4. TSP — Brute Force + Held-Karp DP (Algorithm 4)  
### (Corrected: Now graphs work 100%)

### *Graph Observations*
#### *Brute-force*
- Time graph rises vertically after n=7.
- Memory usage increases slowly, but time is the bottleneck.

#### *Held-Karp DP*
- Faster than brute-force at first.
- Eventually also rises exponentially (but slower than brute-force).
- Memory usage is higher because DP requires storing bitmask tables.

### *Conclusion*
> Both brute-force & Held-Karp are exponential —  
> *Not usable beyond ~12 nodes*, even with optimization.
They are excellent for:
- Demonstrating NP-hard problems  
- Showing exponential growth in graphs  
But not for real delivery routing.

---
