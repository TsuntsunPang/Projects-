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
## The result shows that one extra term $S_t$  from constrain condition contributes to the two-body sacttering matrix. Since both $S_t$ and $S_{XXZ}$ satisfy the YBE equation, their product also satisfies the YBE. It means that the Constrained XXZ model is Yang-Baxter integrable.


# References 
## An Exactly Solvable Constrained XXZ Chain
## https://arxiv.org/abs/cond-mat/9904042
## A pedagogical review on solvable irrelevant deformations of 2D quantum field theory
## https://iopscience.iop.org/article/10.1088/1572-9494/abe4c9
##
##
##
