---
title: "Machine learning supported annealing for prediction of grand canonical crystal structures"
collection: publications
permalink: /publication/2024-machine-learning-csp
excerpt: 'Extend the annealing Crystal Structure Prediction code to arbitrary
potentials with machine learning.'
date: 2024-08-07
venue: 'Preprint'
paperurl: 'https://arxiv.org/abs/2408.03556'
authors: Yannick Couzinie, Yuya Seki, Yusuke Nishiya, Hirofumi Nishi, Taichi Kosugi, Tanaka Shu, Yu-ichiro Matsushita
---

[Download paper and citation here.]({{page.paperurl}})

Abstract
======
This study investigates the application of Factorization Machines with Quantum Annealing (FMQA) to address the crystal structure problem (CSP) in materials science. FMQA is a black-box optimization algorithm that combines machine learning with annealing machines to find samples to a black-box function that minimize a given loss. The CSP involves determining the optimal arrangement of atoms in a material based on its chemical composition, a critical challenge in materials science. We explore FMQA's ability to efficiently sample optimal crystal configurations by setting the loss function to the energy of the crystal configuration as given by a predefined interatomic potential. Further we investigate how well the energies of the various metastable configurations, or local minima of the potential, are learned by the algorithm. Our investigation reveals FMQA's potential in quick ground state sampling and in recovering relational order between local minima.
