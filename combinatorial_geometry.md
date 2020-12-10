
# Combinatorics Seminar - December 8th 2020
## Combinatorial Geometry
### Based on "Extremal problems for pairs of triangles in a convex polygon"
## Hallison Paz

# Convex Geometric Hypergraph

* A convex geometric hypergraph or cgh is a family of subsets of a set of points in strictly convex position in the plane
* We assume these points, denoted by $\Omega_n = {v_0, v_1, . . . , v_{n−1}}$, are the vertices of some regular n-gon with the clockwise cylic ordering $v_0 < v_1 < · · · < v_{n−1} < v_0$.
* Let the extremal function $ex_\circlearrowright(n,F)$ denote the maximum number of edges in an r-uniform cgh on n points that does not contain F – *an F-free cgh*
* In this paper, we concentrated on intersection patterns of pairs of triangles (r = 3)
----
#### Theorem 1 (partial)

For all $n ≥ 3$, if $H$ is an extremal n-vertex $M_1$-free cgh, then $H ∈ \mathcal{H}'(n)$ and:

$$ex_\circlearrowright(n,M_1) = \triangle(n) + \frac{n(n-3)}{2}$$
---
## Construction 1 - $\mathcal{H}^*(n)$

**For $n ≥ 3$ odd**, let $\mathcal{H}^*(n)$ comprise the single cgh consisting of triangles which contain in their interior the centroid of $\Omega_n$. 


---
**For $n ≥ 4$ even**, each $H \in \mathcal{H}^*(n)$ consists of all triangles which contain the centroid of $\Omega_n$ and, for each diameter $\{ v_i, v_{i+n/2}\}$ of $\Omega_n$, we either add all triangles $\{vi, vj, vi+n/2\}$ where vi < vj < vi+n/2, or all triangles {vi, vj, vi+n/2} where vi+n/2 < vj < vi.
Let
<!--stackedit_data:
eyJoaXN0b3J5IjpbNDE4Mzg1MzM4XX0=
-->