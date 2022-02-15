---
title: "Glauber dynamics simulations"
excerpt: "C program that produces the graphics for [my paper with Christian Hirsch](/publication/2021-weakly-reinforced-polya-urns-on-countable-networks) ([github](https://github.com/yannick-c/glauber_dynamics_c)).<br/><center><img src='/images/polya_init.png'><img src='/images/polya_final.png'></center>"
date: 2019-08-26
collection: projects
---

[See the source code here](https://github.com/yannick-c/glauber_dynamics_c)

<center>
<video controls width="500">
        <source src="/files/polya.webm" type="video/webm">

        Sorry, your browser does not support embedded videos.
</video>
</center>

Glauber dynamics in continuous time are a specific example of a Markov Chain
Monte Carlo algorithm in which we put a Poisson point process on each vertex of
a graph, and when a clock rings update the configuration on the graph following
model-specific rules.

The model
-----
In my [master's thesis](/theses/master-thesis) and [my paper with Christian
Hirsch](/publication/2021-weakly-reinforced-polya-urns-on-countable-networks)
each ring checks its incident edges for their weight, and
proportionally to that picks an edge and increments its edge. If the
proportionality is not linear but sublinear, we find that , as time
goes on, the edge weights should homogenize which is why towards the
end of the video the graph looks translationally invariant. In the
above video the edge weights are illustrated by their thickness. 

The code
-----
The code is written entirely in C11 and uses modern frameworks like [doxygen for
documentation](https://yannick-c.github.io/glauber_dynamics_c/) and
[autoconf](https://github.com/yannick-c/glauber_dynamics_c/blob/master/configure.ac)/[make](https://github.com/yannick-c/glauber_dynamics_c/blob/master/Makefile.am) for compiling. Further, [unit tests](https://github.com/yannick-c/glauber_dynamics_c/blob/master/test/test_update_rules.c) are included.

The code is kept deliberately general as the initial idea was to have a single
code base for myself in which I could implement simulations of the various
interacting particle systems (IPS) I would encounter during my Ph.D. In the end this
has not happened since for the IPS I dealt with in my Ph.D. it was the vertices
of the graphs that had the interesting states and not the edges. Instead
of implementing a switch for the output (i.e. graph as in the video above for
edge-based dynamics and simple matrix without edges for vertex based models)
I wrote [shorter and simpler scripts in Python](/projects/2022-east) for these cases.
