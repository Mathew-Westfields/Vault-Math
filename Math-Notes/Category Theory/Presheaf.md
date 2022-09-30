# Presheaf
Let $X \in Top$ and call $Open(X)$ the Category of open sets of $X$
## Definition
We call a [[Functor#Contravariant Functor|Contravariant Functor]] $F:Open(X)\longrightarrow Set, U\longmapsto \Gamma(U,F)$ with
$F(V \hookrightarrow U) = res_{V,U}:F(U) \longrightarrow F(V)$ called **restriction maps** a **Presheaf** if:
$$res_{V,W} \circ res_{U,V} = res_{U,W}$$