circulant
=========

A LaTeX program for creating circulant graphs.

Using tikz this code will draw a circulant graph C_n(S),
(where n is the number of vertices and S is a list of adjacencies).

A circulant graph can be drawn by merely calling $\Circulant{n}{s1,s2,...,sk}$.

Then each node, v_i for i from 1 to n, will have adjacencies v_i +- s1,...,v_i +- sk mod n.
