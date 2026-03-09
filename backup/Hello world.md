This is the first blog for this experiment github blog web. As a test. 

But what should i write for the very first blog? 

Let me think.

Ok

## Spin contamination

What is spin contamination, it occurs when we use **UHF(abbr. for Unrestrictied Hartree Fock)**, in which we relax the spin orbitals so that the sptial part of such orbitals do not need to be the same between the $\alpha$ and $\beta$ ones. Therefore, in some cases such as bond dissociation we can evitate the error caused by the **RHF(abbr. for Restricted Hartree Fock)**.

So basically:
In RHF: 

$$
\psi^{\alpha}_{i} = \psi^{\beta}_{i}
$$

While in UHF:

$$
\psi^{\alpha}_{i}  \neq \psi^{\beta}_{i}
$$

However, this makes the wavefunction formed not the eigenfunction of $\hat{S}^2$. Thus people express a new form of wavefunction $\ket{\phi}$ as the unretricted state expanded by exact singlet, doublet, triplet ... 
in such that:

$$
\begin{align}
\langle^{1} \phi \rangle = c^{1}_{1} \ket{1} +  c^{1}_{3} \ket{3} + c^{1}_{5} \ket{5} + ...  \\
\langle^{2} \phi \rangle = c^{2}_{2} \ket{2} +  c^{2}_{4} \ket{4} + c^{2}_{6} \ket{6} + ... \\
\end{align}
$$

the exact spin states mentioned here may be refered to as **configuration state functions(CSFs)**, obtained by making certain operations on the unstricted wavefunctions. 

Thus, such expansion introduces contaminations from higher spin states. This is exactly where spin contaminations come from.

### Reference:
Szabo A, Ostlund N S. Modern quantum chemistry: introduction to advanced electronic structure theory[M]. Courier Corporation, 2012.
