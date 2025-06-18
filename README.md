# tsp-python-lkl
A metric Traveling Salesman Problem (TSP) solver implemented in Python that combines the Lin-Kernighan gain criterion with various augmentations:

1. Usage of a spatial index (kd-tree for Euclidean problems, S2 for geographic problems) to efficiently and exactly enforce the gain criterion.
2. Edge elimination to prune the search space (number of edges reduced from O(n^2) to O(n)).
