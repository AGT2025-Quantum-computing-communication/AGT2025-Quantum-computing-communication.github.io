---
layout: default
title: Publications
permalink: /publications/
---
<!-- The following will generate a list of all your posts with clickable titles and dates -->
<h1>Publications list</h1>


[Chaos generalized synchronization of coupled Mathieu-Van der Pol and coupled Duffing-Van der Pol systems using fractional order-derivative](https://www.sciencedirect.com/science/article/pii/S0960077917300681)

[Entanglement dynamics of two-qubit and two-qutrit systems coupled to an XY-spin-chain environment: Simultaneous effects of Dzyaloshinskii–Moriya and Kaplan–Shekhtman–Entin-Wohlman–Aharony interactions](https://doi.org/10.1016/j.physb.2024.416691)
 
[Error correction based artificial neural network in multi-modes CV-QKD with simultaneous type-I and type-II parametric-down conversion entangled photon source](https://doi.org/10.1016/j.optcom.2024.130681). 

[Security and Communication Distance Improvement in Decoy States Based Quantum Key Distribution Using Pseudo-Random Bases Choice for Photon Polarization Measurement](https://doi.org/10.1007/s11082-021-03124-2) 

[Privacy amplification of entanglement parametric-down conversion based quantum key distribution via quantum logistic map for photon bases choice](https://doi.org/10.1016/j.chaos.2020.110110) 

[Entanglement Dynamics of a Two-qubit XYZ Spin Chain Under both Dzyaloshinskii-Moriya Interaction and Time-dependent Anisotropic Magnetic Field](https://doi.org/10.1007/s10773-020-04502-4)

[Triggering parametric-down conversion-based quantum key distribution via radiation field](https://doi.org/10.1142/S0219749920500379) 

[Generalized synchronization of regulate seizures dynamics in partial epilepsy with fractionalorder derivatives](
https://doi.org/10.1016/j.chaos.2019.109553)

[Generalized synchronization of the extended Hindmarsh–Rose neuronal model with fractional order 
derivative](https://doi.org/10.1016/j.chaos.2018.11.02)

[Teleportation of single and bipartite states via a two qubits xxz Heizenberg spin chain in a non-Markovian environment](https://doi.org/10.1016/j.physleta.2020.126719)  

[Chaos generalized synchronization of coupled Mathieu-Van der Pol and coupled Duffing-Van der Pol systems using fractional 
order-derivative](https://doi.org/10.1016/j.chaos.2017.03.012) 

[Comparative study of the dynamics of quantum entanglement, purity and degree of purity in two hybrid quantum systems: non-Markovian and Markovian regime]( https://doi.org/10.1007/s73-022-05065-2)  

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
