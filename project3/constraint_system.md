## The XXZ model can be solved through coordinate Bethe ansatz (CBA),assuming the eigenstate of Hamitonian is the superposition of plane wave. The Hamitonian for spin-1/2 XXZ model in one dimension is given by 
 $$H_{XXZ}=-\frac{1}{2}\sum_{i=1}^{L}(\sigma_i^x\sigma_{i+1}^{x}+\sigma_i^y\sigma_{i+1}^y+\Delta \sigma_i^z\sigma_{i+1}^z)$$
## Here we take Yang-Yang notation. Where $\Delta$ is anisotropy papameter. The two-body scattering matrix $S(k_j,k_l)$ can be calculated as 
$$
S(k_j,k_l)=\frac{1-2\Delta e^{ik_j}+e^{i(k_j+k_l)}}{1-2\Delta e^{ik_l}+e^{i(k_j+k_l)}}
$$
## Where $k_j,k_l$ are momentums. We can write down the Bethe equation easily once we know the scattering matrix. The Hamitonian for constrainted integrable XXZ model is given by 
$$ H_{CXXZ}=-\frac{1}{2}\sum_{i=1}^{L}P_t(\sigma_i^x\sigma_{i+1}^{x}+\sigma_i^y\sigma_{i+1}^y+\Delta \sigma_i^z\sigma_{i+1}^z)P_t
$$ 
## where $P_t$ projects out the states where two up spins are at distance smaller or equal to $t$, following the CBA procedures, we can get the two-body sacttering matrix for the constrained XXZ model, the result is 
$$ S_C(k_j,k_l)=e^{it(k_j-k_l)}\frac{1-2\Delta e^{ik_j}+e^{i(k_j+k_l)}}{1-2\Delta e^{ik_l}+e^{i(k_j+k_l)}} =S_t\times S_{XXZ}$$
## The result shows that one extra term $S_t$  from constrain condition contributes to the two-body sacttering matrix. Since both $S_t$ and $S_{XXZ}$ satisfy the YBE equation, their product also satisfies the YBE. It means that the constrained XXZ model is Yang-Baxter integrable. The structure of the scattering matrix  is similar as the irrelavant deformation of the integrable point.The $S$-matrix is given by 
$$ S=S_{CDD}\times S_{I}$$
## we want to know the exact expression of $S$ when some constrains imposed on the system.
## In the Hamitonian level, the Hamitonian for CXXZ is similar as the famous PXP model, the Hamitonian for the PXP model is given by 
$$H=\sum_j P_{j-1}X_jP_{j+1}$$
## In the spin language, $X_j=\sigma_j^X$, when $X_j$ acts on spin state, it just flips the spin state. and $P_j=\frac{1-\sigma_j^z}{2}$,it is forbidden the nearest two sites spin up simutaneously.
## Numerical studies have observed that the PXP energy levels repel,thus confirming that the model is non-integrable
# References 
## An Exactly Solvable Constrained XXZ Chain
## https://arxiv.org/abs/cond-mat/9904042
## A pedagogical review on solvable irrelevant deformations of 2D quantum field theory
## https://iopscience.iop.org/article/10.1088/1572-9494/abe4c9
## Competing density-wave orders in a one-dimensional hard-boson model
## https://journals.aps.org/prb/abstract/10.1103/PhysRevB.69.075106
## Interacting Fibonacci anyons in a Rydberg gas
## https://journals.aps.org/pra/abstract/10.1103/PhysRevA.86.041601
