# DSHA-AMP
This is about the benchmark, source code, solution certificates of our double-stage heuristic algorithm for the antibandwidth maximization problem (AMP, as a famous NP-hard problem).

------------------------------------------------------------------------
Benchmark:
Totally 256 instances in 11 diffirent sets, including 9 stardard benchmark instances and 2 instances of real applications.

- The first ten sets (Normal-Instance: 236 instances): are employed by Lozano et al. [1].
  They shared their results and original instances in https://grafo.etsii.urjc.es/optsicom/abp.html
  Here, we corrected a instance named 'mesh12_12' in this copied and removed the repeated instances (mesh30_34 and mesh34_30).
  
- The set (Sparse-Matrix: 20 instances) is introduced by Scott and Hu [2]
  The original source is published in https://sparse.tamu.edu/
  We made a conversion of the raw materia to have the same interface with the instances above.
  Notes that, 24 instances introduced by Scott and Hu [2], six (curtis54, can_445, 662_bus, nos6, dwt_234, and sherman4) also appear in the Harwell-Boeing set. Four of these (curtis54, can_445, 662_bus, and nos6) are identical in both collections, while the remaining two (dwt_234 and sherman4) are entirely different instances. Therefore, the 'Sparse-Matrix' category effectively contains 20 unique new instances.

------------------------------------------------------------------------
Source Code:
The manuscript is under reivew. The source code of the proposed algorithm will be uploaded upon the accptance of the paper.

------------------------------------------------------------------------
Solution certicates:
The solution for each instance labeled node from 0 not 1.


[1] Lozano M, Duarte A, Gortázar F, et al. Variable neighborhood search with ejection chains for the antibandwidth problem[J]. Journal of Heuristics, 2012, 18(6): 919-938.

[2] Scott J, Hu Y. Level-based heuristics and hill climbing for the antibandwidth maximization problem[J]. Numerical Linear Algebra with Applications, 2014, 21(1): 51-67.
