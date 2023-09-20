# Travelling-Salesman-Problem-TSP-Solution-with-IBM-Cplex-Solve

#### Introduction

The Travelling Salesman Problem (TSP) is one of the most well-studied problems in the realm of optimization and computational mathematics. At its core, the problem involves a salesman who needs to visit a number of cities, but seeks to minimize his travel costs by finding the shortest possible route that ensures he visits each city only once and then returns to his starting point.

#### Problem Statement

Given a list of 20 cities, each with its unique location, and the pairwise distances between them, the challenge is to determine the most efficient route such that:

1. Every city is visited precisely once.
2. The total distance traveled by the salesman is minimized.
3. The salesman returns to the original starting city after visiting all the others.

**Calculation**


![image](https://github.com/adityasarkar123/Travelling-Salesman-Problem-TSP-Solution-with-IBM-Cplex-Solve/assets/112374443/c32c5734-8916-46dd-9994-8ab8943886a1)

#### Importance of the Problem

At a glance, the TSP might appear as a mere puzzle or mathematical curiosity, but its implications are vast:

- **Logistics and Transportation**: Companies need efficient routes for delivery trucks, especially when serving multiple locations.
  
- **Manufacturing**: In circuit manufacturing, the problem of optimizing the layout of a circuit to minimize the amount of wire used is analogous to TSP.
  
- **Astronomy**: The problem of determining the shortest path for a telescope to observe multiple objects can be seen as a TSP.

- **Genomics**: Sequencing DNA, particularly ordering fragments in the most likely arrangement, can be likened to TSP.

#### Complexity

The reason TSP remains significant is due to its combinatorial nature. The number of possible routes a salesman can take grows factorially with the number of cities. For 20 cities, there are roughly 2.43 x 10^18 possible routes to consider. Brute-forcing through each of these routes is computationally infeasible.

Because of this complexity, exact algorithms can only solve TSP for relatively small datasets, while heuristic or approximation methods are applied for larger datasets.

#### Broadening the Problem

While our primary focus is on 20 cities, the techniques and algorithms developed can be adapted and scaled to handle more cities, albeit with increasing computational requirements. It also serves as a foundational problem from which many real-world optimization problems can be derived, making it a cornerstone in the study of algorithmic problem-solving.

#### Conclusion

The Travelling Salesman Problem, while seemingly simple in its description, represents a deep and intricate challenge that bridges pure mathematics, computer science, and practical real-world applications. By seeking to solve the TSP for a set of 20 cities, we are not just finding a route but engaging with a problem that has captivated and challenged researchers for decades.
