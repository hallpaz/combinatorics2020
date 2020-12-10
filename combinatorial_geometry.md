
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

where: 



---
## Construction 1 - $\mathcal{H}^*(n)$

**For $n ≥ 3$ odd**, let $\mathcal{H}^*(n)$ comprise the single cgh consisting of triangles which contain in their interior the centroid of $\Omega_n$. 

[FIGURA 1]

* There are i + 1 choices of $v′, v′′$ so that the shorter arc has exactly $i$ vertices of $\Omega_n$ in the interior, and $i ≤ n−3$.
* Summing over $i$ (and dividing by 3 because we count each triangle 3 times), we get that the number of triangles containing $x$ equals:

[FIGURA 2]

$$\frac{n}{3}(1 + 2 + ... + \frac{n-1}{2}) = \frac{(n+1)n(n-1)}{24} $$

---
**For $n ≥ 4$ even**, each $H \in \mathcal{H}^*(n)$ consists of all triangles which contain the centroid of $\Omega_n$ and, for each diameter $\{ v_i, v_{i+n/2}\}$ of $\Omega_n$, we either add all triangles $\{v_i, v_j, v_{i+n/2}\}$ where $v_i < v_j < v_{i+n/2}$, or all triangles $\{v_i, v_j, v_{i+n/2}\}$ where $v_{i+n/2} < v_j < v_i$.

FIGURA 3

---
* **If $n$ is even** then we do the same count, but first excluding the triangles with one side being the diameter of the circle. We get:
$$\frac{n(n-2)(n-4)}{24}$$

* Next, out of triangles with one side being the diameter exactly half of them contain $x$, which equals $\frac{n(n−2)}{4}$  Summing up, we get that the number of triangles containing x is 
$$\frac{n(n-2)(n-2)}{24}$$

---
* As no two triangles in any $H \in \mathcal{H}^*(n)$ have disjoint interiors, we have:

$$$$ex_\circlearrowright(n,M_1) = \triangle(n) + \frac{n(n-3)}{2}$$$$

<!--stackedit_data:
eyJoaXN0b3J5IjpbMTczODMxNTgyMiwzODU5NjE3ODZdfQ==
-->