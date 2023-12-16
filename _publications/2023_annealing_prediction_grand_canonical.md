---
title: "Annealing for prediction of grand canonical crystal structures: Efficient implementation of n-body atomic interactions"
collection: publications
permalink: /publication/2023-annealing-prediction-grand-canonical
excerpt: 'In this research we present an encoding of multi-body interactions
into HUBOs and first analysis results on annealing machines.'
date: 2023-07-06
venue: 'Preprint'
paperurl: 'https://arxiv.org/abs/2307.03123'
authors: Yannick Couzinie, Yusuke Nishiya, Hirofumi Nishi, Taichi Kosugi, Hidetoshi Nishimori, Yu-ichiro Matsushita
---

[Download paper and citation here.]({{page.paperurl}})

Abstract
======
We propose an annealing scheme usable on modern Ising machines for crystal structures prediction (CSP) by taking into account the general n-body atomic interactions, and in particular three-body interactions which are necessary to simulate covalent bonds. The crystal structure is represented by discretizing a unit cell and placing binary variables which express the existence or non-existence of an atom on every grid point. The resulting quadratic unconstrained binary optimization (QUBO) or higher-order unconstrained binary optimization (HUBO) problems implement the CSP problem and is solved using simulated and quantum annealing. Using the example of Lennard-Jones clusters we show that it is not necessary to include the target atom number in the formulation allowing for simultaneous optimization of both the particle density and the configuration and argue that this is advantageous for use on annealing machines as it reduces the total amount of interactions. We further provide a scheme that allows for reduction of higher-order interaction terms that is inspired by the underlying physics. We show for a covalently bonded monolayer MoS2 crystal that we can simultaneously optimize for the particle density as well as the crystal structure using simulated annealing. We also show that we reproduce ground states of the interatomic potential with high probability that are not represented on the initial discretization of the unit cell.
