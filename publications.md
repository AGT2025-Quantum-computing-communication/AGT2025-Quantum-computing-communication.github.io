---
layout: default
title: Publications
permalink: /publications/
---
<!-- The following will generate a list of all your posts with clickable titles and dates -->
<h1>Publications list</h1>

1- [A Highly Efficient Variational Quantum Algorithm for Solving the Poisson Equation on Quantum Computers](https://doi.org/10.1007/s11128-2)

**Abstract:** The Poisson equation is a cornerstone of mathematical physics and applied mathematics, governing a broad class of physical processes encountered in fields such as fluid mechanics, electrostatics, heat conduction, and various engineering applications. Solving high-dimensional Poisson equations remains computationally challenging for classical methods due to the rapid growth of computational resources required with problem size. In this work, we propose a highly efficient variational quantum algorithm (VQA) for solving the Poisson equation and demonstrate improved accuracy compared with existing quantum approaches. The proposed algorithm consists of three main stages: (i) reformulating the Poisson equation as an eigenvalue problem whose solution corresponds to the ground state of a suitably constructed Hamiltonian, (ii) applying Quantum Phase Estimation (QPE) to encode the Hamiltonian eigenvalues into an auxiliary quantum register, and (iii) employing a classical optimization procedure to maximize the probability of measuring the ground-state energy. We validate the algorithm using Qiskit simulations on Poisson equations with 4, 8, 16, 64, and 256 variables. Our results show that the algorithm achieves high target-state fidelity and low root-mean-square error (RMSE). In particular, the fidelity scales as $O(1-\varepsilon)$, where the error $\varepsilon$ decreases inversely with the number of measurements, approaching the Heisenberg limit. Furthermore, the RMSE decreases as the number of qubits in the energy register increases, leading to progressively more accurate solutions. We also demonstrate the practical feasibility of the approach on the $ibm \_ fez$ quantum processor, obtaining solutions with $\mathrm{RMSE}\lesssim10^{-3}$ for the 4 variables Poisson equation despite the presence of hardware noise. Additional experiments using the \textit{FakeFez} backend reveal that performance remains robust for moderate problem sizes but is ultimately limited by circuit depth on current noisy quantum devices. These results indicate that the proposed VQA provides an effective framework for solving Poisson equations on quantum computers and represents a promising approach for future fault-tolerant quantum architectures. More broadly, the method can be extended to a wide range of applications involving Hamiltonian ground-state preparation, including optimization, machine learning, and quantum chemistry.

2- [Solving a Linear System of Equations on a Quantum Computer by Measurement ](https://doi.org/10.48550/arXiv.2604.26098).
**Abstract:** We present a variational algorithm for fault tolerant quantum computing to solve a system of linear equations  which directly maximises the parameters of the target fidelity. This so-called measurement test algorithm can be applied to any computational task with a solution that is represented as eigenvector of a self-adjoint matrix. The solution is prepared as state of a register in the quantum computer by a von Neumann measurement of a corresponding observable, which is implemented using the phase estimation algorithm. The probability to project the system thus into the unknown target state, which equals the target fidelity,  is measured in terms of relative frequencies and iteratively optimised to read out the target state.   The new algorithm overcomes three issues of previous variational quantum algorithms: i) It does not rely on a decomposition in terms of Pauli strings and therefore can compute eigenvectors of dense matrices. ii) The accuracy  is not limited by the condition number $\kappa$ of the matrix, provided a logarithmic number ($O(\log\kappa)$) of qubits is used to encode the eigenvalues and iii) the target fidelity $F_T = 1-\epsilon$ can be reached with an accuracy that scales with $\epsilon \varpropto1/N$ for $N$ measurements per iteration. We demonstrate this by numerical simulations for dense random real-valued $16\times 16$ matrices with non-vanishing determinant.  

3- [A verification scheme for universal quantum computers](https://doi.org/10.1007/s11128-026-05193-2).

**Abstract:** We present a new verification scheme for universal quantum computers that yields the number of working qubits and measures the noise expected when executing quantum circuits. It is based on detecting the standard deviation of the meta-probability distribution of output values for a single qubit probed by random quantum gates involving all the qubits of the quantum computer. This result is generated directly from the output statistics of the quantum computer and thus does not require any assistance from classical computers. With current technology quantum computers with up to 40 qubits could be tested employing this method, but in future, given faster quantum processors, it might be used to demonstrate quantum supremacy. Our results have been successfully demonstrated on a real quantum computer (IBM-Cairo).

4- [Error correction based artificial neural network in multi-modes CV-QKD with simultaneous type-I and type-II parametric-down conversion entangled photon source](https://doi.org/10.1016/j.optcom.2024.130681).

**Abstract:** We model simultaneous type-I and type-II phase matching in a single non-linear crystal (NLC), based on a double periodically poled lithium niobate crystal. We also discuss entanglement based continuous variable quantum key distribution (CV-QKD), and the security of such scheme is analyzed considering an eavesdropper being capable of individual attacks. We further demonstrate efficiency of the artificial neural network (ANN) algorithm during post-processing or errors correction in such CV-QKD protocols. Results show that employing simultaneous type-I and type-II SPDC process in single NLC is a potential source to generate high dimensional (or hyper-entangled) states, strongly required for quantum information processing tasks, an example of CV-QKD. Security analysis of such a CV-QKD protocol shows a strong advantage of employing the above entangled photon state source, given that it provides a higher secure key rate and thus a secure communication within a larger distance. In addition, the suggested error correction algorithm is less time consuming and highly efficient, since full synchronization is achieved just after a few number of updates of trusted parties’ tree-parity-machines. Our results sufficiently demonstrate that the suggested CV-QKD is able to distribute secure keys in nearby inter-city areas, and therefore allows lower-cost secure communication networks.

5- [Privacy amplification of entanglement parametric-down conversion based quantum key distribution via quantum logistic map for photon bases choice](https://doi.org/10.1016/j.chaos.2020.110110)



[Security and Communication Distance Improvement in Decoy States Based Quantum Key Distribution Using Pseudo-Random Bases Choice for Photon Polarization Measurement](https://doi.org/10.1007/s11082-021-03124-2) 


[Entanglement dynamics of two-qubit and two-qutrit systems coupled to an XY-spin-chain environment: Simultaneous effects of Dzyaloshinskii–Moriya and Kaplan–Shekhtman–Entin-Wohlman–Aharony interactions](https://doi.org/10.1016/j.physb.2024.416691)
  

[Entanglement Dynamics of a Two-qubit XYZ Spin Chain Under both Dzyaloshinskii-Moriya Interaction and Time-dependent Anisotropic Magnetic Field](https://doi.org/10.1007/s10773-020-04502-4)

[Triggering parametric-down conversion-based quantum key distribution via radiation field](https://doi.org/10.1142/S0219749920500379) 

[Teleportation of single and bipartite states via a two qubits xxz Heizenberg spin chain in a non-Markovian environment](https://doi.org/10.1016/j.physleta.2020.126719)  

[Chaos generalized synchronization of coupled Mathieu-Van der Pol and coupled Duffing-Van der Pol systems using fractional 
order-derivative](https://doi.org/10.1016/j.chaos.2017.03.012) 

[Comparative study of the dynamics of quantum entanglement, purity and degree of purity in two hybrid quantum systems: non-Markovian and Markovian regime]( https://doi.org/10.1007/s73-022-05065-2) 

[Chaos generalized synchronization of coupled Mathieu-Van der Pol and coupled Duffing-Van der Pol systems using fractional order-derivative](https://www.sciencedirect.com/science/article/pii/S0960077917300681)

[Generalized synchronization of regulate seizures dynamics in partial epilepsy with fractionalorder derivatives](
https://doi.org/10.1016/j.chaos.2019.109553)

[Generalized synchronization of the extended Hindmarsh–Rose neuronal model with fractional order 
derivative](https://doi.org/10.1016/j.chaos.2018.11.02)
 

[Effect of Non-Commutative Space on Quantum Correlations in Two Bilinearly Coupled Harmonic Oscillators Interacting with its Environment](https://doi.org/10.1007/s10773-022-05065-2) 

[Decoherence dynamics of a charged particle within a nondemolition type interaction in non-commutative phase-space](https://doi.org/10.1088/1402-4896/ac0273)  

[Decoherence of quantum Brownian particle trapped in a penning potential in a non-commutative space](https://doi.org/10.1088/2399-6528/ab2b37) 

[Decoherence of a damped anisotropic harmonic oscillator under magnetic field effects in a two-dimensional noncommutative 
phase-space](https://doi.org/10.4236/jamp.2020.812207) 

[The dynamic of quantum entanglement of two dimensional harmonic oscillator in non-commutative space](https://doi.org/10.1088/1402-4896/ac42a9) 

[Novel Cryptography Technique via Chaos Synchronization of Fractional-Order Derivative Systems](https://doi.org/10.4018/978-1-5225-5418-9.ch01)     

<ul>
  {% for post in site.publications %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a> 
      <span> - {{ post.date | date: "%B %-d, %Y" }}</span>
    </li>
  {% endfor %}
</ul>
