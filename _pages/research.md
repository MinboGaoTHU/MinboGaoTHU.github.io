---
layout: academic
title: "Research"
permalink: /research/
author_profile: false
---

My research concerns the theoretical foundations of quantum computing. My two main directions are quantum algorithms and complexity, and quantum programming languages and semantics. Quantum optimal transport is a mathematical research theme that connects to my work on relational logics and also raises independent questions.

## Quantum Algorithms & Complexity
{: #algorithms }

I study how mathematical structure can guide the design of quantum algorithms, and how lower bounds characterize their computational limits.

- **Quantum dynamics and simulation.** Hamiltonian and Lindbladian simulation, quantum linear systems, and ground-state preparation are central interests. I investigate the mathematical structure that enables efficient algorithms for these tasks.
- **Optimization, sampling, and learning.** My work includes quantum algorithms for zero-sum games, graph and hypergraph problems, sampling random spanning trees, and estimating functionals of probability distributions.
- **Complexity and lower bounds.** I study limits on quantum computation, including communication lower bounds for search problems and the query complexity of quantum algorithms.
- **General algorithmic techniques.** I am particularly interested in algorithmic frameworks, polynomial methods, and the composition of quantum subroutines.

{% include research-publications.html area="algorithms" %}

## Quantum Programming Languages & Semantics
{: #semantics }

Program equivalence and relational reasoning are central questions in my work on quantum programming languages: how can we describe and prove relationships between quantum programs, and how faithfully do logical systems capture their semantics?

- **Program equivalence and relational reasoning.** I study mathematical foundations for comparing quantum programs and reasoning about relationships between their behaviors.
- **Relational quantum Hoare logics.** My work develops logical systems for reasoning about pairs of quantum programs, with particular attention to soundness and completeness.
- **Soundness and completeness.** Quantum optimal transport duality has been a key mathematical tool in proving completeness results for relational program logics, including my LICS work.
- **Infinite-dimensional and classical–quantum programs.** These settings require reasoning about infinite-dimensional states and unbounded assertions, as well as the interaction between classical and quantum data.

{% include research-publications.html area="semantics" %}

## Quantum Optimal Transport
{: #transport }

I study quantum optimal transport both for its applications to program reasoning and as a mathematical subject in its own right. These interests overlap with my work in programming languages without being limited to it.

- **Duality and mathematical foundations.** I am interested in quantum couplings and transport duality, including the mathematical issues that arise in infinite-dimensional settings.
- **Applications to relational program logics.** Transport duality provides a connection between reasoning about quantum couplings and establishing completeness of relational logics.
- **Transport costs and metrics.** I investigate coupling-based formulations of quantum transport and the conditions under which transport costs can define distances between quantum states. My work on fixed cost operators examines limitations of such metric constructions.

{% include research-publications.html area="transport" %}

## Future Directions

An emerging interest is the connection between quantum algorithms and programming languages: how program representations and compilation can preserve semantic guarantees, mathematical structure, and resource bounds. I would like to explore these questions alongside my current work in algorithms, semantics, and quantum optimal transport.

For the full list of papers, see [Publications]({{ '/publications/' | relative_url }}). My [academic activities]({{ '/academic-activities/' | relative_url }}) page lists talks, workshops, and research visits.
