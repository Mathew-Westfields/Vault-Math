#definition
#algebra
# Sheaf
Let $X \in Top$ and $X = \bigcup U_i$ open covering.
## Definition
A **Sheaf** is a [[Presheaf#Definition|Presheaf]] with the following additional Axioms:
Let $s,t \in F(X)$ and $s_i \in F(U_i)$
- Sections are equal if and only if their restrictions agree everywhere
$$s = t \Longleftrightarrow res_{X,U_i}(s) = res_{X,U_i}(t) $$
- Sections can be glued
$$res_{U_i,U_i \cap U_j} s_i = res_{U_j,U_i \cap U_j} s_j \Longrightarrow \exists s\in F(X): res_{X,U_i}s=s_i$$

### Remark
- The Glueing axiom basicly tells you that if sections agree on their intersections they can be glued together into a larger section which restricts back to the original sections.
