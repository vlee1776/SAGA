# SAGA
Reproduction of results from doing convex optimization through SAGA. 
You can find the paper here: http://papers.nips.cc/paper/5258-saga-a-fast-incremental-gradient-method-with-support-for-non 

# Abstract 
SAGA improves on the theory behind SAG and SVRG, with better theoretical convergence rates, and has support
for composite objectives where a proximal operator is used on the regulariser. Unlike SDCA, SAGA supports non-strongly convex problems directly, and is adaptive to any inherent strong convexity of the problem.