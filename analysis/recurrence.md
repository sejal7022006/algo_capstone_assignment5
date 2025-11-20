# 📌 1. Recurrence-Based TSP (Algorithm 1)

### *Graph Observations*
- Time curve increases *exponentially* as number of cities grows.
- Memory also increases because recursion depth expands with city count.
- Memoization slows the rise but does not prevent exponential blow-up.

### *Conclusion*
> Recurrence-based TSP is exponential *O(2ⁿ)*.  
Works only for small n ≤ 12.  
Not suitable for real-world logistics.

---
