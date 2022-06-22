---
title: "The multidimensional East model: a multicolour model and a front evolution problem"
collection: theses
permalink: /theses/phd-thesis
excerpt: Ph.D thesis of Yannick Couzinie
date: 2022-06-13
thesis_type: Ph.D.
degree_name: 'Ph.D. in Mathematics'
university_name: 'Roma Tre University'
---

[Download thesis here]({{base_path}}/files/2022_phd_thesis.pdf)

[Download presentation slides
here]({{base_path}}/files/2022_phd_thesis_presentation.pdf)

Abstract
=====

In this thesis we consider two problems related to the multidimensional East model on $$\mathbb{Z}^d$$, a
well studied kinetically constrained model (KCM). KCM are interacting particle
models in which the local configurations are updated with equilibrium only if
the configuration in the neighbourhood of the update satisfies certain
constraints. Usually KCM are defined on a local $$0$$-$$1$$-state space where the
$$0$$s (or \emph{vacancies}) are the facilitating states and the $$1$$s (or
\emph{particles}) are the neutral ones. For the East model the constraints
for the update at $$x\in \mathbb{Z}^d$$ require a vacancy on a smaller neighbour $$y$$ in
the lexicographic order.

The first problem is a front evolution problem as the equilibrium density $$q$$
of the facilitating vertices vanishes. Starting with a unique unconstrained
vertex at the origin, let $$C(t)$$ consist of those vertices which became
unconstrained within time $$t$$ and, for an arbitrary positive direction
$$\mathbf{x}\in \mathbb{R}^d_+$$, let $$v_{\max}(\mathbf{x}), v_{\min}(\mathbf{x})$$ be
the maximal/minimal velocities at which $$C(t)$$ grows in that direction. If
$$\mathbf{x}$$ is independent of $$q$$, we prove that
$$v_{\max}(\mathbf{x})={v_{\min}(\mathbf{x})}^{(1+o(1))}=\gamma_d^{(1+o(1))}$$ as
$$q\rightarrow 0$$, where $$\gamma_d$$ is the spectral gap of the process on
$$\mathbb{Z}^d$$. We also analyse the case in which some of the coordinates of
$$\mathbf{x}$$ vanish as $$q\rightarrow 0$$. In particular, for $$d=2$$ we prove that
if $$\mathbf{x}$$ approaches one of the two coordinate directions fast enough,
then
$$v_{\max}(\mathbf{x})={v_{\min}(\mathbf{x})}^{(1+o(1))}=\gamma_1^{(1+o(1))}=\gamma_d^{d(1+o(1))}$$,
i.e.\ the growth of $$C(t)$$ close to the coordinate directions is dictated by
the one-dimensional process. As a result the region $$C(t)$$ becomes extremely
elongated inside $$\mathbb{Z}^d_+$$. Using these bounds on the front speed we identify an
elongated subset $$S(t)\subset C(t)$$ that grows in $$t$$ and which is mixing in
$$t\rightarrow \infty$$. In fact, remarkably, these bounds on the front speed
together with past results also imply a cutoff
result for the East process on a box in $$\mathbb{Z}^d$$.

The second problem is a coarse-grained model of glass forming
liquids introduced by Chandler and Garrahan
which is closely related to the East model. Instead of fixing a facilitation
direction in the model, we consider multiple types of facilitating vertices
that evolve on the same lattice, where each type behaves like a rotated version of
the East process, e.g.\ in $$d=2$$ one type requires a vacancy in the south-west
neighbourhood of updating vertices, one south-east, one north-east and one north-west.
The crux is that the neutral vertices, i.e.\ the particles in the East model,
are shared for all types of facilitating vertex. We call this model the
\emph{multicolour East model} (MCEM).  We prove that if the
number of species is equal to the maximum amount of possible rotations the
associated process, the MCEM process, is not ergodic. We then provide sufficient
conditions so that the MCEM process is ergodic and the spectral gap positive in
$$\mathbb{Z}^d$$. For example we show that in $$d=2$$ any MCEM process with three types of
facilitating vertices has a positive spectral gap.  Further, for $$d=2$$, we
analyse the scaling of the spectral gap when the minimum density $$q_{\min}$$ of
the facilitating vertex types tends to zero.  We show sufficient conditions on
the equilibrium distribution of the vertex types  that the spectral gap tends
to $$\gamma_2(q_{\min})$$ as $$q_{\min}\rightarrow 0$$. In particular, we show that
this is also the case when vertices of the least frequent facilitating vertex
type are surrounded by vertices of different types that inhibit their movement.
We do this through a fine analysis, whereby the frequent vertex type move and
remove each other in such a way as to clear the way for an effective
two-dimensional motion of the infrequent types.

A novel technical ingredient is a detailed analysis of the asymptotics of a
principal Dirichlet eigenvalue based on the renormalisation technique
of~Chleboun, Faggionato and Martinelli. This
analysis enters in both sets of results.




Recommended citation: Y. Couzinié. <i>"The multidimensional East model: a multicolour model and a front evolution problem"</i>. Ph.D thesis, Roma Tre University, 2022.

BibTeX (also [as a download]({{base_path}}/files/2022_phd.bib)):
```
@phdthesis{couziniePhd,
        author = "Yannick Couzini\'{e}",
        title = "The multidimensional East model: a multicolour model and a front evolution problem",
        school = "Roma Tre University",
        year = "2022",
        address = "Rome, Italy",
        month = jun
}
```
