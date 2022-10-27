# Eilenberg-Steenrod Axioms
## Homology Axioms
- Homotopy Invariance: $$f \sim g:(X,A) \lra (Y,B) \Lra f_{*}= g_{*}:h_n(X,A)\lra h_n(Y,B)$$
- Pair Sequence: $$\ldots \ra h_{n+1}(X,A)\xrightarrow{\partial} h_n(A)\ra h_n(X)\ra h_n(X,A) \ra \ldots$$
- Excision: $$ B\subset A \subset X \text{ with } \bar{B}\subset A^{\circ} \Lra h_n(X\setminus B,A \setminus B) \xrightarrow{\cong} h_n(X,A)$$ 

## Cohomology Axioms

- Homotopy Invariance: $$f \sim g:(X,A) \lra (Y,B) \Lra f_{*}= g_{*}:h_n(X,A)\longleftarrow h_n(Y,B)$$
- Pair Sequence: $$\ldots \la h_{n+1}(X,A)\xleftarrow{d} h_n(A)\la h_n(X)\la h_n(X,A) \la \ldots$$
- Excision: $$ B\subset A \subset X \text{ with } \bar{B}\subset A^{\circ} \Lra h_n(X\setminus B,A \setminus B) \xleftarrow{\cong} h_n(X,A)$$ 
