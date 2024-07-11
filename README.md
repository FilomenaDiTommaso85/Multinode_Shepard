# Multinode_Shepard
Multinode_Shepard: a software package for the implementation of the multinode Shepard method. The folder contains the following file:
- demo_Stromboli: In this demo we approximate the Stromboli Volcano including the Sciara del Fuoco of 2002 lava flow surface from a data set of 95020 data stored in the file "Stromboli_nodes" on the 2000 points of the file "Stromboli_evaluations".
- demo_trial: In this demo we approximate a given function f by using as dataset Halton points in  [0,1]x[0,1]
- Multinode_Shepard1: corresponds to the implementation of the multinode Shepard method in which we associate to each interpolation node a $m$-tuple $\sigma_j$
- Multinode_Shepard2: correspond to the implementation of the multinode Shepard method in which we reduce the number of $m$-tuples
- powers: computes the powers of the monomial of $d$ variables
- mono_next_grlex: computes, one by one in graded lexicographic order, the monomials of $d$ variables of successively higher degrees.
- BivVand: computes the Bivariate Vandermonde Matrix 
