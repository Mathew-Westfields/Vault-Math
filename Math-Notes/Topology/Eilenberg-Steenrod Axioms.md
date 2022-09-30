# Eilenberg-Steenrod Axioms

## Homology Axioms
- Homotopy Invariance: $$f \sim g:(X,A) \longrightarrow (Y,B) \Longrightarrow f_{*}= g_{*}:h_n(X,A)\longrightarrow h_n(Y,B)$$
- Pair Sequence: $$\ldots \rightarrow h_{n+1}(X,A)\xrightarrow{\partial} h_n(A)\rightarrow h_n(X)\rightarrow h_n(X,A) \rightarrow \ldots$$
- Excision: $$ B\subset A \subset X \text{ with } \bar{B}\subset A^{\circ} \Longrightarrow h_n(X\setminus B,A \setminus B) \xrightarrow{\cong} h_n(X,A)$$ 

## Cohomology Axioms

- Homotopy Invariance: $$f \sim g:(X,A) \longrightarrow (Y,B) \Longrightarrow f_{*}= g_{*}:h_n(X,A)\longleftarrow h_n(Y,B)$$
- Pair Sequence: $$\ldots \leftarrow h_{n+1}(X,A)\xleftarrow{d} h_n(A)\leftarrow h_n(X)\leftarrow h_n(X,A) \leftarrow \ldots$$
- Excision: $$ B\subset A \subset X \text{ with } \bar{B}\subset A^{\circ} \Longrightarrow h_n(X\setminus B,A \setminus B) \xleftarrow{\cong} h_n(X,A)$$ 
