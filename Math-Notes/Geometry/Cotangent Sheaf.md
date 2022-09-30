
# Cotangent Space
Let $(M,\mathcal{A})$ be a $n$ dimensional differential manifold.
## Definition
Let $I_p = \{f \in \mathcal{A}_p : f(p) = 0\}$ be the Vanishing Ideal of the Germs of $\mathcal{A}$ at the point $p \in M$
Then we define the ** cotangent space of M at p** as  $\mathcal{T}_p^* =(I_p/I_p^2)$
# Cotangent Sheaf
Let $(M,\mathcal{A})$ be a $n$ dimensional differential manifold.
To globalize the Cotangent Space we will need to chose all points at once, this is done
by working with $M \times M$ and the diagonal map $\Delta$
## Definition

Let $I_\Delta = \{f \in \mathcal{A}_{M\times M} : f \circ \Delta = 0\}$ be the [[Ideal Sheaf]] of $\Delta(X)$ and $I_\Delta^2 = \{\sum f_ig_j: f_i,g_j\in I_\Delta\}$
Then we define the ** cotangent sheaf** as  follows
$$\mathcal{T}^* = \Delta^*(I_\Delta/I_\Delta^2)$$ 
the pullback along $\Delta$ of the Ideal modulo it's square.

### Remark:
-  One can verify that this is a [[Sheaf#Definition|Sheaf]].
- Even better it's a [[free Sheaf of A-Modules]]