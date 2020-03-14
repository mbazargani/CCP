
# A Cutoff Time Strategy based on the Coupon Collector's Problem
> Companion website
---
[Fernando G. Lobo](http://www.fernandolobo.info/), [Mosab Bazargani](http://www.eecs.qmul.ac.uk/profiles/bazarganimosab.html), and [Edmund K. Burke](https://scholar.google.co.uk/citations?user=rUHfmpQAAAAJ&hl=en&oi=ao)

[This website](https://mbazargani.github.io/CCP/) provides supplementary material for the research work described in the paper A Cutoff Time Strategy based on the Coupon Collector's Problem. The results given in this website were obtained from a comprehensive series of experiments on benchmarks of three well-known combinatorial optimization problems: Travelling Salesman Problem (TSP), Quadratic Assignment Problem (QAP), and Permutation Flowshop Scheduling Problem (PFSP).

Due to space restrictions, the above referenced paper only contains a subset of the results. In this website the complete results for all problem instances are presented. The paper abstract is replicated below.


## Abstract
Throughout the course of an optimization run, the possibility of yielding further improvement falls downward as the search proceeds, and eventually the search stagnates. Under such a state, letting the algorithm continue to run is a waste of time as there is little hope that subsequent improvement can be made. The ability to detect the stagnation point is therefore of prime importance. If such a point can be detected reliably, then it is possible to make better use of the computing resources, perhaps restarting the algorithm at the stagnation point, either with the same or with a different parameter configuration.

This paper proposes a cutoff time strategy, a method that is able to reliably detect the stagnation point for one-point stochastic local search algorithms applied to combinatorial optimization problems. The strategy is derived from the coupon collector's problem, and is scalable based on the employed perturbation operator and its induced neighbourhood size, as well as from feedback from the search. The suitability and scalability of the method is illustrated with the Late Acceptance Hill-Climbing algorithm on a comprehensive set of benchmark instances of three well-known combinatorial optimization problems: the Travelling Salesman Problem, the Quadratic Assignment Problem, and the Permutation Flowshop Scheduling Problem.
