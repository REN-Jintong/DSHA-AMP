# DSHA-AMP
This is about the benchmark, source code, solution certificates of our double-stage heuristic algorithm for the antibandwidth maximization problem (AMP, as a famous NP-hard problem).

------------------------------------------------------------------------
Benchmark: see "Normal-Instance" and "Sparse-Matrix"

Totally 256 instances in 11 diffirent sets, including 9 stardard benchmark instances and 2 sets of instances from real applications.

- The first ten sets (Normal-Instance: 236 instances) are employed by Lozano et al. [1].
  They shared their results and original instances in https://grafo.etsii.urjc.es/optsicom/abp.html
  Here, we corrected a instance named 'mesh12_12' in this copied and removed the repeated instances (mesh30_34 and mesh34_30).
  
- The set (Sparse-Matrix: 20 instances) is introduced by Scott and Hu [2]
  The original source is published in https://sparse.tamu.edu/
  We made a conversion of the raw matieria to have the same interface with the instances above (removing unused information, the repeated edges as well as the self-loop).
  Notes that, 24 instances introduced by Scott and Hu [2], six (curtis54, can_445, 662_bus, nos6, dwt_234, and sherman4) also appear in the Harwell-Boeing set. Four of these (curtis54, can_445, 662_bus, and nos6) are identical in both collections, while the remaining two (dwt_234 and sherman4) are entirely different instances. Therefore, the 'Sparse-Matrix' category effectively contains 20 unique new instances.

------------------------------------------------------------------------
Source Code:

This work has been accepted for publication in Computers & Operations Research. The source code is currently being prepared and will be released around the beginning of September. 


------------------------------------------------------------------------
Solution certicates: See "Solution.zip"

The solution for each instance labeled node from 0 not 1.

------------------------------------------------------------------------
Objective value: See "ObjectiveValue"

There are four csv files storing the instance name, number of node, reference results, our results, the computational time of our algorithm, the lower bound and the upper bound obtained by CPLEX 22
- 1_first7.csv: 164 instances, including the families of path, cycle, mesh, toroidal, hypercube, cbt and hamming
- 2_8_9.csv: 48 instances, including 3dmesh and caterpillar.
- 3_HB.csv: 24 instances, Harwell-Boeing
- 4_NR.csb: 20 instances, Sparse-Matrix


------------------------------------------------------------------------
[1] Lozano M, Duarte A, Gortázar F, et al. Variable neighborhood search with ejection chains for the antibandwidth problem[J]. Journal of Heuristics, 2012, 18(6): 919-938.

[2] Scott J, Hu Y. Level-based heuristics and hill climbing for the antibandwidth maximization problem[J]. Numerical Linear Algebra with Applications, 2014, 21(1): 51-67.
