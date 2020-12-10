
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

$$ex_\circlearrowright(n,\{M_1, S_1, D_1\}) \ge \triangle(n)$$

* Frankl, Holmsen and Kupavskii posed the following problem: *What happens if one relaxes the intersecting condition and allows triangles to intersect on the boundary?*
* One way to see it is we allow $S_1$ and $D_1$ and look for $ex_\circlearrowright(n,M_1)$

---
# FORMATAR DAQUI PRA BAIXO
### Construction 2

For n ≥ 3 odd, the unique cgh in H?(n) is obtained by adding all triangles containing a pair {vi, vi+(n−1)/2} to any cgh in H?(n) (left diagram in Figure 2). For n ≥ 4 even, H?(n) is obtained by adding all triangles containing a diameter of Ωn, plus all triangles containing a pair from a set of n/2 pairwise intersecting pairs of the form {vi, vi+n/2−1} (right diagram in Figure 2).

[FIGURA PDF]

* By inspection, every cgh in H?(n) is M1-free, and has size ·?(n) + n(n − 3)/2.

FIGURAS  4 e 5

--- 
## Proof of Theorem 1 (partial)

For all $n ≥ 3$, if $H$ is an extremal n-vertex $M_1$-free cgh, then $H ∈ \mathcal{H}'(n)$ and:

$$ex_\circlearrowright(n,M_1) = \triangle(n) + \frac{n(n-3)}{2}$$

Let n ≥ 3 be odd. If H ∈ H?(n) then we are done, so we may assume H contains a triangle T(i, j, k) = {vi, vj, vk} with vi < vj < vk < vi+(n−1)/2. Moreover, we may assume that among all such triangles, T(i, j, k) is the triangle where the longest edge {vi, vk} is as short as possible. Replace all triangles T(i, j?, k) ∈ H with i < j? < k with all triangles T(i − 1, k + 1, l) where j and l are on opposite sides of the edge {vi, vk} as shown in Figure 4. Since T(i, j, k) and T(i − 1, k + 1, l) form a copy of M1, T(i − 1, k + 1, l) ?∈ H for all such l. Moreover, since vi < vk < vi+(n−1)/2, the number of triangles T(i − 1, k + 1, l) that we added is greater than the number of triangles T(i, j, k) that we deleted. Consequently, this produces a cgh H? with |H?| > |H|. Since H is extremal M1-free, there exists a copy of M1 in H?, which must contain a triangle T(i − 1, k + 1, l) ∈ H?. Since all triangles T(i − 1, k + 1, l) intersect, the other triangle in the copy of M1 must be T(f, g, h) ∈ H. Since H is M1-free, T(f, g, h) intersects T(i, j, k), which implies vi ≤ vf < vg < vh ≤ vk and {vf, vh} ?= {vi, vk}. However, then the edge {vf, vh} is shorter than the edge {vi, vk}, a contradiction.
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTE1ODM4NjU2MywzODU5NjE3ODZdfQ==
-->